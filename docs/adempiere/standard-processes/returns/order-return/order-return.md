# **Devolución de Cliente** 

## **Preámbulo**

El presente material elaborado por ERPyA pretende ofrecerle una explicación eficiente a nuestros clientes del procedimiento a seguir para realizar una "**Devolución de Cliente**" en la versión 3.9.2 de ADempiere en la localización Venezuela. Dicho proceso de devolución es realizado generando un documento de autorización de devolución y porterior a ello los documentos de devolución y nota de crédito correspondientes, mismos necesarios para reflejar el ingreso de los productos vendidos al almacén de la empresa.

## **Autorización de Devolución (Cliente)**

1. Ubique y seleccione en el menú de ADempiere, la carpeta "**Gestión de Ventas**", luego seleccione la carpeta "**Órdenes de Venta**", por último seleccione la ventana "**Orden de Devolución (Cliente)**".

    ![ADempiere](../resources/menu1.png "Autorización de Devolución (Cliente)")

1. Seleccione el icono "**Registro Nuevo**", en la barra de herramientas de ADempiere y proceda al llenado de los campos correspondientes.

    ![ADempiere](../resources/ventana1.png "Autorización de Devolución (Cliente)")

    1. Seleccione en el campo "**Organización**", la organización para la cual esta realizando el documento "**Autorización de Devolución (Cliente)**".

        ![ADempiere](../resources/org1.png "Autorización de Devolución (Cliente)")

    1. Seleccione el tipo de documento a generar en el campo "**Tipo de Documento Destino**", la selección de este define el comportamiento del documento que se esta elaborando, dicho comportamiento se encuentra explicado en el documento [Tipo de Documento]() elaborado por la empresa ERPyA.

        ![ADempiere](../resources/tipodoc1.png "Autorización de Devolución (Cliente)")

    1. Seleccione en el campo "**Fecha de la Orden**", la fecha en la que se esta realizando el documento.

        ![ADempiere](../resources/fecha1.png "Autorización de Devolución (Cliente)")

    1. Seleccione en el campo "**Tipo Autorización Devolución**", el motivo por el cual son devueltos los productos. Para ejemplificar el registro es utilizada la opción "**Producto Erróneo**".

        ![ADempiere](../resources/tipoauto1.png "Autorización de Devolución (Cliente)")

    1. Seleccione en el campo "**Socio del Negocio**", el socio del negocio cliente seleccionado en la orden de venta.

        ![ADempiere](../resources/socio1.png "Autorización de Devolución (Cliente)")

    1. Seleccione en el campo "**Dirección del Socio del Negocio**", la dirección del socio del negocio cliente seleccionado.

        ![ADempiere](../resources/diresocio1.png "Autorización de Devolución (Cliente)")

    1. Seleccione en el campo "**Almacén**", el almacén en el que serán ingresados los productos.

        ![ADempiere](../resources/almacen1.png "Autorización de Devolución (Cliente)")

    1. Seleccione en el campo "**Lista de Precios**", la lista de precios seleccionada en la orden de venta.

        ![ADempiere](../resources/precios1.png "Autorización de Devolución (Cliente)")

    1. Seleccione en el campo "**Agente Comercial**", el vendedor que realiza la orden de venta.

        ![ADempiere](../resources/agente1.png "Autorización de Devolución (Cliente)")

1. Seleccione el icono "**Guardar Cambios**", para guardar el registro de los campos.

    ![ADempiere](../resources/guardar1.png "Autorización de Devolución (Cliente)")

1. Seleccione el icono "**Proceso**" en la barra de herramientas.

    ![ADempiere](../resources/proceso1.png "Autorización de Devolución (Cliente)")

    1. Podrá apreciar un menú desplegado por el icono "**Proceso**", en el cual debe seleccionar la opción "**Crear Orden de Devolución desde Entrega / Recibo**".

        ![ADempiere](../resources/menupro1.png "Autorización de Devolución (Cliente)")

    1. Podrá apreciar la seguiente ventana de búsqueda inteligente en la cual debe seleccionar en el campo "**Entrega / Recibo**", el documento de entrega con ayuda del identificador.

        ![ADempiere](../resources/entrega1.png "Autorización de Devolución (Cliente)")

    1. Seleccione el documento de entrega y luego seleccione la opción "**OK**".

        ![ADempiere](../resources/selecpro.png "Autorización de Devolución (Cliente)")

    1. Seleccione la opción "**Comenzar Búsqueda**", para apreciar los productos entregados al cliente.

        ![ADempiere](../resources/opcomenzar.png "Autorización de Devolución (Cliente)")

    1. Seleccione el producto de la devolución e introduzca la cantidad de la devolución en la columna cantidad.

        ![ADempiere](../resources/prodevo.png "Autorización de Devolución (Cliente)")

    1. Seleccione la opción "**OK**", para cargar los productos a la pestaña "**Línea de Autorización**".

        ![ADempiere](../resources/ok1.png "Autorización de Devolución (Cliente)")

1. Seleccione la pestaña "**Línea de Autorización**", para verificar que las cantidades, el producto y el precio cargado sean los correctos.

    ![ADempiere](../resources/linea1.png "Autorización de Devolución (Cliente)")

1. Regrese a la ventana principal "**Autorización de Devolución**" y seleccione la opción "**Completar**" ubicada en la parte inferior derecha del documento.

    ![ADempiere](../resources/completar1.png "Autorización de Devolución (Cliente)")

    1. Seleccione la acción "**Completar**" y la opción "**OK**", para completar el documento.

        ![ADempiere](../resources/accion1.png "Autorización de Devolución (Cliente)")

## **Devolución (Cliente)**

1. Ubique y seleccione en el menú de ADempiere, la carpeta "**Gestión de Ventas**", luego seleccione la carpeta "**Entregas**", por último seleccione la ventana de búsqueda inteligente "**Generar Entregas Desde Líneas de Orden**".

    ![ADempiere](../resources/menu2.png "Devolución (Cliente)")

1. Seleccione en el campo "**Socio del Negocio**", el socio del negocio seleccionado en el documento de "**Orden de Devolución Cliente**".

    ![ADempiere](../resources/socio2.png "Devolución (Cliente)")

1. Seleccione la opción "**Comenzar Búsqueda**", para buscar los documentos de ventas relacionados con el socio del negocio seleccionado.

    ![ADempiere](../resources/busqueda2.png "Devolución (Cliente)")

1. Podrá apreciar las órdenes de ventas y las autorizaciones de devoluciones realizadas al socio del negocio seleccionado.

    ![ADempiere](../resources/listado2.png "Devolución (Cliente)")

1. Ubique y seleccione el documento "**Orden de Devolución Cliente**" a utilizar para crear el documento "**Devolución (Cliente)**".

    ![ADempiere](../resources/seleccion2.png "Devolución (Cliente)")

1. Verifique que el campo "**Acción del Documento**" diga "**Completar**", de esta manera el documento "**Devolución (Cliente)**" será generado en estado "**Completo**".

    ![ADempiere](../resources/completar2.png "Devolución (Cliente)")

1. Seleccione la opción "**OK**", para generar el documento "**Devolución (Cliente)**" desde el documento "**Orden de Devolución Cliente**" seleccionado.

    ![ADempiere](../resources/ok2.png "Devolución (Cliente)")

1. Seleccione en el menú de ADempiere, la carpeta "**Gestión de Devoluciones**", luego seleccione la ventana "**Devolución Cliente**".

    ![ADempiere](../resources/menu5.png "Devolución (Cliente)")

1. Podrá apreciar el documento "**Devolución Cliente**", creado desde la ventana de búsqueda inteligente.

    ![ADempiere](../resources/devo.png "Devolución (Cliente)")

!!! note "**Nota**"

    La elaboración de este proceso permite a ADempiere ingresar nuevamente los productos seleccionados en el documento, al almacén de la empresa.

## **Nota de Crédito por Devolución (Cliente)**

1. Para generar el documento "**Nota de Crédito por Devolución (Cliente)**", debe existir obligatoriamente una factura para aplicar la nota de crédito. Para ejemplificar el registro de la devolución de cliente se utiliza la factura número "**84884**".

    ![ADempiere](../resources/factura.png "Nota de Crédito por Devolución (Cliente)")

1. Ubique y seleccione en el menú de ADempiere, la carpeta "**Gestión de Ventas**", luego seleccione la carpeta "**Facturas de Ventas**", por último seleccione la ventana de búsqueda inteligente "**Generar Facturas desde Líneas de la Orden**".

    ![ADempiere](../resources/menu3.png "Nota de Crédito por Devolución (Cliente)")

1. Seleccione en el campo "**Socio del Negocio**", el socio del negocio del documento "**Autorización de Devolución (Cliente)**".

    ![ADempiere](../resources/socio3.png "Nota de Crédito por Devolución (Cliente)")

1. Seleccione la opción "**Comenzar Búsqueda**", para buscar los documentos relacionados con el socio del negocio seleccionado.

    ![ADempiere](../resources/busqueda3.png "Nota de Crédito por Devolución (Cliente)")

1. Seleccione el documento "**Autorización de Devolución (Cliente)**" a utilizar para crear el documento "**Nota de Crédito por Devolución (Cliente)**".

    ![ADempiere](../resources/selec3.png "Nota de Crédito por Devolución (Cliente)")

1. Verifique que el campo "**Acción del Documento**" tenga seleccionada la acción "**Completar**", de esta manera el documento "**Nota de Crédito por Devolución (Cliente)**" será generado en estado "**Completo**".

    ![ADempire](../resources/completar3.png "Nota de Crédito por Devolución (Cliente)")

1. Destilde el checklist "**Agregar Línea de Referencia en Factura**" para que no se genere una línea en el documento solo con la referencia de la transacción.

    ![ADempiere](../resources/checklist3.png "Nota de Crédito por Devolución (Cliente)")

1. Seleccione la opción "**OK**", para que se genere el documento "**Nota de Crédito por Devolución (Cliente)**".

    ![ADempiere](../resources/ok3.png "Nota de Crédito por Devolución (Cliente)")

1. Podrá visualizar el mensaje donde indica que se creó la nota de crédito desde la autorización de devolución "**ADCN-1000014**".

    ![ADempiere](../resources/resultado3.png)

1. Seleccione en el menú de ADempiere, la carpeta "**Gestión de Ventas**", luego seleccione la carpeta "**Facturas de Ventas**", por último seleccione la ventana "**Documentos por Cobrar**".

    ![ADempiere](../resources/menu4.png "Nota de Crédito por Devolución (Cliente)")

1. Podrá apreciar el documento "**Nota de Crédito por Devolución (Cliente)**", creado desde la ventana de búsqueda inteligente.

    ![ADempiere](../resources/nota.png "Nota de Crédito por Devolución (Cliente)")

1. En la pestaña "**Línea de la Factura**", podrá visualizar la factura afectada número "**84884**".

    ![ADempiere](../resources/nota4.png "Nota de Crédito por Devolución (Cliente)")

## **Consultar Saldos Abiertos**

1. Al consultar saldos abiertos se verifica que el resulta es el siguiente.

    ![ADempiere](../resources/saldos.png "Saldos Abiertos")
