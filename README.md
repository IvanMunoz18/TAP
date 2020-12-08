# Desarrollo de aplicaciones donde utilice el envío, recepción y visualización de datos

**Problemática a resolver**
Usted ha sido contratado para desarrollar un Software para gestionar el ingreso de personas a un edificio comercial. Dicho Software estará en capacidad de realizar las acciones básicas para la manipulación de la base de datos (CRUD) de cada persona que ingrese al establecimiento se deberá recolectar: Tipo Documento. Identificación. Nombres. Fecha y hora de Ingreso. A quien Visita. Motivo.

**Características solicitadas del programa**
a) Conectarse al servidor de la base de datos. (Base de datos en red, remota). Crear una interfaz para poder cambiar los valores de conexión a la base de datos. Estos valores deben de guardarse en un archivo de configuración. utilizar un Administrador de esquemas BoxLayout para armar esta interfaz.
b) Registrar en la base de datos todas las personas que ingresen al establecimiento, utilizar un Administrador de esquemas GridBagLayout para armar esta interfaz.
c) Mostrar el listado de todas las personas que ingresaron (Usar un JTable, debe de permitir realizar scroll en caso de que la lista sobrepase el área visible): Posibilidad de actualizar los datos en caso de errores al momento del registro. Posibilidad de eliminar registros de personas registradas.
e) Utilice una interfaz de múltiples documentos (MDI): una ventana principal (a la que se le conoce comúnmente como la ventana padre) que contiene otras ventanas (a las que se les conoce comúnmente como ventanas hijas), para administrar varios documentos abiertos que se procesan en paralelo. Utilizar un menú para abrir las diferentes interfaces.

**Pre-requisitos**
Este programa usa librerias propias de Java invocadas en cada clase correspondiente, 
GitHub para subir nuestras clases, nuestro .jar y un IDE Netbeans 8.2 gratuito que se puede descargar desde oracle en google.
Tambien tenemos que tener instalado el driver mysql-connector-java-5.1.49 para conectar el programa con la base de datos.
Buscar la mysql free para ver la base de datos con su correcto funcionamiento.
Librerías como: 
import java.sql.Connection;
import java.sql.DriverManager;

**COMO EJECUTAR EL PROYECTO**

Subi un archivo el cual es una extension .jar el cual se descarga y abre automaticamente la clase donde esta el main y por ende
echa a jalar el programa sin necesidad de descargar todo el programa y pasarlo a un IDE.


**Agradecimientos**
Agradezco a mi compañero de carrera Alexis Porras por el apoyo a resolver mis dudas y al profesor Carlos Levy por la paciencia 
y el tiempo y atencion que nos da en clase.

Bibliografía
https://anabelisa.co/readme/

http://javapiola.blogspot.com/2009/11/tutorial-jtable.html

http://chuwiki.chuidiang.org/index.php?title=GridLayout

http://panamahitek.com/comunicar-java-con-base-de-datos-mysql/

Ejecución:
https://flipgrid.com/7f9f5914

**DATOS PARA EJECUTARLO EN FREE MYSQL**
Server: sql9.freemysqlhosting.net
Name: sql9380849
Username: sql9380849
Password: p7A4dIjzT7
Port number: 3306

