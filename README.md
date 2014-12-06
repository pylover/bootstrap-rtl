bootstrap-rtl
=============

A branch of bootsrap which supports RTL rendering via a `sass` variable


To build:

  * First your have to install MaryJane:
  

        $ pip install maryjane
    
    
  (Of course, if you are a grunt lover, please fork, provide a grunt file and request a pull! )

  * run maryjane to generates the output files:
  

        $ maryjane
        

  * Sample output:
  

        Building Bootstrap css:
         ./styles/bootstrap-ltr.sass > ./build/css/bootstrap.ltr.css
         ./styles/bootstrap-rtl.sass > ./build/css/bootstrap.rtl.css
         ./build/css/bootstrap.ltr.css > ./build/css/bootstrap.ltr.min.css
         ./build/css/bootstrap.rtl.css > ./build/css/bootstrap.rtl.min.css
        done.
  
  
        Building javascripts:
         ./javascripts/affix.js
          ./javascripts/alert.js
          ./javascripts/button.js
          ./javascripts/carousel.js
          ./javascripts/collapse.js
          ./javascripts/dropdown.js
          ./javascripts/tab.js
          ./javascripts/transition.js
          ./javascripts/scrollspy.js
          ./javascripts/modal.js
          ./javascripts/tooltip.js
          ./javascripts/popover.js
         Into: ./build/js/bootstrap.js
         ./build/js/bootstrap.js > ./build/js/bootstrap.min.js
        done.
