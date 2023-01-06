# predicciones-de-ventas-alimenticias
Predicción de ventas para productos alimenticios vendidos en diversas tiendas.

El problema: los minoristas de alimentos siempre se están quedando sin inventario. Como resultado, los clientes están insatisfechos, lo que se traduce en menores ganancias y mayores costos operativos. La solución: pronosticar las ventas de productos alimenticios específicos, por región y tienda.


Item_Identifier               object     Identificación única del producto.
Item_Weight                  float64     Peso del producto.
Item_Fat_Content              object     Si el producto es bajo en grasa o regular.
Item_Visibility              float64     Porcentaje de la superficie total de exposición de todos los productos de una tienda asignada al producto concreto.
Item_Type                     object     Categoría a la que el producto pertenece.
Item_MRP                     float64     Precio máximo de venta al público (precio de catálogo) del producto.
Outlet_Identifier             object     Identificación única de la tienda.
Outlet_Establishment_Year      int64     El año en que se estableció la tienda.
Outlet_Size                   object     El tamaño de la tienda en cuanto al área total.
Outlet_Location_Type          object     El tipo de área donde se encuentra la tienda
Outlet_Type                   object     Si el punto de venta es una tienda de comestibles o algún tipo de supermercado.
Item_Outlet_Sales            float64     Ventas del producto en una tienda particular. Es la variable objetivo a predecir.
dtype: object


RangeIndex: 8523 entries, 0 to 8522
Data columns (total 13 columns):
 #   Column                     Non-Null Count  Dtype  
---  ------                     --------------  -----  
 0   Item_Identifier            8523 non-null   object 
 1   Item_Weight                8523 non-null   float64
 2   Item_Fat_Content           8523 non-null   object 
 3   Item_Visibility            8523 non-null   float64
 4   Item_Type                  8523 non-null   object 
 5   Item_MRP                   8523 non-null   float64
 6   Outlet_Identifier          8523 non-null   object 
 7   Outlet_Establishment_Year  8523 non-null   int64  
 8   Outlet_Size                8523 non-null   object 
 9   Outlet_Location_Type       8523 non-null   object 
 10  Outlet_Type                8523 non-null   object 
 11  Item_Outlet_Sales          8523 non-null   float64
 12  Sold_Units                 8523 non-null   float64
dtypes: float64(5), int64(1), object(7)
