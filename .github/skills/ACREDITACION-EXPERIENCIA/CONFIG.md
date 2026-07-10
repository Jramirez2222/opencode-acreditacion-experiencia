# CONFIGURACIÓN DE LA SKILL

## Objetivo

Definir la estructura del expediente y los parámetros que utilizará la Skill para localizar, analizar y relacionar documentos.

## Estructura esperada

Expediente/
├── Bases/
├── Contratos/
├── Facturas/
├── OrdenesServicio/
├── Actas/
├── Informes/
├── Certificados/
├── Anexos/
└── Salida/

## Tipos de archivos permitidos

- PDF
- DOC
- DOCX
- XLS
- XLSX
- CSV
- TXT

## Reglas

- No modificar los documentos originales.
- Analizar todos los archivos encontrados.
- Aplicar OCR cuando el PDF sea una imagen.
- Registrar cualquier error de lectura.
- Detectar documentos duplicados.

## Relación documental

Relacionar automáticamente:

- Contrato ↔ Factura
- Contrato ↔ Orden de Servicio
- Contrato ↔ Acta de Conformidad
- Contrato ↔ Informe Final
- Contrato ↔ Certificado

## Archivos de salida

- indice_documental.csv
- indice_documental.json
- matriz_acreditacion.xlsx
- informe_final.md
- observaciones.md
