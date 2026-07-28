# Panel de estado · Base de Conocimiento Educación en Dolor

Estado de avance del corpus de [educacionendolor.com](https://educacionendolor.com):
conceptos escritos frente a los presupuestados en cada uno de los 15 dominios.

**Este repositorio contiene únicamente el panel.** El corpus, la ontología y la
especificación del proyecto no están aquí y no son públicos.

Los datos que se publican son agregados: nombres de dominio y de módulo, número de
conceptos escritos y presupuestados. Ningún contenido clínico.

## Actualizar

Desde el proyecto principal:

```bash
python3 build/publicar.py
```

Regenera el panel con el estado actual, lo copia aquí y hace push. GitHub Pages
lo sirve en un par de minutos.

## Panel en vivo

La versión que se actualiza al recargar corre en local y lee la fuente de verdad
en cada carga:

```bash
python3 build/servir.py
```
