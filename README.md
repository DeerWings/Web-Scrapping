# web-scrapping
Web scrapping con python y pandas

 EJECUCION: 
  1.se abre una terminal dentro de la carpeta web-scrapping.
  2.se ejecuta el archivo pipeline.py escribiendo: python pipeline.py 
  3.dar ENTER
  
 ACLARACIONES: 
  1.Si hay algun error de librerias, hay que descargarlas: como pandas, requests, etc. Utilizando la sentencia (dentro de la terminal): pip install "NOMBRE_LIBRERIA".
  2. PARA MEJOR FUNCIONAMIENTO UTILIZAR ANACONDA CON PYTHON 3. DESCARGA: https://www.anaconda.com/products/distribution
  3. PARA QUE NO HAYA ERRORES SE DEBE UTILZAR LINUX O macOS
  4. Esta solucion funciona solo para la pagina de noticias TN. Si se requiere algun cambio se tiene que hacer: 
      a. Dentro de la carpera "extract" cambiar si se necesita, los parametros en el archivo "config.yaml"
      b. Dentro del archivo "pipeline.py" en las primeras lineas, "news_sites_uids = ['tn']" y agregar: news_sites_uids = ['tn', "ACA PONER EL NUEVO SITIO"].
 
