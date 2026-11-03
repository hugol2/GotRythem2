# GotRythem2

## Aplicación

<p align="center">
  <a href="https://hugol2.github.io/GotRythem2/" target="_blank">
    <strong>▶ Abrir aplicación ejecutable</strong>
  </a>
</p>

Incluye la selección de figuras y colores de los últimos cambios.

La aplicación local requiere que el servidor esté activo. GitHub Pages se actualiza al publicar cambios en la rama `main`.

## Abrir desde otro dispositivo

Inicia el servidor desde la terminal del proyecto:

```bash
python3 -m http.server 8000 --bind 0.0.0.0
```

En Codespaces, abre la pestaña **Ports**, localiza el puerto `8000` y copia su dirección reenviada para abrirla en el otro dispositivo. Si necesitas que sea accesible sin iniciar sesión en GitHub, cambia la visibilidad del puerto a **Public**; cualquiera con el enlace podrá acceder.

Si ejecutas el servidor en un ordenador de tu red local, ambos dispositivos deben estar en la misma red. En ese ordenador, consulta su IP con `hostname -I` y abre `http://IP-DEL-ORDENADOR:8000` desde el otro dispositivo. Puede que tengas que permitir conexiones al puerto `8000` en el firewall.

`localhost:8000` solo funciona en el dispositivo donde se ejecuta el servidor. Para acceder desde cualquier lugar sin dejarlo encendido, usa el enlace de GitHub Pages de arriba después de publicar los cambios.