# **Costos Adicionales**

## **Preámbulo**

El presente material elaborado por ERPyA pretende ofrecerle una explicación eficiente a nuestros clientes del procedimiento a seguir para realizar y obtener un resultado exitoso al momento de generar costos adicionales a los productos en la versión 3.9.2 de ADempiere en la localización Venezuela.

El proceso de costos adicionales de un producto, es realizado desde la ventana "**Documentos por Pagar**", al generar una factura por el servicio aplicado al producto, el costo adicional del mismo es reflejado en la pestaña "**Costos**" de la ventana "**Producto**".

## **Documentos por Pagar**

1. Ubique y seleccione en el menú de ADempiere, la carpeta "**Gestión de Compras**", luego seleccione la ventana "**Documentos por Pagar**".

    ![Menú de ADempiere](../resources/menu1.png "Menú de ADempiere")

    1. Podrá visualizar la ventana "**Documentos por Pagar**", donde debe seleccionar el icono "**Registro Nuevo**" en la barra de herramientas de ADempiere.

        ![Factura por Pagar](../resources/nuevo.png "Factura por Pagar")

    1. Seleccione en el campo "**Organización**", la organización para la cual se esta realizando el documento de factura de cuenta por pagar, el valor en el mismo debe ser diferente del símbolo (*).

        ![Campo Organización](../resources/org1.png "Campo Organización")

    1. Seleccione el tipo de documento a generar en el campo "**Tipo de Documento**", la selección de este define el comportamiento del documento que se esta elaborando, dicho comportamiento se encuentra explicado en el documento [Tipo de Documento]() elaborado por la empresa ERPyA.

        ![Campo Tipo de Documento Destino](../resources/tipodoc1.png "Campo Tipo de Documento Destino")

    1. Seleccione en el campo "**Socio del Negocio**", el socio del negocio proveedor del servicio a facturar.

        ![Campo Socio del Negocio](../resources/socio1.png "Campo Socio del Negocio")

    1. Seleccione en el campo "**Dirección del Socio del Negocio**", la dirección de localización del socio del negocio proveedor.

        ![Campo Dirección del Socio del Negocio](../resources/direc1.png "Campo Dirección del Socio del Negocio")

    1. Seleccione en el campo "**Lista de Precios**", la lista de precios utilizada para la adquisición del servicio.

        ![Campo lista de Precios](../resources/lista1.png "Campo Lista de Precios")}

    1. Seleccione la pestaña "**Línea de Factura**" y proceda al llenado de los campos correspondientes.

        ![Pestaña Línea de Factura](../resources/linea1.png "Pestaña Línea de Factura")

        1. Seleccione en el campo "**Cargo**", el cargo correspondiente al servicio que esta facturando.

            ![Campo Cargo](../resources/carg1.png "Campo Cargo")

        1. Introduzca en el campo "**Cantidad**", la cantidad del servicio a facturar.

            ![Campo Cantidad](../resources/cant1.png "Campo Cantidad")

        1. Introduzca en el campo "**Precio**", el precio del servicio a facturar.

            ![Campo Precio](../resources/precio1.png "Campo Precio")
        
        1. Seleccione la opción "**Guardar Cambios**" en la barra de herramientas de ADempiere, para guardar el registro de los campos.

            ![Icono Guardar Cambios](../resources/guardar1.png "Icono Guardar Cambios")

    1. Seleccione la pestaña "**Costos Adicionales**" y proceda al llenado de los campos correspondientes.

        ![Pestaña Costos Adicionales](../resources/pestcostos1.png "Pestaña Costos Adicionales")
        
        1. Podrá apreciar en el campo "**Distribución de Costo**", que por defecto se encuentra seleccionada la opción "**Cantidad**".

            ![Campo Distribución de Costo](../resources/distcosto1.png "Campo Distribución de Costo")

        1. Seleccione en el campo "**Elemento de Costo**", el costo a aplicar al producto. Para ejemplificar el registro es utilizada la opción "**Costos de Traslado**".

            ![Campo Elemento de Costo](../resources/elemento1.png "Campo Elemento de Costo")

        1. Seleccione en el campo "**Entrega/Recibo**", el documento de recepción del producto al cual será aplicado el costo adicional.

            ![Campo Entrega/Recibo](../resources/entrega1.png "Campo Entrega/Recibo")

            !!! note "**Nota**"

                Si el documento de recepción posee solo una línea de entrega/recibo, no es necesario seleccionar la línea en el campo "**Línea entrega/recibo**".

                Si el documento de recepción posee más de una línea de entrega/recibo, es necesario seleccionar en el campo "**Línea entrega/recibo**", una línea por registro de la pestaña "**Costos Adicionales**". 

        1. Seleccione la opción "**Distribución de Costos**", para aplicar el costo adicional al producto de la recepción.

            ![Opción Distribución de Costos](../resources/distcosto2.png "Distribución de Costos")

            1. Podrá visualizar la ventana "**Distribución de Costos**", donde debe seleccionar la opción "**OK**" para aplicar el costo adicional al producto.

                ![Ventana Distribución de Costos](../resources/distcosto3.png "Ventana Distribución de Costos")

    1. Regrese a la ventana principal "**Factura**" y seleccione la opción "**Completar**", ubicada en la parte inferior derecha del documento.

        ![Opción Completar](../resources/completar.png "Opción Completar")

        1. Seleccione la acción "**Completar**" y la opción "**OK**", para completar el documento por pagar.

            ![Opción Completar](../resources/ok.png "Opción Completar")

## **Consultar Costos Adicionales**

1. Ubique en el menú de ADempiere el producto recepcionado, al cual le fue aplicado el costo adicional.  

    ![Ventana Producto](../resources/producto.png "Ventana Producto")

1. Seleccione la pestaña "**Costos**", donde puede visualizar el registro del costo aplicado.

    ![Pestaña Costo](../resources/costo.png "Pestaña Costo")
    

    

        