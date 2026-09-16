# Proyecto LaTeX de la tesis

El archivo principal es main.tex. La estructura está separada en:

- capitulos: texto de la tesis;
- figuras: diagramas e imágenes;
- figuras_fuente: versiones SVG editables de los diagramas;
- referencias: bibliografía;
- anexos: materiales complementarios;
- build: archivos generados durante la compilación.

Para compilar desde la carpeta tesis_latex se puede usar en VS Code la receta `pdflatex x3 (sin Perl)` o ejecutar tres veces `pdflatex main.tex`. La configuración incluida genera el PDF dentro de `build` y evita depender de `latexmk`/Perl.

Antes de la entrega final se debe sustituir [NOMBRE DE LA UNIVERSIDAD] en datos_tesis.tex y adaptar márgenes, portada y orden de capítulos a la guía institucional.
