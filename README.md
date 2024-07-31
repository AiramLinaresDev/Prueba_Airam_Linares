# AYUDA T PYMES - Página Estática

¡Hola! Soy Airam Linares Ossorio y este es mi proyecto para la prueba técnica de 'AYUDA T PYMES'. He desarrollado una página estática utilizando Astro como framework, siguiendo el diseño proporcionado en Figma.

## Descripción del Proyecto

Este proyecto consiste en una página estática basada en el diseño proporcionado en Figma. La página incluye secciones como consejos de práctica, paquetes asequibles y un pie de página con enlaces útiles y detalles de comunicación.

## Tecnologías Utilizadas

- **Framework:** [Astro](https://astro.build/)
- **Lenguajes:** HTML, CSS, JavaScript
- **Diseño:** Proporcionado por Figma

## Estructura del Proyecto

La estructura del proyecto es la siguiente:

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                          | Action                                           |
| :------------------------------- | :----------------------------------------------- |
| `git clone [URL del repositorio]`| Clona el proyecto de github                      |
| `npm install`                    | Instala todas las dependecias                    |
| `npm run dev`                    | Starts local dev server at `localhost:4321`      |

# Componentes con propiedades

He creado varios componentes con propiedades para que sean lo mas personalizables posible.

```Astro
<!-- Las propiedades timeToComplete, lessons y type son opcionales -->
<ApprodableCard
    title="Training Courses"
    description="We focus on ergonomics and meeting you where you work. It's only a keystroke away."
    image="/src/img/product-cover-3.png"
    sales={15}
    price={16.48}
    salePrice={6.48}
    rate={4.9}
    timeToComplete='2hr 30min'
    lessons='64 lessons'
    type='Progress'
/>

<FaqCard
    title="The quick fox jumps over the lazy dog"
    body="Things on a very small scale behave like nothing "
    href="#"
/>

<CourseCard
    title="2,769 online courses"
    description="The gradual accumulation and small-scale.."
    image="/src/svg/Brain.svg"
/>

<ReviewCard
    image="/src/img/testimonial-user-4.png"
    description="Slate helps you see  how many more days you need to work to reach your financial goal for the month and year."
    PosterName="Regina Miles"
    PosterJob="Designer"
/>
```
