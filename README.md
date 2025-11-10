# Proyecto de Reconocimiento Multimedia

Este proyecto contiene tres actividades que utilizan **p5.js** y **ml5.js** para reconocimiento de imágenes, dibujos y objetos en video. 


## Estructura del proyecto

- `actividad1.html` → Identificador de imágenes con **MobileNet**.
- `actividad2.html` → Login mediante dibujo con **DoodleNet**.
- `actividad3.html` → Identificación de objetos por cámara y voz.
- `images/` → Carpeta de imágenes de referencia para la actividad 3.
- `models/` → Carpeta de modelos entrenados para la actividad 3 (opcional).

---

## Procedimiento de uso

### 1. Clonar el repositorio
```bash
git clone https://github.com/usuario/proyecto-reconocimiento.git
```

### 2. Abrir los archivos
Abrir los archivos actividad1.html, actividad2.html o actividad3.html en un navegador compatible (Chrome o Firefox recomendado).

### 3. Uso de cada actividad
Actividad 1 - Identificador de imágenes
Selecciona una imagen desde tu dispositivo.

El modelo MobileNet clasificará la imagen y mostrará la etiqueta y la confianza.

Actividad 2 - Login con dibujo
Ingresa tu usuario y contraseña.

Dibuja el código esperado en el canvas.

Si el dibujo coincide con el código registrado, se permitirá el acceso.

Actividad 3 - Identificador con cámara
Permite el acceso a tu cámara.

La cámara capturará objetos y el modelo los clasificará en tiempo real.

La etiqueta del objeto detectado se muestra en el canvas.