# Auditoria-GRC-Form
# 🛡️ Formulario de Auditoría NIST CSF (Versión ligera)

Este proyecto es una aplicación web HTML/JS simple y sin backend que permite rellenar un formulario de auditoría basado en el marco **NIST Cybersecurity Framework (CSF)** y exportar los resultados como un archivo PDF.

## 🚀 ¿Qué hace esta app?

- Permite completar campos clave de auditoría:
  - Empresa auditada
  - Fecha
  - Control NIST (ej. PR.AC-1)
  - Cumplimiento (Sí, No, Parcial)
  - Evidencia encontrada
  - Riesgo asociado (Alto, Medio, Bajo)
- Exporta automáticamente el informe como un archivo PDF con solo pulsar un botón.
- Funciona completamente offline (sin base de datos ni servidor).

## 📂 Archivos

- `index.html`: archivo principal con el formulario y lógica JavaScript.
- (Opcional) `README.md`: este documento.

## 💻 Cómo usar

1. Clona o descarga este repositorio.
2. Abre `index.html` en cualquier navegador moderno.
3. Rellena el formulario.
4. Haz clic en **“Descargar como PDF”** para guardar tu informe.


## 📦 Requisitos

- Navegador moderno con soporte para JavaScript.
- Conexión para cargar la librería jsPDF desde CDN (o descargarla localmente si deseas trabajar 100% offline).

## 📄 Licencia

MIT – Puedes usar, modificar y distribuir libremente.

---

Hecho con 💻 para facilitar auditorías técnicas ligeras sin complicaciones.
