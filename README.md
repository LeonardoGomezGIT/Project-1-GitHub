# Análisis de Ventas de un Negocio Pequeño

## Descripción del Proyecto:
Este proyecto analiza el comportamiento de las ventas de un negocio pequeño a traves del tiempo. Desde los registros de ventas diarios, se busca identificar patrones, productos más vendidos, días de mayor demanda y tendencias generales que puedan apoyar la toma de decisiones del negocio para seguir adelante con el mismo.
Es un proyecto de ciencia de datos aplicada a contextos reales y facilmente accesibles, donde los datos son simples pero las conclusiones son valiosas para cualquier emprendedor o comerciante.

## Objetivos:
Cargar y limpiar un dataset de ventas para el negocio para mantener en línea todo lo que se mueve, entra y sale.
Identificar los productos y días con mayor volumen de ventas identificando estaciones en las que el porcentaje de compra es superior respectivo a otros momentos .
Visualizar tendencias de ventas a lo largo del tiempo e identificar el valor de ticket promedio (Lo que gasta cada usuario en cada transacción).
Extraer conclusiones útiles para la gestión del negocio además de identificando mediante la ley de pareto cuál es el 20% de productos que dan el 80% de las ganancias para tomar mejores desiciones.

## Variables:
Categoría del Producto: Para saber qué sección del negocio es la más rentable.
Costo Unitario: Para calcular el Margen de Ganancia.
Método de Pago (Efectivo, Tarjeta, Transferencia): Para comprender el flujo de caja.
Hora de la Venta: Para identificar las horas pico y así optimizar el personal o la apertura del local.
ID de Cliente: Si hay programa de lealtad se utilizaría para medir la frecuencia de recompra.

## Propuesta visual:
Line Chart que muestre la evolución de ventas diarias/mensuales para ver la tendencia.
Bar Chart que meustre top 10 productos más vendidos (por volumen y por ingreso).
Heatmap con una matriz de "Día de la semana" vs. "Hora del día" para identificar picos de tráfico.
Boxplot para detectar valores atípicos (ventas inusualmente altas o bajas).

## Propuesta de Stack Tecnológico:
Limpieza: Uso de Python (Pandas) para manejar valores nulos o formatos de fecha incorrectos.
Exploración: Matplotlib o Seaborn para las gráficas.
Predicción (Opcional): Aplicación un modelo de Series Temporales (como un promedio móvil) para predecir las ventas de la próxima semana.
