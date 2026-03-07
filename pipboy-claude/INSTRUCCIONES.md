# 📱 Claude Pip-Boy — Guía para Generar el APK

## ¿Qué es esta app?
Una app estilo Pip-Boy de Fallout con pantalla verde neón que abre claude.ai directamente.
- ✅ 100% gratis — sin API key
- ✅ Ícono personalizado estilo Pip-Boy
- ✅ Pantalla de carga retro animada
- ✅ Abre claude.ai como app nativa
- ✅ Compatible con Android 7+

---

## PASO 1 — Instalar Android Studio
Descargá Android Studio desde:
**developer.android.com/studio**

Durante la instalación acepta todo por defecto e instalá el Android SDK cuando te lo pida.

---

## PASO 2 — Abrir el proyecto

1. Abrí Android Studio
2. Clic en **"Open"** (Abrir proyecto existente)
3. Navegá hasta la carpeta **claude-pipboy**
4. Seleccioná la carpeta y clic en **OK**
5. Esperá que Gradle sincronice (puede tardar unos minutos la primera vez)

---

## PASO 3 — Generar el APK

1. Menú: **Build → Build Bundle(s) / APK(s) → Build APK(s)**
2. Esperá ~2-3 minutos
3. Aparece notificación **"APK generated"** → clic en **"locate"**
4. El APK está en:
   `app/build/outputs/apk/debug/app-debug.apk`

---

## PASO 4 — Instalar en el teléfono

1. Copiá el APK al teléfono (USB, WhatsApp, Google Drive)
2. En el teléfono: **Ajustes → Seguridad → Fuentes desconocidas → Activar**
3. Abrí el APK → **Instalar**
4. ¡Listo! Aparece el ícono "Claude" en tu pantalla 🎮

---

## ¿Problemas?

**"Gradle sync failed"** → File → Sync Project with Gradle Files

**"SDK not found"** → Tools → SDK Manager → instalá Android SDK 33

**"Installation blocked"** → Activá fuentes desconocidas en Seguridad

---

*Claude Pip-Boy — Vault-Tec AI Assistant*
