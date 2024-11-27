# RLCS Map Changer 2.1

**RLCS Map Changer** es una herramienta para gestionar mapas de Rocket League durante series competitivas, como BO5 y BO7. Permite alternar y personalizar mapas fácilmente, asegurando una experiencia fluida para jugadores y organizadores.

---

## 🎮 Características

- Cambia mapas de manera automática o manual.
- Compatible con series BO5 y BO7.
- Modo RLCS para gestionar rotaciones predeterminadas.
- Soporte multilingüe (Español, Inglés, Portugués).
- Interfaz intuitiva y personalizable.
- Hotkeys para una interacción rápida:
  - **CTRL + 1**: Inicia la rotación.
  - **CTRL + 9**: Retrocede en la rotación.

---

## 🎮 Creación

   ```bash
   pyinstaller --icon=_internal/ico/icon.ico --noconsole --name="RLCS Map Changer 2.1" RLCSMapChangerBySanfeGGV2.1.py
   ```

  **Reemplazar carpeta `_internal`**  
   Copia la carpeta `_internal` en el directorio raíz del proyecto. Asegúrate de conservar su estructura original.

---

## 🚀 Uso

1. **Configurar el idioma y la serie**  
   Accede a la pestaña de ajustes para seleccionar el idioma y la modalidad (BO5 o BO7).

2. **Seleccionar mapas**  
   En la pestaña principal, elige el mapa actual y el siguiente en las rotaciones.

3. **Iniciar rotación**  
   Activa el modo automático o manual y presiona las hotkeys para comenzar.

4. **Gestionar rotaciones**  
   Cambia los mapas directamente desde la pestaña de rotación.

---

## 🛠️ Configuración

Los mapas y configuraciones se cargan desde archivos JSON alojados en GitHub. Si deseas personalizarlos, edita:

- `allmaps.json`: Lista completa de mapas disponibles.
- `rlcsmaps.json`: Mapas en modo RLCS.
- `bo5.json`: Mapas en series BO5.
- `bo7.json`: Mapas en series BO7.

---

## 🖥️ Interfaz

- **Pestaña Principal**: Controla las rotaciones manuales y automáticas.
- **Pestaña Rotación**: Administra la serie BO5 o BO7 actual.
- **Pestaña Ajustes**: Cambia idioma, hotkeys y tipo de serie.

---

## 🌟 Agradecimientos

Creado por **@SanfeGG** para mejorar la experiencia competitiva en Rocket League.  
Para más información, visita mi perfil en [GitHub](https://github.com/SanfeGG).
