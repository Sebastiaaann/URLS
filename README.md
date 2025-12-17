# URLS - Página de Inicio Personalizada 🚀

Una página de inicio personalizada y minimalista para tu navegador con acceso rápido a tus sitios web favoritos.

## 📋 Descripción

URLS es una página de inicio personalizada diseñada para reemplazar la página predeterminada de tu navegador. Ofrece acceso rápido mediante cuadrados de colores a los sitios web más populares, con un diseño limpio y moderno sobre fondo oscuro.

## ✨ Características

- 🎨 **Diseño minimalista** con fondo oscuro (#0f0f0f)
- 🌈 **Colores distintivos** para cada sitio web
- 📱 **Acceso rápido** a 9 sitios populares
- 🖱️ **Interfaz simple** con cuadrados clicables de 250x250px
- ⚡ **Carga rápida** - HTML y CSS puros, sin dependencias

## 🔗 Sitios Incluidos

El proyecto incluye enlaces a los siguientes sitios web:

| Sitio | Color | Descripción |
|-------|-------|-------------|
| YouTube | Rojo (#d12d28) | Plataforma de videos |
| Twitter | Azul (#1DA1F2) | Red social |
| Twitch | Púrpura (#6441A4) | Streaming en vivo |
| Reddit | Naranja (#FF5700) | Foro de comunidades |
| Gmail | Rojo (#D44638) | Correo electrónico |
| WhatsApp | Verde (#28e050) | Mensajería web |
| Instagram | Magenta (#60075a) | Red social de fotos |
| TikTok | Magenta (#60075a) | Videos cortos |
| ChatGPT | Magenta (#60075a) | Asistente de IA |

## 🚀 Instalación

### Opción 1: Usar como Extensión de Nueva Pestaña

1. Clona o descarga este repositorio:
```bash
git clone https://github.com/Sebastiaaann/URLS.git
```

2. Abre tu navegador y ve a la configuración de extensiones:
   - **Chrome/Edge**: `chrome://extensions/`
   - **Firefox**: `about:addons`

3. Activa el "Modo de desarrollador"

4. Carga la extensión sin empaquetar seleccionando la carpeta del proyecto

### Opción 2: Establecer como Página de Inicio

1. Descarga los archivos `index.html` y `style.css`

2. Colócalos en una ubicación permanente en tu computadora

3. En la configuración de tu navegador:
   - **Chrome/Edge**: Configuración → Al iniciar → Abrir una página específica
   - **Firefox**: Opciones → Inicio → Página de inicio y ventanas nuevas
   
4. Establece la ruta completa a tu archivo `index.html` local

### Opción 3: Usar con GitHub Pages

1. Haz un fork de este repositorio

2. Ve a Settings → Pages en tu repositorio

3. Selecciona la rama principal y guarda

4. Accede a tu página en `https://[tu-usuario].github.io/URLS/`

## 🛠️ Personalización

### Cambiar los Enlaces

Edita el archivo `index.html` para modificar las URLs:

```html
<div class="youtube">
    <a href="TU_URL_AQUÍ" style="display:block;height:100%;width:100%"></a>
</div>
```

### Modificar los Colores

Edita el archivo `style.css` para cambiar los colores de fondo:

```css
.youtube {
    background-color: #d12d28; /* Cambia este valor hexadecimal */
}
```

### Agregar Nuevos Sitios

1. Añade un nuevo `div` en `index.html`:
```html
<div class="nuevo-sitio">
    <a href="https://ejemplo.com" style="display:block;height:100%;width:100%"></a>
</div>
```

2. Define el estilo en `style.css`:
```css
.nuevo-sitio {
    height: 250px;
    width: 250px;
    margin-top: 20px;
    margin-left: 10px;
    background-color: #TUCOLOR;
}
```

### Ajustar el Layout

Los cuadrados están organizados en una cuadrícula de 3 columnas. Puedes ajustar:
- `margin-top`: Espaciado vertical
- `margin-left`: Posición horizontal (10px, 275px, 540px para las 3 columnas)
- `height` y `width`: Tamaño de los cuadrados

## 💻 Tecnologías

- HTML5
- CSS3 puro
- Sin frameworks ni dependencias externas

## 🌐 Compatibilidad de Navegadores

✅ Chrome  
✅ Firefox  
✅ Edge  
✅ Safari  
✅ Opera  

## 📸 Vista Previa

La página muestra 9 cuadrados de colores organizados en una cuadrícula de 3x3, cada uno con el color característico del sitio web que representa.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar este proyecto:

1. Haz un fork del repositorio
2. Crea una rama para tu función (`git checkout -b feature/NuevaFuncion`)
3. Haz commit de tus cambios (`git commit -m 'Añadir nueva función'`)
4. Haz push a la rama (`git push origin feature/NuevaFuncion`)
5. Abre un Pull Request

## 📝 Ideas para Mejoras Futuras

- [ ] Agregar íconos/logos a los cuadrados
- [ ] Implementar búsqueda web integrada
- [ ] Añadir reloj y fecha
- [ ] Modo claro/oscuro
- [ ] Efectos hover mejorados
- [ ] Configuración de enlaces mediante panel de control
- [ ] Soporte para más idiomas
- [ ] Widgets personalizables (clima, noticias, etc.)
- [ ] Animaciones de transición
- [ ] Diseño responsive para móviles

## 📄 Licencia

Este proyecto está disponible como código abierto bajo la [Licencia MIT](LICENSE).

## 👤 Autor

**Sebastiaaann**
- GitHub: [@Sebastiaaann](https://github.com/Sebastiaaann)

## 🙏 Agradecimientos

Inspirado en páginas de inicio minimalistas y la necesidad de un acceso rápido a sitios web frecuentes.

---

⭐ Si te gusta este proyecto, ¡dale una estrella en GitHub!
