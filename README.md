# ChatGPT Flask Vercel Deployment

## Pasos de deploy

1. Subir el proyecto a un repositorio de GitHub.

2. En Vercel:
   - Crear nuevo proyecto y seleccionar el repo.
   - Elegir Framework: Other.
   - Agregar variable de entorno:
     - OPENAI_API_KEY = tu clave de OpenAI.
   - Deploy.

3. El endpoint de la API estará disponible en:

https://<tu-proyecto>.vercel.app/api/chat