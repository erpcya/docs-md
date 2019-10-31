# **Asignación de Depósito y Caja Multimoneda**

## **Preámbulo**

## **Asignación de Depósito y Caja Multimoneda**

1. Ubique y seleccione en el menú de ADempiere, la carpeta "**Gestión de Saldos Pendientes**", luego seleccione la carpeta "**Caja**", por último seleccione la ventana "**Diario de Caja Chica**".

    ![ADempiere](../resources/menu1.png "Ventana Reembolso Diario de Caja Chica")

1. Seleccione el icono "**Registro Nuevo**", en la barra de herramientas de ADempiere.

    ![ADempiere](../resources/nuevo.png "Ventana Reembolso Diario de Caja Chica")

1. Luego de realizar el proceso regular de llenado de los campos principales, seleccione la opción "**Crear desde Factura**".

    ![ADempiere](../resources/creardfactura.png "Ventana Reembolso Diario de Caja Chica")

    1. Podrá apreciar la ventana del proceso "**Crear desde Factura**", con diferentes campos para filtar la busqueda.

        ![ADempiere](../resources/ventaproceso.png "Proceso Crear Línea de Caja desde una Factura de acuerdo a la Forma de Pago")

        1. Seleccione en el campo "**Fecha de Facturación**", la fecha de la factura a cobrar.

            ![ADempiere](../resources/fecha.png "Proceso Crear Línea de Caja desde una Factura de acuerdo a la Forma de Pago")
        
        1. Seleccione en el campo "**Socio del Negocio**", el socio del negocio cliente de la factura a cobrar.

            ![ADempiere](../resources/socio.png "Proceso Crear Línea de Caja desde una Factura de acuerdo a la Forma de Pago")
        
        1. Seleccione la opción "**Comenzar Búsqueda**", para buscar las facturas que el socio del negocio cliente tiene con la empresa.

            ![ADempiere](../resources/busqueda.png "Proceso Crear Línea de Caja desde una Factura de acuerdo a la Forma de Pago")

            1. Para ejemplificar el registro es utilizada la factura número "**SERIE A -157648**" del socio del negocio cliente "**Estándar**", la cual es emitida en moneda "**VES**", con un monto de "**2.000.000,00**".

                ![ADempiere](../resources/factura.png "Factura del Socio del Negocio Cliente")

        1. Podrá visualizar las diferentes facturas por pagar que el socio del negocio cliente tiene con la empresa, con la conversión de la moneda "**VES**" de la factura a la moneda "**USD**" de la caja cobranza creada.

            ![ADempiere](../resources/muestrafac.png "Proceso Crear Línea de Caja desde una Factura de acuerdo a la Forma de Pago")

            !!! warning "**Importante**"

                Al buscar una factura emitida con una moneda diferente a la moneda seleccionada en la ventana principal "**Reembolso Diario de Caja Chica**", ADempiere realiza la conversión del monto de la factura a la moneda seleccionada para realizar la cobranza.

        1. Seleccione la factura en la que el socio del negocio cliente esta abonando o cancelando un monto, para este ejemplo la factura a seleccionar es la número "**SERIE A -157637**".

            ![ADempiere](../resources/seleccion.png "Proceso Crear Línea de Caja desde una Factura de acuerdo a la Forma de Pago")

        1. Seleccione en el campo "**Tipo de Pago**", la forma de pago utilizada por el socio del negocio cliente para abonar o cancelar dicho monto. Para ejemplificar el registro es utilizada la opción "**Depósito / Transferencia**".

            ![ADempiere](../resources/tipopago.png "Proceso Crear Línea de Caja desde una Factura de acuerdo a la Forma de Pago")
        
        1. Ingrese en el campo "**Monto**", el monto que el socio del negocio cliente esta abonando o cancelando.

            ![ADempiere](../resources/monto.png "Proceso Crear Línea de Caja desde una Factura de acuerdo a la Forma de Pago")

        1. Seleccione la opción "**OK**", para cargar a la pestaña "**Línea de Efectivo**" la información ingresada en la ventana del proceso "**Crear desde Factura**".

            ![ADempiere](../resources/ok.png "Proceso Crear Línea de Caja desde una Factura de acuerdo a la Forma de Pago")

        1. Podrá apreciar el mensaje "**OK**", indicando que fue cargado el registro a la pestaña "**Línea de Efectivo**".

            ![ADempiere](../resources/mensaje.png "Proceso Crear Línea de Caja desde una Factura de acuerdo a la Forma de Pago")
        
1.  Seleccione la pestaña "**Línea de Efectivo**", para verificar que los datos de los campos "**Factura**", "**Tipo de Pago**" y "**Monto**" ingresados a la línea sean correctos.

    ![ADempiere](../resources/linea.png "Pestaña Línea de Efectivo")

1. Regrese a la ventana principal "**Reembolso Diario de Caja Chica**" y seleccione la opción "**Completar**".

    ![ADempiere](../resources/ventana.png "Ventana Reembolso Diario de Caja Chica")

    1. Seleccione la acción "**Completar**" y la opción "**OK**", para completar el documento.

        ![ADempiere](../resources/accion.png "Ventana Reembolso Diario de Caja Chica")

