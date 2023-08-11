# SocialNetworkUniverseasas

# Red Social Universitaria: UNIverse

## Tabla de contenido
  - [Proposito del Proyecto](#Proposito).
  - [Funcionalidades: Diagrama de Casos de Uso y Prototipo](#Funcionalidades).
  - [Modelo de Dominio: Diagrama de Clases y Módulos](#Modelo-de-Dominio).
  - [Arquitectura y Patrones: Diagra de Componentes o Paquetes](#Arquitectura-y-Patrones).
  -

## Proposito: 
La presente propuesta tiene como objetivo el desarrollo de una plataforma de Red Social que permita a los estudiantes de la Universidad Nacional de San Agust´ın comunicarse mediante mensajerıa, compartir contenido y ampliar sus opciones de interaccion social. Este proyecto busca proporcionar una herramienta eficiente y efectiva para fomentar la conectividad y la participacion activa de los estudiantes en su entorno academico y social.

## Funcionalidades

Desde la perspectiva del proyecto, se presenta una red social especificamente disenada para servir los intereses de los estudiantes universitarios. A traves de sus caracterısticas y funcionalidades, se busca proporcionar una experiencia enriquecedora y satisfactoria para sus usuarios.

[![Diagrama-de-caso-de-uso.png](https://i.postimg.cc/gjgLmCmh/Diagrama-de-caso-de-uso.png)](https://postimg.cc/V0bkFHSs)


		                Figura 1. Diagrama de Casos de Uso


| Tipo de Usuario   | Administrador                          | 
|-------------------|------------------------------------|
| Formacion     | Desarrollador de Software y Experto en Informatica |
| Actividades     | Control y manejo del sistema en general |
					

							Tabla 1 :Perfil de Administrador

| Tipo de Usuario   | Usuario                          | 
|-------------------|------------------------------------|
| Formacion     | Estudiante Universitario de la UNSA |
| Actividades     | Interactuar con la red social, publicar contenido,interactuar con amigos, buscar informacion, reaccionar a publicaciones, chatear, etc.|


							Tabla 2 :Perfil de Usuario


| Requisitos_Funcionales | Requisitos_Funcionales |
|------------------------|------------------------|
|  Iniciar Sesion        |	Escalabilidad     |
|  Registrar             |	Seguridad         |
|  Chatear               |	Disponibilidad    |
|  Editar Perfil         |	Rendimiento       |
|  Publicar              |	Usabilidad        |
|  Navegacion            |	Compatibilidad    |
|  Cerrar sesion         | 			  |
						


## Modelo de Dominio
[![Modelo-Dominio.png](https://i.postimg.cc/3R2y6ykd/Modelo-Dominio.png)]

		Figura 2. Modelo de Dominio y los Subcontextos usando Paquetes UML






# Para ejecutar el proyecto:
```bash
npm install en la carpeta server
npm install en la carpeta socket
npm install en la carpeta client
npm start en la carpeta server
npm start en la carpeta socket
npm start en la carpeta client
```
