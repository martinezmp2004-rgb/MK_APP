# mk_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Documentación de Investigación

- [Estudio de Mercado: Consumo de Alcohol en España (Markdown)](docs/research/consumo_alcohol_espana.md)
- [Estudio de Mercado: Consumo de Alcohol en España (Word/DOCX)](docs/research/consumo_alcohol_espana.docx)
- [Estudio de Mercado: Consumo de Alcohol en España (PDF)](docs/research/consumo_alcohol_espana.pdf)

Análisis del consumo de alcohol en España con especial foco en el ron, con datos de Kantar, NielsenIQ, Mintel, Google Trends, EGM, OCU y AECOC.

### Regenerar documentos

Para regenerar los archivos DOCX y PDF a partir del Markdown fuente:

```bash
pip install python-docx markdown weasyprint
python scripts/generate_docs.py
```
