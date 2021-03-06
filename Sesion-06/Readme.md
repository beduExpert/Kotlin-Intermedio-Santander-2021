[`Kotlin-Intermedio`](../Readme.md) > `Sesión 6`


## Sesión 6: Material Design

<div style="text-align: justify;">
  
  
  
### Introducción

Material Design es un sistema que envuelve a una guia de estilo de diseño, herramientas y componentes para aplicaciones móviles y web. La base del concepto de este es que toda la interfaz debe ser representado por materiales, (específicamente papel y tinta) y añade conceptos visuales como textura, representación de luces y sombras o altura.

**¿En qué se basa Material Design?**

Material Design recibe su nombre por estar basado en objetos materiales. Piezas colocadas en un espacio (lugar) y con un tiempo (movimiento) determinado.

Es un diseño donde la profundidad, las superficies, los bordes, las sombras y los colores juegan un papel principal.

Precisamente este diseño basado en objetos es una manera de intentar aproximarse a la realidad, algo que en un mundo donde todo es táctil y virtual es difícil. Material Design quiere guiarse por las leyes de la física, donde las animaciones sean lógicas, los objetos se superpongan pero no puedan atravesarse el uno al otro y demás.

**No es exclusivo**

No debemos pensar en Material Design como ese diseño destinado para las aplicaciones móviles de Android. De hecho, es multiplataforma. Tantos los smartphones, tablets, smartwatches o televisores pueden hacer uso de este diseño. También las páginas webs. Material Design ha sido creado pensando en todos los sistemas, no solo Android.


Puedes consultar la documentación en la siguiente [liga](https://material.io/design)

<img src="../images/md.jpg" >

### 1. Objetivos :dart: 

---

<img src="../images/android-kotlin.png" align="right" height="120" hspace="10">

- Implementar la guía de estilos de _Material Design_.
- Utilizar los componentes de la biblioteca  _com.google.android.material_.
- Adaptar viejas interfaces a este nuevo modelo.


### 2. Contenido :blue_book:

---

<img src="images/card.png" align="right" height="150"> 

#### <ins>Components</ins>

Un component es un _View_ apegado a los estándares y usos de _Material Design_. La biblioteca  _com.google.android.material_ nos provee de clases que pueden reemplazar las _Views_ que hemos utilizado anteriormente (`Buttons`, `ImageViews`, `EditText`, etc.), o que agregan nuevas funcionalidades. Utilizaremos los elementos más básicos.

- [**`EJEMPLO 1`**](Ejemplo-01/Readme.md)
- [**`RETO 1`**](Reto-01/Readme.md)

---

<img src="images/navigation-drawer.png" align="right" height="150"> 

#### <ins>Appbar y Navigation drawer</ins>

Crearemos y personalizaremos la barra superior de nuestra aplicación y añadiremos `items` con funcionalidades. Agregaremos también un `Navigation drawer` con distintas opciones de navegación y datos de perfil.

- [**`EJEMPLO 2`**](Ejemplo-02/Readme.md)


---

<img src="images/palette.png" align="right" height="150"> 

#### <ins>Themes</ins>

Los estilos son recursos que permiten definir una serie de atributos visuales y de comportamiento para los elementos de la UI. Los temas son estilos que definen una serie de características de manera global (para toda la app). En este ejemplo, crearemos y manipularemos estilos para nuestras _Views_ y utilizaremos sus atributos de manera individual para darle estilo a nuestra aplicación. 
- [**`EJEMPLO 3`**](Ejemplo-03/Readme.md)
- [**`RETO 2`**](Reto-02/Readme.md)

---


### 3. Proyecto :hammer:

Adaptaremos nuestro proyecto al _guideline_ de Material Design sustituyendo `Components` y personalizando nuestros _Themes_. Implementaremos `Components` avanzados como una `Appbar` y crearemos transiciones animadas.

- [**`PROYECTO SESIÓN 6`**](Proyecto/Readme.md)

### 4. Postwork :memo:

Con lo aprendido en esta sesión, continúa con la implementación de ___Material Design___ en tu proyecto.

- [**`POSTWORK SESIÓN 6`**](Postwork/Readme.md)

<br/>

[`Anterior`](../Sesion-05/Readme.md) | [`Siguiente`](../Sesion-07/Readme.md)      

</div>

