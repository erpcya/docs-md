# **Requisición a Compra** 

## **Preámbulo**

Un​a requisición a compra es una solicitud al departamento de compras, realizada con el fin de abastecer de productos o servicios a un determinado departamento en una compañía, la presente documentación elaborada por la empresa ERPyA pretende especificar de manera detallada el procedimiento para realizar una requisición a compra en ADempiere. 

## **Requisición a Compra**

1. Ubique en el menú de ADempiere la ventana "**Requisicón**", adjunto imagen para referencia.

    ![Menú de ADempiere](../resources/menureq.png "Menú de ADempiere")

1. Seleccione la opción "**Registro Nuevo**" en la barra de herramientas.

    ![Registro Nuevo](../resources/nuevareq.png "Registro Nuevo")

1. Seleccione en el campo "**Organización**", la organización para la cual se esta realizando el documento de requisición de productos o servicios, el valor en el mismo debe ser diferente del símbolo (*). 

    ![Campo Organización](../resources/organizacion.png "Campo Organización")

1. Seleccione el tipo de documento a generar en el campo "**Tipo de Documento**", la selección de este define el comportamiento del documento que se esta elaborando, dicho comportamiento se encuentra explicado en el documento "Tipo de Documento" elaborado por la empresa ERPyA.

    ![Campo Tipo de Documento](../resources/tipodoc.png "Campo Tipo de Documento")

1. Introduzca el número del documento en el campo "**No. de Documento**", el mismo no es obligatorio ya que ADempiere genera un número de secuencia automáticamente al ser guardado el registro del documento.

    ![Campo Número de Documento](../resources/numdoc.png "Campo Número de Documento")

1. Seleccione en el campo "**Usuario**", el nombre del usuario que esta realizando el documento de requisición.

    ![Campo Usuario](../resources/usuario.png "Campo Usuario")

1. Introduzca una breve descripción de la requisición en el campo "**Descripción**", este campo es opcional.

    ![Campo Descripción](../resources/descripcion.png "Campo Descripción")

1. Seleccione la prioridad de la requisición en el campo "**Prioridad**", este campo indica la urgencia de los productos o servicios que se estan solicitando en el documento, sin embargo, el documento trae predeterminado la opción "**Media**".

    ![Campo Prioridad](../resources/prioridad.png "Campo Prioridad")

1. Seleccione en el campo "**Fecha Requerida**", la fecha en la que se requieren los productos y servicios.

    ![Campo Fecha Requerida](../resources/fecha.png "Campo Fecha Requerida")

1. Seleccione en el campo "**Almacén**", el almacén en el que se requieren los productos y servicios.

    ![Campo Almacén](../resources/almacen.png "Campo Almacén")

1. Seleccione la lista de precios en el campo "**Lista de Precios**", para una requisición la lista siempre debe ser "**Compra**" y la moneda de la lista de precios "**Compra**" va a depender del tipo de documento seleccionado.

    ![Campo Lista de Precios](../resources/lista.png "Campo Lista de Precios")

1. Seleccione el icono "**Guardar**" de la barra de herramientas de ADempiere para guardar los cambios realizados.

    ![Guardar Cambios](../resources/guardar.png "Guardar Cambios")

1. Seleccione la pestaña "**Línea Requisición**" y proceda al llenado de los campos correspondientes.

    ![Línea Requisición](../resources/linea.png "Línea Requisición")

1. Seleccione en el campo "**Producto**", el producto o servicio a solicitar.

    ![Campo Producto](../resources/producto.png "Campo Producto")

1. Seleccione en el campo "**Cantidad**", la cantidad de productos o servicios a solicitar.

    ![Campo Cantidad](../resources/cantidad.png "Campo Cantidad")

1. Seleccione la unidad de medida del producto a solicitar en el campo "**UM**".

    ![Campo UM](../resources/um.png "Campo UM")
    
1. Guarde el icono "**Guardar**" de la barra de herramientas de ADempiere para guardar los cambios realizados.

    ![Guardar Cambios](../resources/guardarli.png "Guardar Cambios")
    
    !!! note "**Nota**"
    
        Si el departamento requiere diferentes productos o servicios, puede seleccionar en la pestaña "**Línea Requisición**", el icono "**Registro Nuevo**" en la barra de herramientas de ADempiere y proceder al llenado de los campos correspondientes explicados anteriormente.

1. Regrese a la ventana principal "**Requisición**" y seleccione la opción "**Completar**".

    ![Opción Completar](../resources/ventanaycompletar.png "Opción Completar")

1. Seleccione la acción "**Completar**" y la opción "**OK**" para completar el documento.

    ![Completar Documento](../resources/completar.png "Completar Documento")
    
