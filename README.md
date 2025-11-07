# analisis_de_negocio
Análisis de Showz, una empresa de venta de entradas de eventos, para optimizar los gastos de marketing. 

# 🎟️ Análisis de Marketing y Rentabilidad de Clientes — Proyecto Showz

# 🧠 Descripción del Proyecto

Departamento de analítica de Showz, una empresa dedicada a la venta de entradas para eventos.
Ayudar a optimizar los gastos de marketing mediante el análisis de datos sobre visitas, pedidos y costos publicitarios.

El objetivo principal es comprender el comportamiento de los usuarios y determinar qué fuentes de adquisición resultan más rentables para la empresa.

# 🎯 Objetivos del Proyecto

Analizar cómo los clientes utilizan el servicio de Showz.

Identificar cuándo comienzan a comprar y cómo evolucionan las conversiones.

Calcular métricas clave de marketing y negocio:

LTV (Lifetime Value)

CAC (Costo de Adquisición de Clientes)

ROMI (Retorno sobre la Inversión en Marketing)

Determinar cuándo los ingresos superan el costo de adquisición.

Formular recomendaciones de inversión en las fuentes de adquisición más rentables.

# 🗂️ Descripción de los Datos

El proyecto se basa en tres conjuntos de datos que contienen información sobre visitas, pedidos y gastos de marketing entre enero de 2017 y diciembre de 2018.

1. visits — Registros de sesiones en el sitio web
Columna	Descripción
Uid	Identificador único del usuario
Device	Tipo de dispositivo utilizado
Start Ts	Fecha y hora de inicio de la sesión
End Ts	Fecha y hora de finalización de la sesión
Source Id	Identificador de la fuente de adquisición

Todas las fechas están en formato AAAA-MM-DD.

2. orders — Información de pedidos realizados
Columna	Descripción
Uid	Identificador único del usuario
Buy Ts	Fecha y hora de la compra
Revenue	Ingreso generado por el pedido
3. costs — Gastos de marketing
Columna	Descripción
source_id	Identificador de la fuente de anuncios
dt	Fecha de registro
costs	Gasto diario en esa fuente de adquisición
📦 Archivos del Proyecto

/datasets/visits_log_us.csv — Registro de visitas.

/datasets/orders_log_us.csv — Registro de pedidos.

/datasets/costs_us.csv — Gastos de marketing.

# ⚙️ Etapas del Proyecto

## 1️⃣ Preparación de los Datos

Carga y exploración inicial de los datasets.

Conversión de tipos de datos (fechas, números, categorías).

Limpieza y optimización de datos para análisis.

Creación de campos derivados:

Duración de la sesión.

Día, semana y mes de visita.

Identificación de fuentes de adquisición y dispositivos.

## 2️⃣ Análisis Exploratorio y Cálculo de Métricas

📈 Análisis de visitas

Usuarios activos diarios, semanales y mensuales.

Número promedio de sesiones por usuario.

Duración promedio de las sesiones.

Frecuencia de retorno de los usuarios.

🛒 Análisis de ventas

Tiempo promedio desde el registro hasta la primera compra (tiempo de conversión).

Número promedio de pedidos por usuario y tamaño medio del pedido.

Ingresos totales y promedio por usuario (LTV).

💰 Análisis de marketing

Gasto total y gasto por fuente de adquisición.

Cálculo del CAC (Costo de Adquisición de Cliente) por fuente.

Evaluación de la rentabilidad (ROMI):

ROMI
Costos de marketing
Ingresos generados − Costos de marketing​

Comparación del desempeño entre dispositivos y canales publicitarios.

📊 Visualizaciones

Evolución temporal de usuarios, compras y gastos.

Gráficos comparativos de LTV, CAC y ROMI por fuente.

Análisis de tendencias y estacionalidad.

## 3️⃣ Conclusiones y Recomendaciones

Identificación de las fuentes más rentables (mayor ROMI).

Determinación del tiempo de recuperación de la inversión (punto en el que LTV > CAC).

Recomendaciones de asignación de presupuesto de marketing según desempeño de canales y dispositivos.

# 🧩 Métricas Clave del Proyecto

CAC	Costo promedio de adquirir un cliente	 Total Costos / Nuevos Clientes
LTV	Valor total que un cliente aporta durante su ciclo de vida	 Ingresos Totales / Número de Clientes
ROMI	Rentabilidad del gasto en marketing	 (Ingresos - Costos) / Costos

# 📈 Tecnologías Utilizadas

Python

pandas

numpy

matplotlib / seaborn

datetime

Jupyter Notebook

Herramientas de Análisis de Marketing Digital

# 🧾 Resultados Esperados

Identificar patrones de comportamiento de los usuarios (uso, retención, conversión).

Determinar qué fuentes de adquisición generan clientes más rentables.

Evaluar el retorno de la inversión en marketing (ROMI) por canal.

Formular estrategias basadas en datos para optimizar el gasto publicitario.

# ✍️ Autor

Lorena Urquijo N.
Analista de Datos — Proyecto Showz
📅 Año: 2025
