# FORM-TL-01: Taller de Tipos de Requisitos

**Asignatura:** Ingeniería de Requerimientos (ISR401)  
**Institución:** Universidad Técnica Estatal de Quevedo (UTEQ)  
**Caso de Estudio:** Sistema en línea de préstamo de libros para las 17 carreras de la UTEQ  
**Grupo:** 01  

---

## Integrantes del Equipo

- **José Ignacio Gilces Carranza**
- **Danela Dayana Arteaga Álava**
- **Winston Damián Cedeño Ávila**
- **Allan Jeremy Mendoza Palma**

---

## Descripción del Proyecto

Este repositorio contiene los archivos fuente en LaTeX y el documento PDF final compilado para el **Taller FORM-TL-01**, enfocado en la clasificación, análisis y especificación de tipos de requisitos para el sistema de biblioteca de la UTEQ.

---

## Estructura del Repositorio

```text
.
├── .gitignore                # Reglas de exclusión de archivos temporales de compilación
├── README.md                 # Documentación e instrucciones del repositorio
├── main.tex                  # Archivo principal fuente en LaTeX
├── referencias.bib           # Bibliografía en formato BibTeX (IEEE / biblatex)
└── main.pdf                  # PDF compilado final

```

---

## Instrucciones de Compilación (Reproducibilidad)

Para garantizar que el documento compile correctamente en cualquier entorno local o de evaluación, siga las instrucciones indicadas a continuación.

### Requisitos del Entorno

* Distribución LaTeX: MiKTeX / TeX Live / MacTeX.
* Compilador: pdflatex
* Procesador bibliográfico: biber (configurado para el paquete biblatex en estilo IEEE).

### Orden Exacto de Comandos de Compilación

Ejecute la siguiente secuencia desde la consola de comandos en la carpeta raíz del repositorio:

```bash
pdflatex -synctex=1 -interaction=nonstopmode main.tex
biber main
pdflatex -synctex=1 -interaction=nonstopmode main.tex
pdflatex -synctex=1 -interaction=nonstopmode main.tex

```

> **Nota para usuarios de TeXstudio:** Asegúrese de tener seleccionado Biber en *Opciones -> Configurar TeXstudio -> Compilación -> Herramienta de bibliografía por defecto*.

---

## Declaración de Uso de Inteligencia Artificial

De conformidad con las normas de evaluación académica de la asignatura:

* Herramientas de IA empleadas: Gemini / ChatGPT.
* Propósito del uso: Apoyo en la corrección de estilo, revisión ortográfica y asistencia en el maquetado en LaTeX.
* Método de verificación humana: Los integrantes del equipo verificaron, validaron y redactaron íntegramente la clasificación de requisitos, los casos de estudio y las referencias bibliográficas oficiales (ISO/IEC/IEEE 29148).

```

```
