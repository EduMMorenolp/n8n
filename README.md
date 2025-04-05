![Imagen de banner](https://user-images.githubusercontent.com/10284570/173569848-c624317f-42b1-45a6-ab09-f0ea3c247648.png)

# n8n - Automatización de flujos de trabajo segura para equipos técnicos

**n8n** es una plataforma de automatización de flujos de trabajo que le da a los equipos técnicos la flexibilidad del código con la velocidad del no-code. Con más de **400 integraciones**, capacidades de IA nativas y una licencia *fair-code*, n8n te permite crear potentes automatizaciones mientras mantenés el control total de tus datos y despliegues.

![n8n.io - Captura de pantalla](https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-screenshot-readme.png)

## 🧠 Capacidades principales

- **Codificá solo cuando lo necesites**: Escribí JavaScript o Python, agregá paquetes npm o usá la interfaz visual.
- **Plataforma con IA nativa**: Creá flujos de trabajo con agentes de IA basados en LangChain con tus propios datos y modelos.
- **Control total**: Podés alojarlo vos mismo con nuestra licencia *fair-code*, o usar nuestra [versión en la nube](https://app.n8n.cloud/login).
- **Listo para empresas**: Soporte para permisos avanzados, SSO e implementaciones aisladas (*air-gapped*).
- **Comunidad activa**: Más de 400 integraciones y más de 900 [plantillas listas para usar](https://n8n.io/workflows).

## ⚡ Inicio rápido

Probaló al instante con [npx](https://docs.n8n.io/hosting/installation/npm/) (requiere [Node.js](https://nodejs.org/en/)):

```bash
npx n8n
```

O desplegalo con [Docker](https://docs.n8n.io/hosting/installation/docker/):

```
docker volume create n8n_data
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```

Accedé al editor en: http://localhost:5678

### 💾 Para tener persistencia
```bash
docker run -d --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```

### 🔁 Para controlarlo después:

Iniciar nuevamente (si está detenido):
```bash
docker start n8n
```
Parar:
```bash
docker stop n8n
```
Eliminarlo (si querés):
```bash
docker rm n8n
```
Ver si está corriendo:
```bash
docker ps
```

## 📚 Recursos

- 📚 [Documentation](https://docs.n8n.io)
- 🔧 [400+ Integrations](https://n8n.io/integrations)
- 💡 [Example Workflows](https://n8n.io/workflows)
- 🤖 [AI & LangChain Guide](https://docs.n8n.io/langchain/)
- 👥 [Community Forum](https://community.n8n.io)
- 📖 [Community Tutorials](https://community.n8n.io/c/tutorials/28)

## 💬 Soporte

¿Necesitás ayuda? El foro de la comunidad es el mejor lugar para recibir soporte y conectar con otros usuarios:
[community.n8n.io](https://community.n8n.io)

## 📜 Licencia

**n8n** es [fair-code](https://faircode.io) y se distribuye bajo la [Licencia de Uso Sostenible](https://github.com/n8n-io/n8n/blob/master/LICENSE.md) y la [Licencia Empresarial de n8n](https://github.com/n8n-io/n8n/blob/master/LICENSE_EE.md).

- **Código abierto (Source Available)**: Siempre podés ver el código fuente.
- **Auto-hospedable**: Podés desplegarlo donde quieras.
- **Extensible**: Podés agregar tus propios nodos y funcionalidades.

Existen [licencias empresariales](mailto:license@n8n.io) disponibles con características adicionales y soporte técnico.

Más información sobre el modelo de licencias en la [documentación](https://docs.n8n.io/reference/license/).

## 🤝 Contribuir

¿Encontraste un bug 🐛 o tenés una idea ✨ para una nueva funcionalidad?  
Consultá nuestra [Guía para contribuir](https://github.com/n8n-io/n8n/blob/master/CONTRIBUTING.md) para empezar.

## 💼 Unite al equipo

¿Querés ayudar a definir el futuro de la automatización?  
Mirá nuestras [ofertas laborales](https://n8n.io/careers) y sumate a nuestro equipo.

## ❓ ¿Qué significa "n8n"?

**Respuesta corta:** Significa “nodemation” y se pronuncia *n-eight-n*.

**Respuesta larga:**  
"Me hacen esta pregunta bastante seguido (más de lo que esperaba), así que decidí que lo mejor era responderla acá. Mientras buscaba un buen nombre para el proyecto con dominio disponible, me di cuenta rápidamente de que todos los buenos ya estaban tomados.  
Así que, al final, elegí 'nodemation'.  
‘node-’ porque usa una vista en nodos y está basado en Node.js, y ‘-mation’ por ‘automation’ (automatización), que es justamente lo que el proyecto busca facilitar.  
Sin embargo, no me gustaba lo largo que era el nombre y no me imaginaba escribiéndolo completo cada vez en la línea de comandos.  
Así fue como llegué a ‘n8n’."

— **Jan Oberhauser, Fundador y CEO de n8n.io**
