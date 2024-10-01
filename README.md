Actividad

Pregunta 1
¿Cuál es la diferencia entre un componente UI y un componente funcional en React?
Estado y métodos de ciclo de vida: Los Componentes UI tienen su propio estado y métodos de ciclo de vida, mientras que los Componentes Funcionales no los tienen.
Instancias de clase: Los Componentes UI son instancias de una clase, mientras que los Componentes Funcionales son simplemente funciones.
Uso de this: En los Componentes UI, se utiliza this para acceder a las props y el estado, mientras que en los Componentes Funcionales, se utilizan las props directamente.

Pregunta 2
¿Qué son las props en React y cuál es su propósito principal?
son objetos que se pasan de un componente padre a un componente hijo. Estos objetos contienen datos que el componente hijo necesita para renderizar correctamente.
El propósito principal de las props es permitir que los componentes se comuniquen entre sí y compartan datos. De esta manera, los componentes pueden ser reutilizados y 
mantener una lógica de negocio separada.

Pregunta 3:
¿Qué son los children props en React y por qué no se recomienda su uso excesivo?
En React, los children props se refieren a los elementos JSX que se pasan como hijos de un componente. Cuando se utiliza un componente como etiqueta, cualquier contenido dentro de esa etiqueta se pasa como children props al componente.
su uso excesivo puede llevar a problemas de diseño y mantenimiento,
Dificultad para entender la estructura de la aplicación y  Limitaciones para la reutilización de componentes

Pregunta 4:
¿Qué es useState en React y para qué se utiliza principalmente?
En React, useState es un hook que permite a los componentes funcionales mantener un estado local. 
El estado local es una forma de almacenar datos que cambian en un componente y que se utilizan para
renderizar la interfaz de usuario.
Almacenar datos que cambian: Los componentes pueden utilizar useState para almacenar datos que cambian en respuesta a acciones del usuario
Renderizar la interfaz de usuario: El estado local se utiliza para renderizar la interfaz de usuario de manera dinámica




- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
