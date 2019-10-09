# **Socio del Negocio Empleado**

## **Definición de Socio de Negocio Empleado**

Un socio del negocio empleado es aquella persona que presta sus servicios como trabajador en una determinada empresa u organización, a continuación se define el proceso para la creación de socio del negocio empleado en ADempiere.

### **Proceso de Registro del Socio del Negocio**

1. En el menú de ADempiere, ubique y seleccione la carpeta "**Relación con Socio del Negocio**", luego seleccione la carpeta "**Reglas de Socios del Negocio**" y finalmente seleccione la ventana "**Socio del Negocio**". 

    ![Menú de ADempiere](../resources/menusocio.png "Menú de ADempiere")

#### **Ventana Socio del Negocio**

En esta ventana se registran los datos principales que la empresa requiere del socio del negocio empleado. 

!!! note "Nota"

    Cada uno de los campos con el símbolo (*) son obligatorios para el registro.

1. A continuación visualizará la ventana "**Socio del Negocio**", dónde debe seleccionar el icono de "**Registro Nuevo**" que se encuentra ubicado en la barra de herramientas de ADempiere.

    ![ADempiere](../resources/ventana.png "Ventana de Registro de Socio del Negocio")

1. Proceda al llenado de los campos necesarios que a continuación se detallan.
    
    1. Seleccione en el campo "**Organización**", la organización para la cual se esta registrando el socio del negocio empleado.

        ![ADempiere](../resources/organizacion.png "Ventana de Registro de Socio del Negocio")

        !!! warning "**Importante**"

            Para que el socio de negocio este disponible para todas las organizaciones, el mismo deberá estar registrado con la organización en (*) de lo contrario el socio del negocio solo estará disponible para una sola organización. 
    
    1. Introduzca el código de identificación, cédula o rif del socio del negocio en el campo "**Código**", el valor introducido en este campo automáticamente se reflejará en el campo "**Número Identificación**".
        
        ![ADempiere](../resources/codigo.png "Ventana de Registro de Socio del Negocio")
    
        !!! warning "**Importante**"

            Se recomienda que al ingresar el valor al campo "**Código**" se ingrese principalmente el prefijo que le corresponde según el tipo de registro que tenga el socio del negocio (jurídico, natural, entre otros).

    1. Introduzca el nombre del socio del negocio empleado en el campo "**Nombre**".

        ![ADempiere](../resources/nombre.png "Ventana de Registro de Socio del Negocio")

    1. Seleccione el grupo de socio del negocio al que pertenezca el socio del negocio empleado que esta registrando, para este ejemplo el grupo utilizado es "**Empleados**".

        ![ADempiere](../resources/grupo.png "Ventana de Registro de Socio del Negocio")

    1. Seleccione el tipo de persona que le corresponde al socio del negocio en el campo "**Tipo de Persona**".

        ![ADempiere](../resources/tipoper.png "Campo Tipo de Persona")

    1. Seleccione el icono "**Guardar Cambios**" ubicado en la barra de herramientas para guardar los datos ingresados.

        ![ADempiere](../resources/guardar.png "Icono Guardar Cambios")

!!! warning "**Importante**"

    Recuerde guardar el registro de los campos cada vez que se vaya a posicionar en una pestaña de la ventana socio del negocio. 

##### **Pestaña Empleado**

Esta pestaña le indica a ADempiere si el socio del negocio que se esta registrando es un empleado. 

1. Seleccione la pestaña "**Empleado**" que se encuentra del lado izquierdo de la ventana socio del negocio. 

    ![ADempiere](../resources/pestempleado.png "Ventana de Registro de Socio del Negocio")

1. A continuación visualizará la siguiente imagen, dónde debe tildar el checklist "**Empleado**". 

    ![ADempiere](../resources/checklist.png "Ventana de Registro de Socio del Negocio")

!!! warning "**Importante**"

    De no ser tildado el checklist "**Empleado**", ADempiere no tomará el socio de negocio como empleado. 

##### **Pestaña Cuenta Bancaria**

En esta pestaña se registran los datos bancarios del socio del negocio empleado, con el checklist "**Activo**" se pueden registrar los datos de la tarjeta de crédito del socio del negocio. Así mismo, con el checklist "**ACH**" se pueden registrar los datos de la cuenta bancaria del socio del negocio.

1. Seleccione la pestaña "**Cuenta Bancaria**" que se encuentra ubicada del lado izquierdo de la ventana socio del negocio. Por defecto se encuentra tildado el checklist "**Activo**".

    ![ADempiere](../resources/cuenta.png "Ventana de Registro de Socio del Negocio")

###### **Checklist Activo**

1. Seleccione en el campo "**Tarjeta de Crédito**", el tipo de tarjeta de crédito que posee el socio del negocio empleado que esta registrando.

    ![ADempiere](../resources/tarjetacredito.png "Ventana de Registro de Socio del Negocio")

1. Introduzca en el campo "**Número**", el número de tarjeta de crédito del socio del negocio empleado que esta registrando.

    ![ADempiere](../resources/numtarjeta.png "Ventana de Registro de Socio del Negocio")

1. Introduzca en el campo "**Código Verificación**", el código de verificación de la tarjeta de crédito del socio del negocio empleado que esta registrando, este código son los últimos tres números del reverso de la tarjeta.

    ![ADempiere](../resources/verificacion.png "Ventana de Registro de Socio del Negocio")

1. Introduzca en el campo "**Mes de Expiración**", el mes de expiración de la tarjeta de crédito del socio del negocio empleado que esta registrando.

    ![ADempiere](../resources/mes.png "Ventana de Registro de Socio del Negocio")

1. Introduzca el año de expiración de la tarjeta de crédito del socio del negocio empleado que esta registrando en el campo "**Año de Expiración**".

    ![ADempiere](../resources/anoexp.png "Ventana de Registro de Socio del Negocio")

1. Introduzca el nombre de referencia en el campo "**Nombre**", en este campo va el nombre del titular de la tarjeta de crédito o de la cuenta bancaria que esta registrando.

    ![ADempiere](../resources/nomcuenta.png "Ventana de Registro de Socio del Negocio")

!!! warning "**Importante**"

    Este proceso se realiza con la finalidad de registrar la tarjeta de crédito del socio del negocio. 

###### **Checklist ACH**

1. Para registros de cuentas bancarias, tilde el checklist "**ACH**", a continuación se reflejarán los campos para el registro de la cuenta bancaria del socio del negocio.

    ![ADempiere](../resources/ach.png "Ventana de Registro de Socio del Negocio")

1. En el campo "**Banco**" seleccione el banco a registrar con ayuda del ícono identificador (adjunto imagen).

    ![ADempiere](../resources/banco.png "Ventana de Registro de Socio del Negocio")

1. A continuación visualizará la siguiente ventana con los diferentes bancos, dónde debe seleccionar el banco que posee el socio del negocio empleado y la opción "**OK**" para cargar los datos al formulario.

    ![ADempiere](../resources/selecbanco.png "Ventana de Registro de Socio del Negocio")

1. Seleccione el tipo de cuenta correspondiente a la cuenta del socio del negocio empleado en el campo "**Tipo de Cuenta Bancaria**".

    ![ADempiere](../resources/tipocuenta.png "Ventana de Registro de Socio del Negocio")

1. Introduzca en el campo "**No. De Cuenta**", el número de cuenta del socio del negocio empleado que esta registrando.

    ![ADempiere](../resources/numcuenta.png "Ventana de Registro de Socio del Negocio")

!!! warning "**Importante**"

    Este proceso se realiza con la finalidad de registrar la cuenta del socio del negocio. 

##### **Pestaña Localización**

La localización de un socio del negocio es muy importante por diferentes motivos, ya que si el socio del negocio es un empleado de la empresa se deben registrar con exactitud los datos de la dirección del socio del negocio.

1. Seleccione la pestaña "**Localización**" que se encuentra ubicada del lado izquierdo de la ventana socio del negocio.

    ![ADempiere](../resources/localizacion.png "Ventana de Registro de Socio del Negocio")

1. Seleccione en el campo "**País**", el país donde se encuentra domiciliado el socio del negocio que esta registrando.

    ![ADempiere](../resources/pais.png "Campo País")

1. Seleccione en el campo "**Estado**", el estado donde se encuentra domiciliado el socio del negocio que esta registrando.

    ![ADempiere](../resources/estado.png "Campo Estado")

1. Seleccione en el campo "**Ciudad**", la ciudad donde se encuentra domiciliado el socio del negocio que esta registrando.

    ![ADempiere](../resources/ciudad.png "Campo Ciudad")

1. Introduzca la dirección detallada del socio del negocio empleado en el campo "**Dirección 1**" y seleccione la opción "**OK**".

    ![ADempiere](../resources/direccion.png "Ventana de Registro de Socio del Negocio")

!!! warning "**Importante**"
                
    Recuerde guardar el registro de los campos cada vez que se vaya a posicionar en una pestaña de la ventana socio del negocio.

##### **Pestaña Contacto**

En esta pestaña se registran todos los datos de contacto que se tengan del socio del negocio empleado.

1. Seleccione la pestaña "**Contacto**" que se encuentra ubicada del lado izquierdo de la ventana socio del negocio, para proceder a llenar los campos necesarios.

    ![ADempiere](../resources/contacto.png "Ventana de Registro de Socio del Negocio")

1. Introduzca en el campo "**Nombre**", el nombre del contacto directo establecido por el socio del negocio empleado para casos de emergencia.

    ![ADempiere](../resources/nomcontacto.png "Ventana de Registro de Socio del Negocio")

1. Introduzca en el campo "**Email**", el email del contacto directo establecido por el socio del negocio empleado para casos de emergencia.

    ![ADempiere](../resources/email.png "Ventana de Registro de Socio del Negocio")

1. Introduzca en el campo "**Teléfono**", el teléfono del contacto directo establecido por el socio del negocio empleado para casos de emergencia.

    ![ADempiere](../resources/tlf.png "Ventana de Registro de Socio del Negocio")

!!! note "**NOTA:**"
        
    Este procedimiento realizado aplica solo para los **Socios del Negocio** que cumplan el rol de **Empleado**.
