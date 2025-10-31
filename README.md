# ProyectoUnabSantoyo

🕒 GHL - Sistema de Gestión de Horas Libres UNAB
📘 Descripción del Proyecto

GHL (Gestión de Horas Libres) es un sistema desarrollado en Java con interfaz gráfica (GUI) que permite a los estudiantes de la Universidad Autónoma de Bucaramanga (UNAB) registrar, consultar y gestionar sus Horas Libres (HL) de manera sencilla y profesional.

El sistema busca facilitar el control del cumplimiento de horas requeridas para la graduación, integrando funcionalidades de seguimiento, estadísticas, registro en eventos, y administración general, bajo una arquitectura orientada a objetos y con persistencia de datos.

🎯 Objetivos Principales

Crear una herramienta intuitiva y profesional para la gestión de horas libres.

Ofrecer estadísticas detalladas del progreso académico del estudiante.

Permitir la administración de eventos asociados a horas libres.

Implementar buenas prácticas de desarrollo orientado a objetos.

Garantizar persistencia de datos y mantenimiento del sistema.

🧱 Tecnologías y Requisitos

Lenguaje: Java 8+

Entorno de desarrollo: IntelliJ IDEA / Eclipse / NetBeans

Interfaz gráfica: JavaFX o Swing (preferiblemente JavaFX)

Persistencia: Archivos binarios / JSON / SQLite

Paradigma: Programación Orientada a Objetos (POO)

Modelo de datos: Clases modelo (Usuario, Evento, HoraLibre, Estadística, etc.)

Patrones recomendados: MVC (Modelo - Vista - Controlador)

🧩 Funcionalidades Principales
🎨 Interfaz y Diseño

Diseño limpio y profesional.

Aplicación gráfica con menús, botones y vistas interactivas (no consola).

Estructura clara y fácil de navegar.

⏰ Módulo de Horas Libres

CRUD de Horas Libres: Crear, Leer, Actualizar y Eliminar registros de HL.

Cálculo de promedios:

Promedio de HL por semana.

Promedio de HL por mes.

Promedio de HL por semestre.

Promedio de HL por año.

Horas libres faltantes para graduarse.

Consulta de total de horas libres acumuladas.

👤 Módulo de Usuario

Registro en el sistema.

Inicio de sesión (Login).

Visualización y edición del perfil del usuario.

🎉 Módulo de Eventos

Visualizar eventos disponibles.

Filtrar eventos que otorgan HL.

Registrar participación en eventos: ULIBRO, UNABFEST, Semana de Ingeniería, Hackatón, Club de Anime, etc.

Darse de baja de un evento.

CRUD de Eventos (para administradores).

🧰 Mantenimiento

Sistema de mantenimiento regular para corrección de errores y limpieza de datos.

🔧 Funcionalidades Adicionales (10 Nuevas Mejoras)

Notificaciones automáticas: recordatorios de eventos próximos o pendientes.

Exportar reportes: generar reportes en PDF o Excel con el historial de HL.

Ranking de estudiantes: mostrar los 10 estudiantes con más HL acumuladas.

Panel administrativo: gestión de usuarios y validación de HL por parte de coordinadores.

Historial de eventos: registro de los eventos en los que el estudiante ha participado.

Modo oscuro/claro: opción para cambiar el tema visual de la aplicación.

Búsqueda avanzada: filtrar eventos por fecha, tipo o cantidad de HL otorgadas.

Sistema de comentarios: los estudiantes pueden calificar y comentar eventos.

Dashboard estadístico: gráficas interactivas que muestren el progreso de HL (por semanas, meses, semestres).

Copia de seguridad automática: respaldo de la base de datos cada cierto tiempo o al cerrar sesión.

🧠 Estructura Sugerida del Proyecto
📁 GHL/
├── 📂 src/
│   ├── 📂 controller/
│   │   ├── LoginController.java
│   │   ├── EventoController.java
│   │   ├── HorasLibresController.java
│   │   └── UsuarioController.java
│   ├── 📂 model/
│   │   ├── Usuario.java
│   │   ├── Evento.java
│   │   ├── HoraLibre.java
│   │   ├── Estadistica.java
│   │   └── Admin.java
│   ├── 📂 view/
│   │   ├── login.fxml
│   │   ├── dashboard.fxml
│   │   ├── eventos.fxml
│   │   └── perfil.fxml
│   └── Main.java
├── 📂 resources/
│   ├── style.css
│   ├── icons/
│   └── data/
│       └── database.json
└── README.md

💾 Persistencia

El sistema almacenará los datos de usuarios, eventos y horas libres en una base de datos local (ej. SQLite) o en archivos JSON/serializados. Esto garantiza que la información se conserve tras cerrar la aplicación.

🧑‍💻 Créditos

Desarrollado por: Camilo Carrillo, Juan Castillo,Luisa Fernanda
Proyecto académico - Universidad Autónoma de Bucaramanga (UNAB)
Asignatura:Estructura de Datos y Analisis
