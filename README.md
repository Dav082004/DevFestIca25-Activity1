# 🤖 DevFest Ica 2025 - Taller: Automatización de Proyectos con GitHub Copilot y MCP Server

## 🎯 Objetivo del Taller

En este taller, descubrirás cómo usar **GitHub Copilot** y **MCP Server (Model Context Protocol)** para automatizar la gestión de tus proyectos de software. Aprenderás a transformar un documento de requerimientos en un plan de trabajo accionable dentro de GitHub, todo mediante comandos de lenguaje natural.

Exploraremos cómo:
1.  **Analizar archivos de requerimientos** (`.md`, `.pdf`, etc.) para extraer tareas.
2.  **Generar issues de GitHub automáticamente**, con descripciones claras y labels de complejidad.
3.  **Organizar el backlog** de tu proyecto y conectarlo a **GitHub Projects** para un seguimiento visual.

---

## 🚀 Ejercicio Central: Automatiza tu Proyecto con IA

Este ejercicio te guiará para automatizar la creación de issues a partir de un archivo de requerimientos. A continuación, se presentan diferentes métodos según las herramientas que tengas a tu disposición.

### Configurando nuestras bases

1.  **Haz un Fork** de este repositorio a tu cuenta de GitHub.
2.  **Crea un Codespace** desde tu repositorio para obtener un entorno de desarrollo listo para usar.

### Opción 1: Con GitHub Copilot en la Terminal (CLI)

Ideal si prefieres trabajar directamente desde la línea de comandos.

1.  **Instala GitHub Copilot CLI** en la terminal de tu Codespace:
    ```bash
    npm install -g @github/copilot-cli
    ```
2.  **Autentícate** con tu cuenta de GitHub ejecutando:
    ```bash
    /login
    ```
3.  **Usa el siguiente prompt** para que Copilot analice los requerimientos y cree un issue automáticamente:

    	@project/requirements.md Analiza el archivo y genera una #issue_create para cumplir con los requerimientos, la issue debe tener descripción clara y una estimación de complejidad mediante labels y subelo mediante GitHub MCP Server
    
4.  Una vez creado el issue, puedes pedirle a Copilot que genere el código para resolverlo en una nueva rama:
    
     Analiza el último issue creado y genera el código necesario en una nueva rama.
    

### Opción 2: Con GitHub Copilot Chat en VS Code

Perfecto para quienes prefieren una experiencia integrada en el editor.

1.  **Instala y configura el MCP Server de GitHub** 
2.  Abre el chat de GitHub Copilot Chat
3.  Si tienes agentes configurados, elige `quickbuild-assistant.agent`.
4.  Introduce este prompt en el chat:
    ```
    Analiza el archivo 'project/requirements.md' y genera una #issue_create para cumplir con los requerimientos, la issue debe tener descripción clara y una estimación de complejidad mediante labels.
    ```

#### Flujos de trabajo adicionales:

*   **Si tienes GitHub Copilot Pro:**
    Puedes asignar el issue directamente a `@github-copilot` con el agente `quickbuild-assistant` para que lo resuelva de forma automática.

*   **Si no tienes una suscripción de pago:**
    Puedes usar el chat para generar el código, pedirle que lo suba a una nueva rama y luego verificar los cambios para crear tu Pull Request manualmente.

---
