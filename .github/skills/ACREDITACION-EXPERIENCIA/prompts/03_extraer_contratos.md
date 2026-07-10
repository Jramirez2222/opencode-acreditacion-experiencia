# MÓDULO 03 - EXTRAER CONTRATOS

## Objetivo

Analizar automáticamente todos los contratos encontrados en la carpeta configurada y extraer la información necesaria para acreditar experiencia.

## Entrada

Carpeta:

Contratos/

## Archivos compatibles

- PDF
- DOCX
- DOC

## Información a extraer

Para cada contrato identificar:

- Código interno
- Número de contrato
- Cliente
- RUC del cliente (si existe)
- Objeto contractual
- Nombre del estudio
- Especialidad
- Fecha de suscripción
- Fecha de inicio
- Fecha de término
- Monto contratado
- Moneda
- Estado
- Firmas
- Alcance del servicio
- Palabras clave técnicas

## Clasificación

Determinar automáticamente si el contrato corresponde a:

- Hidrología
- Hidrogeología
- Cambio climático
- Modelamiento numérico
- Recursos hídricos
- Estudios ambientales
- Otros

## Validaciones

Verificar:

- Contrato completo.
- Firmas presentes.
- Fechas legibles.
- Objeto identificable.
- Cliente identificable.

## Salida

Generar:

contratos_extraidos.csv

contratos_extraidos.json

resumen_contratos.md
