
# ErrorN: Error Notificator using Bootstrap
ErrorN (copyright) 2023 by Jose Inestroza is licensed under  
Attribution-NonCommercial-ShareAlike 4.0 International 

**Simplifies the implementation of Bootstrap Toast Messages only using Javascript**.
This software requires the CSS and JS of bootstrap from getbootstrap.com

Please view the main **features and installation** at https://joseinestroza.github.io/ErrorN/

```
You may use this software in your business app, but 
ErrorN cannot be primarily intended for commercial advantage 
or monetary compensation as part of you software. You cannot
sell ErrorN or a modified version of ErrorN.
```

## Bootstrap version
Error Notificator using Bootstrap 5.3.1.

## Requirements to your code

```
    <link rel="stylesheet" href="bootstrap.min.css">
    <script src="bootstrap.bundle.min.js"></script>
    <script src="ErrorN.min.js"></script>
```

## Usage:

### Position:
```
     ErrorN.setPositionTopRight(); //Default
     ErrorN.setPositionTopLeft();
     ErrorN.setPositionBottomRight();
     ErrorN.setPositionBottomLeft();
     ErrorN.setPositionCenter();
```

### Simple:
```
     ErrorN.error(message,duration=9000);
     ErrorN.warning(message,duration=9000);
     ErrorN.success(message,duration=9000);
     ErrorN.info(message,duration=9000);
     ErrorN.primary(message,duration=9000);
     ErrorN.indigo(message,duration=9000);
```

### Complex:
```
     ErrorN.errorComplex(message,title,smallText,duration=9000);
     ErrorN.warningComplex(message,title,smallText,duration=9000);
     ErrorN.successComplex(message,title,smallText,duration=9000);
     ErrorN.infoComplex(message,title,smallText,duration=9000);
     ErrorN.primaryComplex(message,title,smallText,duration=9000);
     ErrorN.indigoComplex(message,title,smallText,duration=9000);
```

## Author
- **Author:** @joseinestroza, https://github.com/joseinestroza
- **Date:** 2023/12/08
- **Since:** 2023/12/07
- **Version:** 0.1.1.2332
- **License:** CC BY-NC-SA 4.0, Attribution-NonCommercial-ShareAlike 4.0 International
- **At:** Tegucigalpa, Honduras, C.A.