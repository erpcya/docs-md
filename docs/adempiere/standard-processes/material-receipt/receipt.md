# **Recepción de Productos**

## **Preámbulo**

Una recepción de productos en ADempiere, es el proceso por el cual los productos procedentes de un proveedor llegan al almacén de una compañía u organización determinada. 

Para que se pueda realizar un documento de recepción de una compra realizada, debe existir obligatoriamente un documento de "**Orden de Compra**" o un "**Documento por Pagar**". Sin embargo, para recepcionar productos o servicios obsequiados a la compañía u organización, ADempiere permite que se complete el documento "**Recepción de Productos**" satisfactoriamente. 

El presente material elaborado por ERPyA, pretende ofrecerle una explicación eficiente a nuestros clientes del procedimiento a seguir para elaborar una recepción de productos correctamente en ADempiere, en su versión 3.9.2 para la localización Venezuela.

## **Recepción de Productos**

1. Ubique en el menú de ADempiere la carpeta "**Gestión de Compras**", luego seleccione la ventana "**Recepción de Productos**", adjunto imagen para referencia.

    ![Menú de ADempiere](../resources/menurecep.png "Menú de ADempiere")

1. Seleccione la opción "**Registro Nuevo**" en la barra de herramientas de ADempiere, para crear un documento nuevo.

    ![Registro Nuevo](../resources/regnuevo.png "Registro Nuevo")

1. Seleccione en el campo "**Organización**", la organización para la cual se esta realizando el documento de recepción de productos, el valor en el mismo debe ser diferente del símbolo (*).

    ![Campo Organización](../resources/organizacion.png "Campo Organización")

1. Seleccione el tipo de documento a generar en el campo "**Tipo de Documento Destino**", la selección de este define el comportamiento del documento que se esta elaborando, dicho comportamiento se encuentra explicado en el documento [Tipo de Documento]() elaborado por la empresa ERPyA.

    ![Campo Tipo de Documento](../resources/tidoc.png "Campo Tipo de Documento")

1. Seleccione en el campo "**Fecha de Movimiento**", la fecha en la que se recepcionaron los productos.

    ![Campo Fecha de Movimiento](../resources/fechamov.png "Campo Fecha de Movimiento")

1. Seleccione en el campo "**Fecha Contable**", la fecha de elaboración del documento.

    ![Campo Fecha Contable](../resources/fechacon.png "Campo Fecha Contable")

1. Seleccione en el campo "**Socio del Negocio**", el socio del negocio proveedor del cual se estan recibiendo los productos.

    ![Campo Socio del Negocio](../resources/socio.png "Campo Socio del Negocio")

1. Seleccione en el campo "**Almacén**", el almacén en que cual se guardarán los productos que se estan recibiendo.

    ![Campo Almacén](../resources/almacen.png "Campo Almacén")

1. Selecione la opción "**Crear Desde**" para crear el documento de recepción desde una factura o una orden de compra.

    ![Opción Crear Desde](../resources/creardesde.png "Opción Crear Desde")

    1. Seleccione en el campo "**Crear Desde Tipo**", el tipo de documento desde donde se va a crear el documento de recepción, para este ejemplo se crea desde tipo "**Factura**". 

        ![Campo Crear Desde Tipo](../resources/creardetipo.png "Campo Crear Desde Tipo")
    
    1. Seleccione en el campo "**Factura**", la factura desde donde va a crear el documento de recepción.

        ![Campo Factura](../resources/selecfac.png "Campo Factura")
    
    1. Seleccione la opción "**Comenzar Busqueda**" para buscar la factura a seleccionar.

        ![Opción Comenzar Busqueda](../resources/comenzar.png "Opción Comenzar")
    
    1. Seleccione la factura desde donde va a crear el documento de recepción.

        ![Selección de Factura](../resources/seleccion.png "Selección de Factura")
    
    1. Seleccione la opción "**OK**" para cargar la factura al documento de recepción.

        ![Opción OK](../resources/ok.png "Opción OK")
    
1. Seleccione la opción "**Completar**" en la parte inferior derecha del documento de recepción de productos.

    ![Opción Completar](../resources/opcioncom.png "Opción Completar")

1. Seleccione la acción "**Completar**" y la opción "**OK**" para completar el documento.

    ![Completar Documento](../resources/completar.png "Completar Documento")

