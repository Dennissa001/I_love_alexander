# 📸 GUÍA COMPLETA: Subir Fotos a GitHub (SIN usar servicios externos)

## 🎯 MÉTODO FÁCIL - PASO A PASO

### PASO 1: Preparar las fotos en tu computadora

1. Elige 4 fotos que quieras mostrar
2. Renómbralas exactamente así:
   - `foto1.jpg` (o .png, .jpeg)
   - `foto2.jpg`
   - `foto3.jpg`
   - `foto4.jpg`

**IMPORTANTE:** 
- ✅ Sin espacios
- ✅ Sin tildes
- ✅ Todo en minúsculas
- ✅ Formatos aceptados: .jpg, .jpeg, .png, .gif

---

### PASO 2: Subir las fotos a GitHub

#### **Opción A - Arrastrar archivos (MÁS FÁCIL)**

1. Abre tu repositorio `valentine` en GitHub
2. Click en **"Add file"** → **"Upload files"**
3. Antes de arrastrar nada, mira arriba donde dice: `valentine /`
4. Después de la `/` escribe: `images/`
5. Ahora arrastra tus 4 fotos
6. Verás algo como:
   ```
   valentine / images / foto1.jpg
   valentine / images / foto2.jpg
   valentine / images / foto3.jpg
   valentine / images / foto4.jpg
   ```
7. Abajo en "Commit changes" escribe: "Agregando nuestras fotos 💕"
8. Click en **"Commit changes"**

#### **Opción B - Si la Opción A no funciona**

1. En tu repositorio, click en **"Add file"** → **"Create new file"**
2. En el nombre del archivo escribe: `images/.gitkeep`
3. Click en **"Commit new file"**
4. Ahora entra a la carpeta `images` que se creó
5. Dentro de `images`, click en **"Add file"** → **"Upload files"**
6. Arrastra tus 4 fotos
7. Click en **"Commit changes"**

---

### PASO 3: Verificar que las fotos se subieron

1. En tu repositorio, deberías ver una carpeta llamada `images`
2. Haz click en ella
3. Deberías ver tus 4 fotos listadas:
   - foto1.jpg
   - foto2.jpg
   - foto3.jpg
   - foto4.jpg

---

### PASO 4: El código ya está listo

El archivo `index.html` actualizado ya tiene el código para usar estas fotos:

```javascript
const photos = [
    'images/foto1.jpg',
    'images/foto2.jpg',
    'images/foto3.jpg',
    'images/foto4.jpg'
];
```

**¡No necesitas cambiar nada más!** 🎉

---

## 📝 NOTAS IMPORTANTES:

### ¿Qué pasa si mis fotos tienen otros nombres?

Si tus fotos se llaman diferente (ej: `playa.jpg`, `cumpleaños.png`), puedes:

**Opción 1:** Renombrarlas a foto1.jpg, foto2.jpg, etc.

**Opción 2:** Editar el código en `index.html`:

1. Abre `index.html` en GitHub
2. Click en el ✏️ para editar
3. Busca la línea `const photos = [`
4. Cámbialo por:
```javascript
const photos = [
    'images/playa.jpg',
    'images/cumpleaños.png',
    'images/parque.jpg',
    'images/cena.jpg'
];
```

---

### ¿Puedo usar más de 4 fotos?

¡SÍ! Solo agrega más líneas:

```javascript
const photos = [
    'images/foto1.jpg',
    'images/foto2.jpg',
    'images/foto3.jpg',
    'images/foto4.jpg',
    'images/foto5.jpg',
    'images/foto6.jpg'
];
```

---

### ¿Qué tamaño deben tener las fotos?

- **Recomendado:** 500px x 500px a 1000px x 1000px
- **Máximo en GitHub:** Cada archivo debe ser menor a 25 MB
- La página las redimensionará automáticamente

---

## 🔧 SOLUCIÓN DE PROBLEMAS

### "Las fotos no aparecen, solo veo emojis"

**Causas posibles:**

1. **Los nombres no coinciden**
   - Verifica que las fotos se llamen exactamente `foto1.jpg`, `foto2.jpg`, etc.
   - Revisa mayúsculas/minúsculas

2. **Las fotos no están en la carpeta `images`**
   - Entra a tu repositorio
   - Verifica que exista la carpeta `images`
   - Verifica que las fotos estén dentro de esa carpeta

3. **Esperando que cargue GitHub Pages**
   - Después de subir las fotos, espera 1-2 minutos
   - Recarga la página con Ctrl+F5 (o Cmd+Shift+R en Mac)

### "GitHub no me deja crear la carpeta images"

- Usa la Opción B del PASO 2
- Primero crea el archivo `images/.gitkeep`
- Luego sube las fotos dentro de esa carpeta

---

## ✅ CHECKLIST FINAL

Antes de enviarle el link a tu novio, verifica:

- [ ] Carpeta `images` existe en tu repositorio
- [ ] Las 4 fotos están dentro de `images`
- [ ] Los nombres son: foto1.jpg, foto2.jpg, foto3.jpg, foto4.jpg
- [ ] GitHub Pages está activado en Settings
- [ ] Esperaste 1-2 minutos después de subir las fotos
- [ ] Probaste abrir el link en tu celular primero

---

## 🎉 ¡LISTO!

Ahora tu página mostrará TUS fotos en lugar de los emojis.

Las fotos están en TU repositorio de GitHub, totalmente privadas dentro de tu cuenta.
Solo las personas que tengan el link podrán verlas.
