## Generar Factura desde Préstamo

El documento por cobrar a generar (Fiscal o no Fiscal) será emitido por concepto de cuota vencida, con los siguientes conceptos dependiendo del préstamo inicial solicitado(Producto Financiero) y su configuración **(_Vea Configuración de Producto Financiero (Préstamo)_)**:

- Préstamo con Interés Gravado:
   - Capital
   - Interés + IVA
- Préstamo con Interés Exento:
   - Capital
   - Interés
- Préstamo sin Interés:
   - Capital

Sin embargo existen casos en los cuales el solicitante retarda la cancelación de cuotas vencidas en estos casos ADempiere calcula intereses moratorios sobre la cuota vencida generando así una línea más en el documento.


## Interpretando la Ventana

Panel de Parámetros de **_Consulta de Amortización:_** En este panel dispone de los parámetros que serán de filtro para consultar las cuotas  pendientes por Facturar.

![drawing](resources/invoice-window-preview.png "Interpretando la Ventana")

Panel de resultados **_Para Selección de Cuotas_**: En este panel seleccionará las cuotas pendientes por Facturar.

![drawing](resources/invoice-result-preview.png "Interpretando la Ventana")

Panel de **_Datos para Generar la Factura_**: En este panel indicará los datos para generar la factura.

![drawing](resources/invoice-parameters-preview.png "Interpretando la Ventana")

## Generar Factura desde Préstamo

**Generar Factura desde Préstamo**

Se creó un Smart Browser permitiendo al usuario seleccionar múltiples cuotas de un préstamo en específico y generar de manera eficiente y segura, agrupando varias cuotas en una factura, ó discriminando por cuota si el usuario así lo desea de esta forma será generada una factura por cuota.

Vaya a la ventana Generar Factura (Desde Préstamo) (Adjunto Imagen)

![alt_text](resources/invoice-menu.png "Menú de Factura")

A continuación se desplegará la siguiente ventana (Adjunto Imagen)

![alt_text](resources/invoice-generate-preview.png "Generar Factura")


Proceda a llenar los Parámetros de **_Consulta de Cuotas_** necesarios para generar la factura:

**Socio de Negocio:** Es un parámetro obligatorio, filtrará los préstamos pendientes por cobrar con el Socio del Negocio indicado.

**Acuerdo Financiero(Préstamo):** Es un parámetro obligatorio, filtrará las cuotas pendientes por cobrar del Préstamos indicado.

**Fecha Inicio:** filtrará las cuotas pendientes por cobrar  en el Rango de fecha indicada.

**Fecha Final:** filtrará las cuotas pendientes por cobrar  en el Rango de fecha indicada.

**Fecha de Vencimiento:** filtrará las cuotas pendientes por cobrar  en el Rango de fecha indicada.

Vencido: Si selecciona la opción SI, filtrará las cuotas  vencidas, Si selecciona la opción NO, filtrará las cuotas   no vencidas.

**Seleccione la opción comenzar búsqueda** ![alt_text](resources/pay-selection-init-search.png "Comenzar Búsqueda")


A continuación verá los siguientes resultados:

![alt_text](resources/invoice-init-search.png "Comenzar Búsqueda")

Seleccione la cuota que desea facturar:

![alt_text](resources/invoice-search-result.png "Resultado de Búsqueda")

Proceda a llenar los **_Datos para Generar la Factura_**.

![alt_text](resources/invoice-fill-values.png "Llenando Datos")


**Tipo de Documento Destino:** Seleccione el tipo de Documento con el que desea sea generada el Documento por Cobrar.

**Fecha de Facturación:** Indique la fecha en la cual será facturada la cuota.

**Dividir Factura:** Esta opción debe ser marcada si desea dividir las facturas por cuota, de lo contrario se generará una factura consolidada con las cuotas seleccionadas.

**Acción de Documento:** Indique la acción de documento con la cual desea generar la selección.

![alt_text](resources/invoice-action-search.png "Datos para Facturar")

Si desea generar la selección de pago seleccione la opción ok ![alt_text](resources/loan-ok-icon.png "Opción Aceptar"), caso contrario seleccione la opción cancelar ![alt_text](resources/loan-cancel-icon.png "Opción Cancelar")

Si seleccionó la opción OK el sistema generará la(s)  factura(s) de forma exitosa generando el siguiente mensaje indicando el número(s) de la(s) factura(s) generada.

![drawing](resources/invoice-generated.png "Documentos Generados")

## Consulta de Factura de Préstamo

Existen dos posibles formas de consultar las facturas generadas asociadas a un préstamo, a continuación serán explicadas.

Ventanas en Documento por Cobrar

Vaya a la ventana Documento por Cobrar (Adjunto Imagen)

![alt_text](resources/invoice-generated-menu.png "Menú de Factura")

A continuación se desplegará la siguiente ventana (Adjunto Imagen).

![alt_text](resources/invoice-window.png "Ventana de Factura")

Busque el registro desde la opción “**_Encontrar Registro_**” ubicada en la barra de herramientas.

![drawing](resources/invoice-search-icon.png "Buscar Factura")

A continuación se desplegará el siguiente dialogo

![alt_text](resources/invoice-search-dialog.png "Diálogo de Búsqueda")

Ingrese el número de la selección generada en el proceso **Generar Factura (Desde Préstamo)**

**Ventana de Préstamo:**

Una vez en la ventana de Préstamo

Vaya a la opción “**_Visualiza Detalle(Donde es Usado)_**” ubicada en la barra de herramientas.

![alt_text](resources/invoice-search-reference-icon.png "Referencias de Factura")

A continuación se desplegará el siguiente dialogo

![alt_text](resources/invoice-search-reference-list.png "Lista de Referencias")

Seleccione la opción “**_Documento por Cobrar de Cuota _**”

![alt_text](resources/invoice-search-reference-list-selected.png "Lista de Referencias Seleccionadas")


Esta opción lo llevará automáticamente a los pagos asociados a este préstamo.


## Contabilidad del Proceso

ADempiere contabilizará el Documento por Cobrar dependiendo de la definición del producto financiero (**_Vea Configuración de Producto Financiero (Préstamo)_**), a continuación se detalla:

**Capital:** Contabilidad definida en el producto asociado en producto financiero.

**Interés:** Contabilidad definida en el cargo asociado en  la tasa financiera relacionada en el producto financiero.

**IVA:** Contabilidad definida en la tasa de impuesto asociada en el cargo perteneciente a la tasa financiera relacionada en el producto financiero.

<table>
  <tr>
   <td><strong>Cuenta</strong></td>
   <td><strong>Débito Contabilizado</strong></td>
   <td><strong>Crédito Contabilizado</strong></td>
  </tr>
  <tr>
   <td><strong>12410 - Prestamos por Cobrar</strong></td>
   <td><p style="text-align: right">0,00</p></td>
   <td><p style="text-align: right">1.522,36</p></td>
  </tr>
  <tr>
   <td><strong>12410 - Interés por Cobrar</strong></td>
   <td><p style="text-align: right">0,00</p></td>
   <td><p style="text-align: right">316,48</p></td>
  </tr>
  <tr>
   <td><strong>22000 - IVA</strong></td>
   <td><p style="text-align: right">0,00</p></td>
   <td><p style="text-align: right">69,6256</p></td>
  </tr>
  <tr>
   <td><strong>12110 - Cuentas por Cobrar Comerciales</strong></td>
   <td><p style="text-align: right">1908,4656</p></td>
   <td><p style="text-align: right">0,00</p></td>
  </tr>
  <tr>
   <td><strong>Total</strong></td>
   <td><p style="text-align: right">1908,4656</p></td>
   <td><p style="text-align: right">1908,4656</p></td>
  </tr>
</table>
