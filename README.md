📚 Herramientas Informáticas y Ciberseguridad 2026-I
Aplicación web interactiva de repaso para el curso Herramientas Informáticas y Ciberseguridad del IESTPN-CITEN (Marina de Guerra del Perú).
🚀 Demo en vivo
> Publicar con **GitHub Pages** (ver instrucciones abajo)
---
✅ Características
Preguntas organizadas en 6 temas:
Introducción a la Informática e Internet
Microsoft Word y Documentos Institucionales
Microsoft Excel
Microsoft PowerPoint
Inteligencia Artificial
Seguridad Digital y Transformación Digital
4 modos de test: 10, 20, 40 o 160 preguntas (balotario completo)
Preguntas aleatorias en cada test
Retroalimentación inmediata por pregunta (correcto / incorrecto + respuesta correcta)
Pantalla de resultados con:
Puntaje porcentual
Conteo de correctas e incorrectas
Revisión detallada de cada error con la alternativa correcta
Sin dependencias externas ni instalación — solo un archivo `index.html`
---
📁 Estructura
```
quiz-app/
└── index.html   ← aplicación completa (HTML + CSS + JS)
```
---
🌐 Publicar en GitHub Pages
Paso 1 — Crear repositorio
Ingresar a github.com e iniciar sesión.
Clic en New repository.
Nombre sugerido: `balotario-hic-2026` (público).
No inicializar con README (se usará el de este paquete).
Clic en Create repository.
Paso 2 — Subir archivos
Opción A — desde el navegador (más simple):
En la página del repositorio vacío, clic en uploading an existing file.
Arrastrar `index.html` y este `README.md`.
Clic en Commit changes.
Opción B — con Git:
```bash
git init
git add index.html README.md
git commit -m "Balotario HIC 2026-I"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/balotario-hic-2026.git
git push -u origin main
```
Paso 3 — Activar GitHub Pages
En el repositorio → Settings → Pages (menú lateral izquierdo).
En Branch seleccionar `main` y carpeta `/root`.
Clic en Save.
En ~1 minuto la app estará disponible en:
```
   https://TU_USUARIO.github.io/balotario-hic-2026/
   ```
---
👨‍🏫 Autor
T3 PDA. Trejo Sare Pablo Alejandro  
IESTPN-CITEN · Marina de Guerra del Perú · 2026-I
