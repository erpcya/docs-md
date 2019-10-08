# **Cerrar Autorización de Devolución de Cliente** 

## **Preámbulo**

El presente documento elaborado por la empresa ERPyA pretende explicar a los usuarios el procedimiento que debe ser realizado en ADempiere para cerrar el documento "**Autorización de Devolución de Cliente**", mismo que es utilizado por las empresas que poseen clientes a los que no les emiten ningún tipo de facturas.

El proceso de devolución de cliente es realizado por la empresa con la finalidad de reflejar en ADempiere el ingreso al inventario de los productos o servicios vendidos al cliente, para generar una devolución la empresa debe contar con los documentos "**Orden de Venta**" y "**Entrega**".

## **Cerrar Autorización de Devolución de Cliente**

Realice su proceso regular de devolución de cliente, para este ejemplo el documento de entrega es el número "**8939**" y el de autorización de devolución de cliente es el número "**123456789**".

1. Ubique la ventana "**Generar Factura (Manual)**" para visualizar la autorización de devolución de cliente disponible.

    ![Generar Factura Manual](../resources/generarfactura1.png "Generar Factura Manual")

1. Proceda a ubicar el documento "**Autorización de Devolución de Cliente**" que se procederá a cerrar.

    ![Autorización de Devolución de Cliente](../resources/autorizacion.png "Autorización de Devolución de Cliente")

1. Seleccione la opción "**Cerrar**" en el documento para que no sea visualizado en el proceso "**Generar Factura (Manual)**".

    ![Opción Cerrar](../resources/cerrar.png "Opción Cerrar")

    !!! warning "**Importante**"

        Esta opción se puede realizar para aquellos clientes a los que no le son generadas ningún tipo de factura.

1. Seleccione la acción "**Cerrar**" y la opción "**OK**" para cerrar el documento.

    ![Acción Cerrar y Opción OK](../resources/accion.png "Acción Cerrar y Opción OK")

1. Verifique que el campo "**Estado del Documento**" diga "**Cerrado**".

    ![Estado del Documento](../resources/estado.png "Estado del Documento")

1. Ubique la ventana "**Generar Facturas (Manual)**" para rectificar que el documento "**Autorización de Devolución de Cliente**" de número "**123456789**" se cerró correctamente.

    ![Generar Factura Manual](../resources/generarfactura2.png "Generar Factura Manual")

!!! warning "**Importante**"

    Al realizar este procedimiento no se visualiza el documento "**Autorización de Devolución de Cliente**" en el formulario "**Generar Facturas (Manual)**".
