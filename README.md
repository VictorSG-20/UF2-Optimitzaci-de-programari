# UF2 Optimitzaci de programari
Las pruebas tiene el objectivos de comprobar si el software hace lo que tiene que hacer y no otra cosa.
Existen diferentes tios de frameworcks para llevar a cabo las pruebas. Un frameworcks es un conjunto de
herramientas y librerias comunes. Permite que los desarrolladores trabajen en conjuto y unifiquen su trabajo
sin problemas.
## Pruebas
### Forma de las Pruebas 
Hay dos tipos de pruebas, las dinámicas y las estáticas.  
**Pruebas dinámicas:** Son pruebas que requieren ejecutar el software, para ver como funciona la aplicacion.  
**Pruebas estáticas:** Son pruebas que se realizan sin ejecutar el código, en ellas lo que se examina es el   
codigo fuente de la aplicacion sin tener en cuenta su funcionalidad.

### Estrategias de prueba
**Caja negra:** Pruebas de funcionalidad en la que le damos unos parametros al software y comprobamos que el  
resultado este acorde a los parametros introducidos, por lo tanto no nos interesa tanto el codigo, si no el   
funcionamiento del programa.  
**Caja blaca:** En este caso nos fijamos mas en el códio fuente y la manera en que este se ejecuta. Son pruebas  
dode comprobamos la estructura del programa sin importar la finalidad de este.  
<img src="http://jamj2000.github.io/entornosdesarrollo/3/assets/caja_blanca-caja_negra.png" width="250" height="300" />  
En las pruebas de caja negra seguimos la siguiente estrategia:
- Se estudia desde fuera
- Se trabaja sobrte la interfaz
- No mira la estructura del código
- Se dan parametrtos y se comprueba resultados
- Técnicas: participacio de equivalencia y Valores limite    

En las pruebas de caja blanca seguimos la siguiente estrategia:    
- Se estudia el codigo fuente y su ejecucion
- Se los flujos de ejecucion en cada unidad
- También pueden comprobarse los flujos entre unidades 
- E incluso entre subsistemas, durante las pruebas de sistema
- Técnicas: Cobertura de código y Prueba de bucles  

### Tipos de pruebas
**Funcionales** Comprueba que se cumplan los requisitos.
- Pruebas unitarias (o de unidad)
- Pruebas de regresión
- Pruebas de integración
- Pruebas de humo (smoke test)
- Pruebas del sistema
- Pruebas alfa y beta
- Pruebas de aceptación (validación por parte del cliente) 

**No funcionales** Comprueban aspectos como el rendimiento y la seguridad   
- Pruebas de usabilidad
- Pruebas de rendimiento
- Pruebas de stress
- Pruebas de seguridad
- Pruebas de compatibilidad
- Pruebas de portabilidad  

### Mecanismos de pruebas
**Manual** Mediante pruebas realizadas por personal de la empresa o externo.
**Automático** Mediante software que ejecuta código de forma automatizada y compara los resultados obtenidos   
y los resultados esperados.




 
