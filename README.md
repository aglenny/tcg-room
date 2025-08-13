# TCG Room

Aplicación para gestión de cartas y mazos de **Gundam TCG**.  
MVP *offline-first* con funciones de búsqueda, colección, carpetas, listas y estadísticas.

## ✨ Características previstas (MVP)
- Buscar cartas en el catálogo por nombre, set, coste y nivel.
- Añadir cartas a la colección personal.
- Crear y gestionar mazos.
- Organizar colección y mazos en carpetas y listas.
- Mostrar estadísticas de mazos (curva de coste y curva de nivel).
- Guardado local en el dispositivo (Isar o Drift).
- Exportar/Importar backup manual en ZIP (con cifrado opcional).
- Uso de imágenes servidas desde CDN configurable.
- **Sin registro online** en el MVP → todos los datos permanecen en el dispositivo.

## 🛠️ Tecnologías
- **Flutter + Dart**
- **Isar** (o Drift) para base de datos local.
- **Riverpod** para gestión de estado.
- **cached_network_image** para imágenes de cartas.
- **AES-GCM** para cifrado de backups (opcional).

## 📦 Estructura del proyecto
lib/
├─ domain/ # Modelos y entidades
├─ data/ # Repositorios y fuentes (Isar/HTTP)
├─ application/ # Providers y casos de uso
├─ presentation/ # UI y pantallas
├─ services/ # Backup, cifrado, imágenes
└─ config/ # Env, constantes


## 📜 Licencia
Este proyecto está protegido por una **licencia propietaria**.  
Está permitido ver y descargar este código con fines personales y educativos.  
No se concede permiso para uso comercial, redistribución o modificación sin consentimiento expreso del autor.
