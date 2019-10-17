# **Socio del Negocio Proveedor**

## **Definición de Socio del Negocio Proveedor**                

El socio del negocio puede ser cualquier persona, este puede tener tres (3) condiciones ya que puede ser proveedor, cliente o empleado. Un socio del negocio proveedor es aquella persona que provee de productos y servicios a otra persona que lo necesite, a continuación se define el proceso para la creación de socio del negocio proveedor en ADempiere.

### **Proceso de Registro del Socio del Negocio**

1. En el menú de ADempiere, ubique y seleccione la carpeta "**Relación con Socios del Negocio**", luego seleccione la carpeta "**Reglas de Socios del Negocio**" y finalmente seleccione la ventana "**Socio del Negocio**", adjunto imagen para referencia.

    ![ADempiere](../img/menu.png "Menú de ADempiere")

#### **Ventana Socio del Negocio** 

En esta ventana se registran los datos principales del socio del negocio. Cada uno de los campos con el símbolo (*) son campos obligatorios para el registro.

1. A continuación visualizará la ventana principal "**Socio del Negocio**", dónde debe seleccionar el icono de "**Registro Nuevo**" que se encuentra ubicado en la barra de herramientas de ADempiere.

    ![ADempiere](../img/ventana.png "Ventana de Registro de Socio del Negocio")

1. Proceda al llenado de los campos necesarios que a continuación se detallan.
    
    1. Seleccione en el campo "**Organización**", la organización para la cual se esta registrando el socio del negocio proveedor.

        ![ADempiere](../img/organizacion.png "Ventana de Registro del Socio del Negocio")

        !!! warning "**Importante**"

            Para que el socio del negocio este disponible para todas las organizaciones de la compañía, el mismo deberá estar registrado con la organización en (*) de lo contrario el socio del negocio solo estará disponible para una sola organización. 
    
    1. Introduzca el código de identificación, cédula o rif del socio del negocio en el campo "**Código**", el valor introducido en este campo automáticamente se reflejará en el campo "**Número Identificación**".
        
        ![ADempiere](../img/codigo.png "Ventana de Registro de Socio del Negocio")
    
        !!! warning "**Importante**"

            Se recomienda que al ingresar el valor al campo "**Código**" se ingrese principalmente el prefijo que le corresponde según el tipo de registro que tenga el socio del negocio (jurídico, natural, entre otros).

    1. Introduzca el nombre del socio del negocio proveedor en el campo "**Nombre**".

        ![ADempiere](../img/nombre.png "Ventana de Registro de Socio del Negocio")

    1. Seleccione el grupo de socio del negocio al que pertenezca el socio del negocio proveedor que esta registrando, para este ejemplo el grupo utilizado es "**Proveedores Nacionales**".

        ![ADempiere](../img/grupo.png "Ventana de Registro de Socio del Negocio")

    1. Seleccione en el campo "**Tipo de Persona**, el tipo de persona al que pertenece el socio del negocio que se esta registrando, este campo obligatorio permite la configuración esencial de las retenciones a generar al mismo.

        ![ADemmpiere](../img/tipopers.png "Ventana de Registro de Socio del Negocio") 

    1. Seleccione el icono "**Guardar Cambios**" ubicado en la barra de herramientas para guardar los datos ingresados.

!!! warning "**Importante**"

    Recuerde guardar el registro de los campos cada vez que se vaya a posicionar en una pestaña de la ventana socio del negocio. 

##### **Pestaña Proveedor**

Esta pestaña le indica a ADempiere si el socio del negocio que se esta registrando es un proveedor. 

1. Seleccione la pestaña "**Proveedor**" que se encuentra del lado izquierdo de la ventana principal "**Socio del Negocio**". 

    ![ADempiere](../img/pestproveedor.png "Ventana de Registro de Socio del Negocio")

    !!! info "La pestaña "**Proveedor**" se compone de:"

        - Un checklist "**Proveedor**".
        
        - Los datos principales del socio del negocio donde los campos "**Compañía**", "**Organización**", "**Código**" y "**Nombre**", vienen cargados de la ventana principal "**Socio del Negocio**". 
        
        - Ademas posee un grupo de campos que definen la configuración de retenciones a aplicar al socio del negocio, dichos campos se encuentran explicados en los documentos ["**Retenciones IVA**"](), ["**Retenciones ISLR**"]() y ["**Retenciones Municipales**"]().

1. Seleccione el checklist "**Proveedor**" para habilitar en ADempiere el socio del negocio como proveedor de la compañía u organización. 

    ![ADempiere](../img/checklist.png "Ventana de Registro del Socio del Negocio")

    !!! warning "**Importante**"

        De no ser tildado el checklist "**Proveedor**", ADempiere no tomará el socio del negocio como proveedor.

1. Al tildar el checklist "**Proveedor**" podrá apreciar un grupo de campos necesarios para la compra de productos al mismo, dichos campos no son obligatorios ya que pueden ser definidos en el documento "**Orden de Compra**" al momento de su elaboración.

    ![ADempiere](../img/campos.png "Ventana de Registro de Socio del Negocio")

    1. El campo "**Regla de Pago**" establece la regla de pago definitiva para las compras al socio del negocio proveedor que se esta registrando, para este ejemplo la regla de pago utilizada es "**A Crédito**". 

        ![ADempiere](../img/regla.png "Ventana de Registro de Socio del Negocio")

    1. El campo "**Lista de Precios de Compra**" establece la lista de precios definitiva para las compras al socio del negocio proveedor que se esta registrando, para este ejemplo la lista de precios utilizada es "**Compra (VES)**".

        ![ADempiere](../img/lista.png "Ventana de Registro de Socio del Negocio")

    1. El campo "**Término Pago Orden de Compra**" establece el término de pago definitivo para las compras al socio del negocio proveedor que se esta registrando, para este ejemplo el término de pago utilizado es "**Crédito a 15 días**".

        ![ADempiere](../img/termino.png "Ventana de Registro de Socio del Negocio")

    1. El campo "**Esquema del Descuento en OC**" establece el descuento definitivo para las compras al socio del negocio proveedor que se esta registrando, para este ejemplo el esquema de descuento utilizado es "**Compras Porcentaje Simple**".

        ![ADempiere](../img/esq.png "Ventana de Registro de Socio del Negocio")

    1. El campo "**Exento de (IGTF)**" establece que no se aplicará el impuesto "**IGTF**" al socio del negocio proveedor que se esta registrando

        ![ADempiere](../img/igtf.png "Ventana de Registro de Socio del Negocio")

##### **Pestaña Cuenta Bancaria**

En esta pestaña se registran los datos bancarios del socio del negocio proveedor, con el checklist "**Activo**" se pueden registrar los datos de la tarjeta de crédito del socio del negocio. Así mismo, con el checklist "**ACH**" se pueden registrar los datos de la cuenta bancaria del socio del negocio.

1. Seleccione la pestaña "**Cuenta Bancaria**" que se encuentra ubicada del lado izquierdo de la ventana socio del negocio. Por defecto se encuentra tildado el checklist "**Activo**".

    ![ADempiere](../img/pestcuenta.png "Ventana de Registro de Socio del Negocio")

###### **Checklist Activo**

1. Seleccione en el campo "**Tarjeta de Crédito**", el tipo de tarjeta de crédito que posee el socio del negocio proveedor que esta registrando.

    ![ADempiere](../img/tipotarjeta.png "Ventana de Registro de Socio del Negocio")

1. Introduzca en el campo "**Número**", el número de tarjeta de crédito del socio del negocio proveedor que esta registrando.

    ![ADempiere](../img/nutarjeta.png "Ventana de Registro de Socio del Negocio")

1. Introduzca en el campo "**Código Verificación**", el código de verificación de la tarjeta de crédito del socio del negocio proveedor que esta registrando, este código son los últimos tres números del reverso de la tarjeta.

    ![ADempiere](../img/codverificacion.png "Ventana de Registro de Socio del Negocio")

1. Introduzca en el campo "**Mes de Expiración**", el mes de expiración de la tarjeta de crédito del socio del negocio proveedor que esta registrando.

    ![ADempiere](../img/mesexpiracion.png "Ventana de Registro de Socio del Negocio")

1. Introduzca el año de expiración de la tarjeta de crédito del socio del negocio proveedor que esta registrando en el campo "**Año de Expiración**".

    ![ADempiere](../img/añoexpiracion.png "Ventana de Registro de Socio del Negocio")

1. Introduzca el nombre de referencia de la tarjeta en el campo "**Nombre**", en este campo va el nombre del titular de la tarjeta de crédito que esta registrando.

    ![ADempiere](../img/nomcuenta.png "Ventana de Registro de Socio del Negocio")

!!! warning "**Importante**"
    
    Este proceso se realiza con la finalidad de registrar la tarjeta de crédito del socio del negocio. 

###### **Checklist ACH**

1. Para registros de cuentas bancarias, tilde el checklist "**ACH**", a continuación se reflejarán los campos para el registro de la cuenta bancaria del socio del negocio proveedor.
    
    ![ADempiere](../img/ACH.png "Ventana de Registro de Socio del Negocio")

1. En el campo "**Banco**" seleccione el banco a registrar con ayuda del icono identificador (adjunto imagen).

    ![ADempiere](../img/banco.png "Ventana de Registro de Socio del Negocio")

1. A continuación visualizará la siguiente ventana con los diferentes bancos, dónde debe seleccionar el banco que posee el socio del negocio proveedor y la opción "**OK**" para cargar los datos a la ventana.

    ![ADempiere](../img/ventcuentas.png "Ventana de Registro de Socio del Negocio")

1. Seleccione en el campo "**Tipo de Cuenta Bancaria**", el tipo de cuenta correspondiente a la cuenta del socio del negocio proveedor.

    ![ADempiere](../img/tipocuenta.png "Ventana de Registro de Socio del Negocio")

1. Introduzca en el campo "**No. De Cuenta**", el número de cuenta del socio del negocio proveedor que esta registrando.

    ![ADempiere](../img/numcuenta.png "Ventana de Registro de Socio del Negocio")

1. Introduzca en el campo "**Nombre**", el nombre del titular de la cuenta bancaria que esta registrando.

    ![ADempiere](../img/nomcuenta2.png "Ventana de Registro de Socio del Negocio")

!!! warning "**Importante**"

    Este proceso se realiza con la finalidad de registrar la cuenta bancaria del socio del negocio proveedor. 

##### **Pestaña Localización**

La localización de un socio del negocio es muy importante por diferentes motivos y más si el socio del negocio es proveedor. Ya que las transacciones de compras serán realizadas al mismo, en esta pestaña se deben registrar con exactitud los datos de la dirección del socio del negocio.

1. Seleccione la pestaña "**Localización**" que se encuentra ubicada del lado izquierdo de la ventana socio del negocio.

    ![ADempiere](../img/pestlocalizacion.png "Ventana de Registro de Socio del Negocio")

1. A continuación visualizará la siguiente ventana, dónde debe introducir la dirección exacta del socio del negocio proveedor que esta registrando.

    ![ADempiere](../img/ventlocalizacion.png "Ventana de Registro de Socio del Negocio")

!!! warning "**Importante**"

    Recuerde guardar el registro de los campos cada vez que se vaya a posicionar en una pestaña de la ventana socio del negocio.

##### **Pestaña Contacto**

En esta pestaña se registran todos los datos de contacto que se tengan del socio del negocio proveedor.

1. Seleccione la pestaña "**Contacto**" que se encuentra ubicada del lado izquierdo de la ventana socio del negocio, para proceder a llenar los campos necesarios.

    ![ADempiere](../img/pestcontacto.png "Ventana de Registro de Socio del Negocio")

1. Introduzca en el campo "**Nombre**", el nombre del socio del negocio contacto para las transacciones entre las empresas.

    ![ADempiere](../img/nombcontacto.png "Ventana de Registro de Socio del Negocio")

1. Introduzca en el campo "**Email**", el email del socio del negocio contacto para las transacciones entre las empresas.

    ![ADempiere](../img/emailcontacto.png "Ventana de Registro de Socio del Negocio")

1. Introduzca en el campo "**Teléfono**", el teléfono del socio del negocio contacto para las transacciones entre las empresas.

    ![ADempiere](../img/telecontacto.png "Ventana de Registro de Socio del Negocio")

!!! note "**NOTA:**"
        
    Este procedimiento realizado aplica solo para los **Socios del Negocio** que cumplan el rol de **Proveedor**.
