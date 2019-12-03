# **Costos Adicionales**

## **Preámbulo**

El presente material elaborado por ERPyA pretende ofrecerle una explicación eficiente a nuestros clientes del procedimiento a seguir para realizar y obtener un resultado exitoso al momento de generar costos adicionales a los productos en la versión 3.9.2 de ADempiere en la localización Venezuela.

Las empresas realizan un estudio sobre el costo de producción de un producto determinado con la finalidad de establecer el precio de venta en base a los resultados obtenidos. Con esto se quiere decir que según el método empleado por la empresa, se toma en cuenta el costo de la materia prima, el costo de la producción, impresión, empaque, flete y cualquier otro servicio o producto necesario para lograr un producto final, para obtener el precio de venta del producto acorde a los costos que implica la producción del mismo.

El proceso de costos adicionales de un producto, es realizado desde la ventana "**Documentos por Pagar**". Al generar una factura por un servicio o producto aplicada a otro producto, se incrementa el costo del mismo para la venta según las tipologías empleadas por la empresa.

Un producto puede tener costos adicionales por flete, servicios de impresión, entre otros casos que son calculados según la tipología empleada por la empresa. Para ejemplificar la definición anterior, se explica el costo adicional que puede tener un producto por flete. 

## **Documentos por Pagar**

1. Ubique y seleccione en el menú de ADempiere, la carpeta "**Gestión de Compras**", luego seleccione la ventana "**Documentos por Pagar**".

    ![Menú de ADempiere](../resources/menu1.png "Menú de ADempiere")

1. Realice el procedimiento regular para generar una factura de cuentas por pagar, definido en el material [Documento por Pagar](https://docs.erpya.com/adempiere/standard-processes/invoice/invoice/) de la versión 3.9.2 de ADempiere en la localización Venezuela.

    ![Factura por Pagar](../resources/nuevo.png "Factura por Pagar")

    !!! note "**Nota**"

        Es necesario que el documento por pagar no se encuentre en estado completo, de esta manera se pueden aplicar los costos adicionales a los productos.

1. Seleccione la pestaña "**Costos Adicionales**" y proceda al llenado de los campos correspondientes.

    ![Pestaña Costos Adicionales](../resources/pestcostos1.png "Pestaña Costos Adicionales")
        
    1. Podrá apreciar en el campo "**Distribución de Costo**", que por defecto se encuentra seleccionada la opción "**Cantidad**". 

        ![Campo Distribución de Costo](../resources/distcosto1.png "Campo Distribución de Costo")

        !!! note "**Nota**"

            Este campo permite establecer con que tipología sera realizada la distribución de costos. ADempiere utiliza cinco (5) tipologías para aplicar la distribución de costo a un producto.
            
            - Cantidad.
            
            - Costos.

            - Línea.

            - Peso.

            - Volumen. 

    1. Seleccione en el campo "**Elemento de Costo**", el costo a aplicar al producto. Para ejemplificar el registro es utilizada la opción "**Costos de Traslado**".

        ![Campo Elemento de Costo](../resources/elemento1.png "Campo Elemento de Costo")

    1. Seleccione en el campo "**Entrega/Recibo**", el documento de recepción del producto al cual será aplicado el costo adicional.

        ![Campo Entrega/Recibo](../resources/entrega1.png "Campo Entrega/Recibo")

        !!! note "**Nota**"

            Este campo define el producto recepcionado al cual se le aplicará la distribución de costo según la tipología seleccionada anteriormente.

            - Si el documento de recepción posee solo una línea de entrega/recibo, no es necesario seleccionar la línea en el campo "**Línea entrega/recibo**".

            - Si el documento de recepción posee más de una línea de entrega/recibo, es necesario seleccionar en el campo "**Línea entrega/recibo**", una línea por registro de la pestaña "**Costos Adicionales**". 

    1. Seleccione la opción "**Distribución de Costos**", para aplicar el costo adicional al producto de la recepción.

        ![Opción Distribución de Costos](../resources/distcosto2.png "Distribución de Costos")

        !!! note "**Nota**"

            Según la tipología seleccionada anteriormente, ADempiere realiza la distribución de costos de la siguiente manera:

            - Cantidad, realiza la distribución dividiendo el costo de la factura entre la cantidad del producto recepcionado.
            
            - Costos, realiza la distribución porcentualmente al costo del producto.

            - Línea, realiza la distribución dividiendo el costo de la factura entre el número de líneas que tenga la factura.

            - Peso, realiza la distribución porcentualmente al peso del producto.

            - Volumen, realiza la distribución porcentualmente al volumen del producto. 

        1. Podrá visualizar la ventana "**Distribución de Costos**", donde debe seleccionar la opción "**OK**" para aplicar el costo adicional al producto.

            ![Ventana Distribución de Costos](../resources/distcosto3.png "Ventana Distribución de Costos")

1. Regrese a la ventana principal "**Factura**" y seleccione la opción "**Completar**", ubicada en la parte inferior derecha del documento.

    ![Opción Completar](../resources/completar.png "Opción Completar")

    1. Seleccione la acción "**Completar**" y la opción "**OK**", para completar el documento por pagar.

        ![Opción Completar](../resources/ok.png "Opción Completar")

## **Consultar Costos Adicionales**

1. Ubique en el menú de ADempiere, la carpeta "**Análisis de Desempeño**", luego seleccione la carpeta "**Gestión de Costos**", por último seleccione el reporte "**Detalle Costo del Producto**".  

    ![Ventana Producto](../resources/menu2.png "Ventana Producto")

1. Podrá visualizar el reporte "**Detalle Costo del Producto**" de la siguiente manera.

    ![Pestaña Costo](../resources/costo.png "Pestaña Costo")
