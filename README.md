![image](https://github.com/pabloing93/supermarket-sales-analysis/assets/32267303/984eb94f-34c6-4ab2-9392-52e4c91ecdfa)

# Reportes de ventas para un supermercado 📈

## Escenario 📝
Un cliente posee una cadena de supermercados en Brasil, nos contrata para realizar insights sobre sus reportes de ventas de los últimos 4 años.
Nuestro objetivo será el de analizar sus datos y poder convertilos en información que generen valor para su negocio.

## Tecnologías utilizadas 👨🏽‍💻

### Python 🐍
Python es uno de los lenguajes de programación por excelencia en el mundo de la ciencia de datos con una amplia comunidad, variedad de librerías y documentaciones.

### Pandas 🐼
Pandas es una biblioteca esencial para el análisis y manipulación de datos en Python. Muy utilizada en proyectos de Ciencia de Datos.

### Pyplot 📊
Pyplot es una biblioteca de creación de gráficos a partir de datos pre-procesados y visualización. 
Indispensable para representar conclusiones, insights y hacer reportes de manera sencilla para poder comunicarse a un nivel gerencial y del negocio.


## Etapas del algoritmo

## Configuración del ambiente
> [!IMPORTANT] 
> Si lo ejecutan de manera local, se requiere correr la siguiente línea de código para instalar las tecnologías requeridas:
> ```
> pip install python3, pandas, matplotlib
> ```

## Obtencion de datos 📁

## AED 🕵️‍♂️ y Limpieza de los datos 🧹

[<kbd> <br> Link al código <br> </kbd>][KBD]

[KBD]: /Supermarket_Sales_Analysis.ipynb

## Insights 🚀

### ¿Cómo nos fué estos últimos 4 años y cuál fué el mejor año?

![image](https://github.com/pabloing93/supermarket-sales-analysis/assets/32267303/ef59e4ce-d667-4691-847f-e8ea1dee3b12)


#### Conclusión
El 2022, fue el mejor año en que el supermercado tuvo un mejor su desempeño en cuanto a las ganancias reales por ventas realizadas. Sin embargo, apreciamos un incremento en ganancias de ventas cada año transcurrido.

### Si separamos las ventas totales por año y por regiones ¿Qué insight podemos obtener de nuestras ventas?

![image](https://github.com/pabloing93/supermarket-sales-analysis/assets/32267303/c2f60ca8-a2c8-4430-b4e6-80ca6de4f168)

#### Conclusión
Como conclusión podemos observar que el Sureste de Brasil fué la región que mayores ganancias generó en los últimos 4 años. Seguida por las regiones del Noreste y Centro-Oeste.
A su vez en dichas regiones notamos, paulatinamente, un incremento de las ganancias en los últimos 2 años.

### Y hablando del sureste de Brasil, hablemos de la ciudad que más destacó, Sao Paulo.

![image](https://github.com/pabloing93/supermarket-sales-analysis/assets/32267303/af760cf1-849e-4039-bb3e-260252db6575)

#### Conclusión
En la ciudad de São Paulo en el mes de Diciembre de los último 3 años, fue en donde más ganancias por ventas se obtuvieron. Sin embargo, durante los primeros trimestres, las ventas disminuyeron.

### Ya hablamos de ganancias... ¿pero cuáles fueron los mejores productos que nos dejaron esas ganancias?

![image](https://github.com/pabloing93/supermarket-sales-analysis/assets/32267303/7eef8d9e-4efd-49bb-9a0f-f8fa3cd829af)

#### Conclusión
Los datos indican que los 4 productos que generan mayor ganancia son los del departamento de **Electrónicos**.
Podemos notar tamquén que el departamente de productos de limpieza tiene 2 productos con buen margen de ganancia totalizando U$D 87k
durante el periodo analizado

### ¿Y cómo se enviaron esos productos?

![image](https://github.com/pabloing93/supermarket-sales-analysis/assets/32267303/146b85fa-393b-4499-80c0-2c0ba5e026d8)

#### Conclusión
El método de envío preferido por sus clientes (B2B|B2C) es el de "Entrega estándar".

###  Revisemos el comportamiento de sus clientes y agrupemos estrategicamente los productos.

![image](https://github.com/pabloing93/supermarket-sales-analysis/assets/32267303/f5a8b4c8-42e2-4845-beb1-43c8151930be)

#### Conclusión

Determinamos con un **nivel de confianza del 100%** que **todos aquellos que compraron Ambientador en spray y Bolsas de basura también adquirieron Lámparas LED**. 
Por lo que recomendamos agrupar estos productos para mejorar la experiencia de compra y así generar más ganancias aprovechando la estrecha relación que sus clientes le otorgaron durante este último periodo.
Ésto podría impulsar las ventas de los productos de limpieza al mismo tiempo que mantenemos e incluso mejoramos las ventas de electrónicos.
