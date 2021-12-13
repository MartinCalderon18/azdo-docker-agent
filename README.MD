# Basado en el siguiente articulo
https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/docker?view=azure-devops 

# Script de Inicio
docker run -e AZP_URL=https://dev.azure.com/[ORGANIZACION] -e AZP_TOKEN=[XXXXXXXXXXXXXXX] -e AZP_AGENT_NAME=mydockeragent dockeragent:latest