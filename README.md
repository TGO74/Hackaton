# Sistema de Gestión de Participantes en Hackathon

## Descripción General

Este proyecto es un sistema web diseñado para gestionar el registro y la participación de individuos en un evento de hackathon. La hackathon se extiende por tres días, y los participantes son asignados a un día específico (Día 1, Día 2 o Día 3) para presentar sus soluciones. El sistema permite a los participantes registrarse, iniciar sesión, ver y actualizar su perfil, y acceder a su boleto de entrada. Los supervisores pueden gestionar a los participantes, incluyendo asignar fechas, bloquear participantes y eliminar participantes.

## Funcionalidades

### Para Participantes

1. **Registro**:
    - Navegar a la página de registro.
    - Completar el formulario de registro (nombre completo, contraseña, correo electrónico, número de contacto y RUT).
    - Enviar el formulario de registro y redirigirse a la página de inicio de sesión.

2. **Inicio de Sesión**:
    - Ingresar correo electrónico y contraseña para acceder al sistema.

3. **Página de Perfil**:
    - Ver información personal, incluyendo la fecha asignada para la participación en la hackathon.
    - Actualizar el número de contacto.
    - Ver un boleto de entrada con su nombre, fecha asignada y un código generado aleatoriamente.

### Para Supervisores

1. **Inicio de Sesión**:
    - Navegar a la página de inicio de sesión de supervisores.
    - Ingresar correo electrónico y contraseña para acceder al sistema.

2. **Página de Administrador**:
    - Mostrar el correo del supervisor.
    - Listar todos los participantes con opciones para eliminar o bloquear.
    - Asignar fechas a los participantes.
    - Asignar fechas en bloque a múltiples participantes seleccionados.

## Detalles Técnicos

- **Arquitectura**: Modelo-Vista-Controlador (MVC)
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Servlets Java, JSP
- **Base de Datos**: MySQL
- **Framework**: Apache Tomcat

## Configuración e Instalación

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/yourusername/sistema-gestion-hackathon.git
   ```

2. **Configuración de la Base de Datos**:
    - Crear una base de datos MySQL llamada `hackathon`.
    - Ejecutar los scripts SQL en la carpeta `db` para crear las tablas necesarias y agregar datos iniciales.

3. **Configurar la Conexión a la Base de Datos**:
    - Actualizar los detalles de conexión a la base de datos en el archivo `DBConnector.java`.

4. **Construir y Desplegar**:
    - Construir el proyecto usando tu IDE preferido (por ejemplo, IntelliJ IDEA, Eclipse).
    - Desplegar la aplicación en Apache Tomcat.

5. **Acceder a la Aplicación**:
    - Abrir un navegador web y navegar a `http://localhost:8080/sistema-gestion-hackathon`.

## Uso

### Registro e Inicio de Sesión de Participantes

1. **Registro**:
    - Navegar a la página de registro.
    - Completar el formulario de registro con tus datos.
    - Enviar el formulario para crear tu cuenta y ser redirigido a la página de inicio de sesión.

2. **Inicio de Sesión**:
    - Usar tu correo electrónico y contraseña registrados para iniciar sesión.
    - Ver tu perfil, actualizar detalles de contacto y acceder a tu boleto de entrada.

### Gestión por Supervisores

1. **Inicio de Sesión**:
    - Navegar a la página de inicio de sesión de supervisores.
    - Ingresar tus credenciales para acceder a la interfaz de administración.

2. **Gestionar Participantes**:
    - Ver todos los participantes registrados.
    - Asignar fechas, bloquear o eliminar participantes.
    - Usar acciones en bloque para gestionar múltiples participantes de manera eficiente.

## Capturas de Pantalla

*Incluye capturas de pantalla relevantes de la aplicación aquí, como la página de registro, la página de inicio de sesión, la página de perfil, la página de administrador, etc.*

## Contribuyendo

Si deseas contribuir a este proyecto, por favor bifurca el repositorio y envía una solicitud de extracción. Para cambios mayores, abre un issue para discutir lo que te gustaría cambiar.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

## Contacto

Para cualquier consulta o comentario, por favor contáctanos en [correo@example.com](mailto:correo@example.com).

---

¡Gracias por usar el Sistema de Gestión de Participantes en Hackathon! Esperamos que ayude a hacer de tu evento de hackathon un éxito.