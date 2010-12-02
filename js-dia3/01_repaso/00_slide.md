!SLIDE transition=scrollUp
    @@@ javaScript
    var OB = {
      Application : {
        language : '192',
        systemVersion : '_version=2.0.0&_language=192', // global version used in all hyperlinks
        contextUrl: '/openbravo/',
        communityBrandingUrl: '',
        communityBrandingStaticUrl: '',
        butlerUtilsUrl: '',
        purpose: 'D',
        licenseType: 'C',
        versionDescription: '2.50 - Community Edition - dev'
      },
      User : {
        // (...)
      }
    
      // (...)
    }

!SLIDE transition=scrollUp
    @@@ javaScript
    isc.defineClass('OBWindow', isc.Window);

    isc.OBWindow.addProperties({
      miVariable: '',

      initWidget: function() {
        // inicializar el componente
        this.Super('initWidget', arguments);
      }
    });

