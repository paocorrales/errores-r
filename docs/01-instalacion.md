# Problemas de instalación

## Instalación de paquetes

**Problema 1:**

Al usar `install.packages()` R devuelve algo como:

```
Warning in install.packages :
  package ‘gplot2’ is not available for this version of R
```

**Causa:** R no encuentra el paquete para descargar e instalar

**Posible solución:** 

* Revisá si escribiste el nombre del paquete correctamente. En este ejemplo, escribí "gplot2" en vez de "ggplot2". 
* Asegurate de que tu computadora esté conectada a internet.

**Problema 2:**

El paquete se instala bien pero al usar `library()` me deuvelve algo como

```
Error in library(gplot2) : there is no package called ‘gplot2’
```

**Causa:** R no encuentra el paquete instalado en tu computadora. 

**Posible solución:** Revisá si escribiste el nombre del paquete correctamente. En este ejemplo, acá también escribí "gplot2" en vez de "ggplot2".
