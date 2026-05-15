# Proyecto: Gestionador de Tareas 

---

## 🧑‍💻 Integrantes del Equipo
- Benyahir Y. Martínez Hermina - R00624824 - bmm68benya@gmail.com
- Adriana M. Marrero Sanchéz - R0062700 - amarrero7200@gmail.com

---

## 🎯 Descripción General
Describe brevemente tu aplicación:
- ¿Qué hace?
>La aplicación permite que el usuario pueda agregar una o varias tareas en una lista. En donde este puede marcar las tareas que este haya realizado y eliminar las tareas de la lista para seguir añadiendo tareas para evitar la confusión de lo que se haya realizado.
- ¿A quién va dirigida?
>Esta dirigida hacia estudiantes y empleados que quieren tenere un mejor control sobre lo que tienen que realizar en el momento o lo que tiene que hacer despues.
- ¿Qué problema resuelve o qué funcionalidad ofrece?
>Responde a la necesidad de personas de tener un lugar donde puedan mantenerse en día de las cosas que tienen que realizar tras el transcurso del día. Por ejemplo si un usuario en su trabajo le es otorgado con labores que tiene que realizar en es día, el usuario puede anotar estas en la aplicación para tener un mejor visualización de lo que tiene que hacer y mejor control en como tiene que hacerlo.

---

## ☁️ Servicios de Azure Utilizados

| Servicio              | Propósito dentro del proyecto                    | Gratuito en Azure for Students |
|-----------------------|--------------------------------------------------|--------------------------------|
| Azure App Service     | Donde se aloja nuestras aplicaciones web y también donde podemos controlar el funcionamiento de esta  | ✅ Sí                           |
| Azure SQL Database    | Recurso donde se estará almacenando los datos del sistema de las aplicaciones. | ✅ Sí                           |
| Azure Storage Account | Lugar donde se almacena archivos cargados por los usuarios de las aplicaciones. | ✅ Sí                           |
| Flask                 | Funciona como un servidor web que gestiona rutas de HTTP, renderizado las plantillas de HTML del proyecto. | ✅ Sí                      |
| Boostrap              | Se implemento para añadir a la aplicación una interfaz grafica mas amigable a los usuarios que utilizan la aplicación.   | ✅ Sí            |
| Repositorio de Github | Donde se localiza el código de nuestras aplicaciones web. En base a estar ese código en el repositorio Azure App Service coje ese código y realiza el despliegue en la nube.       | ✅ Sí       |

---

## 🧱 Diagrama de Arquitectura

![Diagrama](./Diagrama.png)

---

## ⚙️ Despliegue y Configuración

### 1. Preparacion del codigo
  
### 2. Configuración en Azure
- Pasos realizados en Azure Portal
- Configuración del App Service
- Variables de entorno definidas (nombres, no valores)
- Configuración del SQL Server
-


---

## 💻 Enlace a la Aplicación Desplegada
> [https://gestionadordetareas.azurewebsites.net](https://gestionadordetareas.azurewebsites.net) - Benyahir Y. Martinez Hermina

> [https:// ]() - Adriana M. Marrero Sanchéz
---

## 💸 Estimación del Costo (Azure Pricing Calculator)

> ![]()

---

## 📁 Capturas del Portal de Azure
- Microsoft Azure SQL Database:
  >![1](./Documentación-DB/DB-Gestion_de_Tareas-Benyahir/1.png)
  >![2](./Documentación-DB/DB-Gestion_de_Tareas-Benyahir/2.png)
  >![3](./Documentación-DB/DB-Gestion_de_Tareas-Benyahir/3.png)
  >![4](./Documentación-DB/DB-Gestion_de_Tareas-Benyahir/4.png)
  >![5](./Documentación-DB/DB-Gestion_de_Tareas-Benyahir/5.png)
  >![6](./Documentación-DB/DB-Gestion_de_Tareas-Benyahir/6.png)
- Microsoft Azure App Service:
  >![1](./Documentación-AppService/AppService-Gestion_de_Tareas-/1.png)
- Microsoft Azure Storage Account:
  >![1]()

---

## 📘 Lecciones Aprendidas
- ¿Qué retos enfrentaron y cómo los resolvieron?
  >Se exihibieron problemas con la inicializacion de la applicación en Microsoft Azure App Service con el repositorio de GitHub. Otro problema
  que se exhibio fue en hacer que la applicacion corriera de manera local en nuestras computadoras.
  >Para resolver el problema de la inicialización de la aplicación, se tuvo que varios “refreshes” y “resets” a la aplicación en Microsoft
  Azure App para que al final se pueda presentar sin ningún problema. Pero lastimosamente el problema con correr la aplicación de manera local no se pudo resolver.

- ¿Qué aprendieron sobre trabajar con servicios cloud?
  
- ¿Qué mejorarían en una próxima versión del proyecto?
  
  
---

## 📚 Repositorio del Código
Incluye el link al repositorio de GitHub (debe estar público o accesible para el profesor):
> [https://github.com/BenyahirMartinez2004/Comp4260-Projecto-Gestionador-de-Tareas.git](https://github.com/BenyahirMartinez2004/Comp4260-Projecto-Gestionador-de-Tareas.git) - Benyahir Y. Martínez Hermina
> [https://github.com/AdrianaM2S/Comp4260-Projecto-Gestionador-de-Tareas.git](https://github.com/AdrianaM2S/Comp4260-Projecto-Gestionador-de-Tareas.git) - Adriana M. Marrero Sanchéz
---

## 📄 Instrucciones para Reproducir el Proyecto
1. Clonar el repositorio.
2. Crear una base de datos en Microsoft Azure
3. Crear un Storage Account en Azure
4. Crear un App Service en Azure
5. Conectar el App Service con un Repositorio de Github
6. En ese repositorio se colocara el contenido del repositorio clonado 
7. Activar/Inicializar el despliegue en Azure App Service

---

## ✅ Checklist Final
- [ ] App funcional y desplegada
- [ ] Servicios gratuitos utilizados correctamente
- [ ] Diagrama de arquitectura incluido
- [ ] Documentación clara y completa
- [ ] Costos estimados incluidos
- [ ] Repositorio disponible en GitHub
- [ ] Lecciones aprendidas y reflexión final escritas

---

