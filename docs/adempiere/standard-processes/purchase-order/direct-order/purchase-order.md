# **Orden de Compra**

## **Preámbulo**

Una orden de compra es un documento elaborado por el departamento de compras de una empresa determinada, contiene los productos y servicios que dicha empresa necesita, la cantidad y los precios acordados con el proveedor a la que va dirigida, así como el sello del departamento de compras y la firma del jefe de dicho departamento. 

En ADempiere es posible generar una orden de compra directa. El presente material elaborado por ERPyA, pretende ofrecerle una explicación eficiente a nuestros clientes del procedimiento a seguir para generar en ADempiere una orden de compra, en su versión 3.9.2 para la localización Venezuela. 

## **Orden de Compra**

1. Ubique en el menú de ADempiere la carpeta "**Gestión de Compras**", luego seleccione la ventana "**Órdenes de Compra**", adjunto imagen para referencia.

    ![Menú de ADempiere](../resources/menu.png "Menú de ADempiere")

1. Seleccione el icono "**Registro Nuevo**" en la barra de herramientas de ADempiere para crear un nuevo documento.

    ![Registro Nuevo](../resources/registronuevo.png "Registro Nuevo")

1. Seleccione en el campo "**Compañía**", el nombre de la compañía para la cual se esta realizando el documento "**Orden de Compra**".

    ![Campo Compañía](../resources/compania.png "Campo Compañía")

1. Seleccione en el campo "**Organización**", la organización para la cual se esta realizando el documento "**Orden de Compra**", el valor en el mismo debe ser diferente del símbolo (*). 

    ![Campo Organización](../resources/organizacion.png "Campo Organización")

1. Introduzca el número del documento en el campo "**No. de Documento**", el mismo no es obligatorio ya que ADempiere genera un número de secuencia automáticamente al ser guardado el registro del documento.

    ![Campo No. del Documento](../resources/numdoc.png "Campo No. del Documento")

1. Introduzca en el campo "**Descripción**", una breve descripción referente a la orden de compra que se esta realizando, este campo es opcional.

    ![Campo Descripción](../resources/descripcion.png "Campo Descripción")

1. Seleccione el tipo de documento a generar en el campo "**Tipo de Documento Destino**", la selección de este define el comportamiento del documento que se esta elaborando, dicho comportamiento se encuentra explicado en el documento [Tipo de Documento]() elaborado por la empresa ERPyA.

    ![Campo Tipo de Documento Destino](../resources/tipodoc.png "Campo Tipo de Documento Destino")

1. Seleccione en el campo "**Fecha de la Orden**", la fecha de elaboración del documento "**Orden de Compra**".

    ![Campo Fecha de la Orden](../resources/fechaord.png "Campo Fecha de la Orden")

1. Seleccione en el campo "**Fecha Prometida**", la fecha de entrega de la orden prometida por el proveedor.

    ![Campo Fecha Prometida](../resources/fechapro.png "Campo Fecha Prometida")

1. Seleccione en el campo "**Socio del Negocio**", el nombre del socio del negocio proveedor al que se le emite el documento "**Orden de Compra**".

    ![Campo Socio del Negocio](../resources/socio.png "Campo Socio del Negocio")

1. Seleccione la dirección del socio del negocio en el campo "**Dirección del Socio del Negocio**".

    ![Campo Dirección del Socio del Negocio](../resources/direcsocio.png "Campo Dirección del Socio del Negocio")

1. Seleccione en el campo "**Almacén**", el nombre del almacén al que se le realizará la entrega.

    ![Campo Almacén](../resources/almacen.png "Campo Almacén")

1. Seleccione en el campo "**Vía de Entrega**", la opción de cómo serán entregados los productos y servicios de la orden.

    ![Campo Vía de Entrega](../resources/entrega.png "Campo Vía de Entrega")

1. Seleccione en el campo "**Regla de Costo de Flete**", la regla para cargar los costos del flete.

    ![Campo Regla de Costo de Flete](../resources/regla.png "Campo Regla de Costo de Flete")

1. Seleccione la prioridad de la orden en el campo "**Prioridad**", este campo indica la urgencia de los productos o servicios que se estan ordenando en el documento, sin embargo, el documento trae predeterminado la opción "**Media**".

    ![Campo Prioridad](../resources/prioridad.png "Campo Prioridad")

1. Seleccione la lista de precios en el campo "**Lista de Precios**", para una orden de compra la lista siempre debe ser "**Compra**" y la moneda de la lista de precios "**Compra**" va a depender del tipo de documento seleccionado.

    ![Campo Lista de Precios](../resources/lisprecios.png "Campo Lista de Precios")

1. Seleccione en el campo "**Agente Compañía**", el nombre del usuario que esta realizando el documento "**Orden de Compra**".

    ![Campo Agente Compañía](../resources/agente.png "Campo Agente Compañía")

1. Seleccione en el campo "**Termino de Pago**", las condiciones de pago del documento "**Orden de Compra**" que se esta realizando.

    ![Campo Termino de Pago](../resources/terpago.png "Campo Termino de Pago")

    !!! warning "**Importante**"

        Recuerde guardar el registro de la ventana con el icono "**Guardar**" de la barra de herramientas de ADempiere, antes de cambiar a la pestaña "**Línea Orden Compra**".

1. Seleccione la pestaña "**Línea Orden Compra**" y proceda al llenado de los campos correspondientes.

    ![Línea Orden Compra](../resources/linea.png "Línea Orden Compra")

    !!! warning "**Importante**"

        Los campos "**Compañía**", "**Organización**", "**Orden de Compra**", "**Socio del Negocio**" y "**Dirección del Socio del Negocio**", vienen precargados de la ventana principal "**Orden de Compra**".

1. Seleccione en el campo "**Producto**", el producto o servicio a ordenar al socio del negocio seleccionado anteriormente.

    ![Campo Producto](../resources/producto.png "Campo Producto")

1. Seleccione en el campo "**Cantidad**", la cantidad a ordenar del producto o servicio seleccionado.

    ![Campo Cantidad](../resources/cantidad.png "Campo Cantidad")

1. Seleccione la unidad de medida del producto seleccionado en el campo "**UM**", esta puede ser unidad, gramos, kilos, toneladas, entre otras.

    ![Campo UM](../resources/unidmedida.png "Campo UM")

1. Introduzca el precio unitario del producto seleccionado en el campo "**Precio**", este precio es el establecido por el socio del negocio proveedor.

    ![Campo Precio](../resources/precio.png "Campo Precio")

1. Seleccione el impuesto en el campo "**Impuesto**", este puede variar dependiendo del impuesto aplicable al producto seleccionado.

    ![Campo Impuesto](../resources/impuesto.png "Campo Impuesto")

    !!! warning "**Importante**"

        Recuerde guardar el registro de la pestaña "**Línea Orden Compra**" con el icono "**Guardar**" de la barra de herramientas de ADempiere, antes de cambiar a la ventana principal "**Orden de Compra**".

1. Regrese a la ventana principal "**Orden de Compra**" y seleccione la opción "**Completar**" ubicada en la parte inferior derecha del documento. 

    ![Opción Completar](../resources/ventanaycompletar.png "Opción Completar")
