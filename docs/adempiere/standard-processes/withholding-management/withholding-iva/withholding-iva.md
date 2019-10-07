# **Retenciones de IVA** 

## **Preámbulo**

Las retenciones de impuesto al valor agregado (IVA) en Venezuela son impuestos aplicados a un documento y retenidos por el cliente de la empresa que genera dicho documento. ADempiere permite aplicar el IVA a los documentos conforme a lo estipulado en la ley que establece el impuesto al valor agregado vigente en Venezuela, así como también aplicar la retención de un porcentaje o la totalidad del IVA aplicado a un documento determinado.

El presente documento elaborado por la empresa ERPyA pretende explicar a los usuarios el procedimiento para configurar y aplicar las retenciones de IVA a los documentos en la versión 3.9.2 de ADempiere en la localización Venezuela.

## **Selección de las Retenciones por Socio del Negocio**

ADempiere permite seleccionar por socio del negocio el porcentaje de IVA a aplicar en los documentos de compra/venta del mismo, a continuación se explica el procedimiento para seleccionar el IVA en un socio del negocio determinado.

1. Ubique en el menú de ADempiere la carpeta "**Relación con Socios del Negocio**", luego seleccione la carpeta "**Reglas de Socios del Negocio**", por último seleccione la ventana "**Socio del Negocio**".

    ![Menú de ADempiere](../resources/menu.png "Menú de ADempiere")

1. Ubique el socio del negocio proveedor al cual se le va a configurar la retención de IVA, para este ejemplo el socio del negocio proveedor es "**Standard Standard**".

    ![Socio del Negocio](../resources/socio.png "Socio del Negocio")

1. En la ventana principal "**Socio del Negocio**" verifique que en el campo "**Tipo de Persona**" se encuentre seleccionado el tipo de socio del negocio al que se le aplicará la retención de IVA, en este campo debe indicar si el socio es persona jurídica domiciliada, persona jurídica no constituída domiciliada, persona jurídica no domiciliada, persona natural no residente, persona natural residente. 

    ![Campo Tipo de Persona](../resources/tipoperso.png "Campo Tipo de Persona")

1. Seleccione la pestaña "**Proveedor**" para configurar la retención de IVA a aplicar al socio del negocio.

    ![Pestaña Proveedor](../resources/proveedor.png "Pestaña Proveedor")

1. Ubique en la parte inferior del documento los checklist para definir las retenciones a aplicar a un socio del negocio proveedor.

    ![Retenciones](../resources/retenciones.png "Retenciones")

    !!! note "Nota"

        Al tildar el checklist en los campos de retenciones ubicados en la parte inferior del documento, significa para ADempiere que no se aplicará dicha retención seleccionada al socio del negocio.

1. Para realizar este ejemplo de la retención de IVA y observar el comportamiento de los checklist en ADempiere, se tildan los checklist referentes a retención de ISLR y municipal.

    ![Checklist Retenciones](../resources/check.png "Checklist Retenciones")

1. Seleccione en el campo "**Retención de IVA Aplicada**", el porcentaje de IVA a retener al socio del negocio proveedor, para este ejemplo el porcentaje a retener es cien por ciento (100%).

    ![Campo Retención de IVA Aplicada](../resources/selecporcentaje.png "Campo Retención de IVA Aplicada")

!!! warning "**Recuerde**"

    Solo debe tildar la retención que no se aplicará al socio del negocio proveedor que esta configurando y guarde los cambios realizados en el socio del negocio con ayuda del icono "**Guardar Cambios**" de la barra de herramientas de ADempiere.

## **Selección de Retenciones a Aplicar en un Documento**

1. Ubique la factura ya realizada al socio del negocio, la misma debe estar en estado "**Completo**", para este ejemplo se utiliza la factura número "**1000034**" del socio del negocio proveedor "**Standard Standard**".

    ![Factura Aplicada al Socio del Negocio](../resources/factura.png "Factura Aplicada al Socio del Negocio")

1. En la barra de herramientas seleccione el icono "**Visualiza Detalle**" para apreciar donde es usado el documento, en este caso la factura.

    ![Icono Visualiza Detalle](../resources/visudetalle.png "Icono Visualiza Detalle")

1. Podrá apreciar el menú desplegado por el icono "**Visualiza Detalle**", el mismo muestra los documentos donde es utilizada la factura.

    ![Menú del Icono Visualiza Detalle](../resources/submenu.png "Menú del Icono Visualiza Detalle")

    1. La opción "**Socio del Negocio**" muestra el documento del socio del negocio utilizado en la factura número "**1000034**" seleccionada para el ejemplo, puede ser utilizada para corroborar que las retenciones aplicadas a la factura sean las mismas configuradas para el socio del negocio.

        ![Opción Socio del Negocio](../resources/opcionsocio.png "Opción Socio del Negocio")
    
    1. La opción "**Retención Generada**" muestra el documento de retención aplicado a la factura número "**1000034**" seleccionada para el ejemplo.

        ![Opción Retención Generada](../resources/retencion.png "Opción Retención Generada")

    1. La opción "**Log de Retención**" muestra el log de la retención no aplicada a la factura número "**1000034**" seleccionada para el ejemplo.

        ![Opción Log de Retención](../resources/log.png "Opción Log de Retención")

!!! warning "**Importante**"

    ADempiere le genera al usuario por medio del icono "**Visualiza Detalle**", las alertas donde indica cuales fueron las retenciones aplicadas (**Retención Generada**) y cuales retenciones no fueron aplicadas (**Log**) según la configuración que tiene un socio del negocio determinado.

## **Generar Retenciones a un Socio del Negocio Proveedor**

1. Ubique la carpeta "**Manejo de Retenciones**" en el menú de ADempiere, luego seleccione la ventana de busqueda inteligente "**Generar Retenciones**".

    ![Menú de ADempiere](../resources/menugenerar.png "Menú de ADempiere")

1. Podrá apreciar la ventana de busqueda inteligente con diferentes campos para filtrar la busqueda.

    ![Ventana de Busqueda Inteligente](../resources/ventana.png "Ventana de Busqueda Inteligente") 

1. Seleccione el socio del negocio en el campo "**Socio del Negocio**", para este ejemplo utilizaremos el socio del negocio "**Standard Standard**".

    ![Filtrar por Socio del Negocio](../resources/selecsocio.png "Filtrar por Socio del Negocio")

1. Seleccione la opción "**Comenzar Busqueda**" para buscar por los campos introducidos.

    ![Opción Comenzar Busqueda](../resources/opcioncomenzar.png "Opción Comenzar Busqueda")

1. Podrá apreciar las retenciones que el socio del negocio seleccionado tiene en los diferentes documentos.

    ![Retenciones del Socio del Negocio](../resources/socioretenciones.png "Retenciones del Socio del Negocio")

1. Seleccione la retención a generar y la opción "**OK**" para generar la retención al socio del negocio seleccionado.

    ![Selección de Retención y Opción OK](../resources/ok.png "Selección de Retención y Opción OK")

1. Podrá apreciar que el proceso se realizó correctamente con el mensaje "**OK**" mostrado por ADempiere al final de la ventana de busqueda inteligente.

    ![Mensaje OK](../resources/final.png "Mensaje OK")

## **Imprimir Documento de la Retención Aplicada al Socio del Negocio**

1. Ubique en el menú de ADempiere la carpeta "**Gestión de Compras**" y luego seleccione la ventana "**Documentos por Pagar**".

    ![Menú de ADempiere](../resources/menudoc.png "Menú de ADempiere")

1. Podrá apreciar la ventana "**Documentos por Pagar**" donde se encuentran todos los registros que posee la misma.

    ![Ventana Documentos por Pagar](../resources/ventanadoc.png "Ventana Documentos por Pagar")

1. Seleccione el icono "**Encontrar Registro**" en la barra de herramientas de ADempiere, para realizar una busqueda avanzada del documento de retención generado.

    ![Icono Encontrar Registro](../resources/iconobuscar.png "Icono Encontrar Registro")

1. Seleccione la pestaña "**Avanzado**" para filtrar la busqueda por "**Socio del Negocio**", "**Tipo de Documento de Retención de Cuentas por Pagar**" y "**Fecha de la Retención**".

    ![Buscador Avanzado](../resources/buscador.png "Buscador Avanzado")

1. Seleccione el icono "**Nuevo**" para generar el número de filas de busqueda que se necesitan, para este ejemplo se necesitan tres (3) filas.

    ![Icono Nuevo](../resources/nuevo.png "Icono Nuevo")

    1. Seleccione en la primera fila la opción "**Socio del Negocio**" y introduzca el nombre del socio del negocio en la columna "**Valor Consulta**", para este ejemplo el socio del negocio es "**Standard Standard**".

        ![Selección Socio del Negocio](../resources/nomsocio.png "Selección Socio del Negocio")

    1. Seleccione en la segunda fila la opción "**Tipo de Documento Destino**" y seleccione en la columna "**Valor Consulta**" el tipo de documento destino, para este ejemplo el tipo de documento destino es "**Retención de IVA para Factura de Cuentas por Pagar**".

        ![Selección Tipo de Documento Destino](../resources/docdestino.png "Selección Tipo de Documento Destino")

    1. Seleccione en la tercera fila la opción "**Fecha Contable**" y seleccione en la columna "**Valor Consulta**" la fecha en la que se realizo la retención, para este ejemplo la fecha es "**24/09/2019**".

        ![Selección Fecha Contable](../resources/fecha.png "Selección Fecha Contable")
    
    1. Seleccione la opción "**OK**" para realizar la busqueda filtrada por los campos seleccionados.

        ![Opción OK](../resources/opcionok.png "Opción OK")

1. Seleccione en la barra de herramientas de ADempiere el icono "**Imprimir**", para imprimir el documento de retención buscado.

    ![Opción Imprimir](../resources/imprimir.png "Opción Imprimir")

1. Podrá apreciar el documento de retención de la siguiente manera.

    ![Documento de Retención](../resources/doc.png "Documento de Retención")
