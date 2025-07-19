# Colaborar en un repositorio de GitHub

## Ser Invitado Directamente por el Propietario del Repositorio 📨

Esta es la forma más directa y común. Si conoces al propietario del repositorio, pueden invitarte a colaborar.

**Pasos para el Propietario del Repositorio:**

1. Ir a la página principal del repositorio en GitHub.

2. Hacer clic en "Settings" (Configuración) en la parte superior.

3. En la barra lateral izquierda, hacer clic en "Collaborators and teams" (Colaboradores y equipos).

4. Hacer clic en el botón verde "Add people" (Agregar personas).

5. Buscar tu nombre de usuario de GitHub, tu nombre completo o tu correo electrónico y seleccionarte.

6. Hacer clic en "Add [tu_nombre_de_usuario] to this repository" (Agregar [tu_nombre_de_usuario] a este repositorio).

**Lo que Necesitas Hacer (Tú):**

1. Recibirás un correo electrónico de GitHub con un enlace de invitación.

2. Haz clic en el enlace para aceptar la invitación.

3. Una vez aceptada, tendrás los permisos de colaborador y podrás realizar acciones como push (subir cambios) directamente a las ramas del repositorio (dependiendo de los permisos específicos que te den).

## Hacer un "Fork" y Enviar "Pull Requests" 🔄

Esta es la forma estándar de contribuir a proyectos de código abierto o a repositorios donde no tienes acceso directo de escritura desde el principio. No te convierte en un "colaborador" en el sentido de tener acceso directo, pero tus contribuciones pueden ser integradas por el propietario.

Pasos:

1. Hacer un Fork: En la página principal del repositorio original en GitHub, haz clic en el botón "Fork" en la esquina superior derecha. Esto creará una copia del repositorio en tu propia cuenta de GitHub. Esta copia es tu "fork".

2. Clonar tu Fork: Clona tu fork a tu máquina local usando el comando git clone en tu terminal. Por ejemplo:

```
git clone https://github.com/tu_usuario/nombre_del_repositorio_forkeado.git
```

3. Realizar Cambios: Haz los cambios que desees en los archivos de tu repositorio local.

4. Confirmar y Subir Cambios: Una vez que estés satisfecho con tus cambios, confírmalos (commit) y súbelos (push) a tu fork en GitHub.

```
git add .
git commit -m "Descripción de mis cambios"
git push origin nombre_de_tu_rama
```

5. Crear un Pull Request (PR):

- Ve a la página de tu fork en GitHub.
- Deberías ver un botón o un mensaje que te sugiere crear un "Pull Request" o "Compare & pull request". Haz clic en él.
- Asegúrate de que el repositorio base sea el original (el que forkeaste) y que la rama base sea la que quieres contribuir (usualmente main o master).
- Asegúrate de que el repositorio head sea tu fork y la rama compare sea la que tiene tus cambios.
- Escribe un título claro y una descripción detallada de tus cambios.
- Haz clic en "Create pull request".

**¿Qué Sucede Después de un PR?**

El propietario o los mantenedores del repositorio original revisarán tu Pull Request. Pueden:

- Aprobarlo y Fusionarlo: Tus cambios se integran al repositorio original.
- Pedir Cambios: Te solicitarán que realices modificaciones antes de fusionar.
- Cerrarlo: Decidirán no integrar tus cambios por diversas razones.

Si tus Pull Requests son consistentemente valiosos y bien hechos, es posible que el propietario del repositorio eventualmente considere invitarte como colaborador directo (método 1).

## Unirse a una Organización de GitHub 🏢

Si el repositorio pertenece a una organización de GitHub, podrías convertirte en colaborador al ser añadido a la organización y/o a un equipo dentro de ella que tenga permisos sobre ese repositorio.

**Pasos:**

1. Ser Invitado a la Organización: Un administrador de la organización te enviará una invitación para unirte a la organización.
2. Aceptar la Invitación: Aceptarás la invitación a través de un correo electrónico o en tu panel de notificaciones de GitHub.
3. Ser Añadido a un Equipo: Una vez dentro de la organización, el administrador te asignará a un equipo que tenga los permisos necesarios (por ejemplo, "Write" o "Admin") sobre el repositorio específico al que deseas contribuir.
