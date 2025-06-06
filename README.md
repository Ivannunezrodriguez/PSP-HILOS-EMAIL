PSP-HILOS-EMAIL
Este proyecto es una práctica del módulo de Programación de Servicios y Procesos (PSP), centrada en la implementación de hilos en Java para gestionar tareas relacionadas con el envío de correos electrónicos. El objetivo principal es demostrar cómo utilizar la concurrencia para manejar múltiples operaciones de envío de emails de manera eficiente y simultánea.

📁 Estructura del Proyecto
css
Copiar
Editar
PSP-HILOS-EMAIL/
├── .idea/
├── src/
│   └── main/
│       └── java/
│           └── [Paquete con las clases Java]
├── Actividad UF 1-5 HilosINR.docx
├── Actividad UF 1-5 HilosINR.pdf
├── pom.xml
└── .gitignore
src/main/java/: Contiene el código fuente en Java, incluyendo las clases que implementan la funcionalidad de envío de correos utilizando hilos.

Actividad UF 1-5 HilosINR.docx / .pdf: Documentación de la actividad, que describe los objetivos, requerimientos y detalles de implementación del proyecto.

pom.xml: Archivo de configuración de Maven, que gestiona las dependencias y la construcción del proyecto.

🧠 Funcionalidades
Envío Concurrente de Correos: Utiliza hilos para enviar múltiples correos electrónicos de forma simultánea, mejorando la eficiencia y reduciendo el tiempo de espera.

Configuración Personalizable: Permite configurar parámetros como el servidor SMTP, puerto, autenticación y contenido del correo.

Gestión de Errores: Implementa mecanismos para manejar posibles errores durante el proceso de envío, como fallos de conexión o direcciones de correo inválidas.

🛠️ Tecnologías Utilizadas
Java: Lenguaje de programación principal del proyecto.

Maven: Herramienta de gestión y construcción de proyectos.

JavaMail API: Biblioteca utilizada para la funcionalidad de envío de correos electrónicos.

🚀 Instrucciones de Uso
Clonar el Repositorio:

bash
Copiar
Editar
git clone https://github.com/Ivannunezrodriguez/PSP-HILOS-EMAIL.git
Importar el Proyecto: Abrir el proyecto en tu IDE favorito (por ejemplo, IntelliJ IDEA o Eclipse) como un proyecto Maven.

Configurar Parámetros: Modificar las configuraciones necesarias, como las credenciales del servidor SMTP, en las clases correspondientes.

Ejecutar el Proyecto: Ejecutar la clase principal que inicia el proceso de envío de correos utilizando hilos.

📄 Licencia
Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

👨‍💻 Autor
Iván Núñez Rodríguez - GitHub
