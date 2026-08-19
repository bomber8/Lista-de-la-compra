# 📋 Instrucciones para Configurar tu Lista de la Compra con NFC

## 🎯 ¿Qué·· vas a conseguir?

Una pegatina NFC que, al tocarla con el móvil, abre automáticamente la lista de la compra familiar donde todos pueden añadir/quitar productos.

---

## 📁 Paso 1: Subir el archivo HTML a Internet

Necesitas que el archivo `lista-compra-familiar.html` esté accesible vía URL. Tienes 3 opciones gratuitas:

### OPCIÓ·N A: GitHub Pages (Recomendada)

1. Crea una cuenta en [GitHub.com](https://github.com)
2. Crea un nuevo repositorio (p.ej: `lista-compra-familiar`)
3. Sube el archivo `lista-compra-familiar.html`
4. Ve a **Settings → Pages**
5. Activa GitHub Pages
6. Tu URL será: `https://tu-usuario.github.io/lista-compra-familiar/lista-compra-familiar.html`

### OPCIÓ·N B: Netlify Drop (Má··s rá­pido)

1. Ve a [Netlify Drop](https://app.netlify.com/drop)
2. Arrastra el archivo HTML
3. Te dará una URL como: `https://random-name.netlify.app/lista-compra-familiar.html`

### OPCIÓ·N C: Vercel

1. Ve a [Vercel](https://vercel.com)
2. Sube el archivo
3. Obtendrá··s una URL similar

### OPCIÓ·N D: Tu propio servidor

Si tienes hosting web, sube el archivo y usa esa URL.

---

## 📱 Paso 2: Programar la pegatina NFC

### Materiales necesarios:
- Pegatina NFC (NTAG213, NTAG215 o NTAG216)
- Móvil con lector NFC (Android o iPhone)
- App para escribir NFC

### Apps recomendadas:

**Para Android:**
- **NFC Tools** (gratis, muy fá­cil)
- **NFC Tasks** (para automatizaciones)

**Para iPhone:**
- **NFC Tools** (iOS 13+)
- La app nativa ya lee NFC automáticamente

### Pasos para programar:

1. **Instala NFC Tools** en tu móvil
2. **Abre la app** y selecciona "Write" (Escribir)
3. **Elige "Add a record" → "URL / URI"**
4. **Introduce la URL** de tu lista (la que obtuviste en el Paso 1)
   - Ejemplo: `https://tu-usuario.github.io/lista-compra-familiar/lista-compra-familiar.html`
5. **Toca "Write"** y acerca la pegatina NFC al móvil
6. **¡Listo!** La pegatina ya está programada

---

## 🏠 Paso 3: Uso en familia

### Cómo usar:

1. **Toca la pegatina** con el móvil (Android o iPhone)
2. Se abrirá·· automáticamente la lista de la compra
3. **Añ···ade productos** escribiendo y pulsando "Añ···adir"
4. **Marca como comprado** tocando el cí­­rculo
5. **Elimina** con el botón 🗑️

### Caracterí··sticas:

✅ **Todos ven la misma lista** (se guarda en el navegador de cada dispositivo)  
✅ **Funciona sin internet** una vez cargada  
✅ **Se puede instalar como app** (añ···adir a pantalla de inicio)  
✅ **Cada usuario queda registrado** (verá··s quién añ­­adió··· cada producto)  
✅ **Estadí··sticas en tiempo real** (total, pendientes, comprados)

---

## 🔧 Paso 4: Instalació···n como App (Opcional)

Para que sea máá··s ráá··pido acceder:

### En Android (Chrome):
1. Abre la URL en Chrome
2. Toca los 3 puntos ⋮
3. Selecciona "Añ···adir a pantalla de inicio"
4. ¡Listo! Tendrá··s un icono como una app

### En iPhone (Safari):
1. Abre la URL en Safari
2. Toca el botón compartir (cuadrado con flecha)
3. Selecciona "Añ···adir a pantalla de inicio"
4. ¡Listo!

---

## 📊 Sincronizació···n entre dispositivos

**Importante:** Esta versió···n usa `localStorage`, lo que significa:

✅ **Ventajas:**
- Funciona sin internet
- Muy ráá··pido
- No necesita servidor

⚠️ **Limitació···n:**
- Cada dispositivo tiene su propia copia
- Para sincronizació···n real entre todos los mñ···viles, necesitarí··­as un backend (Firebase, Supabase, etc.)

### Solució···n para sincronizació···n total:

Si quieres que todos vean exactamente lo mismo en tiempo real:

1. Usa **Google Keep** o **Google Tasks** (compartido en familia)
2. O usa **Any.do** con cuenta familiar
3. O implementa un backend con **Firebase Realtime Database**

---

## 🎨 Personalizació···n

Puedes modificar el archivo HTML para:

- Cambiar colores (edita la secció···n `<style>`)
- Añ···adir categorías (Frutas, Láá··cteos, etc.)
- Poner el nombre de tu familia
- Añ···adir cantidades
- Integrar con APIs de supermercados

---

## 💡 Consejos de uso

1. **Pega la NFC** en la nevera o despensa
2. **Enseñ···a a la familia** cómo usarla la primera vez
3. **Revisad la lista** antes de ir a comprar
4. **Marcad como comprado** mientras hacé··­s la compra
5. **Borrad la lista** cuando volvá··­s (o dejad lo recurrente)

---

## 🛠️ Soporte técnico

Si tienes problemas:

1. **La NFC no se lee:**
   - Asegñ···rate de que el móvil tiene NFC activado
   - Acerca bien la pegatina (zona superior trasera del móvil)
   - Prueba con otra app NFC

2. **La páá··gina no carga:**
   - Verifica que la URL es correcta
   - Comprueba que tienes internet
   - Prueba en otro navegador

3. **Los datos no se guardan:**
   - Asegñ···rate de no estar en modo incó···gnito
   - No borres la caché·· del navegador

---

## 📄 Archivos generados

- `lista-compra-familiar.html` → El programa
- `INSTRUCCIONES-configuracion-NFC.md` → Este archivo

---

## 🚀 Prñ···ximos pasos (mejoras futuras)

Si quieres mejorar el sistema:

1. **Sincronizació···n en la nube** (Firebase/Supabase)
2. **Notificaciones push** ("Falta leche")
3. **Integració···n con supermercados online**
4. **Reconocimiento de voz** para añ­­adir productos
5. **Sugerencias automá··­ticas** basadas en compras anteriores
6. **Modo offline avanzado** con Service Workers

---

## ✨ ¡Disfruta de tu lista inteligente!

Con esto tienes un sistema profesional de lista de la compra accesible con una simple pegatina NFC. 🎉