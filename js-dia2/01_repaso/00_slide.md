!SLIDE bullets incremental transition=scrollUp
# JavaScript #
* Es un lenguaje funcional
* __No__ es Java
* Herencia basada en prototipos
* Los _objetos_ son contenedores
* Las funciones son _objetos_

!SLIDE transition=scrollUp

# Objetos #

    @@@ javaScript
    var Persona = {};

!SLIDE transition=scrollUp

    @@@ javaScript
    var Persona = {
      nombre: '',
    
      apellido: ''
    };


!SLIDE transition=scrollUp

    @@@ javaScript
    var Persona = {
      nombre: '',
    
      apellido: '',

      saludo: function() {
        console.log('hola: ' + nombre + ' ' + 
                    apellido);
      }
    };


!SLIDE transition=scrollUp

    @@@ javaScript
    var OB = {
      Application: {
        version: '3.0',
        label: 'RC3'
      },
      Modules: []
    };

