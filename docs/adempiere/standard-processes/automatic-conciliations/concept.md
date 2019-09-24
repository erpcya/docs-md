# **Conciliaciones Automáticas**

## **Preámbulo**

El proceso conciliación automática permite comparar los registros bancarios que se tienen en ADempiere con el estado de cuenta real del banco, para realizar una conciliación es necesario realizar primero una importación del extracto bancario del banco a conciliar. 

El presente documento elaborado por la empresa ERPyA pretende explicar a los usuarios de forma detallada el procedimiento correcto para realizar una conciliación en ADempiere.

## **Importación del Extracto Bancario**

Un extracto bancario es un estado de cuenta generado por un banco determinado utilizado por la empresa para realizar sus operaciones o transacciones, el documento es generado por lapsos que la mayoria de las veces es mensual. La importación del extracto bancario, valga la redundancia, es importar a ADempiere el estado de cuenta generado por el banco, a continuación se explica el procedimiento que se debe realizar para importar el documento en ADempiere.

1. Ubique en el menú de ADempiere la carpeta "**Gestión del Sistema**", luego seleccione la carpeta "**Datos**", finalmente seleccione la carpeta "**Importar Datos**", por último seleccione el proceso "**Carga de Estado de Cuentas**" y proceda al llenado de los campos correspondientes. 

    ![Menú de ADempiere](../resources/menuimportacion.png "Menú de ADempiere")

1. Seleccione en el campo "**Cargador de Estado de Cuenta**" el nombre del banco del cual pertenece el estado de cuenta a importar.

    ![Campo Cargador de Estado de Cuenta](../resources/banco.png "Campo Cargador de Estado de Cuenta")

1. Seleccione en el campo "**Nombre del Archivo**" el archivo a importar. 

    ![Campo Nombre del Archivo](../resources/nombre.png "Campo Nombre del Archivo")

1. Seleccione la opción "**Seleccionar Archivo**" para buscar el archivo a importar.

    ![Opción Seleccionar Archivo](../resources/nueva.png "Opción Seleccionar Archivo")

1. Seleccione la opción "**Cargar Archivo (Upload)**" para cargar el archivo seleccionado.

    ![Opción Cargar Archivo](../resources/archivo.png "Opción Cargar Archivo")

1. Seleccione la opción "**OK**" para importar el archivo seleccionado.

    ![Opción OK](../resources/ok.png "Opción OK")

1. Podrá apreciar la importación exitosa en la ventana y seleccionar la opción "**OK**" para finalizar el proceso, adjunto imagen para referencia.

    ![Mensaje Exitoso](../resources/finalimportacion.png "Mensaje Exitoso")

## **Conciliación**

Es un proceso que se realiza con la finalidad de garantizar los saldos de las cuentas por cobrar y las cuentas por pagar que posee una determinada empresa, el mismo compara la información del estado de cuenta con la existente en ADempiere para corroborar que ambos coincidan y no existan errores en la contabilidad de la empresa, a continuación se explica el procedimiento que se debe realizar para generar una conciliación bancaria en ADempiere.

1. Ubique en el menú de ADempiere la carpeta "**Gestión de Saldos Pendientes**" y luego seleccione la ventana "**Estado de Cuenta Bancario**".

    ![Menú de ADempiere](../resources/menuconciliacion.png "Menú de ADempiere")

1. Seleccione el icono "**Registro Nuevo**" en la barra de herramientas de ADempiere y proceda al llenado de los campos correspondientes.

    ![Registro Nuevo](../resources/nuevoreg.png "Registro Nuevo")

1. Seleccione la organización en el campo "**Organización**".

    ![Campo Organización](../resources/organizacion.png "Campo Organización")

1. Seleccione el tipo de documento destino en el campo "**Tipo de Documento Destino**".

    ![Campo Tipo de Documento](../resources/tipodoc.png "Campo Tipo de Documento Destino")

1. Seleccione la cuenta bancaria en el campo "**Cuenta Bancaria**".

    ![Campo Cuenta Bancaria](../resources/cuentabancaria.png "Campo Cuenta Bancaria")

1. Seleccione el icono "**Guardar**" en la barra de herramientas de ADempiere para guardar los cambios realizados en el documento.

    ![Icono Guardar](../resources/guardar.png "Icono Guardar")

    !!! note "Nota"

        Hasta este paso es el llenado del encabezado de la conciliación, donde se define el banco en el cual se va a realizar la conciliación de los pagos/cobros que ha tenido la empresa en un rango determinado. En adelante se procedera a realizar la conciliación.

1. Seleccione el icono "**Proceso**" en la barra de herramientas de ADempiere.

    ![Icono Proceso](../resources/proceso.png "Icono Proceso")

1. Seleccione la opción "**Conciliación de Estado de Cuenta**" en el menú que es desplegado por el icono "**Proceso**".

    ![Menú Proceso](../resources/conciliar.png "Menú Proceso")

    1. Se le desplegará una ventana de busqueda inteligente con campos por los cuales se filtrará la busqueda para realizar la conciliación.

        ![Filtrar Busqueda](../resources/datos.png "Filtrar Busqueda")

        !!! note "Nota"

            Puede observar que la ventana de busqueda inteligente trae precargado el campo "**Cuenta Bancaria**" con la información del banco seleccionado en la ventana principal "**Estado de Cuentas Bancario**". Los otros campos reflejados en esta ventana serán utilizados acorde al criterio de busqueda que se requiera.

    1. Una vez definido el criterio de busqueda, seleccione la opción "**Refrescar**" para que se muestre la información del estado de cuenta bancario importado y los pagos/cobros realizados en ADempiere.

        ![Refrescar](../resources/refrescar.png "Refrescar")
    
    1. Podrá apreciar los movimientos del estado de cuenta del lado izquierdo de la venta de busqueda inteligente.

        ![Movimientos Importados](../resources/movimientos.png "Movimientos Importados")

    1. Podrá apreciar del lado derecho de la ventana de busqueda inteligente los movimientos realizados en ADempiere.

        ![Movimientos de ADempiere](../resources/movimientosad.png "Movimientos de ADempiere")

    1. Seleccione la opción "**Simular Conciliación**" para buscar coincidencia entre la información reflejada en ambos lados de la ventana de busqueda inteligente.

        ![Opción Simular Conciliación](../resources/simular.png "Opción Simular Conciliación")

    1. Podrá apreciar los movimientos con coincidencia en la parte inferior de la ventana de busqueda inteligente.

        ![Pagos con Coincidencia](../resources/coincidencias.png "Pagos con Coincidencia")

        !!! note "Nota"

            Si existe coincidencia entre los pagos/cobros y el extracto bancario se le mostrarán los movimientos con coincidencias, de lo contrario no se le mostrará ningun movimiento con coincidencia.
    
    1. Seleccione la opción "**OK**" para guardar el registro de coincidencia entre los movimientos reflejados en la ventana de busqueda inteligente, estos movimientos automaticamente se cargarán en la pestaña "**Línea Estado Cuentas**"

        ![Opción OK](../resources/okbusqueda.png "Opción OK")
    
1. Seleccione la pestaña "**Línea Estado Cuentas**" para verificar el registro de coincidencias de movimientos de la venta de busqueda inteligente.

    ![Pestaña Línea Estado Cuentas](../resources/linea.png "Pestaña Línea Estado Cuentas")

1. Regrese a la ventana principal "**Estado Cuentas Bancario**" y seleccione la opción "**Completar**".

    ![Ventana Principal y Opción Completar](../resources/ventanaycompletar.png "Ventana Principal y Opción Completar")
    
1. Seleccione la acción "**Completar**" y la opción "**OK**" para completar el documento.

    ![Acción Completar Documento](../resources/completar.png "Acción Completar Documento")