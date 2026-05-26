# 🦦 MakeMd — Conversor de archivos a Markdown

## ¿Por qué convertir tus archivos a Markdown antes de pasárselos a Claude?

Cuando le enviás un PDF, un Word o una planilla Excel directamente a Claude u otro modelo de lenguaje, el modelo tiene que procesar el archivo completo: imágenes incrustadas, metadatos, formatos de página, encabezados decorativos, estilos tipográficos y todo el "ruido" visual que no aporta información real. Ese procesamiento consume **tokens**, y los tokens cuestan dinero o tienen límite de uso.

Un archivo Markdown (`.md`) es texto plano estructurado. Sin imágenes decorativas, sin capas de formato, sin bytes desperdiciados. Es puro contenido. Al convertir tu documento a Markdown antes de subirlo a Claude:

- **Reducís el consumo de tokens hasta un 60–80%** según el tipo de archivo
- El modelo lee más rápido y responde con mayor precisión, porque tiene menos ruido que filtrar
- Podés incluir documentos mucho más largos dentro del mismo contexto
- Ahorrás créditos si usás Claude Pro, Teams o API

En resumen: **mismo contenido, mucho menos costo**.

---

## ¿Qué es MakeMd?

En 2024, **Microsoft lanzó [markitdown](https://github.com/microsoft/markitdown)**, una biblioteca de código abierto que convierte decenas de formatos de archivo a Markdown de forma automática. Es gratuita y potente, pero pensada para desarrolladores: requiere terminal y conocimientos técnicos para usarla.

**MakeMd** es la interfaz visual sobre esa biblioteca. Una aplicación de escritorio con dark mode y conversión en lote — sin instalar nada, sin abrir ninguna terminal, sin escribir una sola línea de código.

Descargás el `.exe`, lo abrís, seleccionás tus archivos y listo.

---

## ¿Cómo se usa?

### 1. Abrís MakeMd.exe

Doble clic. No requiere instalación. No deja rastros en el sistema. Si Windows muestra una advertencia de seguridad la primera vez, elegís "Ejecutar de todas formas" — es normal para ejecutables portables sin firma digital.

### 2. Seleccionás tus archivos

Usás el botón **"seleccionar archivos"** para agregarlos. Podés agregar varios a la vez — todos quedan en una cola visual con nombre, formato y estado de cada uno.

### 3. Elegís dónde guardar (opcional)

Por defecto el `.md` se guarda en la misma carpeta que el original. Si querés centralizar los resultados, usás el selector en la barra superior.

### 4. Convertís todo

Un clic en **▶ Convertir Todo** procesa la cola completa. Cada archivo muestra su progreso. Si algo falla, el error aparece al lado de ese ítem sin interrumpir el resto.

### 5. Pegás el `.md` en Claude

Abrís el `.md` con el Bloc de notas, copiás el contenido y lo pegás en Claude. O lo adjuntás directamente. El modelo recibe texto limpio y estructurado, y trabaja con mucha mayor eficiencia.

---

## Formatos soportados

| Categoría | Formatos |
|---|---|
| Documentos | PDF, DOCX |
| Presentaciones | PPTX |
| Planillas | XLSX |
| Web y datos | HTML, CSV, JSON, XML |
| Imágenes (OCR) | PNG, JPG, GIF |
| Audio | MP3, WAV |
| Archivos comprimidos | ZIP |

---

## Características

- **Portable** — un solo `.exe`, sin instalación, sin dependencias
- **Dark mode** — interfaz cómoda para trabajar horas seguidas
- **Conversión en lote** — todos los archivos de una vez
- **Trilingüe** — Español, Inglés y Portugués
- **Gratis** — sin publicidad, sin registro, sin telemetría

---

## Requisitos

- Windows 10 / 11 (64 bits)
- Nada más

---

## ☕ Apoyar el proyecto

MakeMd es gratuito. Si te resultó útil y querés colaborar con el desarrollo:

👉 [cafecito.app/mestizokabalin](https://cafecito.app/mestizokabalin)

---

*Motor de conversión: [markitdown](https://github.com/microsoft/markitdown) © Microsoft — MIT License*
