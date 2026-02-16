# Mi primer proyecto profesional colaborativo

<!-- hide -->

Por [@marcogonzalo](https://github.com/marcogonzalo) y [otros contribuidores](https://github.com/4GeeksAcademy/first-dashboard-tailwind-css/graphs/contributors) en [4Geeks Academy](https://4geeksacademy.com/)

[![build by developers](https://img.shields.io/badge/build_by-Developers-blue)](https://4geeks.com)
[![4Geeks Academy](https://img.shields.io/twitter/follow/4geeksacademy?style=social&logo=x)](https://x.com/4geeksacademy)

🌐 _These guidelines are also [available in English](./README.md)_.

**Antes de empezar**:

> ¡Te necesitamos! Estos ejercicios se construyen y mantienen en colaboración con personas como tú. Si encuentras algún error 🐞 o falta de ortografía, por favor contribuye y/o repórtalos.

<!-- endhide -->

---

## Tu reto

Estás trabajando en un pequeño equipo de desarrollo dentro de una consultora y acaba de llegar un nuevo proyecto: **una reconocida marca de ropa con sede en Francia** quiere un **prototipo visual y funcional** para su próxima tienda online.

El cliente ha sido claro con los requisitos:

- **SEO bien trabajado** (estructura semántica, contenido indexable, buenas prácticas).
- **Diseño moderno** y consistente.
- **Responsive completo**: móvil, tablet y escritorio.

Antes de avanzar a desarrollo completo, necesitan ver un prototipo que incluya **al menos 5 vistas principales**:

1. **Home**
2. **Catálogo**
3. **Vista de producto**
4. **Carrito**
5. **Formulario de pago (checkout)**

Ha llegado el momento de brillar. La consultora armó un equipo para el proyecto y te asignó a ti y a otra persona para sacarlo adelante.

Tu _project manager_ te ha compartido un documento con la estructura mínima de cada vista para evitar olvidos y asegurar que el prototipo cubra lo que el cliente espera.

### Especificaciones por vista

#### 1) Página de inicio (Home)

- **Barra superior (navbar)** con:
  - Logo
  - Barra de búsqueda
  - Menú de cuenta de usuario
- **Sección Hero** destacando productos especiales o campañas de la marca.
- Dos secciones con listados horizontales (_cards_ de producto):
  - **Nuevos lanzamientos**
  - **Más vendidos**
- **Footer** con secciones:
  - **Categorías:** calzado, camisas, pantalones, accesorios
  - **Legal:** términos y condiciones, política de privacidad, sobre la marca
  - **Contacto**
- **La navbar y el footer se reutilizan** en todas las demás vistas.

#### 2) Catálogo

- Mantiene **navbar y footer**.
- Incluye una **barra de filtros** antes del listado:
  - Filtro por **categoría**
  - Filtro por **talla**
- Listado de productos en **rejilla (grid) 4×5** (20 productos visibles como referencia).

#### 3) Vista de producto

- Diseño en dos columnas:
  - **Izquierda:** foto del producto ocupando aproximadamente **la mitad del ancho**.
  - **Derecha:** información principal del producto:
    - Nombre
    - Código o referencia
    - Talla
    - Precio
    - Selector de cantidad
    - Botón **"Agregar al carrito"**
- Debajo, una sección de **descripción detallada**:
  - Materiales
  - Uso recomendado / escenarios donde se puede usar la prenda

#### 4) Carrito

- Vista completa del carrito (no un panel lateral).
- Listado de productos añadidos con:
  - Miniatura
  - Precio unitario
  - Cantidad
  - Total por producto
- Cuadro de totalización con:
  - Subtotal
  - Impuestos
  - Total
  - Botón **"Comprar"**
- Añadir **3 productos de ejemplo** para mostrar el comportamiento visual.

#### 5) Formulario de pago (Checkout)

Flujo en **3 pasos**:

1. **Datos personales**
2. **Dirección de entrega**
3. **Pago con tarjeta** (datos de tarjeta)

Ahora sí: toca construir un prototipo claro, consistente y responsive que demuestre el potencial de la tienda y facilite la aprobación del cliente. **¡Manos a la obra!** 😁

> **⚠️ IMPORTANTE:** En este proyecto solo usaremos **HTML y Tailwind CSS**. Asegúrate de que tu IA Copiloto **no incluya tecnologías más avanzadas** (por ejemplo, React). Indícalo desde el inicio del trabajo.

---

## 💻 Qué debes hacer

Debes desarrollar un _sitio web_ de e-commerce en colaboración con tu compañer@ de trabajo, empleando buenas prácticas tanto en el desarrollo como en la gestión del proyecto con Git.

Debes aplicar todos los conocimientos adquiridos hasta el momento: **HTML semántico**, **Tailwind**, **Schema.org**, diseño responsivo, **Git**…

Apóyate en la IA para hacer tu trabajo ágilmente, pero poco a poco y con calidad.

Solo deberás hacer las vistas mencionadas anteriormente y conectarlas entre sí:

- [ ] **Home** — barra de navegación, Hero, listado de productos nuevos, listado de productos más comprados, footer
- [ ] **Catálogo** — listado de productos y barra de filtros
- [ ] **Vista de producto** — foto, detalles, precio y descripción
- [ ] **Carrito** — vista completa del contenido con productos, totalización y botón de comprar
- [ ] **Formulario de pago** — datos personales, dirección de entrega y datos de tarjeta

**Respecto a la gestión de cambios:**

- [ ] Trabajar con _ramas_ para cada una de las vistas (te harán más fácil las entregas).
- [ ] Entregar cada rama mediante una _pull request_ (PR) para integrarla luego a la rama principal.
- [ ] Actualizar tu rama antes de entregarla para garantizar que no hay errores ni conflictos.
- [ ] En caso de conflictos, analizar con tu equipo y resolver los problemas en colaboración.
- Es buena opción pedirle a la IA que haga un _commit_ en la rama cada vez que agregues algo que ya ha quedado bien.

---

## ✅ Qué vamos a evaluar

Aplicación de todos los conocimientos adquiridos hasta el momento:

- [ ] **Uso correcto de de HTML semántico**
- [ ] **Uso adecuado de Tailwind CSS**
- [ ] **Correcta diagramación y agrupación de componentes visuales**
- [ ] **Aplicación de diseño responsivo**
- [ ] **Uso de Schema.org**
- [ ] **Uso adecuado de Git**

El proyecto entregado debe tener **al menos 5 documentos HTML** (uno por vista) y su documento de estilos, si corresponde.

---

## 📦 Cómo entregar este proyecto

Sigue los pasos habituales de entrega para subir tu repositorio a GitHub y compártelo según las indicaciones de tu instructor.

---

## 🌱 Cómo iniciar el proyecto

Abre el repositorio de plantilla usando una herramienta de aprovisionamiento como [Codespaces](https://4geeks.com/lesson/what-is-github-codespaces) (recomendado) o clónalo en local:

```bash
https://github.com/4GeeksAcademy/html-hello
```

Sigue los pasos en [cómo comenzar un proyecto de codificación](https://4geeks.com/es/lesson/como-comenzar-un-proyecto-de-codificacion).

💡 **Importante:** Crea un nuevo repositorio en GitHub para tu código, actualiza el remoto (`git remote set-url origin <tu-nueva-url>`) y sube los cambios con `add`, `commit` y `push`.

---

## Contribuidores

Este y muchos otros proyectos son construidos por estudiantes como parte de los [Coding Bootcamps](https://4geeksacademy.com/) de 4Geeks Academy. Por [@marcogonzalo](https://github.com/marcogonzalo) y [otros contribuidores](https://github.com/4GeeksAcademy/first-dashboard-tailwind-css/graphs/contributors). Descubre más sobre [Full-Stack Software Developer](https://4geeksacademy.com/es/coding-bootcamps/programador-full-stack), [Data Science & Machine Learning](https://4geeksacademy.com/es/coding-bootcamps/curso-datascience-machine-learning), [Ciberseguridad](https://4geeksacademy.com/es/coding-bootcamps/curso-ciberseguridad) e [Ingeniería de IA](https://4geeksacademy.com/es/coding-bootcamps/ingenieria-ia).
