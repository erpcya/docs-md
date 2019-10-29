# **Autorización de Devolución a Proveedor desde Recepción con más de una Factura**

## **Preámbulo**

El presente material elaborado por ERPyA pretende ofrecerle una explicación eficiente a nuestros clientes del procedimiento a seguir para generar la autorización de devolución a proveedor, desde una recepción con más de una factura asociada, en la versión 3.7.0 de ADempiere en la localización Venezuela, agregando el campo "**Línea de Factura**" en la pestaña "**Línea Autorización Devolución**", permitiendo con esto seleccionar la factura que contiene el producto o servicio a devolver. 

## **Autorización de Devolución a Proveedor**

1. Realizar el proceso regular de elaboración del documento "**Autorización de Devolución a Proveedor**". 

    1. Anteriormente, al seleccionar la línea de recepción con más de una factura asociada, ADempiere generaba el siguiente error.

    ![Error al ingresar línea de entrega / recibo](../resources/error.png "Error al ingresar línea de entrega / recibo")

    !!! info "**Información**"

        El error es generado porque el documento de recepción posee más de un documento de factura asociado al mismo. ERPyA agregó un nuevo campo llamado "**Línea de Factura**", para que los usuarios puedan generar de manera exitosa el documento "**Autorización de Devolución a Proveedor**" desde una recepción con más de una factura asociada a la misma.

1. Posterior a la selección de la línea de recepción, seleccione en el nuevo campo "**Línea de Factura**", la línea de la factura afectada donde se encuentra el producto o servicio a devolver. Para este ejemplo la línea de la factura es "**1029977 - 2019-10-07 00:00:00 - 25282647.53_10_21795385.80**".

    ![Factura Afectada](../resources/lineafactura.png "Factura Afectada")

1. Seleccione en el campo "**Cantidad**", la cantidad de productos o servicios a devolver, para este ejemplo la cantidad es "**2**".

    ![Campo Cantidad](../resources/cantidad.png "Campo Cantidad")

1. Seleccione en el campo "**UM**", la unidad de medida del producto o servicio a devolver, para este ejemplo la misma es "**CAJA**".

    ![Campo UM](../resources/um.png "Campo UM")

1. Seleccione el icono "**Guardar Cambios**" en la barra de herramientas de ADempiere.

    ![Icono Guardar Cambios](../resources/guardar.png "Icono Guardar Cambios")

1. Regrese a la ventana principal "**Autorización Devolución Proveedor**" y seleccione la opción "**Completar**".

    ![Ventana Principal y Opción Completar](../resources/completar.png "Ventana Principal y Opción Completar")

1. Seleccione la acción "**Completar**" y la opción "**OK**", para completar el documento.

    ![Acción Completar y Opción OK](../resources/accioncompletar.png "Acción Completar y Opción OK")

1. Verifique que en el campo "**Estado del Documento**" diga "**Completo**".

    ![Estado del Documento](../resources/estado.png "Estado del Documento")

!!! warning "**Importante**"

    Proceda a realizar el proceso regular de devolución a proveedor y nota de crédito por devolución a proveedor.