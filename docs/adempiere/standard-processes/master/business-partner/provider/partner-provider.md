# **Socio del Negocio Proveedor**

## **Definición de Socio del Negocio Proveedor**                

El socio del negocio puede ser cualquier persona, este puede tener tres (3) condiciones ya que puede ser proveedor, cliente o empleado. Un socio del negocio proveedor es aquella persona que provee de productos y servicios a otra persona que lo necesite, a continuación se define el proceso para la creación de socio del negocio proveedor en ADempiere.

### **Proceso de Registro del Socio del Negocio**

1. En el menú de ADempiere, ubiqué la carpeta "**Relación con Socios del Negocio**", "**Reglas de Socios del Negocio**", y finalmente seleccione la ventana "**Socio del Negocio**" (adjunto imagen).


    ![ADempiere](../img/menu.png "Menú de ADempiere")


#### **Ventana Socio del Negocio** 

En esta ventana se registran los datos principales del socio del negocio. Cada uno de los campos con el símbolo (*) son obligatorios para el registro.

1. A continuación visualizará la siguiente ventana del Socio del Negocio, dónde debe seleccionar el ícono de "**Registro Nuevo**" que se encuentra ubicado en la barra de herramientas de ADempiere.


    ![ADempiere](../img/ventana.png "Ventana de Registro de Socio del Negocio")


1. Proceda al llenado de los campos necesarios que a continuación se detallan.
    
    1. Seleccione la organización en el campo "**Organización**".
        

        ![ADempiere](../img/organizacion.png "Ventana de Registro de Socio del Negocio")


        !!! warning "**Importante**"

                Para que el socio de negocio este disponible para todas las organizaciones, el mismo deberá estar registrado con la organización en (*) de lo contrario el socio del negocio solo estará disponible para una sola organización. 
    

    1. Introduzca el código del socio del negocio en el campo "**Código**".
        

        ![ADempiere](../img/codigo.png "Ventana de Registro de Socio del Negocio")
    

    1. Introduzca el nombre del socio del negocio en el campo "**Nombre**".


        ![ADempiere](../img/nombre.png "Ventana de Registro de Socio del Negocio")


    1. Seleccione el grupo al que pertenezca el socio del negocio que esta registrando, para este ejemplo el grupo utilizado es "**Proveedores Nacionales**".


        ![ADempiere](../img/grupo.png "Ventana de Registro de Socio del Negocio")


    1. Seleccione el ícono "**Guardar Cambios**" para guardar los datos.


!!! warning "**Importante**"

        Recuerde guardar los campos requeridos cada vez que se vaya a posicionar en una pestaña de la ventana socio del negocio. 


##### **Pestaña Proveedor**

Esta pestaña le indica a ADempiere si el socio del negocio que se esta registrando es un proveedor. 

1. Seleccione la pestaña "**Proveedor**" que se encuentra del lado izquierdo de la ventana socio del negocio. 


    ![ADempiere](../img/pestproveedor.png "Ventana de Registro de Socio del Negocio")


1. A continuación visualizará la siguiente imagen, dónde debe tildar el checklist "**Proveedor**". 


    ![ADempiere](../img/checklist.png "Ventana de Registro de Socio del Negocio")


!!! warning "**Importante**"

        De no ser tildado el checklist "**Proveedor**", ADempiere no tomará el socio de negocio como proveedor. 

##### **Pestaña Cuenta Bancaria**


En esta pestaña se registran los datos bancarios del socio del negocio proveedor, con el checklist "**Activo**" se pueden registrar los datos de la tarjeta de crédito del socio del negocio. Así mismo, con el checklist "**ACH**" se pueden registrar los datos de la cuenta bancaria del socio del negocio.

1. Seleccione la pestaña "**Cuenta Bancaria**" que se encuentra ubicada del lado izquierdo de la ventana socio del negocio. Por defecto se encuentra tildado el checklist "**Activo**".


    ![ADempiere](../img/pestcuenta.png "Ventana de Registro de Socio del Negocio")


###### **Checklist Activo**

1. Seleccione el tipo de tarjeta en el campo "**Tarjeta de Crédito**".


    ![ADempiere](../img/tipotarjeta.png "Ventana de Registro de Socio del Negocio")


1. Introduzca el número de tarjeta en el campo "**Número**".


    ![ADempiere](../img/nutarjeta.png "Ventana de Registro de Socio del Negocio")


1. Introduzca el código de verificación en el campo "**Código Verificación**".


    ![ADempiere](../img/codverificacion.png "Ventana de Registro de Socio del Negocio")


1. Introduzca el mes de expiración en el campo "**Mes de Expiración**".


    ![ADempiere](../img/mesexpiracion.png "Ventana de Registro de Socio del Negocio")


1. Introduzca el año de expiración en el campo "**Año de Expiración**".


    ![ADempiere](../img/añoexpiracion.png "Ventana de Registro de Socio del Negocio")


1. Introduzca el nombre de referencia de la tarjeta en el campo "**Nombre**".


    ![ADempiere](../img/nomcuenta.png "Ventana de Registro de Socio del Negocio")


!!! warning "**Importante**"
        Este proceso se realiza con la finalidad de registrar la tarjeta de crédito del socio del negocio. 

###### **Checklist ACH**

1. Para registros de cuentas bancarias, tilde el checklist "**ACH**", a continuación se reflejarán los campos para el registro de la cuenta bancaria del socio del negocio.

    
    ![ADempiere](../img/ACH.png "Ventana de Registro de Socio del Negocio")


1. En el campo "**Banco**" seleccione el banco a registrar con ayuda del ícono identificador (adjunto imagen).

    
    ![ADempiere](../img/banco.png "Ventana de Registro de Socio del Negocio")


1. A continuación visualizará la siguiente ventana con los diferentes bancos, dónde debe seleccionar el banco que posee el socio del negocio y la opción "**OK**" para cargar los datos al formulario.


    ![ADempiere](../img/ventcuentas.png "Ventana de Registro de Socio del Negocio")


1. Seleccione el tipo de cuenta correspondiente a la cuenta del socio del negocio en el campo "**Tipo de Cuenta Bancaria**".


    ![ADempiere](../img/tipocuenta.png "Ventana de Registro de Socio del Negocio")


1. Introduzca el número de cuenta del socio del negocio en el campo "**No. De Cuenta**".


    ![ADempiere](../img/numcuenta.png "Ventana de Registro de Socio del Negocio")


1. Introduzca el nombre de referencia de la cuenta en el campo "**Nombre**".


    ![ADempiere](../img/nomcuenta2.png "Ventana de Registro de Socio del Negocio")


!!! warning "**Importante**"

        Este proceso se realiza con la finalidad de registrar la cuenta del socio del negocio. 


##### **Pestaña Localización**

La localización de un socio del negocio es muy importante por diferentes motivos y más si el socio del negocio es proveedor. Ya que las transacciones de compras serán realizadas al mismo, en esta pestaña se deben resgistrar con exactitud los datos de la dirección del socio del negocio.

1. Seleccione la pestaña "**Localización**" que se encuentra ubicada del lado izquierdo de la ventana socio del negocio.

    ![ADempiere](../img/pestlocalizacion.png "Ventana de Registro de Socio del Negocio")

1. A continuación visualizará la siguiente ventana, dónde debe introducir la dirección exacta del socio del negocio.

    ![ADempiere](../img/ventlocalizacion.png "Ventana de Registro de Socio del Negocio")


!!! warning "**Importante**"
                
        Recuerde guardar los campos requeridos cada vez que se vaya a posicionar en una pestaña de la ventana socio del negocio.


##### **Pestaña Contacto**

En esta pestaña se registran todos los datos de contacto que se tengan del socio del negocio proveedor.

1. Seleccione la pestaña "**Contacto**" que se encuentra ubicada del lado izquierdo de la ventana socio del negocio, para proceder a llenar los campos necesarios.

    ![ADempiere](../img/pestcontacto.png "Ventana de Registro de Socio del Negocio")

1. Introduzca el nombre de contacto del socio del negocio en el campo "**Nombre**".

    ![ADempiere](../img/nombcontacto.png "Ventana de Registro de Socio del Negocio")

1. Introduzca el email de contacto del socio del negocio en el campo "**Email**".

    ![ADempiere](../img/emailcontacto.png "Ventana de Registro de Socio del Negocio")

1. Introduzca el teléfono de contacto del socio del negocio en el campo "**Teléfono**".

    ![ADempiere](../img/telecontacto.png "Ventana de Registro de Socio del Negocio")


!!! note "**NOTA:**"
        
        Este procedimiento realizado aplica solo para los **Socios del Negocio** que cumplan el rol de **Proveedor**.
