# **Documentos de Cuentas por Cobrar en Dolares**

## **Preámbulo**

El presente instructivo es elaborado por la empresa ERPyA, con la finalidad de brindar a los usuarios un documento específico que le permita rebajar en monto de una factura de cuentas por cobrar en dolares, para una mejor ejemplificación del proceso este debe tener factura previamente elaborada, completada y que se encuentre trabajando con la moneda extrajera USD.

A continuación se explican cada uno de los pasos a seguir para elaborar el proceso correctamente.

## **Ajuste de Crédito**

1. Ubique en el menú de ADempiere la ventana "**Documentos por Cobrar**", adjunto imagen para referencia.

    ![Menú de ADempiere](../resources/menu.png "Menú de ADempiere")

1. Seleccione la opción "**Registro Nuevo**" en la barra de herramientas de ADempiere y proceda al llenado de los campos correspondientes.

    ![Registro Nuevo](../resources/nuevo.png "Registro Nuevo")

1. Seleccione la organización en el campo "**Organización**".

    ![Campo Organización](../resources/organizacion.png "Campo Organización")

1. Selecione el tipo de documento destino en el campo "**Tipo de Documento Destino**".

    ![Campo Tipo de Documento Destino](../resources/tipodoc.png "Campo Tipo de Documento Destino")

1. Seleccione el socio del negocio en el campo "**Socio del Negocio**", este debe ser el mismo socio del negocio de la factura a la cual se le aplicará el ajuste de crédito.

    ![Campo Socio del Negocio](../resources/socio.png "Campo Socio del Negocio")

1. Seleccione el tipo de conversión en el campo "**Tipo de Conversión**".

    ![Campo Tipo de Conversión](../resources/conversion.png "Campo Tipo de Conversión")
    
1. Seleccione la opción "**Guardar**" en la barra de herramientas de ADempiere para guardar los cambios realizados.

    ![Guardar Cambios](../resources/guardar.png "Guardar Cambios")

1. Seleccione la pestaña "**Línea de la Factura**" y proceda al llenado de los campos correspondientes.

    ![Pestaña Línea](../resources/linea.png "Pestaña Línea")

1. Seleccione el cargo en el campo "**Cargo**".

    ![Campo Cargo](../resources/cargo.png "Campo Cargo")

1. Introduzca el monto en el campo "**Precio**".

    ![Campo Precio](../resources/monto.png "Campo Precio")

1. Seleccione la opción "**Guardar**" en la barra de herramientas de ADempiere para guardar los cambios realizados.

    ![Guardar Cambios](../resources/guardarli.png "Guardar Cambios")

1. Regrese a la ventana principal "**Factura**" y seleccione la opción "**Completar**".

    ![Opción Completar](../resources/completar.png "Opción Completar")

1. Verificar que el campo "**Estado del Documento**" diga "**Completo**" y el campo "**Tipo de Documento**" diga "**AJDC (CxC) ARA**".

    ![Verificar](../resources/verificar.png "Verificar")

## **Asignación de Pagos**

1. Ubique en el menú de ADempiere la ventana "**Asignación de Pagos**".

    ![Menú de ADempiere](../resources/asigmenu.png "Menú de ADempiere")

1. Seleccione el socio del negocio en el campo "**Socio del Negocio**".

    ![Campo Socio del Negocio](../resources/asigsocio.png "Campo Socio del Negocio")

1. Selccione la organización en el campo "**Organización**".

    ![Campo Organización](../resources/asiorganizacion.png "Campo Organización")

1. Seleccione la moneda en el campo "**Moneda**".

    ![Campo Moneda](../resources/asigmoneda.png "Campo Moneda")

1. Seleccione primero el documento del ajuste de crédito creado para indicar a ADempiere que ese es el monto que se va a restar a la factura.

    ![Ajuste de Crédito](../resources/ajuste.png "Ajuste de Crédito")

1. Seleccione el documento de la factura creada para indicar a ADempiere que esa es la factura a la que se le aplicará el ajuste de crédito seleccionado.

    ![Factura](../resources/factura.png "Factura")

1. Seleccione la opción "**Proceso**" para realizar el cruce de cuentas.

    ![Opción Proceso](../resources/proceso.png "Opción Proceso")

1. ADempiere muestra el número de la "**Asignación de Pagos**" en la parte inferior del documento.

    ![Número de la Asignación de Pagos](../resources/numasig.png "Número de la Asignación de Pagos")

## **Diario de Caja Chica**

1. Ubique en el menú de ADempiere la ventana "**Diario de Caja Chica**".

    ![Menú de ADempiere](../resources/menu.png "Menú de ADempiere")

1. Seleccione la opción "**Registro Nuevo**" en la barra de herramientas de ADempiere y proceda al llenado de los campos correspondientes.

    ![Registro Nuevo](../resources/registronuevo.png "Registro Nuevo")

1. Seleccione la caja menor en el campo "**Caja Menor**".

    ![Campo Caja Menor](../resources/cajamenor.png "Campo Caja Menor")

1. Seleccione el tipo de documento destino en el campo "**Tipo de Documento Destino**".

    ![Campo Tipo de Documento Destino](../resources/tipodocaja.png "Campo Tipo de Documento Destino")

1. Seleccione el agente comercial en el campo "**Agente Comercial**".

    ![Campo Agente Comercial](../resources/agente.png "Campo Agente Comercial")

1. Seleccione la pestaña "**Línea de Efectivo**" y proceda al llenado de los campos correspondientes.

    ![Pestaña Línea de Efectivo](../resources/lineacaja.png "Pestaña Línea de Efectivo")

1. Seleccione el tipo de efectivo en el campo "**Tipo de Efectivo**".

    ![Campo Tipo de Efectivo](../resources/tipoefectivo.png "Campo Tipo de Efectivo")

1. Seleccione el socio del negocio en el campo "**Socio del Negocio**", este debe ser el mismo socio seleccionado en el documento factura y en el documento ajuste de crédito.

    ![Campo Socio del Negocio](../resources/sociocaja.png "Campo Socio del Negocio")

1. Seleccione la actividad en el campo "**Actividad**".

    ![Campo Actividad](../resources/actividad.png "Campo Actividad")

1. Seleccione el cargo en el campo "**Cargo**", este debe ser el mismo seleccionado en el documento ajuste de crédito.

    ![Campo Cargo](../resources/cargocaja.png "Campo Cargo")

1. Introduzca el monto en el campo "**Monto**", este debe ser el resultante de la multiplicación del monto del ajuste de crédito por la tasa de cambio del cobro.

    ![Campo Monto](../resources/montocaja.png "Campo Monto")

1. Seleccione el impuesto en el campo "**Impuesto**". 

    ![Campo Impuesto](../resources/impuesto.png "Campo Impuesto")

1. Regrese a la ventana principal "**Reembolso Diario de Caja Chica**" y seleccione la opción "**Completar**".

    ![Opción Completar](../resources/completarcaja.png "Opción Completar")

