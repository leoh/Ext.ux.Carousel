Ext.ux.Carousel
===============

Patched Ext.ux.Carousel to match ExtJS 4.1.x

    Ext.onReady(function() {
                new Ext.ux.Carousel('simple-example');

                new Ext.ux.Carousel('full-example', {
                    itemSelector : 'img',
                    interval : 5,
                    autoPlay : true,
                    showPlayButton : true,
                    pauseOnNavigate : true,
                    freezeOnHover : true,
                    transitionType : 'fade',
                    navigationOnHover : true
                });

                new Ext.ux.Carousel('html-example', {
                    itemSelector : 'div.item',
                    interval : 5,
                    autoPlay : true,
                    transitionEasing : 'easeIn'
                });
      });
