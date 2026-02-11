# El “Iceberg” de Volumen en Capitulación Industrial

Detección de Compras Institucionales Invisibles

## 📌Descripción General

Este proyecto detecta señales de acumulación institucional extrema que ocurren durante eventos de capitulación sectorial.

El patrón es contraintuitivo pero poderoso:
- toda una industria colapsa,
- el pánico minorista domina,
- pero un ticker específico absorbe volumen masivo sin que el precio caiga.

Esto es característico de órdenes Iceberg: grandes compradores institucionales ejecutando órdenes ocultas para no mover el mercado.

## 📍Insight Clave

¿Dónde está el suelo real cuando todo parece roto?

Cuando:
- la industria cae violentamente,
- el volumen de un activo se multiplica,
- y el precio permanece estable,
- el mercado está revelando demanda estructural invisible.

Por Qué es Sorprendente?
- El precio no sube (no hay confirmación clásica).
- El RSI puede seguir débil.
- Las noticias son negativas.

Pero el volumen cuenta otra historia .... alguien grande está comprando todo.

## Valor de Negocio

- Identifica suelos definitivos antes de la recuperación.
- Detecta acumulación institucional en tiempo real.

Permite entrar cuando:
- el riesgo/retorno es asimétrico,
- el consenso es totalmente negativo.

Ideal para:
- estrategias contrarian,
- event-driven,
- análisis de microestructura.

Fuentes de Datos
- tickers
- ticker_id
- industria
- precios_diarios
- ticker_id
- fecha
- open
- close
- volume

## 🧠Lógica del Análisis

1. Identificación de Capitulación Industrial
- Se calcula el rendimiento promedio diario por industria.
- Se filtran industrias con caída significativa (ej. > 5%).

2. Detección de Iceberg en Tickers Individuales
- Dentro de industrias en pánico, se buscan tickers que cumplan:
volumen > 5× su promedio histórico, variación de precio mínima (precio plano), mismo día de la capitulación.

## 📊Interpretación de Resultados

Volumen extremo + precio plano
→ Absorción total de oferta.
→ Comprador dominante presente.

Volumen extremo + precio cayendo
→ Distribución, no acumulación.

Precio plano sin volumen
→ Falta de interés real.

## 🧩Casos de Uso

- Identificación temprana de suelos.
- Filtrado de oportunidades deep value.
- Confirmación de hipótesis de acumulación.
- Trading contrarian de alta convicción.
- Estudios de comportamiento institucional.

## 🚀Posibles Extensiones

- Repetición del patrón en varios días consecutivos.
- Integrar con skewness post-evento.
- Confirmar con cierre por encima del VWAP.
- Analizar posteriores rupturas alcistas.
- Aplicar a ETFs industriales.

## ✒️Nota Final

Cuando todos venden y el precio no cae, no es magia.
Es dinero grande trabajando en silencio 🧊📊

## 👤Autora
Flavia Hepp Proyecto de SQL aplicó un análisis de riesgo basado en eventos.
Este insight no busca señales ruidosas.
Busca el momento exacto donde el mercado deja de caer, aunque nadie lo note.
