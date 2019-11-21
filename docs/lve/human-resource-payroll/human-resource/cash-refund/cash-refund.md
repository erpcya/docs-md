# **Caja Reembolso**

## **Preámbulo**

ADempiere permite controlar el dinero que la empresa le asigna a sus trabajadores seleccionados, por medio de la caja creada a cada uno de ellos. El proceso "**Caja Reembolso**" es realizado con la finalidad de reintegrar un dinero a un empleado, utilizado para solventar situaciones laborales en un determinado momento. De igual manera, el dinero puede ser asignado a los mismos por situaciones de viaje, por ende debe reflejarse en su caja correspondiente.

El presente material elaborado por ERPyA, pretende ofrecerle una explicación eficiente a nuestros clientes del procedimiento a seguir para generar en ADempiere un reembolso a caja, en su versión 3.9.2 para la localización Venezuela.

## **Solicitud de Pago de Cuentas por Pagar**

1. Ubique y seleccione en el menú de ADempiere, la carpeta "**Gestión de Saldos Pendientes**", luego seleccione la ventana "**Selección de Pagos**".

    ![Menú de ADempiere](../resources/menu.png "Menú de ADempiere")

    1. Podrá visualizar la ventana de "**Selección de Pago**", en la cual debe seleccionar el icono "**Registro Nuevo**" en la barra de herramientas de ADempiere.

        ![Icono Registro Nuevo](../resources/nuevo1.png "Icono Registro Nuevo")

        1. Seleccione en el campo "**Organización**", la organización para la cual está realizando el documento "**Solicitud de Pago**".

            ![Campo Organización](../resources/org.png "Campo Organización")

        1. Seleccione el tipo de documento a generar en el campo "**Tipo de Documento Destino**", la selección de este define el comportamiento del documento que se está elaborando, dicho comportamiento se encuentra explicado en el documento [Tipo de Documento]() elaborado por la empresa ERPyA. Para ejemplificar el registro es utilizado el tipo de documento "**Solicitud de Pagos de Cuentas por Pagar**".

            ![Campo Tipo de Documento](../resources/tipodoc.png "Campo Tipo de Documento")
        
        1. Seleccione en el campo "**F. Documento**", la fecha en la cual se está generando el documento de solicitud de pago.

            ![Campo F. Documento](../resources/fdoc.png "Campo F. Documento")
        
        1. Seleccione en el campo "**Fecha de Pago**", la fecha en la cual se debe realizar el pago.

            ![Campo Fecha de Pago](../resources/fpago.png "Campo Fecha de Pago")

        1. Seleccione en el campo "**Moneda**", la moneda para realizar la solicitud de pago.

            ![Campo Moneda](../resources/moneda.png "Campo Moneda")

        1. Introduzca en el campo "**Nombre de Referencia**", un nombre de referencia de la solicitud de pago que está realizando.

            ![Campo Nombre de Referencia](../resources/nrefe.png "Campo Nombre de Referencia")

        1. Introduzca en el campo "**Descripción**", una breve descripción referente a la solicitud de pago que está realizando.

            ![Campo Descripción](../resources/drefe.png "Campo Descripción")

        1. Seleccione la opción "**Crear desde factura**", para crear la solicitud de pago desde la factura.

            ![Opción Crear desde factura](../resources/creardef.png "Campo Crear desde factura")

            1. Seleccione la opción "**Comenzar Búsqueda**", para buscar las facturas de los socios del negocio proveedores.

                ![Opción Comenzar Búsqueda](../resources/comenzarb.png "Opción Comenzar Búsqueda")

            1. Seleccione la factura y la opción "**OK**", para cargar a la pestaña "**Línea de Selección de Pago**" la información de la factura.

                ![Seleccionar Factura y Opción OK](../resources/selefac.png "Seleccionar Factura y Opción OK")

        1. Seleccione el icono "**Refrescar**", ubicado en la barra de herramientas de ADempiere para refrescar la ventana y pueda visualizar la información cargada desde la opción "**Crear desde factura**".

            ![Icono Refrescar](../resources/refrescar1.png "Icono Refrescar")

    1. Seleccione la pestaña "**Línea de Selección de Pago**", para verificar que la información cargada desde la opción "**Crear desde factura**" sea correcta.

        ![Pestaña Línea de Selección de Pago](../resources/peslinea1.png "Pestaña Línea de Selección de Pago")

    1. Regrese a la ventana principal "**Selección de Pago**" y seleccione la opción "**Completar**", ubicada en la parte inferior del documento.

        ![Opción Completar](../resources/completar1.png "Opción Completar")

        1. Seleccione la acción "**Completar**" y la opción "**OK**", para completar el documento.

            ![Acción Completar](../resources/accion.png "Acción Completar")

## **Selección de Pago de Cuentas por Pagar**

1. Ubique y seleccione en el menú de ADempiere, la carpeta "**Gestión de Saldos Pendientes**", luego seleccione la ventana "**Selección de Pagos**".

    ![Menú de ADempiere](../resources/menu.png "Menú de ADempiere")

    1. Podrá visualizar la ventana de "**Selección de Pago**", en la cual debe seleccionar el icono "**Registro Nuevo**" en la barra de herramientas de ADempiere.

        ![Icono Registro Nuevo](../resources/nuevo1.png "Icono Registro Nuevo")

        1. Seleccione en el campo "**Organización**", la organización para la cual está realizando el documento "**Selección de Pago**".

            ![Campo Organización](../resources/org.png "Campo Organización")

        1. Seleccione el tipo de documento a generar en el campo "**Tipo de Documento Destino**", la selección de este define el comportamiento del documento que se está elaborando, dicho comportamiento se encuentra explicado en el documento [Tipo de Documento]() elaborado por la empresa ERPyA. Para ejemplificar el registro es utilizado el tipo de documento "**Selección de Pagos de Cuentas por Pagar**".

            ![Campo Tipo de Documento](../resources/tipodoc2.png "Campo Tipo de Documento")
        
        1. Seleccione en el campo "**F. Documento**", la fecha en la cual se está generando el documento de selección de pago.

            ![Campo F. Documento](../resources/fdoc2.png "Campo F. Documento")
        
        1. Seleccione en el campo "**Fecha de Pago**", la fecha en la cual se debe realizar el pago.

            ![Campo Fecha de Pago](../resources/fpago2.png "Campo Fecha de Pago")

        1. Seleccione en el campo "**Cuenta Bancaria**", la cuenta bancaria de la caja a la que se le realizará el reembolso.

            ![Campo Cuenta Bancaria](../resources/cuentab.png "Campo Cuenta Bancaria")

        1. Introduzca en el campo "**Nombre de Referencia**", un nombre de referencia de la solicitud de pago que está realizando.

            ![Campo Nombre de Referencia](../resources/nrefe2.png "Campo Nombre de Referencia")

        1. Introduzca en el campo "**Descripción**", una breve descripción referente a la solicitud de pago que está realizando.

            ![Campo Descripción](../resources/drefe2.png "Campo Descripción")

        1. Seleccione la opción "**Crear desde selección de pago**", para crear la selección de pago desde la solicitud de pago creada anteriormente.

            ![Opción Crear desde factura](../resources/creardesel.png "Campo Crear desde factura")

            1. Seleccione en el campo "**Selección de Pago**", la solicitud de pago realizada anteriormente.

                ![Campo Selección de Pago](../resources/selep.png "Campo Selección de Pago")

            1. Seleccione la opción "**Comenzar Búsqueda**", para buscar las facturas de los socios del negocio proveedores.

                ![Opción Comenzar Búsqueda](../resources/comenzarb2.png "Opción Comenzar Búsqueda")

            1. Seleccione la selección de pago y la opción "**OK**", para cargar a la pestaña "**Línea de Selección de Pago**" la información de la solicitud de pago realizada anteriormente.

                ![Seleccionar Factura y Opción OK](../resources/selefac2.png "Seleccionar Factura y Opción OK")

        1. Seleccione el icono "**Refrescar**", ubicado en la barra de herramientas de ADempiere para refrescar la ventana y pueda visualizar la información cargada desde la opción "**Crear desde selección de pago**".

            ![Icono Refrescar](../resources/refrescar2.png "Icono Refrescar")

    1. Seleccione la pestaña "**Línea de Selección de Pago**", para verificar que la información cargada desde la opción "**Crear desde selección de pago**" sea correcta.

        ![Pestaña Línea de Selección de Pago](../resources/peslinea2.png "Pestaña Línea de Selección de Pago")

    1. Regrese a la ventana principal "**Selección de Pago**" y seleccione la opción "**Completar**", ubicada en la parte inferior del documento.

        ![Opción Completar](../resources/completar2.png "Opción Completar")

        1. Seleccione la acción "**Completar**" y la opción "**OK**", para completar el documento.

            ![Acción Completar](../resources/accion.png "Acción Completar")

## **Imprimir / Exportar Pagos**

1. Ubique y seleccione en el menú de ADempiere, la carpeta "**Gestión de Saldos Pendientes**", luego seleccione ventana "**Imprimir / Exportar Pagos**".

    ![Menú de ADempiere](../resources/menu3.png "Menú de ADempiere")

    1. Podrá visualizar la ventana "**Imprimir / Exportar Pagos**" y proceder al llenado de los campos correspondientes.

        ![Ventana Imprimir / Exportar Pagos](../resources/iepagos.png "Ventana Imprimir / Exportar Pagos")

    1. Seleccione en el campo "**Selección de Pago**", la selección de pago realizada anteriormente.

        ![Campo Selección de Pago](../resources/selepago.png "Campo Selección de Pago")

    1. Seleccione la opción "**Exportar Registros**", para realizar la exportación de los registros de la caja reembolso.

        ![Opción Exportar Registros](../resources/exportar.png "Opción Exportar Registros")

    1. Podrá visualizar la siguiente ventana con el mensaje de "**Registro guardado**".

        ![Ventana de Registro guardado](../resources/registrog.png "Ventana de Registro guardado")

## **Consultar Pago Generado**

1. Al consultar la pestaña "**Pago Generado**", de la ventana "**Selección de Pago**", se puede apreciar el registro del pago en la caja reembolso seleccionada en la selección de pago.

    ![Pestaña Pago Generado](../resources/pagog.png "Pestaña Pago Generado")

## **Consultar Registro en Caja**

1. Al consultar el registro creado en caja, se puede apreciar el registro de la selección de pago de la siguiente manera.

    ![Ventana Caja](../resources/caja.png "Ventana Caja")

## **Cierre de Caja**

1. Ubique y seleccione en el menú de ADempiere, la carpeta "**Gestión de Saldos Pendientes**", luego seleccione la ventana "**Diario de Caja**", por último seleccione la ventana "**Cierre de Caja**".

    ![Menú de ADempiere](../resources/menu4.png "Menú de ADempiere")

1. Podrá visualizar la ventana "**Cierre de Caja**", donde debe seleccionar el icono "**Registro Nuevo**" y proceder al llenado de los campos correspondientes.

    ![Ventana Cierre de Caja](../resources/nuevo3.png "Ventana Cierre de Caja")

    1. Seleccione en el campo "**Organización**", la organización para la cual está realizando el cierre de caja.

        ![Campo Organización](../resources/org2.png "Campo Organización")

    1. Seleccione el tipo de documento a generar en el campo "**Tipo de Documento**", la selección de este define el comportamiento del documento que se está elaborando, dicho comportamiento se encuentra explicado en el documento [Tipo de Documento]() elaborado por la empresa ERPyA. Para ejemplificar el registro es utilizado el tipo de documento "**Cierre de Caja Reembolso**".

        ![Campo Tipo de Documento](../resources/tipodoc3.png "Campo Tipo de Documento")

    1. Seleccione en el campo "**Cuenta Bancaria**", la cuenta bancaria de la caja reembolso a la cual se le realizará el cierre de caja.

        ![Campo Cuenta Bancaria](../resources/cuentab2.png "Campo Cuenta Bancaria")

    1. Introduzca en el campo "**Descripción**", una breve descripción referente al documento que está realizando.

        ![Campo Descripción](../resources/descrip2.png "Campo Descripción")

    1. Seleccione la opción "**Crear a partir de Pagos**", para realizar el cierre de caja desde la selección de pagos realizada anteriormente.

        ![Opción Crear a partir de pagos](../resources/creardp.png "Opción Crear a partir de pagos")

        1. Podrá visualizar la siguiente ventana de búsqueda inteligente, donde debe seleccionar la opción "**Comenzar Búsqueda**" para buscar los pagos.

            ![Opción Comenzar Búsqueda](../resources/vcrear.png "Opción Comenzar Búsqueda")

        1. Seleccione el registro de la "**Selección de Pago**" creada anteriormente y la opción "**OK**", para cargar la información a la pestaña "**Línea de Cierre de Caja**".

            ![Selección de Pago y Opción OK](../resources/seleccionar.png "Selección de Pago y Opción OK")

    1. Seleccione el icono "**Refrescar**" en la barra de herramientas de ADempiere, para refrescar el registro en la ventana "**Cierre de Caja**".

        ![Icono Refrescar](../resources/refrescar3.png "Icono Refrescar")

    1. Seleccione la opción "**Completar**", ubicada en la parte inferior del documento.

        ![Icono Completar](../resources/completar3.png "Icono Completar")

        1. Seleccione la acción "**Completar**" y la opción "**OK**", para completar el documento.

            ![Acción Completar](../resources/accion.png "Acción Completar")

## **Transferencia Bancaria**

1. Ubique y seleccione en el menú de ADempiere, la carpeta "**Gestión de Saldos Pendientes**", luego seleccione el proceso "**Transferencia Bancaria**".

    ![Menú de ADempiere](../resources/menu2.png "Menú de ADempiere")

    1. Podrá visualizar la ventana del proceso "**Transferencia Bancaria**" y proceder al llenado de los campos correspondientes.

        ![Icono Registro Nuevo](../resources/nuevo2.png "Icono Registro Nuevo")

        1. Seleccione en el campo "**Cuenta bancaria desde**", la cuenta a debitar el monto de la transferencia realizada.

            ![Campo Cuenta bancaria desde](../resources/cuentadesde.png "Campo Cuenta bancaria desde")

        1. Seleccione en el campo "**Cuenta Bancaria a Transferir**", la cuenta caja reembolso a acreditar el monto de la transferencia realizada.

            ![Campo Cuenta Bancaria a Transferir](../resources/cuentacaja.png "Campo Cuenta Bancaria a Transferir")

        1. Seleccione en el campo "**Socio del Negocio**", el socio del negocio titular de la cuenta caja reembolso.

            ![Campo Socio del Negocio](../resources/socio.png "Campo Socio del Negocio")

        1. Seleccione en el campo "**Moneda**", la moneda seleccionada en la solicitud de pago realizada anteriormente.

            ![Campo Moneda](../resources/moneda2.png "Campo Moneda")

        1. Seleccione en el campo "**Cargo**", el cargo correspondiente al reembolso o la transferencia entre cuentas que se está realizando.

            ![Campo Cargo](../resources/cargo.png "Campo Cargo")

        1. Introduzca en el campo "**No. del Documento**", la referencia correspondiente a la transferencia bancaria realizada.

            ![Campo No. del Documento](../resources/referencia1.png "Campo No. del Documento")

        1. Introduzca en el campo "**Documento Destino**", la referencia correspondiente a la transferencia bancaria realizada.

            ![Campo Documento Destino](../resources/referencia2.png "Campo Documento Destino")

        1. Introduzca en el campo "**Monto**", el monto total de la transferencia bancaria realizada.

            ![Campo Monto](../resources/monto.png "Campo Monto")

        1. Introduzca en el campo "**Descripción**", una breve descripción referente a la transferencia que está realizando.

            ![Campo Descripción](../resources/descrip.png "Campo Descripción")

        1. Introduzca en el campo "**Fecha de Estado de Cuenta**", la fecha de la transferencia bancaria realizada.

            ![Campo Fecha de Estado de Cuenta](../resources/ftrans.png "Campo Fecha de Estado de Cuenta")

        1. Introduzca en el campo "**Fecha Contable**", la fecha de la transferencia bancaria realizada.

            ![Campo Fecha Contable](../resources/ftrans2.png "Campo Fecha Contable")

        1. Seleccione la opción "**OK**", para generar en ADempiere la transferencia entre cuentas bancarias.

            ![Opción OK](../resources/ok.png "Opción OK")
    
    1. Podrá apreciar el resultado del proceso de la siguiente manera.

        ![Resultado del Proceso](../resources/resultado.png "Resultado del Proceso")

!!! note "**Nota**"

    Al realizar el proceso de transferencia bancaria, es generado un egreso de banco y un ingreso a caja. De igual manera, es creado un cobro en caja y un pago en pago/cobro. Adicional a ello, el monto de la caja reembolso queda en cero (0).

## **Cierre de Caja**

1. Ubique y seleccione en el menú de ADempiere, la carpeta "**Gestión de Saldos Pendientes**", luego seleccione la ventana "**Diario de Caja**", por último seleccione la ventana "**Cierre de Caja**".

    ![Menú de ADempiere](../resources/menu4.png "Menú de ADempiere")

1. Podrá visualizar la ventana "**Cierre de Caja**", donde debe seleccionar el icono "**Registro Nuevo**" y proceder al llenado de los campos correspondientes.

    ![Ventana Cierre de Caja](../resources/nuevo3.png "Ventana Cierre de Caja")

    1. Seleccione en el campo "**Organización**", la organización para la cual está realizando el cierre de caja.

        ![Campo Organización](../resources/org2.png "Campo Organización")

    1. Seleccione el tipo de documento a generar en el campo "**Tipo de Documento**", la selección de este define el comportamiento del documento que se está elaborando, dicho comportamiento se encuentra explicado en el documento [Tipo de Documento]() elaborado por la empresa ERPyA. Para ejemplificar el registro es utilizado el tipo de documento "**Cierre de Caja Reembolso**".

        ![Campo Tipo de Documento](../resources/tipodoc3.png "Campo Tipo de Documento")

    1. Seleccione en el campo "**Cuenta Bancaria**", la cuenta bancaria de la caja reembolso a la cual se le realizará el cierre de caja.

        ![Campo Cuenta Bancaria](../resources/cuentab3.png "Campo Cuenta Bancaria")

    1. Introduzca en el campo "**Descripción**", una breve descripción referente al documento que está realizando.

        ![Campo Descripción](../resources/descrip3.png "Campo Descripción")

    1. Seleccione la opción "**Crear a partir de Pagos**", para realizar el cierre de caja desde el ingreso generado de la transferencia bancaria realizada anteriormente.

        ![Opción Crear a partir de pagos](../resources/creardp2.png "Opción Crear a partir de pagos")

        1. Podrá visualizar la siguiente ventana de búsqueda inteligente, donde debe seleccionar la opción "**Comenzar Búsqueda**" para buscar los pagos.

            ![Opción Comenzar Búsqueda](../resources/vcrear.png "Opción Comenzar Búsqueda")

        1. Seleccione el registro de la "**Transferencia a Caja Reembolso Usuario**" creada anteriormente y la opción "**OK**", para cargar la información a la pestaña "**Línea de Cierre de Caja**".

            ![Selección de Pago y Opción OK](../resources/seleccionar2.png "Selección de Pago y Opción OK")

    1. Seleccione el icono "**Refrescar**" en la barra de herramientas de ADempiere, para refrescar el registro en la ventana "**Cierre de Caja**".

        ![Icono Refrescar](../resources/refrescar4.png "Icono Refrescar")

    1. Seleccione la opción "**Completar**", ubicada en la parte inferior del documento.

        ![Icono Completar](../resources/completar4.png "Icono Completar")

        1. Seleccione la acción "**Completar**" y la opción "**OK**", para completar el documento.

            ![Acción Completar](../resources/accion.png "Acción Completar")
