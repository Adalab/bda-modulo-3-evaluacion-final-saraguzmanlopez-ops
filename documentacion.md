## Documento "Customer Loyalty History.csv" es un documento proporcionado por nuestro cliente en formato CSV


 Características principales :
        Formato CSV

        Consta de 16737 filas , 15 columnas

        Duplicados: No me da duplicados puesto que tiene la columna Loyalty Number que es el indice o identificador unico (PK),   
                 misma columna que en el segundo documento.

        Nulos : las columnas 'Cancellation Year','Cancellation Month' dan tan solo  filas por lo que hay que observar si son      
                 nulos o categórica o falsa categórica.
                 la columna ' Salary' sólo tiene 12499 filas lo que me indica posibles nulos 

        Tipo son String, Float e Int
                Float:
                     Salary, normalmente es Float para hacer calculos matematicos
                     CLV: valor estimado de client y empresa por lo que se usa para calculos matematicos
                     'Cancellation Year','Cancellation Month', investigar si estas dos columnas no son completamente 
                INT :  
                    'Enrollment Year', 'Enrollment Month'


Características por columnas :

    COUNTRY , columna candidata a ser eliminada, ya que sólo tiene un valor Canada, por lo tanto no es relevante
          16737  filas por lo tanto sin nulos 
          un solo valor 'Canada', por lo tanto no aporta informacion relevante y es candidata a ser eliminada

    PROVINCE :
          16737  filas por lo tanto sin nulos 
          tipo String
          11 provincicias diferentes introducidas , canad tiene 10 provincias y 3 territorios, YUkon lo han metido como       
          provincia y no como territorio
          Bien escrito los nombres mayusculas y sin objetos raros

               Ontario: 32.29%
               British Columbia: 26.34%
               Quebec: 19.72%
               Alberta: 5.79%
               Manitoba: 3.93%
               New Brunswick: 3.8%
               Nova Scotia: 3.09%
               Saskatchewan: 2.44%
               Newfoundland: 1.54%
               Yukon: 0.66%
               Prince Edward Island: 0.39%


    City:
          16737  filas por lo tanto sin nulos 
          tipo String
          29 ciudades diferententes que se han introducido
          bien escrito los nombres mayusculas y sin objetos raros

    Postal Code
          tipo ship, por lo que se valora que tenga que separar los datos o fusionarlos
          Sin nulos
          tipo string 

    Gender
          sin nulos porque hay 16737 filas
          tipo string
          Cateórica ,dos categorias, Male y Fameles
               49.75% de los clientes son hombres
               50.25% de las clientas son mujeres     


     Education
          sin nulos porque hay 16737 filas
          tipo string
               Bachelor: 62.59%
               College: 25.32%
               High School or Below: 4.67%
               Doctor: 4.39%
               Master: 3.04%

     Salary
          25,32 % de valores nulos
          0,12 % de valores negativos, en esta columna es erroneo que se encuentre valores negativos 
                        
                          

Columnas que se deben valorar eliminar:
     COUNTRY ,ya que sólo tiene un valor Canada, por lo tanto no es relevante y puede ser eliminada.

Columnas a estudias los nulos 
     Saraly , con un 25,32%  de valores nulos  y un 0,12% de valores negativos



