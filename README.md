

# Portafolio Personal en React

Este es el repositorio del portafolio personal desarrollado en React. El portafolio muestra una colección de proyectos, habilidades y experiencia profesional. Está diseñado con una arquitectura modular, usando componentes reutilizables y gestionando los datos a través de archivos JSON.

## Descripción

El portafolio está dividido en varias secciones:
- **Inicio**: Introducción del perfil profesional.
- **Proyectos**: Lista de proyectos destacados, con descripciones y enlaces.
- **Habilidades**: Una sección que muestra las principales habilidades técnicas.
- **Contacto**: Formulario para que los usuarios se pongan en contacto.

## Tecnologías Utilizadas

- **React**: Biblioteca principal para construir la interfaz de usuario.
- **JavaScript/JSX**: Lenguaje principal del proyecto.
- **CSS**: Para el diseño visual y el estilo de los componentes.
- **JSON**: Los datos de proyectos y habilidades se gestionan a través de archivos JSON en la carpeta `data`.
- **GitHub Pages** o **Netlify**: Para el despliegue del proyecto.

## Instalación y Uso

### Clonar el repositorio

```bash
git clone https://github.com/m1gue21/portfolio.git
cd portfolio
```

### Instalar las dependencias

Asegúrate de tener instalado [Node.js](https://nodejs.org/). Luego, ejecuta el siguiente comando para instalar las dependencias del proyecto:

```bash
npm install
```

### Ejecutar en modo desarrollo

```bash
npm start
```

Esto iniciará el servidor de desarrollo y podrás ver el portafolio en `http://localhost:3000`.

### Desplegar en Producción

Para desplegar el proyecto en producción:

```bash
npm run build
```

Este comando generará los archivos estáticos en la carpeta `build`. Puedes desplegarlos en servicios como GitHub Pages o Netlify.

## Contribuir

Si deseas contribuir a este proyecto:
1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -m 'Añadir nueva funcionalidad'`).
4. Empuja tu rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.
