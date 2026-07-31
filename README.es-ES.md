

<p align="center">
  <img src="assets/images/ic_glovo_launcher.png" alt="Glovo Clone Logo" width="120" height="120" />
</p>

<h1 align="center">Clon de Glovo – Recreación de UI en Flutter</h1>

<p align="center">
  Un clon de Flutter, inspirado en píxeles y sin fines comerciales, de la interfaz de usuario de la aplicación de entregas <a href="https://glovoapp.com">Glovo</a>.
  <br/>
  <strong>⚠️ Esto NO es un producto oficial de Glovo. Es un proyecto personal creado únicamente con fines de aprendizaje y portafolio.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Dart-3.x-0175C2?logo=dart&logoColor=white" alt="Dart" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License" />
  <img src="https://img.shields.io/badge/Status-In%20Progress-orange" alt="Status" />
</p>

---

## 📖 Acerca de

Este proyecto es un **clon de la interfaz de usuario** de la popular aplicación de comida y entregas **Glovo**, construida completamente con **Flutter**. El objetivo fue replicar la apariencia y la experiencia de la aplicación original de Glovo lo más cerca posible, entendiendo que **esto NO es una copia al 100%**. Algunas pantallas, animaciones y funciones han sido adaptadas, simplificadas o reimaginadas para ajustarse al alcance de un proyecto personal.

> **Descargo de responsabilidad:** Este proyecto está destinado **únicamente a fines educativos y de portafolio**. No está afiliado, respaldado ni conectado de ninguna manera con Glovo. No se utilizan datos reales, API ni servicios backend de Glovo. Todas las marcas comerciales pertenecen a sus respectivos propietarios.

---

## 📸 Capturas de pantalla

<table>
  <tr>
    <td align="center"><strong>Iniciar sesión</strong></td>
    <td align="center"><strong>Verificación</strong></td>
    <td align="center"><strong>Inicio</strong></td>
    <td align="center"><strong>Explorar</strong></td>
  </tr>
  <tr>
    <td><img src="screenshots/login-screen.jpg" alt="Pantalla de inicio de sesión" width="200"/></td>
    <td><img src="screenshots/verification-screen.jpg" alt="Pantalla de verificación" width="200"/></td>
    <td><img src="screenshots/home-screen.jpg" alt="Pantalla de inicio" width="200"/></td>
    <td><img src="screenshots/explorer-screen.jpg" alt="Pantalla de exploración" width="200"/></td>
  </tr>
  <tr>
    <td align="center"><strong>Explorar (Detalles)</strong></td>
    <td align="center"><strong>Pedidos</strong></td>
    <td align="center"><strong>Perfil</strong></td>
    <td align="center"><strong>Modificar</strong></td>
  </tr>
  <tr>
    <td><img src="screenshots/explroer-screen-2.jpg" alt="Pantalla de detalles de exploración" width="200"/></td>
    <td><img src="screenshots/commandes-screen.jpg" alt="Pantalla de pedidos" width="200"/></td>
    <td><img src="screenshots/profile-screen.jpg" alt="Pantalla de perfil" width="200"/></td>
    <td><img src="screenshots/modify-screen.jpg" alt="Pantalla de modificación" width="200"/></td>
  </tr>
</table>

---

## ✨ Características

- 🔐 **Inicio de sesión y Verificación** – Flujo de autenticación por número de teléfono con interfaz de verificación OTP
- 🏠 **Pantalla de Inicio** – Navegación por categorías, banners promocionales y listados de restaurantes
- 🔍 **Pantalla de Exploración** – Descubre restaurantes, cocinas y categorías de comida
- 📦 **Pantalla de Pedidos** – Visualiza pedidos anteriores y actuales
- 👤 **Pantalla de Perfil / Cuenta** – Interfaz de gestión del perfil del usuario
- ✏️ **Pantalla de Modificación** – Edita la información del usuario
- 🎨 **Fuentes personalizadas** – Utiliza la familia de fuentes original de Glovo (Black, Bold, Book, Medium) + WorkSans
- 🎞️ **Animaciones Lottie** – Animaciones suaves y atractivas en toda la aplicación
- 📱 **Activos SVG** – Gráficos vectoriales nítidos para iconos e ilustraciones
- 🧭 **Navegación inferior** – Navegación fluida basada en pestañas (Inicio, Explorar, Pedidos, Cuenta)

---

## 🛠️ Stack Tecnológico

| Tecnología | Propósito |
|---|---|
| **Flutter** | Marco de trabajo de interfaz multiplataforma |
| **Dart** | Lenguaje de programación |
| **flutter_svg** | Renderizado de SVG |
| **Lottie** | Reproducción de animaciones |
| **Fuentes personalizadas** | Tipografía inspirada en Glovo |

---

## 🚀 Primeros pasos

### Prerrequisitos

- [SDK de Flutter](https://docs.flutter.dev/get-started/install) (3.x o posterior)
- [SDK de Dart](https://dart.dev/get-dart) (3.x o posterior)
- Android Studio / VS Code con extensiones de Flutter
- Un emulador de Android o iOS, o un dispositivo físico

### Instalación

```bash
# Clonar el repositorio
git clone https://github.com/YOUR_USERNAME/glovo-clone.git

# Navegar al directorio del proyecto
cd glovo-clone/glovo

# Instalar dependencias
flutter pub get

# Ejecutar la aplicación
flutter run
```

---

## 📂 Estructura del Proyecto

```
glovo/
├── assets/
│   ├── fonts/          # Fuentes personalizadas de Glovo y WorkSans
│   ├── images/         # Activos PNG (categorías, restaurantes, iconos…)
│   ├── lotties/        # Archivos de animación Lottie
│   └── svgs/           # Activos vectoriales SVG
├── lib/
│   ├── constants/      # Constantes de toda la app (colores, estilos…)
│   ├── screens/        # Todas las pantallas de la app
│   │   ├── home_screen.dart
│   │   ├── explorer_screen.dart
│   │   ├── orders_screen.dart
│   │   ├── account_screen.dart
│   │   ├── login_screen.dart
│   │   ├── verification_screen.dart
│   │   └── ...
│   ├── widgets/        # Componentes de IU reutilizables
│   └── main.dart       # Punto de entrada de la app
├── screenshots/        # Capturas de pantalla de la app
└── pubspec.yaml        # Configuración del proyecto Flutter
```

---

## ⚠️ ¿Qué es diferente de la aplicación original de Glovo?

Este es un proyecto de **solo interfaz de usuario** sin **integración de backend**. Aquí están las diferencias:

| Aspecto | Glovo Original | Este Clon |
|---|---|---|
| Backend / API | Backend completo de producción | ❌ Sin backend – solo IU estática |
| Pagos | Procesamiento de pagos real | ❌ No implementado |
| Rastreo en vivo | Rastreo de pedidos en tiempo real | ❌ No implementado |
| Autenticación | Autenticación real por teléfono/correo | 🎨 Solo IU (sin autenticación real) |
| Datos | Datos en vivo de restaurantes y productos | 📦 Datos estáticos / de simulación |
| Todas las pantallas | Más de 50 pantallas | 🔢 ~10 pantallas clave recreadas |
| Animaciones | Animaciones propietarias | 🎞️ Alternativas basadas en Lottie |

---

## 🤝 Contribuir

¡Las contribuciones, problemas y solicitudes de funciones son bienvenidas! No dudes en revisar la [página de issues](https://github.com/YOUR_USERNAME/glovo-clone/issues).

1. Realiza un fork del proyecto
2. Crea tu rama de característica (`git checkout -b feature/amazing-feature`)
3. Confirma tus cambios (`git commit -m 'Add some amazing feature'`)
4. Sube a la rama (`git push origin feature/amazing-feature`)
5. Abre un Pull Request

---

## 📄 Licencia

Este proyecto está licenciado bajo la **Licencia MIT**. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

## 🙏 Agradecimientos

- [Glovo](https://glovoapp.com) – por la inspiración del diseño
- [Flutter](https://flutter.dev) – por el increíble marco de trabajo multiplataforma
- [Lottie](https://airbnb.io/lottie/) – por las hermosas animaciones
- [flutter_svg](https://pub.dev/packages/flutter_svg) – por el soporte de SVG

---

<p align="center">
  Hecho con ❤️ y Flutter
  <br/>
  <strong>Este proyecto es únicamente con fines educativos y no está afiliado con Glovo.</strong>
</p>
