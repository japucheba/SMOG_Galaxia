Instrucciones para navegación:

En el folder "region_files" se encuentran todos los documentos utilizados para el código para cada región.

En el folder "Galaxias" se encuentran las fotos de las galaxias encontradas para cada región, divididas en sus respectivos filtros. Las coordenadas en los nombres de las fotos son las galácticas.

En el folder principal se encuentran los códigos utilizados. Aquí un breve resumen de cada uno:

    Oficial.ipynb : Código utilizado para extraer las fotos de las galaxias y guardarlas en sus respectivos folders.

    Find Duplicates.ipynb : Encuentra coordenadas duplicadas en cada region file, ya sea en físicas o galácticas.

    Coordenadas_Duplicadas.txt : Las coordenadas galacticas duplicadas de cada region. Esto se encontro para que se supiera si el numero de imagenes creadas
    corresponde al numero de coordenadas galacticas. Esta lista de coordenadas se obtuvo del Drive titulado: Materiales SMOG => Regiones

    Create_reg_file.ipynb : Crea archivos tipo .reg (para ser utilizados en DS9) de las coordenadas dadas por los archivos .reg en el folder region_files

    Parametros_Imagenes.txt : Los parametros de cada filtro para crear las imagenes RGB.