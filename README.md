# EV-PRAC-01

Transcripción fiel de la prueba práctica EV-PRAC-01 (Unidad I, Ingeniería de Requerimientos ISR-401, UTEQ), escrita a mano el 18 de noviembre de 2026.

**Estudiante:** Alcivar Velez Anderson Adonis

## Contenido del repositorio

| Ruta | Contenido |
|------|-----------|
| `evidencias/hoja-01.jpg`, `evidencias/hoja-02.jpg` | Fotografías de las hojas originales, tomadas antes de entregarlas |
| `main.tex` | Transcripción fiel de la prueba, con el anexo de fotografías |
| `main.pdf` | PDF compilado desde `main.tex` |
| `README.md` | Este archivo: instrucciones de compilación |

## Instrucciones de compilación

- **Compilador:** `pdflatex`
- **Archivo principal:** `main.tex`
- **Distribución LaTeX:** TeX Live (Linux/macOS) o MiKTeX (Windows), con instalación de paquetes faltantes activada. También compila en Overleaf.
- **Dependencias:**
  - Las fotografías de la carpeta `evidencias/` (`hoja-01.jpg`, `hoja-02.jpg`), que se insertan en el anexo.
  - Los paquetes LaTeX que se cargan en el preámbulo de `main.tex` y vienen incluidos en TeX Live o MiKTeX.
  - No se usa bibliografía externa (no hay archivo `.bib`), así que no hace falta ejecutar `bibtex` ni `biber`.

## Orden de comandos

```bash
git clone https://github.com/AdonisAlcivar/EV-PRAC-01.git
cd EV-PRAC-01
pdflatex main.tex
pdflatex main.tex
```

Se ejecuta `pdflatex` dos veces para que se resuelvan las referencias internas (tablas, numeración y páginas). El resultado es `main.pdf`.