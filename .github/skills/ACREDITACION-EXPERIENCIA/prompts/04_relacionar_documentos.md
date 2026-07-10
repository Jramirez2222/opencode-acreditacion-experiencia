# MÓDULO 04 - RELACIONAR DOCUMENTOS

## Objetivo

Relacionar automáticamente todos los documentos pertenecientes a un mismo estudio para construir un expediente completo.

## Entrada

Analizar la información extraída de:

- Contratos
- Facturas
- Órdenes de Servicio
- Actas de Conformidad
- Informes
- Certificados

## Reglas de relación

Relacionar los documentos utilizando:

- Cliente
- Nombre del estudio
- Número de contrato
- Fecha
- Monto
- Objeto del servicio

## Validaciones

- Verificar que exista contrato.
- Verificar que exista factura cuando corresponda.
- Verificar que exista informe final.
- Detectar documentos faltantes.
- Detectar documentos duplicados.

## Salida

Generar una tabla con:

- Estudio
- Cliente
- Contrato
- Factura
- Acta
- Informe
- Estado
- Observaciones
