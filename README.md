# Poop: base de aplicación Android en Kotlin

[![Kotlin](https://img.shields.io/badge/Kotlin-1.3.20-7F52FF?logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Android](https://img.shields.io/badge/Android-API%2017%2B-3DDC84?logo=android&logoColor=white)](https://developer.android.com/)
[![Gradle](https://img.shields.io/badge/Gradle-4.6-02303A?logo=gradle&logoColor=white)](https://gradle.org/)
[![Estado](https://img.shields.io/badge/estado-plantilla%20inicial-lightgrey)](#estado-del-proyecto)

Proyecto Android creado con Android Studio a partir de la plantilla de actividad vacía (`MainActivity`) para el paquete `com.instanceshape.poop`. Sirve como punto de partida de una aplicación Kotlin.

## Estado del proyecto

Es una plantilla inicial: la pantalla principal solo muestra un texto de bienvenida y no incluye lógica de negocio. Se conserva como base de arranque.

## Estructura

```
.
├── app/
│   ├── build.gradle                         # Módulo de la aplicación (SDK 28, minSdk 17)
│   └── src/
│       ├── main/
│       │   ├── AndroidManifest.xml
│       │   ├── java/com/instanceshape/poop/MainActivity.kt
│       │   └── res/                         # Layout, colores, estilos e íconos
│       ├── test/                            # Pruebas unitarias de ejemplo
│       └── androidTest/                     # Pruebas instrumentadas de ejemplo
├── build.gradle                             # Configuración raíz (Kotlin 1.3.20, AGP 3.2.1)
├── settings.gradle
└── gradlew / gradlew.bat                    # Gradle Wrapper
```

## Requisitos

- Android Studio compatible con Android Gradle Plugin 3.2.1.
- JDK 8 y Android SDK 28.
- Un emulador o dispositivo con Android 4.2 (API 17) o superior.

## Ejecución local

```bash
git clone git@github.com:KevinAndrey96/poop.git
cd poop
./gradlew assembleDebug
```

También puedes abrir la carpeta en Android Studio y pulsar **Run**.

## Licencia

Sin licencia de código abierto. Todos los derechos reservados.
