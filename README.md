# ▸ PuestoControl 💹

**PuestoControl** es una Aplicación Web Progresiva (PWA) diseñada para la gestión eficiente de inventarios, ventas y finanzas en puestos de venta físicos. Enfocada en la velocidad y la privacidad, la app funciona de manera 100% offline y almacena todos los datos localmente en el dispositivo.

## ✨ Características Principales

* **📱 Experiencia PWA:** Instálala en Android (Chrome), iOS (Safari) o PC como una aplicación nativa.
* **📡 100% Offline:** Gracias a su Service Worker, la app carga y funciona sin conexión a internet una vez instalada.
* **📦 Inventario Multi-variante:** Gestión avanzada de stock por tallas (S/M/L/XL) o cualquier variante personalizada.
* **💰 Dashboard Financiero:** Visualiza en tiempo real tu Ganancia Bruta, Gastos Operativos y Ganancia Real del día.
* **📑 Historial y Archivo:** Cada día cerrado se guarda automáticamente en un historial para consultas posteriores.
* **💾 Control de Datos:** Exporta e importa toda tu información en formato JSON para respaldos, o descarga reportes en CSV para Excel.

## 🛠️ Tecnologías Utilizadas

* **HTML5 & CSS3:** Diseño responsivo con arquitectura de "pestañas" y variables CSS para el tema oscuro.
* **JavaScript (Vanilla):** Lógica de negocio pura, sin dependencias externas ni frameworks pesados.
* **Service Workers:** Implementación de caché para funcionamiento offline.
* **Web Storage API (LocalStorage):** Persistencia de datos local rápida y segura.

## 🚀 Instalación Rápida

PuestoControl no requiere cuentas ni suscripciones. Solo necesitas tres archivos en el mismo directorio:

1.  `index.html` (La aplicación y lógica)
2.  `manifest.json` (Configuración de PWA)
3.  `sw.js` (Service Worker para modo offline)

### En Móvil:
* **Android:** Abre `index.html` en Chrome, toca los tres puntos y selecciona "Instalar aplicación".
* **iOS:** Abre el archivo en Safari, toca el botón "Compartir" y selecciona "Agregar a inicio".

## 📊 Flujo de Trabajo (Vibe Coding)

1.  **Carga tu Inventario:** Define tus categorías, costos y precios.
2.  **Registra Ventas:** Toca la variante vendida y el stock se descontará automáticamente.
3.  **Gestiona Gastos:** Ingresa renta, comida o salarios del día.
4.  **Cierra el Día:** Al finalizar, archiva los datos para limpiar el dashboard y empezar fresco mañana.

## 🔒 Privacidad y Respaldos

Tus datos **nunca salen de tu dispositivo**. La aplicación no tiene base de datos en la nube.
> **Importante:** Se recomienda realizar una exportación JSON semanalmente y guardarla en Google Drive o enviarla por WhatsApp para evitar pérdida de datos si se limpia la caché del navegador o se formatea el equipo.

---
*Diseñado para ser ligero, rápido y funcional en cualquier entorno.*