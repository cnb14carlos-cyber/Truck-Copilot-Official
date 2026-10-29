# 🚛 Truck Copilot

Voice assistant for Euro Truck Simulator 2 and American Truck Simulator.  
Copiloto por voz para Euro Truck Simulator 2 y American Truck Simulator.

**Version / Versión:** 0.3 · Windows x64 · Experimental

---

## 🇬🇧 English

Truck Copilot is a telemetry plugin that provides spoken driving alerts for ETS2 and ATS.

### Features

- Alerts for speeding, low fuel, and truck wear/damage.
- Spoken messages in Spanish, English, and German.
- Selection of compatible Windows SAPI voices installed on your computer.
- Configurable speed limit in km/h or mph.
- Adjustable fuel threshold in litres and wear/damage threshold.
- Voice volume and speaking rate controls.
- Independent switches for each alert and a master switch.
- External settings window opened with Ctrl + F11.
- Separate saved settings for ETS2 and ATS.

The settings interface is in Spanish.

### Download

[Download Truck Copilot 0.3](https://cloud.vento.build/networks/carbank/plugins/TruckCopilot-0.3-win64.zip)

The download may require signing in to Vento.

### Installation

1. Close the game and extract the ZIP.
2. Open the game's installation folder.
3. Copy `dist/TruckCopilot.dll` into:

   `bin\win_x64\plugins`

4. Create the `plugins` folder if it does not exist.
5. Start the game and accept the SDK warning if displayed.
6. Load your profile and press **Ctrl + F11**.
7. Select your voice and settings, then click **Aplicar y guardar**.

When updating, replace the previous `TruckCopilot.dll` with the game closed.

### Requirements

- ETS2 or ATS running on 64-bit Windows.
- A compatible 64-bit Windows SAPI desktop voice.
- Windowed or borderless mode recommended.

Voices are not bundled. Some Windows Narrator/OneCore voices may not appear.

### Important limitations

- Experimental release; compatibility with every game version is not guaranteed.
- The settings panel is an external window, not an in-game overlay.
- Speed alerts use your manually configured limit, not the road's limit.
- Wear/damage alerts use the highest reported value among monitored truck components.
- No GPS turn-by-turn navigation.
- This is a DLL plugin, not an `.scs` Mod Manager file.
- No cloud voice service or AI subscription is required.

### Troubleshooting

**No voice:** select an installed compatible SAPI voice, enable the copilot,
increase the volume, and click **Probar voz y guardar**.

**No alerts:** apply your settings, check the individual alert switches,
load a driving session, and keep the game in the foreground.

**Panel not visible:** use windowed or borderless mode and press Ctrl + F11.

When reporting an issue, include your game version, plugin version,
a description of the problem, and relevant lines from `game.log.txt`.
Remove personal information before sharing logs publicly.

### Uninstall

Close the game and remove `TruckCopilot.dll` from the `plugins` folder.

---

## 🇪🇸 Español

Truck Copilot es un plugin de telemetría que ofrece avisos de conducción
por voz para ETS2 y ATS.

### Características

- Avisos por exceso de velocidad, combustible bajo y desgaste/daños.
- Mensajes hablados en español, inglés y alemán.
- Selección de voces Windows SAPI compatibles instaladas en tu ordenador.
- Límite de velocidad configurable en km/h o mph.
- Umbral de combustible en litros y umbral de desgaste/daños.
- Control de volumen y velocidad de lectura.
- Interruptores independientes para cada aviso e interruptor general.
- Ventana externa de configuración mediante Ctrl + F11.
- Ajustes guardados por separado para ETS2 y ATS.

La interfaz de configuración está en español.

### Descarga

[Descargar Truck Copilot 0.3](https://cloud.vento.build/networks/carbank/plugins/TruckCopilot-0.3-win64.zip)

La descarga puede requerir iniciar sesión en Vento.

### Instalación

1. Cierra el juego y descomprime el ZIP.
2. Abre la carpeta de instalación del juego.
3. Copia `dist/TruckCopilot.dll` en:

   `bin\win_x64\plugins`

4. Crea la carpeta `plugins` si no existe.
5. Inicia el juego y acepta el aviso del SDK si aparece.
6. Carga tu perfil y pulsa **Ctrl + F11**.
7. Selecciona la voz y las opciones; pulsa **Aplicar y guardar**.

Para actualizar, sustituye la DLL anterior con el juego cerrado.

### Requisitos

- ETS2 o ATS en Windows de 64 bits.
- Una voz de escritorio Windows SAPI de 64 bits compatible.
- Se recomienda modo ventana o ventana sin bordes.

No se incluyen voces. Algunas voces de Narrador/OneCore pueden no aparecer.

### Limitaciones importantes

- Versión experimental; no se garantiza compatibilidad con todas las versiones.
- El panel es una ventana externa, no un menú integrado sobre el juego.
- Los avisos de velocidad usan un límite manual, no el de la carretera.
- El aviso de desgaste/daños utiliza el mayor valor de los componentes supervisados.
- No incluye navegación GPS giro a giro.
- Es un plugin DLL, no un archivo `.scs` para el gestor de mods.
- No requiere servicios de voz en la nube ni suscripciones de IA.

### Solución de problemas

**No se oye la voz:** selecciona una voz SAPI compatible, activa el copiloto,
sube el volumen y pulsa **Probar voz y guardar**.

**No hay avisos:** aplica los ajustes, comprueba los interruptores de cada aviso,
carga una sesión de conducción y mantén el juego en primer plano.

**No aparece el panel:** usa modo ventana o sin bordes y pulsa Ctrl + F11.

Para comunicar un fallo, incluye la versión del juego y del plugin,
una descripción y las líneas relevantes de `game.log.txt`.
Elimina los datos personales antes de publicar registros.

### Desinstalación

Cierra el juego y elimina `TruckCopilot.dll` de la carpeta `plugins`.

---

Independent community project. Not affiliated with or endorsed by SCS Software.  
Proyecto independiente de la comunidad. No afiliado ni respaldado por SCS Software.

Third-party SDK files retain their respective licence.  
Los archivos del SDK de terceros conservan su licencia correspondiente.
