## Generar Pagos de Préstamo

Una vez generada la selección de pago, podrá generar los pagos de los préstamos (Desembolso), el pago generado como se explicó anteriormente, hereda el cargo seleccionado en la definición del producto financiero **(_Vea Configuración de Producto Financiero (Préstamo)_)** .

Vaya a la ventana de Imprimir/Exporta Pago (Adjunto Imagen)


![alt_text](resources/payment-menu.png "Menú de Pagos")

A continuación se desplegará la siguiente ventana (Adjunto Imagen)


![alt_text](resources/payment-pay-print.png "Imprimir y Exportar Pagos")

Ingrese la selección de pagos generada en la sección

[Generar Selección de Pago](generate-payment-selection.md), seleccionando la opción de búsqueda ![alt_text](resources/payment-pay-selection-find.png "Buscar Selección de Pagos")

![alt_text](resources/payment-pay-print-find.png "Búsqueda de Selección de Pagos")

A continuación se desplegará la siguiente ventana (Adjunto Imagen)

![alt_text](resources/payment-pay-print-search.png "Búsqueda de Selección de Pagos")


Seleccione la Selección de pago generada  en la sección [Generar Selección de Pago](generate-payment-selection.md)

![alt_text](resources/payment-generate-pay-selection.png "Generar Selección de Pagos")

Seleccione la opción imprimir ![alt_text](resources/payment-print.png "Imprimir Pago")

![alt_text](resources/payment-print-window.png "Imprimir Pago")

A Continuación ADempiere habrá generado el pago y usted verá el siguiente reporte (Adjunto Imagen)

![alt_text](resources/payment-print-report.png "Reporte de Impresión de Pago")

## Consulta de Pagos de Préstamo

Existen dos posibles formas de consultar los pagos generados asociadas a un préstamo, a continuación serán explicadas.

Ventanas en Menú

Pago/Cobro

Si el pago generado desde el proceso [Generar Selección de Pago (Desde Préstamo)](generate-payment-selection.md) es generado con una cuenta bancaria podrá consultar con esta opción.

Vaya a la ventana _“**Pago/Cobro”**_ (Adjunto Imagen)

![alt_text](resources/payment-payment-menu.png "Menú de Pago")

A continuación se desplegará la siguiente ventana (Adjunto Imagen).

![alt_text](resources/payment-window.png "Ventana de Pago")

Busque el registro desde la opción “**_Encontrar Registro_**” ubicada en la barra de herramientas.

![alt_text](resources/payment-window-search.png "Búsqueda de Pago")

A continuación se desplegará el siguiente dialogo

![alt_text](resources/payment-search-dialog.png "Ventana de Búsqueda de Pago")

Ingrese el número de la selección generada en el proceso [Generar Selección de Pago (Desde Préstamo)](generate-payment-selection.md) Caja Si el pago generado desde el proceso

[Generar Selección de Pago (Desde Préstamo)](generate-payment-selection.md) es generado con una cuenta de caja podrá consultar con esta opción.

Vaya a la ventana Caja (Adjunto Imagen)

![alt_text](resources/payment-cash-menu.png "Menú de Caja")


A continuación se desplegará la siguiente ventana (Adjunto Imagen).


![alt_text](resources/payment-cash-window.png "Ventana de Caja")


Busque el registro desde la opción “**_Encontrar Registro_**” ubicada en la barra de herramientas.

![alt_text](resources/payment-window-search.png "Ventana de Caja")

A continuación se desplegará el siguiente dialogo

![alt_text](resources/payment-search-dialog.png "Búsqueda de Caja")

Ingrese el número de la selección generada en el proceso [Generar Selección de Pago (Desde Préstamo)](generate-payment-selection.md)

**Ventana de Préstamo:**

Una vez en la ventana de Préstamo

Vaya a la opción “**_Visualiza Detalle(Donde es Usado)_**” ubicada en la barra de herramientas.

![alt_text](resources/payment-loan-search.png "Búsqueda de Referencia de Préstamo")

A continuación se desplegará el siguiente dialogo

![alt_text](resources/payment-loan-search-reference.png "Referencia de Préstamo")

Seleccione la opción “**_Pagos de Préstamos_**”

![alt_text](resources/payment-loan-search-reference-selected.png "Referencia de Préstamo Seleccionada")

Esta opción lo llevará automáticamente a los pagos asociados a este préstamo.

## Contabilidad del Proceso

ADempiere contabilizará el préstamo dependiendo de la contabilidad configurada en el cargo heredado desde la definición del producto financiero (**_Vea Configuración de Producto Financiero (Préstamo)_**) .


<table>
  <tr>
   <td><strong>Cuenta</strong></td>
   <td><strong>Débito Contabilizado</strong></td>
   <td><strong>Crédito Contabilizado</strong></td>
  </tr>
  <tr>
   <td><strong>12410 - Prestamos por Cobrar</strong></td>
   <td><p style="text-align: right"><strong>20.000,00</strong></p></td>
   <td><p style="text-align: right"><strong>0,00</strong></p></td>
  </tr>
  <tr>
   <td><strong>89900 - Cheques y Depósito en Circulación</strong></td>
   <td><p style="text-align: right">0,00</p></td>
   <td><p style="text-align: right">20.000,00</p></td>
  </tr>
  <tr>
   <td><strong>Total</strong></td>
   <td><p style="text-align: right">20.000,00</p></td>
   <td><p style="text-align: right">20.000,00</p></td>
  </tr>
</table>
