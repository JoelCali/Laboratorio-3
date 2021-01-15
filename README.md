# Laboratorio-3

* Objetivos

  1.- Objetivo General
    - Estudiar el teorema de superposición en circuitos mixtos apoyandose de los simuladores para comprobar que se cumple el teorema con los resultados analíticos.

  1.1.- Objetivos Específicos
    - Identificar la dirección en la que circula la corriente en el circuito.
    - Analizar el circuito y su comportamiento al momento de hacer "cero" a las fuentes de voltaje.
    - Comparar los datos en el simulador con resultados calculados y realizar el cálculo del error.
    
  2.- Marco Teórico
  
     ![image](https://user-images.githubusercontent.com/76134214/104668449-1746ae00-56a6-11eb-8de9-bef74029114e.png)
      
     ![image](https://user-images.githubusercontent.com/76134214/104668455-1a419e80-56a6-11eb-8ddc-4b3f0972ba11.png)

  
  3.- Diagramas
    
    - Circuito General.
    
    ![image](https://user-images.githubusercontent.com/76132461/104648944-ee142680-5681-11eb-9ae3-aa223f3561aa.png)
    
    - Voltaje en VA:
    
    ![image](https://user-images.githubusercontent.com/76132461/104648975-f79d8e80-5681-11eb-9271-e80699e91f64.png)
    
    - Corriente en IX:
   
   ![image](https://user-images.githubusercontent.com/76132461/104650930-f0c44b00-5684-11eb-8728-95bcda22bb20.png) 
    
    - Voltaje en VA cuando Fuente 12 V= 0:
    
    ![image](https://user-images.githubusercontent.com/76132461/104649027-0a17c800-5682-11eb-9ba8-1d390570b103.png)
    
    - Corriente en IX cuando Fuente 12 V=0:
    
    ![image](https://user-images.githubusercontent.com/76132461/104650987-06d20b80-5685-11eb-8d13-0ad0adfc8f49.png)
    
    - Voltaje en VA cuando Fuente de 20 V=0:
    
    ![image](https://user-images.githubusercontent.com/76132461/104649058-14d25d00-5682-11eb-9528-bf97bbbe59d2.png)
    
    - Corriente en IX cuando Fuente de 20 V=0:
    
    ![image](https://user-images.githubusercontent.com/76132461/104651035-18b3ae80-5685-11eb-8b15-e6faac03c23b.png)
    
    4.- Lista de componentes
    
    ![image](https://user-images.githubusercontent.com/76132461/104652024-7c8aa700-5686-11eb-9f38-c312bb53b8d4.png)

    5.- Explicación
    
    5.1.- Procedimiento
    
    1. Se ingresa a la plataforma Tinkercad, se crea una cuenta, a continuación en el apartado de circuitos seleccionar nuevo circuito.
    
    2. Se seleccionan los materiales que vamos a utilizar, una placa de pruebas, 4 resistencias, multimetros digitales y dos fuente de voltaje.
    
    3. En la primera fuente de voltaje, se la configura con 20 V, mientras que la segunda fuente de voltaje tendrá un valor de 12 V.
    
    4. Se procede a configurar cada resistencia con el valor ya establecido en el circuito.

    5. La fuente de voltaje de 20 V, el lado positivo ira hacia un extremo de la resistecia de 1K ohms.
    
    6. Del otro extremo de la resistencia de 1K ohms se conectará a un extremo de la resistencia de 820 ohms.
    
    7. Del nodo formado por estos dos elementos se conectará una resistencia de 2.2k ohms.
    
    8. Del lado negativo de la fuente de 20 V, se conectará al extremo de la resistencia de 2.2k ohms.
    
    9. Del extremo de la resistencia de 820 ohm, se conectará una resistencia de 470 ohm.
    
    10. Del extremo de la resistencia de 470 ohm, se conectará con la resistencia de 2.2k ohm.
    
    11. La fuente de voltaje de 12 V, se conectará en paralelo a la resistencia de 470 ohm.
    
    5.2.- Con las dos fuentes conectadas, mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.
    
   Para medir el voltaje en VA se conectará en paralelo a la resistencia de 820 ohmios. 
   Para medir la intensidad en IX se debe conectar en serie desde el positivo de la fuente de 12 V y el otro lado del amperímetro a la resistencia de 470 ohmios.
    
    5.3.- Haga “cero” la fuente de voltaje de 12 V (V2) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se
proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

   En este punto se debe dejar las conexiones del amperimetro y el voltímetro, salvo que la fuente que tenemos del lado derecho que es de 12 V, se vuelve 0 y se anota los valores en la tabla.
   
   5.4.- Haga “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se
proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

  Para este literal se debe dejar las conexiones del amperimetro y el voltímetro, salvo que la fuente que tenemos del lado izquierdo que es de 20 V, se vuelve 0 y se anota los valores en la tabla.
  
  Tabla 4.1. Medición de voltaje aplicando superposición.
  
  ![image](https://user-images.githubusercontent.com/76132461/104659536-ce392e80-5692-11eb-8e7f-160695ea1214.png)
  
  Tabla 4.2. Medición de corriente aplicando superposición.
  
  ![image](https://user-images.githubusercontent.com/76132461/104659594-e5781c00-5692-11eb-8e32-585f88a883ea.png)
  
  5.5.- Verifique el cumplimiento del Teorema de Superposición y compare los resultados obtenidos prácticamente con los obtenidos analíticamente. Realice sus conclusiones.
  
  Despues de realizar el teorema de superposición tanto calculado como medido en tinkercad, se llega a una conclusión que se cumple el teorema, pero se tiene un mínimo error porcentual que se debe a los decimales que no se toman en cuenta, en el caso de la simulación, el programa redondea a dos decimales y cuando realizamos los valores calculados, tomamos más decimales pero aun asi se pierden muchos de estos, ademas es un número muy cercano y tienen relación entre ellos. El error porcentual que se tiene en cada caso es el siguiente.
  
  ![image](https://user-images.githubusercontent.com/76132461/104661563-c7141f80-5696-11eb-8b86-fbb62480e24d.png)

  6.- Conclusiones
  
  -Concluimos que cuando se aplica el método de superposición es muy importante la dirección y sentido en el que fluye la corriente, debido a que así se puede cuando entra en un nodo o no y el signo (positivo o negativo) al momento de realizar las mediciones u operaciones.
  
-Analizando el comportamiento del circuito cuando una de sus fuentes se vuelve “cero”, observamos que este se divide en dos valores distintos los cuales serán claves al realizar la operación de superponerlos ya que otorgaron un resultado igual al de las dos fuentes encendidas.

-Realizando los cálculos pertinentes de ambos circuitos concluimos que los valores obtenidos solo tienen un margen de error menor a 1.15% referente a voltajes y un valor menor de 0.11% referente a corrientes, el cual nos indica que tanto cálculos como simulación obtuvieron valores no muy alejados.

  
  
  7.- Bibliografía

  Floyd, T.L. (2007). Principios de circuitos eléctricos (Octava ed.)
  
  






    
    
    
    
    
    
    
    
