# Le Verdict

**Que tu oído dicte el veredicto.** Le Verdict es un plugin VST3 de Le Prof para
comparar dos plugins de mastering al mismo volumen, alineados en el tiempo y sin
clics.

**Versión actual:** 1.0.0 · Beta pública · Gratis · Windows 64-bit

*[English below](#english)*

---

## ¿Para qué sirve?

Comparar plugins dentro de tu DAW suele ser lento y engañoso: pistas duplicadas,
niveles igualados a mano y latencias que separan las señales. Y casi siempre gana
el que suena más fuerte, no el que suena mejor.

Le Verdict junta los dos plugins en un solo lugar y quita esas trampas para que
decidas solo con el oído.

## Cómo funciona

Insertas Le Verdict en tu pista o en el master y eliges un plugin VST3 para cada
cadena:

- **Cadena A y cadena B:** cada una aloja el plugin que tú elijas desde su
  engranaje. Puedes abrir la ventana de cada plugin y ajustarlo como siempre.
- **Cambio A/B sin clics:** alternas entre A y B con un fundido de 10 ms. Escuchas
  el plugin, no el corte.
- **Unity Gain:** iguala el nivel de B al de A para que el volumen no decida por
  ti. El panel muestra cuánto se ajustó (B Match).
- **Delta:** escucha solo la diferencia entre los dos plugins (A − B) y descubre
  qué está haciendo cada uno.
- **Bypass:** vuelve a la señal original en cualquier momento.
- **Medición:** LUFS integrado, short-term, true peak y LRA siempre a la vista.
- **Compensación de latencia:** A, B, Delta y Bypass se mantienen alineados
  aunque un plugin use lookahead.
- **Se guarda con tu sesión:** tu DAW recuerda qué plugin hay en cada cadena y
  su configuración.

## Compatibilidad

**Funciona con**
- Plugins VST3 de cualquier desarrollador
- FL Studio (probado)
- Ableton Live, Reaper, Cubase, Studio One y Bitwig (deberían funcionar)
- Windows 10 y 11, 64-bit

**No funciona con**
- Los plugins nativos de tu DAW (Fruity Limiter, el Limiter de Ableton…): solo
  existen dentro de tu DAW y ningún plugin externo puede cargarlos.
- Plugins que solo existen en VST2 o AAX
- macOS, por ahora

## Instalación

1. Descarga y descomprime `LeVerdict-1.0.0-win64.zip`.
2. Copia la carpeta `LeVerdict.vst3` a `C:\Program Files\Common Files\VST3`.
3. Vuelve a escanear los plugins en tu DAW y busca **Le Prof · Le Verdict**.

El plugin todavía no está firmado digitalmente, así que Windows o tu navegador
pueden mostrar una advertencia al descargarlo. Puedes comparar la suma SHA-256
publicada en la página de descarga para verificar que el archivo es el original.

## Sugerencias y reportes de bugs

Es una beta y tu opinión cuenta. Deja tu sugerencia o reporta un bug desde el
formulario de la página de Le Verdict, o escribe a
[leprofmx@gmail.com](mailto:leprofmx@gmail.com).

## Créditos

Hecho por **Le Prof**, DJ y productor de House, Tech House y Latin House.
[Instagram](https://www.instagram.com/leprof.mx/) ·
[Spotify](https://open.spotify.com/intl-es/artist/5M4kYlPCoCVnaY8BzRTLKO) ·
[Apple Music](https://music.apple.com/us/artist/le-prof/1755048266) ·
[TikTok](https://www.tiktok.com/@leprof.mx) ·
[X](https://x.com/leprof_mx) ·
[Facebook](https://www.facebook.com/profile.php?id=61560888995049)

## Licencia

Le Verdict es gratuito y de código cerrado. Puedes usarlo en tus proyectos
personales y comerciales; no está permitido redistribuirlo ni venderlo.
© Le Prof. Todos los derechos reservados.

VST es una marca registrada de Steinberg Media Technologies GmbH.

---

## English

**Let your ears deliver the verdict.** Le Verdict is a VST3 plugin by Le Prof for
comparing two mastering plugins at matched loudness, time-aligned, with no clicks.

**Current version:** 1.0.0 · Public beta · Free · Windows 64-bit

### What it does

Comparing plugins in your DAW is slow and misleading: duplicate tracks,
hand-matched levels and latency that pulls signals apart, and the louder one
almost always wins. Le Verdict puts both plugins in one place and removes those
tricks, so your ears decide.

### How it works

- **Chains A and B:** each hosts the VST3 you pick from its gear menu, with its
  own plugin window.
- **Click-free A/B:** switch with a 10 ms crossfade.
- **Unity Gain:** matches B's level to A (shown as B Match).
- **Delta:** hear only the difference between the two plugins (A − B).
- **Bypass:** back to the original signal at any time.
- **Metering:** integrated and short-term LUFS, true peak and LRA.
- **Latency compensation:** A, B, Delta and Bypass stay aligned, even with
  lookahead plugins.
- **Saved with your session:** your DAW remembers each chain's plugin and
  settings.

### Compatibility

Works with VST3 plugins from any developer, on Windows 10 and 11 (64-bit).
Tested in FL Studio; Ableton Live, Reaper, Cubase, Studio One and Bitwig should
work. It can't load your DAW's built-in plugins, VST2-only or AAX-only plugins,
and it doesn't run on macOS for now.

### Install

1. Download and unzip `LeVerdict-1.0.0-win64.zip`.
2. Copy the `LeVerdict.vst3` folder to `C:\Program Files\Common Files\VST3`.
3. Rescan plugins in your DAW and look for **Le Prof · Le Verdict**.

The plugin isn't digitally signed yet, so Windows may warn you; compare the
published SHA-256 checksum to verify the file.

### Feedback

Send suggestions or bug reports through the form on the Le Verdict page, or
email [leprofmx@gmail.com](mailto:leprofmx@gmail.com).

### License

Le Verdict is free and closed source. You may use it in personal and commercial
projects; redistributing or selling it is not allowed. © Le Prof. All rights
reserved.
