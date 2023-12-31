# SocialNetworkUniversity

# Red Social Universitaria: UNIverse
Integrantes:
- Sergio Daniel Mogollon Caceres
- Paul Anthony Parizaca Mozo
- Braulio Nayap Maldonado Casilla
- Luciana Julissa Huaman Coaquira
- Jharold Alonso Mayorga Villena
- Andrea Del Rosario Lopez Condori
## Tabla de contenido
   1. [Proposito del Proyecto](#Proposito).
   2. [Funcionalidades: Diagrama de Casos de Uso y Prototipo](#Funcionalidades).
   3. [Modelo de Dominio: Diagrama de Clases y Módulos](#Modelo-de-Dominio).
   4. [Arquitectura y Patrones: Diagra de Componentes o Paquetes](#Arquitectura-y-Patrones).
   5. [Practicas de Codificacion Limpia](#Practicas-de-Codificacion-Limpia)
   6. [Estilos de Programacion](#Estilos-de-Programacion)
   7. [Principios SOLID](#Principios-SOLID)
   8. [Conceptos DDD](#Conceptos-DDD)

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

## Arquitectura y Patrones

### 4.1 Diagrama de Componentes o Paquetes
#### Diagrama de Paquetes
Los paquetes son unidades de organización en el código fuente de un proyecto de software. Representan una forma de agrupar lógicamente funcionalidades relacionadas. Los paquetes ayudan a dividir el código en módulos más pequeños y manejables, lo que facilita la comprensión, el desarrollo y el mantenimiento. Además, proporcionan encapsulación y modularidad, lo que significa que se pueden desarrollar, probar y modificar componentes individuales sin afectar al resto del sistema.

[![UWu.png](https://i.postimg.cc/nr376Ww6/UWu.png)](https://postimg.cc/N2r5Xdt4)


### Diagrama Despliegue
La infraestructura de despliegue se inicia con balanceadores de carga, dispositivos especializados que gestionan la distribución equitativa de las solicitudes de los usuarios hacia varios servidores web. Estos servidores, basados en tecnologías como HTTP o HTTPS, atienden las peticiones mediante la generación y presentación de la interfaz de usuario de la red social.

Por debajo de esta capa, se encuentran los servidores de aplicaciones, donde se aloja la lógica de negocio más sofisticada. Aquí se gestionan procesos como la manipulación de perfiles de usuarios, la administración de relaciones sociales y la publicación de contenido. Estos servidores operan en conjunto con las bases de datos, que almacenan los datos estructurados y relacionales del sistema. Dependiendo de la escala y los requisitos de almacenamiento, pueden emplearse bases de datos SQL o NoSQL.

[![diagrama-Despliegue.png](https://i.postimg.cc/PJ9KnF4y/diagrama-Despliegue.png)]

### Diagrama de componentes
Diagrama de componentes es una representación visual que muestra la estructura y las relaciones entre los componentes principales de un sistema de software. En el contexto de una red social, este diagrama ilustra cómo se organizan y comunican los elementos fundamentales que conforman el sistema.

#### Componentes:

Interfaz de Usuario: Este componente representa la interfaz visual a través de la cual los usuarios interactúan con la red social. Puede dividirse en subcomponentes más pequeños que manejen la presentación y la interacción del usuario.

#### Controladores: 
Los controladores son componentes que manejan la lógica de la aplicación y actúan como intermediarios entre la interfaz de usuario y la lógica empresarial. Controlan las acciones y las solicitudes del usuario, procesan la entrada y coordinan la comunicación entre otros componentes.

#### Servicios: 
Los servicios son componentes que encapsulan la lógica empresarial. Pueden incluir funcionalidades como la gestión de perfiles de usuarios, la publicación de contenido y la administración de relaciones sociales. Estos servicios se utilizan desde los controladores y otros componentes para realizar tareas específicas.

### Bases de Datos: 
Representa las bases de datos en las que se almacenan los datos de la red social, como perfiles de usuarios, publicaciones, comentarios y relaciones. Pueden subdividirse en componentes específicos para diferentes tipos de datos o módulos.

[![Diagrama-compo-1.png](https://i.postimg.cc/6pdcFcGV/Diagrama-compo-1.png)]



Se incluye un diagrama que representa la arquitectura de componentes o paquetes del sistema. Esto ayuda a comprender la distribución y la interacción de los diferentes componentes del software.

## Practicas de Codificacion Limpia

# Practicas generales en el proyecto
## _Consistent Identation_
Consiste en mantener una indentación coherente y uniforme en todo el código fuente de un programa. La indentación se refiere a la cantidad de espacios o tabulaciones utilizadas para desplazar el código hacia la derecha y crear una estructura jerárquica y legible en el código.

El objetivo de tener una indentación consistente es mejorar la legibilidad del código y hacerlo más comprensible para los desarrolladores. Cuando el código está indentado de manera consistente, es más fácil seguir la lógica del programa, identificar bloques de código y entender la estructura del código.

Aquí hay algunos principios clave relacionados con la indentación consistente en Clean Code:

1. **Cantidad de espacios o tabulaciones:** Se debe elegir una cantidad específica de espacios o tabulaciones para cada nivel de indentación y mantenerla consistente en todo el código. La cantidad típica de espacios es 2 o 4, pero lo más importante es que se mantenga la misma cantidad en todo el proyecto.

2. **Indentación dentro de bloques de código:** Cada vez que se abre un bloque de código (por ejemplo, una función, un bucle o una condición), se debe aumentar la indentación para mostrar que el bloque está contenido dentro de otro. Cuando el bloque se cierra, la indentación debe disminuir para volver al nivel anterior.

3. **Consistencia en todo el equipo:** Para tener un código limpio y consistente en un proyecto, es fundamental que todos los miembros del equipo sigan las mismas reglas de indentación. Esto facilita la colaboración y revisión del código.

4. **Evitar mezclar tabulaciones y espacios:** Es importante mantener la coherencia en el uso de tabulaciones o espacios para la indentación. Mezclar ambos puede llevar a problemas de formato y dificultar la lectura del código.

```javascript
export const createMessage = async (req, res) => {
    try {
        const { sender, receiver, content } = req.body;
        const newMessage = new Message({
        sender,
        receiver,
        content,
        });

        await newMessage.save();
        res.status(201).json(newMessage);
    } catch (error) {
        console.log(error.message);
        return res.status(500).json({ message: error.message });
    }
};
```

## _Comments_
Esta practica se refiere a la práctica de agregar comentarios y documentación al código para explicar su funcionamiento, propósito y cualquier detalle relevante. Esta práctica es esencial para mejorar la legibilidad y mantenibilidad del código, así como para facilitar la colaboración en equipos de desarrollo.

**Comentarios (Comments):**

- Los comentarios son fragmentos de texto que se insertan en el código fuente para explicar el propósito de un bloque de código, una función o una línea de código.
- Los comentarios ayudan a los desarrolladores a comprender rápidamente qué hace una porción de código, especialmente cuando la lógica es compleja o poco intuitiva.
- Los comentarios también pueden proporcionar información sobre el razonamiento detrás de ciertas decisiones de diseño o implementación.

```
## _Code Grouping_
Según Clean Code, "Code Grouping" se refiere a la práctica de agrupar el código relacionado y funcionalmente coherente en bloques o secciones. El objetivo es mejorar la legibilidad y comprensión del código al tener componentes lógicos y relacionados ubicados juntos.

- Funciones y Métodos Bien Definidos:
Agrupar código relacionado en funciones y métodos claros mejora la comprensión y seguimiento del código. Cada función o método debe tener una sola responsabilidad y realizar una tarea específica.

- Clases y Módulos Coherentes:
Dentro de un archivo o módulo, las clases y funciones deben estar organizadas de manera coherente. Las clases deben contener métodos relacionados con el estado y comportamiento del objeto que representan.
Orden Lógico del Código:

- Organizar el código de forma lógica y legible facilita su comprensión.
Las funciones más utilizadas deben ubicarse cerca del inicio del archivo para mayor accesibilidad.

- Comentarios y Separadores:
El uso de comentarios y separadores divide el código en secciones lógicas, facilitando la navegación y comprensión.

- Evitar Lógica Repetitiva:
Evitar duplicación de código y agrupar lógica repetitiva en funciones reutilizables hace el código más conciso y mantenible.

- Organización de Importaciones:
En lenguajes con importaciones de módulos, agrupar importaciones relacionadas y mantenerlas ordenadas mejora la legibilidad.

En el siguiente ejemplo se ve que la logica de los middlewares esta agrupada y separada de la logica de las routes y de los imports:

```javascript
import express from "express";
import fileUpload from "express-fileupload";
import chatRoutes from "./routes/chat.routes.js";
import { dirname, join } from "path";
import { fileURLToPath } from "url";
import cors from 'cors';

const app = express();
const __dirname = dirname(fileURLToPath(import.meta.url));

// middlewares
app.use(cors())
app.use(express.json());
app.use(
  fileUpload({
    useTempFiles: true,
    tempFileDir: "./upload",
  })
);

// routes
app.use(chatRoutes);
console.log(__dirname);
app.use(express.static(join(__dirname, "../client/build")));

export default app;
```
## _Limit Line Length_
Significa establecer un límite máximo para la longitud de las líneas de código en un programa. La idea detrás de este principio es que las líneas de código largas pueden ser difíciles de leer y comprender, lo que afecta la legibilidad y mantenibilidad del código.Sus punto claves son los siguientes:

- Establecer una longitud máxima: Se debe establecer un límite máximo para la longitud de las líneas de código en el código base. Si una línea de código excede este límite, se considera demasiado larga y debe ser dividida en líneas más cortas.

- Facilitar la lectura: Limitar la longitud de las líneas de código ayuda a que el código sea más fácil de leer y seguir. Los desarrolladores pueden comprender rápidamente una línea más corta sin tener que desplazarse horizontalmente en el editor de código.

- Evitar la horizontalidad excesiva: Las líneas de código extremadamente largas pueden requerir desplazamiento horizontal constante, lo que puede dificultar la comprensión de la lógica del programa.
En este fragmento de codigo el limite de caracteres ronda los 80 caracteres de ancho:
```javascript
import mongoose from "mongoose";
import { MONGODB_URI } from "./config.js";

export async function connectDB() {
  try {
    mongoose.set("strictQuery", true);
    const db = await mongoose.connect(MONGODB_URI);
    console.log(`Connected to database: ${db.connection.name}`);
  } catch (error) {
    console.log(error);
  }
}
```
## _Avoid Using Magic Numbers_
Se refiere a la práctica de evitar el uso de números literales sin una explicación o contexto claro en el código fuente. En lugar de usar números "mágicos" directamente en el código, se deben utilizar constantes con nombres descriptivos para darles significado y facilitar su comprensión.

Los números "mágicos" son valores numéricos que aparecen directamente en el código sin una explicación adecuada o un comentario que los acompañe. Por ejemplo, considera el siguiente fragmento de código:

Además, al utilizar constantes con nombres descriptivos, si es necesario cambiar el valor del número en el futuro, solo se necesita modificar la constante en un solo lugar en lugar de buscar y reemplazar todas las apariciones del número en el código.

En este caso la constante `PORT` esta declarada en el archivo `index.js` y puede ser usada por cualquier archivo, cumpliendo con la practica de *Avoid Using Magic Numbers*:

- config.js
```javascript
import dotenv from 'dotenv'

dotenv.config();

export const MONGODB_URI = process.env.MONGODB_URI || "mongodb://localhost/testdb";
export const PORT = process.env.PORT || 4000;
```
- index.js
```javascript
import app from './app.js'
import { connectDB } from "./db.js";
import { PORT } from "./config.js";

connectDB();
app.listen(PORT);
console.log(`Server on port ${PORT}`);
```


### 5.1 Parte Implementada en el Proyecto

#### 5.1.1 Código Limpio en el Componente Auth

Sea componente `Auth.jsx` de la carpeta `Auth`

1. **Nombres descriptivos:**
   - `handleChange`, `handleSubmit`, `resetForm`, `loading`, `confirmPass`, `isSignUp` son ejemplos de nombres descriptivos.

2. **Indentación y formato:**
   - El código en general mantiene una estructura de indentación consistente y utiliza espacios en blanco de manera efectiva.

3. **Comentarios claros:**
   - Los comentarios en línea que explican qué hace cada sección de código:

```javascript
// handle Change in input
const handleChange = (e) => {
  setData({ ...data, [e.target.name]: e.target.value });
};

// Form Submission
const handleSubmit = (e) => {
  setConfirmPass(true);
  e.preventDefault();
  if (isSignUp) {
    data.password === data.confirmpass
      ? dispatch(signUp(data, navigate))
      : setConfirmPass(false);
  } else {
    dispatch(logIn(data, navigate));
  }
};
```

4. **Separación de preocupaciones:**
   - Cada función tiene una responsabilidad específica y está bien definida en su propósito, como `handleChange`, `handleSubmit`, `resetForm`, etc.

5. **Reutilización de código:**
   - El estado `data` se utiliza para manejar los datos del formulario en lugar de repetir los campos.

6. **Evitar redundancia:**
   - La función `resetForm` restablece los datos y el estado de confirmación de contraseña.

7. **Uso adecuado de espacios en blanco:**
   - El código utiliza espacios en blanco para separar visualmente las secciones lógicas y mejorar la legibilidad en varias partes.

8. **Uso de destructuring:**
   - Ejemplos de destructuring en el código:

```javascript
const loading = useSelector((state) => state.authReducer.loading);
```

9. **Manejo de eventos:**
   - Los manejadores de eventos `onChange` y `onClick` se utilizan para gestionar la interacción del usuario.

10. **Ternarios para claridad:**
    - Se utiliza un operador ternario para mostrar el mensaje de error de confirmación de contraseña:

```javascript
<span
  style={{
    color: "red",
    fontSize: "12px",
    alignSelf: "flex-end",
    marginRight: "5px",
    display: confirmPass ? "none" : "block",
  }}
>
  *Confirm password is not same
</span>
```

#### 5.1.2 Código Limpio en el Componente Chat

Sea componente `Chat.jsx` de la carpeta `Chat`

1. **Nombres descriptivos:**
   - `socket`, `chats`, `onlineUsers`, `currentChat`, `sendMessage`, `receivedMessage` son ejemplos de nombres descriptivos.

2. **Indentación y formato:**
   - El código mantiene una estructura de indentación consistente y utiliza espacios en blanco de manera efectiva.

3. **Comentarios claros:**
   - Los comentarios en línea explican las funciones de cada bloque de código:

```jsx
// Get the chat in chat section
useEffect(() => {
  const getChats = async () => {
    try {
      const { data } = await userChats(user._id);
      setChats(data);
      console.log(data);
    } catch (error) {
      console.log(error);
    }
  };
  getChats();
}, [user._id]);

// Connect to Socket.io
useEffect(() => {
  socket.current = io("ws://localhost:8800");
  socket.current.emit("new-user-add", user._id);
  socket.current.on("get-users", (users) => {
    setOnlineUsers(users);
  });
}, [user]);
```

4. **Separación de preocupaciones:**
   - Las funciones `checkOnlineStatus`, `handleChatClick`, `handleSendMessage` tienen responsabilidades bien definidas.

5. **Reutilización de código:**
   - La función `checkOnlineStatus` se encarga de verificar el estado en línea de un miembro del chat.

6. **Evitar redundancia:**
   - Se utiliza el estado `sendMessage` para evitar el envío de mensajes innecesarios al servidor.

7. **Uso adecuado de espacios en blanco:**
   - El código utiliza espacios en blanco para separar visualmente las partes de la interfaz izquierda y derecha.

8. **Uso de destructuring:**
   - Ejemplo de destructuring en el código:

```jsx
const { user } = useSelector((state) => state.authReducer.authData);
```

9. **Manejo de eventos:**
   - Los manejadores de eventos `onClick` se utilizan para gestionar la interacción del usuario:

```jsx
<Conversation
  data={chat}
  currentUser={user._id}
  online={checkOnlineStatus(chat)}
  onClick={() => handleChatClick(chat)}
/>
```

10. **Uso de `map` para generar elementos:**
    - Se utiliza el método `map` para generar elementos en la lista de chats:

```jsx
{chats.map((chat) => (
  <div key={chat.id} onClick={() => handleChatClick(chat)}>
    <Conversation
      data={chat}
      currentUser={user._id}
      online={checkOnlineStatus(chat)}
    />
  </div>
))}
```


#### 5.1.3 Código Limpio en el Componente Conversation

Sea componente `Conversation.jsx` de la carpeta `Conversation`

1. **Nombres descriptivos:**
   - `data`, `currentUser`, `online`, `userData`, `dispatch`, `getUserData` son ejemplos de nombres descriptivos.

2. **Indentación y formato:**
   - El código mantiene una estructura de indentación consistente y utiliza espacios en blanco de manera efectiva.

3. **Comentarios claros:**
   - Se incluyen comentarios que explican el propósito de las secciones clave:

```jsx
// Obtener datos del usuario y mostrar en el componente de conversación
useEffect(() => {
  const userId = data.members.find((id) => id !== currentUser);
  
  const getUserData = async () => {
    try {
      const { data } = await getUser(userId);
      setUserData(data);
      dispatch({ type: "SAVE_USER", data: data });
    } catch (error) {
      console.log(error);
    }
  };

  getUserData();
}, []);
```

4. **Separacion de preocupaciones:**
   - El efecto `useEffect` se utiliza para separar la lógica de obtención de datos del usuario y el dispatch de Redux.

5. **Reutilización de código:**
   - Se reutiliza el estado `userData` para manejar los datos del usuario y evitar la duplicación.

6. **Evitar redundancia:**
   - La imagen de perfil predeterminada se maneja de manera coherente, ya sea con una imagen personalizada o una imagen predeterminada.

7. **Uso adecuado de espacios en blanco:**
   - El código utiliza espacios en blanco para separar visualmente las secciones lógicas y mejorar la legibilidad.

8. **Uso de operador ternario:**
   - Se utiliza un operador ternario para mostrar el estado en línea del usuario:

```jsx
<span style={{ color: online ? "#51e200" : "" }}>
  {online ? "Online" : "Offline"}
</span>
```

9. **Manejo de propiedades:**
   - Las propiedades `data`, `currentUser` y `online` se manejan de manera adecuada y se utilizan en el componente.

10. **Uso de destructuring:**
    - Ejemplo de destructuring en el código:

```jsx
const { data } = await getUser(userId);
```

11. **Envolvimiento adecuado:**
    - El componente `Conversation` está envuelto en un fragment para evitar elementos adicionales en el DOM.
   



#### 5.1.4 Código Limpio en el Componente PostShare

Sea componente `PostShare.jsx` de la carpeta `PostShare`

1. **Nombres descriptivos:**
   - `dispatch`, `user`, `loading`, `image`, `desc`, `serverPublic`, `onImageChange`, `imageRef`, `handleUpload`, `resetShare` son ejemplos de nombres descriptivos.

2. **Indentación y formato:**
   - El código mantiene una estructura de indentación consistente y utiliza espacios en blanco de manera efectiva.

3. **Comentarios claros:**
   - Los comentarios en línea explican el propósito de algunas funciones y secciones:

```jsx
// handle Image Change
const onImageChange = (event) => {
  if (event.target.files?.[0]) {
    let img = event.target.files[0];
    setImage(img);
  }
};

// Reset Post Share
const resetShare = () => {
  setImage(null);
  desc.current.value = "";
};
```

4. **Separacion de preocupaciones:**
   - El componente `PostShare` se encarga de la interfaz de usuario y la lógica de carga de publicaciones.

5. **Reutilización de código:**
   - La lógica de reseteo se coloca en una función `resetShare` para evitar duplicación.

6. **Evitar redundancia:**
   - Se evita la redundancia en el manejo del estado de la imagen y el campo de descripción.

7. **Uso adecuado de espacios en blanco:**
   - El código utiliza espacios en blanco para separar visualmente las secciones lógicas y mejorar la legibilidad.

8. **Uso de iconos:**
   - Se utilizan iconos para representar diferentes opciones de publicación.

9. **Uso de eventos y acciones:**
   - Los eventos `onClick` y `onChange` se utilizan para manejar la interacción del usuario.

10. **Manejo de propiedades:**
    - Se manejan las propiedades `user` y `loading` utilizando `useSelector`.

11. **Uso de formularios:**
    - Se utiliza un formulario para recopilar la información de la publicación.

12. **Uso de destructuring:**
    - Ejemplo de destructuring en el código:


#### 5.1.5 Codigo Limpio en el Componente User

Sea componente `User.jsx` de la carpeta `User`

1. **Nombres descriptivos:**
   - `publicFolder`, `user`, `dispatch`, `following`, `handleFollow` son ejemplos de nombres descriptivos.

2. **Indentación y formato:**
   - El código mantiene una estructura de indentación consistente y utiliza espacios en blanco de manera efectiva.

3. **Comentarios claros:**
   - Los comentarios en línea explican el propósito de algunas secciones del código:

```jsx
// Manejo del estado de seguir / no seguir y envío a Redux
const handleFollow = () => {
  following
    ? dispatch(unfollowUser(person._id, user))
    : dispatch(followUser(person._id, user));
  setFollowing((prev) => !prev);
};
```

4. **Separación de preocupaciones:**
   - El componente `User` se encarga de mostrar información de un usuario y gestionar el seguimiento.

5. **Reutilización de código:**
   - Se reutiliza la lógica para manejar el estado de "following" en la función `handleFollow`.

6. **Evitar redundancia:**
   - Se evita la redundancia en la construcción de la URL de la imagen de perfil.

7. **Uso adecuado de espacios en blanco:**
   - El código utiliza espacios en blanco para separar visualmente las secciones lógicas y mejorar la legibilidad.

8. **Uso de propiedades y datos:**
   - La propiedad `person` se utiliza para mostrar la información del usuario.

9. **Uso de botones y eventos:**
   - El evento `onClick` se utiliza para manejar el seguimiento y no seguimiento del usuario.

10. **Uso de estados y actualización:**
    - El estado `following` se utiliza para reflejar el estado actual de seguimiento.

11. **Uso de destructuring:**
    - Ejemplo de destructuring en el código:

```jsx
const { user } = useSelector((state) => state.authReducer.authData);
```

12. **Uso de operador ternario:**
    - Se utiliza un operador ternario para determinar el texto del botón de seguimiento:

```jsx
{following ? "Unfollow" : "Follow"}
```


#### 5.1.6 Codigo Limpio en el Componente FollowersModal

Sea componente `FollowersModal.jsx` de la carpeta `FollowersModal`

1. **Nombres descriptivos:**
   - `theme`, `modalOpened`, `setModalOpened` son ejemplos de nombres descriptivos.

2. **Indentación y formato:**
   - El código mantiene una estructura de indentación consistente y utiliza espacios en blanco de manera efectiva.

3. **Comentarios claros:**
   - No se necesitan comentarios adicionales ya que el código es bastante legible en sí mismo.

4. **Separación de preocupaciones:**
   - El componente `FollowersModal` se encarga de mostrar un modal con los seguidores.

5. **Uso adecuado de espacios en blanco:**
   - El código utiliza espacios en blanco para separar visualmente las secciones lógicas y mejorar la legibilidad.

6. **Uso de propiedades:**
   - Las propiedades `modalOpened` y `setModalOpened` se utilizan para manejar la apertura y cierre del modal.

7. **Uso de componentes externos:**
   - El componente utiliza `Modal` de la biblioteca Mantine para mostrar el modal.

8. **Configuración de estilo y apariencia:**
   - El modal tiene configuraciones de estilo y apariencia, como colores de superposición y tamaño.

```jsx
const theme = useMantineTheme();
return (
  <Modal
    overlayColor={
      theme.colorScheme === "dark"
        ? theme.colors.dark[9]
        : theme.colors.gray[2]
    }
    overlayOpacity={0.55}
    overlayBlur={3}
    size="55%"
    opened={modalOpened}
    onClose={() => setModalOpened(false)}
  >
    <FollowersCard location='modal' />
  </Modal>
);
```


#### 5.1.7 Codigo Limpio en el Componente InfoCard

Sea componente `InfoCard.jsx` de la carpeta `InfoCard`

1. **Nombres descriptivos:**
   - `dispatch`, `params`, `modalOpened`, `profileUserId`, `profileUser`, `handleLogOut` son ejemplos de nombres descriptivos.

2. **Indentación y formato:**
   - El código mantiene una estructura de indentación consistente y utiliza espacios en blanco de manera efectiva.

3. **Comentarios claros:**
   - No se necesitan comentarios adicionales ya que el código es bastante legible en sí mismo.

4. **Separación de preocupaciones:**
   - El componente `InfoCard` se encarga de mostrar información de perfil y opciones de edición.

5. **Uso adecuado de espacios en blanco:**
   - El código utiliza espacios en blanco para separar visualmente las secciones lógicas y mejorar la legibilidad.

6. **Uso de propiedades y datos:**
   - Las propiedades `modalOpened`, `setModalOpened`, `data` se utilizan para manejar la edición del perfil.

7. **Uso de componentes externos:**
   - El componente utiliza `ProfileModal` para mostrar un modal de edición de perfil.

8. **Uso de enrutamiento:**
   - Se utiliza `useParams` para obtener el parámetro de la URL.

9. **Uso de Redux:**
   - Se utiliza `useDispatch` y `useSelector` para manejar acciones y el estado global.

10. **Uso de eventos y acciones:**
    - El evento `onClick` se utiliza para manejar la apertura del modal de edición y el cierre de sesión.

11. **Uso de efectos y actualización:**
    - Se utiliza `useEffect` para cargar los detalles del perfil del usuario y reaccionar a cambios.

12. **Uso de operador ternario:**
    - Se utiliza un operador ternario para mostrar el icono de edición y el botón de cierre de sesión.

```jsx
const theme = useMantineTheme();
return (
  <Modal
    overlayColor={
      theme.colorScheme === "dark"
        ? theme.colors.dark[9]
        : theme.colors.gray[2]
    }
    overlayOpacity={0.55}
    overlayBlur={3}
    size="55%"
    opened={modalOpened}
    onClose={() => setModalOpened(false)}
  >
    <ProfileModal
      modalOpened={modalOpened}
      setModalOpened={setModalOpened}
      data={user}
    />
  </Modal>
);
```


#### 5.1.8 Codigo Limpio en el Componente LogoSearch

Sea componente `LogoSearch.jsx` de la carpeta `LogoSearch`

1. **Nombres descriptivos:**
   - `LogoSearch`, `unsalogoPrincipal` son ejemplos de nombres descriptivos.

2. **Indentación y formato:**
   - El código mantiene una estructura de indentación consistente y utiliza espacios en blanco de manera efectiva.

3. **Comentarios claros:**
   - No se necesitan comentarios adicionales ya que el código es bastante legible en sí mismo.

4. **Separación de preocupaciones:**
   - El componente `LogoSearch` se encarga de mostrar el logo y la barra de búsqueda.

5. **Uso adecuado de espacios en blanco:**
   - El código utiliza espacios en blanco para separar visualmente las secciones lógicas y mejorar la legibilidad.

6. **Uso de componentes externos:**
   - Se utilizan íconos de varias bibliotecas para mostrar íconos de búsqueda.

```jsx
const LogoSearch = () => {
  return (
    <div className="LogoSearch">
      <DiJqueryUiLogo className="unsalogoPrincipal" />
      <div className="Search">
        <input type="text" placeholder="#Explore" />
        <div className="">
          <BiSolidSearchAlt2 className="unsa" />
        </div>
      </div>
    </div>
  );
};
```



#### 5.1.9 Codigo Limpio en el Componente ChatBox

Sea componente `ChatBox.jsx` de la carpeta `ChatBox`

1. **Nombres descriptivos:**
   - `userData`, `messages`, `newMessage`, `handleChange`, `scroll`, `imageRef`, `handleSend` son ejemplos de nombres descriptivos.

2. **Indentación y formato:**
   - El código mantiene una estructura de indentación consistente y utiliza espacios en blanco de manera efectiva.

3. **Comentarios claros:**
   - Los comentarios en línea explican el propósito de algunas secciones del código:

```jsx
// Always scroll to last Message
useEffect(() => {
  scroll.current?.scrollIntoView({ behavior: "smooth" });
}, [messages]);

// Receive Message from parent component
useEffect(() => {
  if (receivedMessage !== null && receivedMessage.chatId === chat._id) {
    setMessages([...messages, receivedMessage]);
  }
}, [receivedMessage]);
```

4. **Separación de preocupaciones:**
   - El componente `ChatBox` se encarga de mostrar la conversación y gestionar el envío y recepción de mensajes.

5. **Reutilización de código:**
   - La lógica de manejo de mensajes y actualización de estados se coloca en funciones separadas.

6. **Evitar redundancia:**
   - Se evita la redundancia en la construcción de la URL de la imagen de perfil.

7. **Uso adecuado de espacios en blanco:**
   - El código utiliza espacios en blanco para separar visualmente las secciones lógicas y mejorar la legibilidad.

8. **Uso de ciclos y listas:**
   - El componente utiliza el método `map` para iterar y mostrar cada mensaje en la conversación.

9. **Uso de estados y actualización:**
   - Los estados `messages` y `newMessage` se utilizan para manejar la conversación y la entrada de texto.

10. **Uso de eventos y acciones:**
    - Los eventos `onChange`, `onClick` se utilizan para manejar la interacción del usuario.

11. **Uso de destructuring:**
    - Ejemplo de destructuring en el código:

```jsx
const { user } = useSelector((state) => state.authReducer.authData);
```

12. **Uso de componentes externos:**
    - El componente utiliza `InputEmoji` para manejar la entrada de texto con emojis.

13. **Manejo de referencias:**
    - Se utilizan referencias `scroll` y `imageRef` para manejar el desplazamiento y la carga de imágenes.


## Estilos de Programacion

## Estilos de Programacion generales
## _Estilo RestFul_
La implementación del estilo RESTful en el código proporcionado se centra en la creación de una API que sigue los principios y restricciones de REST (REpresentational State Transfer) para construir una interfaz interactiva entre un cliente y un servidor. A continuación, explicaré cómo se implementan los principios RESTful en el código detalladamente:

1. **Separación entre Cliente y Servidor:**
La separación entre cliente y servidor se logra al utilizar Express, una librería de Node.js, para crear el servidor y definir las rutas y controladores necesarios para manejar las solicitudes HTTP. Por otro lado, el cliente se encarga de hacer las solicitudes HTTP al servidor para obtener o enviar datos.

2. **Statelessness (Sin estado):**
RESTful implica que cada solicitud del cliente al servidor debe contener toda la información necesaria para que el servidor pueda procesar la solicitud sin necesidad de almacenar el estado del cliente en el servidor. En este código, cada solicitud contiene la información requerida en el cuerpo de la solicitud (por ejemplo, datos JSON) o en los parámetros de la URL (por ejemplo, ID en la ruta).

3. **Uniform Interface (Interfaz uniforme):**
En una interfaz uniforme RESTful, los recursos son identificados y manipulados a través de URLs. El servidor proporciona representaciones de recursos en formatos estándar (como JSON) y los clientes interactúan con estos recursos utilizando métodos HTTP (GET, POST, PUT, DELETE). En el código, podemos ver cómo se definen las rutas utilizando `app.use(chatRoutes)` y cómo se manejan las solicitudes GET, POST, PUT y DELETE en las rutas definidas en el archivo `chat.routes.js`.

4. **Recursos y Métodos HTTP:**
RESTful utiliza recursos (por ejemplo, una entidad de base de datos) como conceptos clave y los expone a través de URLs para que los clientes puedan interactuar con ellos mediante métodos HTTP. En este código, se están utilizando las rutas y los métodos HTTP para interactuar con los recursos de la aplicación, como la obtención de mensajes de chat, el envío de mensajes, etc.

5. **Recursos y Representación de Recursos:**
En RESTful, cada recurso tiene una representación, que suele ser en formato JSON o XML. La representación es lo que el servidor devuelve al cliente cuando se realiza una solicitud para un recurso en particular. En el código, vemos cómo se devuelven los mensajes de chat en formato JSON cuando se realiza una solicitud para obtener los mensajes.

La implementación del estilo RESTful en el código se logra al crear una API que sigue los principios y restricciones de REST. Se definen rutas y controladores para cada recurso, y el cliente interactúa con estos recursos utilizando métodos HTTP y URLs. Los datos se intercambian en formato JSON entre el cliente y el servidor, lo que proporciona una interfaz uniforme y sin estado para una comunicación efectiva entre ambas partes.

- index.js
```javascript
import express from "express";
import bodyParser from "body-parser";
import cors from "cors";
import dotenv from "dotenv";
import mongoose from "mongoose";

// routes
import AuthRoute from './routes/AuthRoute.js'
import UserRoute from './Users/Routes/UserRoute.js'
import PostRoute from './Posts/Routes/PostRoute.js'
import UploadRoute from './Posts/Routes/UploadRoute.js'
import ChatRoute from './Messages/Routes/ChatRoute.js'
import MessageRoute from './Messages/Routes/MessageRoute.js'

const app = express();


// middleware
app.use(bodyParser.json({ limit: "30mb", extended: true }));
app.use(bodyParser.urlencoded({ limit: "30mb", extended: true }));
app.use(cors());
// to serve images inside public folder
app.use(express.static('public')); 
app.use('/images', express.static('images'));


dotenv.config();
const PORT = process.env.PORT;

const CONNECTION =process.env.MONGODB_CONNECTION;
mongoose
  .connect(CONNECTION, { useNewUrlParser: true, useUnifiedTopology: true })
  .then(() => app.listen(PORT, () => console.log(`Listening at Port ${PORT}`)))
  .catch((error) => console.log(`${error} did not connect`));


app.use('/auth', AuthRoute);
app.use('/user', UserRoute)

app.use('/posts', PostRoute)
app.use('/upload', UploadRoute)

app.use('/chat', ChatRoute)
app.use('/message', MessageRoute)
```


## 1. Estilo de Programación "Things" (The Kingdom of Nouns)

El estilo de programación "Things", también conocido como "The Kingdom of Nouns", es un enfoque orientado a objetos para organizar y estructurar el código. En este estilo, el problema se descompone en "cosas" (things) que tienen sentido dentro del dominio del problema. Cada "cosa" es una cápsula de datos que expone procedimientos para interactuar con el mundo exterior. La comunicación con los datos internos de una cosa siempre se realiza a través de estos procedimientos, nunca accediendo directamente a los datos.

Este enfoque promueve la encapsulación y la abstracción, lo que facilita el diseño modular y mantenible del software. Cada cosa representa un concepto en el dominio del problema y encapsula su estado y comportamiento, lo que permite cambios internos sin afectar el resto del sistema.



### Componente `LogoSearch`

```jsx
import React from "react";
import Logo from "../../img/logo.png";
import './LogoSearch.css'
import {UilSearch} from '@iconscout/react-unicons';
import {BiSolidSearchAlt2} from "react-icons/bi";
import {DiJqueryUiLogo} from "react-icons/di";

const LogoSearch = () => {
    return (
        <div className="LogoSearch">
            <DiJqueryUiLogo className="unsalogoPrincipal"/>
            {/* <img src={Logo} alt=""/> */}
            <div className="Search">
                <input type="text" placeholder="#Explore"/>
                <div className="">
                    {/* <UilSearch/> */}
                    <BiSolidSearchAlt2 className="unsa"/>
                </div>
            </div>
        </div>
    );
};

export default LogoSearch;
```


**Cookbook (Recetario):** Se utiliza el componente `DiJqueryUiLogo` y `BiSolidSearchAlt2` de bibliotecas de iconos como "recetas" predefinidas para incorporar iconos en la interfaz de usuario.

**Abstract Things (Cosas Abstractas):** Utiliza componentes abstractos para representar elementos visuales, como iconos.

**Code Golf (Golf de código):** El código es relativamente corto, pero no parece optimizado para minimizar su longitud al máximo.

**The One (El Elegido):** El componente `LogoSearch` podría considerarse el "Elegido" para representar la parte de la interfaz de usuario que muestra el logotipo y la barra de búsqueda.

---

### Componente `ChatBox`

```jsx
import React, { useEffect, useState, useRef } from "react";
import { addMessage, getMessages } from "../../api/MessageRequests";
import { getUser } from "../../api/UserRequests";
import "./ChatBox.css";
import { format } from "timeago.js";
import InputEmoji from 'react-input-emoji'

const ChatBox = ({ chat, currentUser, setSendMessage,  receivedMessage }) => {
  const [userData, setUserData] = useState(null);
  const [messages, setMessages] = useState([]);
  const [newMessage, setNewMessage] = useState("");

  const handleChange = (newMessage)=> {
    setNewMessage(newMessage)
  }

  // fetching data for header
  useEffect(() => {
    const userId = chat?.members?.find((id) => id !== currentUser);
    const getUserData = async () => {
      try {
        const { data } = await getUser(userId);
        setUserData(data);
      } catch (error) {
        console.log(error);
      }
    };

    if (chat !== null) getUserData();
  }, [chat, currentUser]);

  // fetch messages
  useEffect(() => {
    const fetchMessages = async () => {
      try {
        const { data } = await getMessages(chat._id);
        setMessages(data);
      } catch (error) {
        console.log(error);
      }
    };

    if (chat !== null) fetchMessages();
  }, [chat]);

  // Always scroll to last Message
  useEffect(()=> {
    scroll.current?.scrollIntoView({ behavior: "smooth" });
  },[messages])

  // Send Message
  const handleSend = async(e)=> {
    e.preventDefault()
    const message = {
      senderId : currentUser,
      text: newMessage,
      chatId: chat._id,
    }
    const receiverId = chat.members.find((id)=>id!==currentUser);
    // send message to socket server
    setSendMessage({...message, receiverId})
    // send message to database
    try {
      const { data } = await addMessage(message);
      setMessages([...messages, data]);
      setNewMessage("");
    }
    catch
    {
      console.log("error")
    }
  }

  // Receive Message from parent component
  useEffect(()=> {
    console.log("Message Arrived: ", receivedMessage)
    if (receivedMessage !== null && receivedMessage.chatId === chat._id) {
      setMessages([...messages, receivedMessage]);
    }
  },[receivedMessage])

  const scroll = useRef();
  const imageRef = useRef();
  return (
    <>
      <div className="ChatBox-container">
        {chat ? (
          <>
            {/* chat-header */}
            <div className="chat-header">
              <div className="follower">
                <div>
                  <img
                    src={
                      userData?.profilePicture
                        ? process.env.REACT_APP_PUBLIC_FOLDER +
                          userData.profilePicture
                        : process.env.REACT_APP_PUBLIC_FOLDER +
                          "defaultProfile.png"
                    }
                    alt="Profile"
                    className="followerImage"
                    style={{ width: "50px", height: "50px" }}
                  />
                  <div className="name" style={{ fontSize: "0.9rem" }}>
                    <span>
                      {userData?.firstname} {userData?.lastname}
                    </span>
                  </div>
                </div>
              </div>
              <hr
                style={{
                  width: "95%",
                  border: "0

.1px solid #ececec",
                  marginTop: "20px",
                }}
              />
            </div>
            {/* chat-body */}
            <div className="chat-body" >
              {messages.map((message) => (
                <>
                  <div ref={scroll}
                    className={
                      message.senderId === currentUser
                        ? "message own"
                        : "message"
                    }
                  >
                    <span>{message.text}</span>{" "}
                    <span>{format(message.createdAt)}</span>
                  </div>
                </>
              ))}
            </div>
            {/* chat-sender */}
            <div className="chat-sender">
              <div onClick={() => imageRef.current.click()}>+</div>
              <InputEmoji
                value={newMessage}
                onChange={handleChange}
              />
              <div className="send-button button" onClick = {handleSend}>Send</div>
              <input
                type="file"
                name=""
                id=""
                style={{ display: "none" }}
                ref={imageRef}
              />
            </div>{" "}
          </>
        ) : (
          <span className="chatbox-empty-message">
            Tap on a chat to start conversation...
          </span>
        )}
      </div>
    </>
  );
};

export default ChatBox;
```

**Cookbook (Recetario):** El uso de componentes predefinidos como `InputEmoji`, la representación visual de mensajes y el manejo de eventos de cambio y clic reflejan un estilo de "recetario".

**Hollywood:** El manejo de la lógica de mensajes, la obtención de usuarios y la comunicación con el servidor a través de API muestran cierta inversión de control.

**Abstract Things (Cosas Abstractas):** El componente `ChatBox` encapsula la lógica para mostrar mensajes, manejar la entrada de texto y la interacción con emojis.

**Infinite Mirror (Espejo Infinito):** Podría haber múltiples instancias del componente `ChatBox` en la aplicación, lo que podría reflejar una replicación similar.

**Pipeline (Tubería):** La lógica de obtención de usuarios, obtención de mensajes, manejo de mensajes y renderizado de la interfaz se puede ver como pasos en un flujo de datos.

**Code Golf (Golf de código):** El código es conciso y utiliza variables para mantener la claridad del flujo de lógica, sin comprometer la legibilidad.

**The One (El Elegido):** El componente `ChatBox` podría considerarse el "Elegido" para coordinar y gestionar la representación visual de la conversación en el chat.

---

### Componente `FollowersCard`

```jsx
import React, { useState } from "react";
import "./FollowersCard.css";
import FollowersModal from "../FollowersModal/FollowersModal";
import { getAllUser } from "../../api/UserRequests";
import User from "../User/User";
import { useSelector } from "react-redux";
const FollowersCard = ({ location }) => {
  const [modalOpened, setModalOpened] = useState(false);
  const [persons, setPersons] = useState([]);
  const { user } = useSelector((state) => state.authReducer.authData);

  useEffect(() => {
    const fetchPersons = async () => {
      const { data } = await getAllUser();
      setPersons(data);
    };
    fetchPersons();
  }, []);

  return (
    <div className="FollowersCard">
      <h3>People you may know</h3>

      {persons.map((person, id) => {
        if (person._id !== user._id) return <User person={person} key={id} />;
      })}
      {!location ? (
        <span onClick={() => setModalOpened(true)}>Show more</span>
      ) : (
        ""
      )}

      <FollowersModal
        modalOpened={modalOpened}
        setModalOpened={setModalOpened}
      />
    </div>
  );
};

export default FollowersCard;
```

**Monolith (Monolito):** El componente `FollowersCard` no es necesariamente un monolito, ya que se centra en mostrar sugerencias de personas y enlaces de navegación.

**Cookbook (Recetario):** El uso de componentes predefinidos como `Modal` y `FollowersCard`, así como la reutilización de patrones para manejar la apertura del modal y mostrar más sugerencias, reflejan un estilo de "recetario".

**Hollywood:** El manejo de la lógica de abrir y cerrar el modal está invertido y se delega en componentes externos como `Modal` y `FollowersModal`.

**Abstract Things (Cosas Abstractas):** El componente `FollowersCard` encapsula la lógica para mostrar sugerencias de personas y utiliza componentes abstractos como `Modal` y enlaces.

**Pipeline (Tubería):** La lógica de apertura del modal y la obtención de sugerencias de personas se pueden ver como pasos en un flujo de datos.

**Code Golf (Golf de código):** El código es conciso y utiliza componentes de biblioteca para representar sugerencias de personas y manejar la apertura del modal.

**The One (El Elegido):** El componente `FollowersCard` podría considerarse el "Elegido" para coordinar y gestionar la representación de sugerencias de personas.

---

### Componente `FollowersModal`

```jsx
import React from "react";
import { Modal, useMantineTheme } from "@mantine/core";
import FollowersCard from "../FollowersCard/FollowersCard";

const FollowersModal = ({ modalOpened, setModalOpened }) => {
  const theme = useMantineTheme();
  return (
    <Modal
      overlayColor={
        theme.colorScheme === "dark"
          ? theme

.colors.dark[9]
          : theme.colors.gray[2]
      }
      overlayOpacity={0.55}
      overlayBlur={3}
      size="55%"
      opened={modalOpened}
      onClose={() => setModalOpened(false)}
    >

    <FollowersCard location='modal'/>
    </Modal>
  );
};

export default FollowersModal;
```

**Cookbook (Recetario):** Utiliza la biblioteca `@mantine/core` para establecer propiedades del modal y contiene un componente `FollowersCard` predefinido.

**Hollywood:** Delega la lógica del modal y su apertura/cierre en la biblioteca `@mantine/core` y en el componente `FollowersCard`.

**Abstract Things (Cosas Abstractas):** El componente `FollowersModal` encapsula la lógica para mostrar un modal y utiliza la abstracción proporcionada por la biblioteca `@mantine/core`.

**Code Golf (Golf de código):** El código es conciso y utiliza propiedades predefinidas de la biblioteca `@mantine/core`.

**The One (El Elegido):** El componente `FollowersModal` podría considerarse el "Elegido" para representar la interacción con modales en la aplicación.

---

### Componente `Post`

```jsx
import React, { useState } from "react";
import "./Post.css";
import Comment from "../../img/comment.png";
import Share from "../../img/share.png";
import Heart from "../../img/like.png";
import NotLike from "../../img/notlike.png";
import { likePost } from "../../api/PostsRequests";
import { useSelector } from "react-redux";

const Post = ({ data }) => {
  const { user } = useSelector((state) => state.authReducer.authData);
  const [liked, setLiked] = useState(data.likes.includes(user._id));
  const [likes, setLikes] = useState(data.likes.length);

  const handleLike = () => {
    likePost(data._id, user._id);
    setLiked((prev) => !prev);
    liked ? setLikes((prev) => prev - 1) : setLikes((prev) => prev + 1);
  };

  return (
    <div className="Post">
      <img
        src={data.image ? process.env.REACT_APP_PUBLIC_FOLDER + data.image : ""}
        alt=""
      />

      <div className="postReact">
        <img
          src={liked ? Heart : NotLike}
          alt=""
          style={{ cursor: "pointer" }}
          onClick={handleLike}
        />
        <img src={Comment} alt="" />
        <img src={Share} alt="" />
      </div>

      <span style={{ color: "var(--gray)", fontSize: "12px" }}>
        {likes} likes
      </span>
      <div className="detail">
        <span>
          <b>{data.name} </b>
        </span>
        <span>{data.desc}</span>
      </div>
    </div>
  );
};

export default Post;
```
**Cookbook (Recetario):** Utiliza imágenes predefinidas para representar elementos visuales como iconos y muestra la cantidad de "me gusta" y comentarios.


**Abstract Things (Cosas Abstractas):** El componente `Post` encapsula la lógica para manejar "me gusta" y la representación visual de la publicación.

**Code Golf (Golf de código):** El código es relativamente conciso y utiliza operaciones condicionales para manejar el estado de "me gusta".

**The One (El Elegido):** El componente `Post` podría considerarse el "Elegido" para representar la interacción de "me gusta" y la visualización de publicaciones en la aplicación.

---

### Componente `NavIcons`

```jsx
import React from "react";
import { UilSetting } from "@iconscout/react-unicons";
import { Link } from "react-router-dom";
import "./Navicons.css";
import { AiFillHome, AiFillBell } from 'react-icons/ai';
import { BsFillGearFill, BsFillChat

DotsFill } from 'react-icons/bs';

const NavIcons = () => {
    return (
        <div className="navIcons">
            <Link to="../home">
                <AiFillHome className="unsa"/>
            </Link>
            <BsFillGearFill className="unsa"/>
            <AiFillBell className="unsa"/>
            <Link to="../chat">
                <BsFillChatDotsFill className="unsa"/>
            </Link>
        </div>
    );
};

export default NavIcons;
```

**Cookbook (Recetario):** Utiliza íconos predefinidos de bibliotecas como `react-icons` y `@iconscout/react-unicons` para representar íconos de navegación.

**Abstract Things (Cosas Abstractas):** El componente `NavIcons` encapsula la lógica para mostrar íconos de navegación y utiliza componentes abstractos para representar elementos visuales.

**Code Golf (Golf de código):** El código es relativamente conciso y utiliza componentes de biblioteca para representar íconos de navegación.

**The One (El Elegido):** El componente `NavIcons` podría considerarse el "Elegido" para representar la parte de la interfaz de usuario relacionada con los íconos de navegación en la aplicación.

---

## Principios SOLID

### 7.1 Descripción

Se explica cómo se aplicaron los principios SOLID (Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion) en el desarrollo del software.

### 7.2 Principio de Responsabilidad Unica(SRP) 

El principio de Responsabilidad Única (SRP) se refiere a que una clase o función debería tener una sola razón para cambiar, es decir, debe tener una única responsabilidad. 
Se exhibe un fragmento de código que demuestra la adhesión a uno o varios principios

```createPost:
export const createPost = async (req, res) => {
    const newPost = new PostModel(req.body);
    try {
        await newPost.save();
        res.status(200).json(newPost);
    } catch (error) {
        res.status(500).json(error);
    }
};
```
### 7.3 Principio de Inversión de Dependencia (DIP) 

El Principio de Inversión de Dependencia (DIP) es uno de los principios SOLID que sugiere cómo estructurar las relaciones entre módulos y componentes dentro de un sistema de software. En lugar de que los módulos de alto nivel dependan directamente de los módulos de bajo nivel, el DIP propone que ambos niveles dependan de abstracciones o interfaces. Esto permite una mayor flexibilidad, mantenibilidad y extensibilidad del código.

Cada una de estas funciones, se puede observar cómo se enfocan en una tarea específica, lo que sugiere que el código sigue el principio de Responsabilidad Única al desglosar cada tarea en funciones separadas y claramente definida SOLID.

 ###Definiriamos una interfaz para el manejo de usuarios:
```createPost:
// IUserService.js
export default class IUserService {
    async createUser(user) {}
    async findUserByUsername(username) {}
    // Otros métodos relevantes...
};
```

Luego, podríamos implementar esta interfaz en el archivo userService.js:
```userService.js
// userService.js
import UserModel from "../Users/Models/userModel.js";

export default class UserService extends IUserService {
    async createUser(user) {
        // Implementación específica para crear un usuario en la base de datos
    }

    async findUserByUsername(username) {
        // Implementación específica para encontrar un usuario por nombre de usuario
    }
    // Otros métodos relevantes...
}

```
Finalmente, en el archivo original, usamos esta interfaz y la implementación concreta a través de la inyección de dependencias: 

```AuthController.js
// userService.js
import UserService from "./userService.js";
import IUserService from "./IUserService.js";
// Otros imports...

// Crear una instancia de UserService (implementación concreta)
const userService = new UserService();

// Ahora podrías usar userService en lugar de UserModel directamente
export const registerUser = async (req, res) => {
    // ...
    try {
        const oldUser = await userService.findUserByUsername(username);
        // ...
        const user = await userService.createUser(newUser);
        // ...
    } catch (error) {
        res.status(500).json({ message: error.message });
    }
};

export const loginUser = async (req, res) => {
    // ...
    try {
        const user = await userService.findUserByUsername(username);
        // ...
    } catch (err) {
        res.status(500).json(err);
    }
};


```

Este enfoque introduce una abstracción (IUserService) y la implementación concreta (UserService) que cumplen con el DIP. El enrutador ahora depende de la interfaz y la implementación concreta, en lugar de depender directamente de UserModel. Esto hace que el codigo sea más flexible, mantenible y extensible, ya que puedes cambiar la implementacion subyacente sin afectar el enrutador.




## Conceptos DDD


A continuación se presenta un análisis de los componentes "Chat", "Auth" y "Home", examinando cómo se relacionan con los conceptos del Domain-Driven Design (DDD) y las buenas prácticas de programación:

### Componente "Chat"

El componente "Chat" esta relacionado con la funcionalidad de mensajería y la gestión de conversaciones entre usuarios. Veamos cómo se relaciona con los conceptos de DDD:

- *Aggregates y Entity*: El componente "Chat" podría representar Aggregates que contienen información sobre conversaciones y mensajes. Cada conversación podría considerarse una entidad del dominio, con propiedades como miembros y mensajes intercambiados.

- *Commands y Events*: Se observa la interacción con el servidor de sockets para enviar y recibir mensajes. Esto podría considerarse como comandos y eventos que representan acciones en el dominio de la mensajería.

- *Repositories*: Aunque no se muestra directamente en el código, es posible que el componente interactúe con repositorios para obtener y almacenar información de conversaciones y mensajes.

```jsx
// Código del Componente "Chat"
import React, { useRef, useState, useEffect } from "react";
import ChatBox from "../../components/ChatBox/ChatBox";
import Conversation from "../../components/Coversation/Conversation";
import LogoSearch from "../../components/LogoSearch/LogoSearch";
import NavIcons from "../../components/NavIcons/NavIcons";
import "./Chat.css";
import { userChats } from "../../api/ChatRequests";
import { useSelector } from "react-redux";
import { io } from "socket.io-client";

const Chat = () => {
  // ... (Otras declaraciones y efectos)

  return (
    <div className="Chat">
      {/* Contenido del chat */}
    </div>
  );
};

export default Chat;
```

### Componente "Auth"

El componente "Auth" gestiona la autenticación de usuarios y el registro en la aplicación. Veamos cómo se relaciona con los conceptos de DDD:

- *Aggregates y Entity*: Si bien no se muestra directamente en el código, el componente podría estar relacionado con entidades del dominio como "Usuarios" y "Cuentas", que son esenciales para la autenticación y el registro.

- *Value Objects*: El componente maneja datos como nombres, contraseñas y confirmación de contraseña, que podrían considerarse como Value Objects que representan atributos de entidades del dominio.

- *Commands y Events*: El componente interactúa con acciones como "logIn" y "signUp", que podrían considerarse comandos que cambian el estado del dominio y generan eventos relacionados con la autenticación y el registro.

```jsx
// Código del Componente "Auth"
import React from "react";
import "./Auth.css";
import Logo from "../../img/logo.png";
import { logIn, signUp } from "../../actions/AuthActions.js";
import { useDispatch, useSelector } from "react-redux";
import { useNavigate } from "react-router-dom";

const Auth = () => {
  // ... (Declaraciones y efectos)

  return (
    <div className="Auth">
      {/* Contenido de autenticación */}
    </div>
  );
};

export default Auth;
```

### Componente "Home"

El componente "Home" parece representar la página principal de la aplicación. Analicemos cómo se relaciona con los conceptos de DDD:

- *Dominio y Aggregates*: El componente podría estar relacionado con la presentación de contenido principal de la aplicación, como publicaciones y perfiles de usuario. Cada publicación podría considerarse un Aggregate que contiene información relevante.

- *UI Composition*: El componente compone la interfaz utilizando subcomponentes como "ProfileSide", "PostSide" y "RightSide". Esto muestra una estructura modular que puede reflejar una organización en capas y composición de UI.

``` jsx
// Código del Componente "Home"
import React from "react";
import PostSide from "../components/PostSide/PostSide";
import ProfileSide from "../components/profileSide/ProfileSide";
import RightSide from "../components/RightSide/RightSide";
import "./Home.css";

const Home = () => {
  return (
    <div className="Home">
      {/* Contenido de la página principal */}
    </div>
  );
};

export default Home;
```

# Para ejecutar el proyecto:
```bash
npm install en la carpeta server
npm install en la carpeta socket
npm install en la carpeta client
npm start en la carpeta server
npm start en la carpeta socket
npm start en la carpeta client
```
