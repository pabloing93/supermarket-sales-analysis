![image](https://github.com/pabloing93/supermarket-sales-analysis/assets/32267303/984eb94f-34c6-4ab2-9392-52e4c91ecdfa)

# Insights de reportes de ventas para un supermercado 📈

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

Primero limpiamos los datos
Nos pusimos a investigar los datos, quitamos algunos duplicados, tratamos valores en blanco y nulos y cambiamos el tipo de datos de columnas para que todo encaje a la perfección. 
¡Nos hemos vuelto unos cracks en la corrección de sus datos!

[<kbd> <br> Link al código <br> </kbd>][KBD]

[KBD]: /Supermarket_Sales_Analysis.ipynb

## Insights 🚀

## Ganancias
¿Cómo nos fué estos últimos 4 años y cuál fué el mejor año?

¡Increíble! ¡Descubrimos que pegaron un salto en los últimos 4 años! 
El crecimiento fue constante, con un aumento ponderado del 55% en las ganancias netas desde el 2019 hasta el 2022 💸
¡Un avance espectacular! Ni siquiera la pandemia fue capaz de detenerlos 🦠

![image](https://github.com/pabloing93/supermarket-sales-analysis/assets/32267303/ef59e4ce-d667-4691-847f-e8ea1dee3b12)

“¡Gracias! Pero, ¿Cómo podemos sacarle provecho a este dato?”

¡Fácil! Es el primer paso para establecer un punto de partida. Una vez que conocemos dónde estamos, podemos proyectar mejoras y superarnos. Pero no nos detengamos aquí... ¡Sigamos adelante!
Vamos a desglosar las ganancias netas por regiones y descubrir quién se llevó la corona y quién podría necesitar un empujoncito extra.

### Si separamos las ventas totales por año y por regiones ¿Qué insight podemos obtener de nuestras ventas?

![image](https://github.com/pabloing93/supermarket-sales-analysis/assets/32267303/c2f60ca8-a2c8-4430-b4e6-80ca6de4f168)

**Se ve que la región sureste es la ganadora** 👑 Quizás sea por la cantidad de habitantes, pero no podemos dejar atrás las otras regiones, especialmente la del Norte y la del Sur. 
¡A darles un empujón! 💪

### Y hablando del sureste de Brasil, hablemos de la ciudad que más destacó, Sao Paulo.

![image](https://github.com/pabloing93/supermarket-sales-analysis/assets/32267303/af760cf1-849e-4039-bb3e-260252db6575)

¡Aquí viene la info jugosa! 🤤 Resulta que cada año, en los últimos tres meses, hacemos un mega hit con las ganancias netas. ¡En diciembre nos va muy bien! 📈
Pero, aquí viene lo interesante: 
El próximo trimestre, las ganancias netas disminuyen 📉 Pero no se preocupen, porque ya estamos al tanto de esto. 
Así que, ¡manos a la obra para mejorar! 

## PRODUCTOS
Ya sabemos cuánto ganamos
pero ¿Cuáles son los TOP productos detrás de nuestras ganancias?. 
La respuesta a este misterio quizás nos ayude a descubrir las oportunidades de mejora ¡Vamos a investigar!

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

¡Y ahora, lo mejor de lo mejor! Descubrimos un comportamiento en los clientes:
"Nos dimos cuenta de que todos los que compraron ambientadores en spray y bolsas de basura TAMBIÉN compraron lámparas LED". Esto lo sabemos con una confianza del 100%. 
Además, las compras de productos de limpieza y bolsas de basura van de la mano el 80% de las veces. Hasta los clientes que compraron vestidos y papel higiénico no se resistieron y también se llevaron sus bolsas de basura.

![image](https://github.com/pabloing93/supermarket-sales-analysis/assets/32267303/f5a8b4c8-42e2-4845-beb1-43c8151930be)

# Ideas de negocio 🧠
1. Agrupemos productos de manera estratégica en su sitio web utilizando esta información.
2. ¡Creemos kits o promociones emocionantes como "Transformá tu hogar" para subir las ventas de productos de limpieza!
3. Sigamos analizando el comportamiento de nuestros queridos clientes, generando reglas de asociación y utilizando el marketing a nuestro favor.
4. En nuestro sitio web de ventas, ¿Qué tal si les recordamos a nuestros clientes que, además de un ambientador en spray y bolsas de basura, también hay promociones en lámparas LED? ¡Utilicemos recomendaciones con pop-ups para que no se les escape!
5. ¡Implementemos tecnología de machine learning para predecir y ajustar las ganancias de los primeros trimestres de cada año!
6. Se acerca el calor en enero, ¡así que incorporemos productos acordes a la estación para impulsar las ventas de productos de vestimenta!
7. Las regiones con menos ganancias netas suelen tener pocos habitantes y problemas de conexión. ¡Hagamos su día con una aplicación más liviana y rápida!
8. **¡Atrévanse a ser el cambio que quieren ver en el mundo!**
