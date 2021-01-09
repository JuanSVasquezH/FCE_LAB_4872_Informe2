# FCE_LAB_4872_Informe2
Informe 2 "Análisis de Mallas"
                                                      UNIVERSIDAD DE LAS FUERZAS ARMADAS-ESPE

                                                   DEPARTAMENTO DE ELÉCTRICA Y ELECTRÓNICA

                                             CARRERA DE INGENIERÍA ELECTRÓNICA Y AUTOMATIZACIÓN

                                    PERIODO        	                :       Noviembre 2020 – Abril 2021

                                    ASIGNATURA     	                :       Fundamentos de Circuitos Eléctricos 

                                    TEMA	                        : 	Informe de laboratorios
 
                                    NOMBRES       	          	:       Freddy Stalin Cárdenas Carrera 
					                                   Juan Sebastián Vásquez Hurtado 

                                    NIVEL-PARALELO                      :       Segundo

                                    DOCENTE       	 	        :       Ing. Darwin Alulema MSc.

                                    FECHA DE ENTREGA                    :       12/01/2021

                                    NRC 				:	4872
 
                                                             SANGOLQUI - ECUADOR

                                                                       2020



1.	Tema: Análisis de mallas

2.	Objetivos

	1.1 Objetivo General

	●	Analizar y comprender el comportamiento de la intensidad corriente eléctrica 	suministrada por dos fuentes dentro de un circuito mediante el análisis de mallas 	derivado de las leyes de Kirchoff.

	1.2 Objetivos Específicos

	●	Comparar los resultados analíticos, los resultados experimentales y resultados 	simulados mediante cálculos medidos, calculados y simulados.

	●	Demostrar que los instrumentos de medición básicos para el análisis de 	circuitos, algunos métodos de solución para hallar valores teóricos de tensión y 	corriente.
	
	●	Identificar la forma correcta de medición de corriente y voltaje con el multímetro   para circuitos resistivos, y más específicamente de los circuitos analizaos por mallas. 
      	

3.	Marco Teórico 

![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe2/blob/main/ImagenesInforme/T1.png)

![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe2/blob/main/ImagenesInforme/T2.png)


4.	Diagramas 
 
![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe2/blob/main/ImagenesInforme/Circuito.jpeg)
 
Figura 2.1 Circuito para el análisis de mallas. 

●	El presente diagrama se lo realizó en las prácticas a partir de previos conocimientos sobre las leyes de Kirchhoff en cuanto a voltajes y corrientes, el diagrama está compuesto de varios componentes circuitillos de los cuales tenemos un circuito con positivo y negativo la cual representa una fuente de corriente en D.C, la cual suministra la energía al circuito, también existen líneas en forma de sic sac que se le conoce como resistencias la cual impiden el paso de la corriente. 

5.	Lista De Componentes 

![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe2/blob/main/ImagenesInforme/Material.jpeg)

  5.1 	Explicación
  
  
●	Para le elaboración del análisis de mallas debemos tomar en cuenta el número de mallas presentes en el circuito, luego veremos el sentido de las corrientes el cual se va a tomar, esto es importante ya que este nos dará el signo en el valor final de cada corriente en las diferentes mallas que analizamos.


EL número de corrientes que se hallara es igual al número de mallas que se tenga en el circuito, en este caso analizamos 3 mallas por ende existe 3 corrientes una circulando en cada malla.


Cabe mencionar que para el análisis es importante identificar que elemento en el circuito está compartiendo dos o más corrientes, ya que estas se restaran para poder realizar una correcta formulación de las ecuaciones. 


Ya identificado los resistores R4 y R5 que son los que comparten corrientes tanto de I2 e I1 para el resistor R4 y I2 e I3 para R5, procedemos a armar las ecuaciones. Si se tiene una fuente de voltaje solo se copia el valor que se encuentre, siempre respetando el orden de los signos ya que si no lo hacemos nos dará un valor erróneo y a su vez inservible para el análisis futuro que se realizara con la simulación del Simulador a implementar “MULTISIM”.

   
   ●	Imágenes representativas de análisis de mallas en un circuito.
   
                    
   https://hetpro-store.com/TUTORIALES/wp-content/uploads/2020/04/Circuito-cerrado.png
		    
   https://hetpro-store.com/TUTORIALES/wp-content/uploads/2020/04/Mallas_0.png


6.	Procedimiento 

             
      1. Abrir el simulador “Multisim”, Para la implementación del Circuito.
	
	
      ![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe2/blob/main/ImagenesInforme/P1.png)
      
      
 
      2. Crear un nuevo proyecto, en la barra de herramientas seleccionar los elementos para armar el circuito.


      ![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe2/blob/main/ImagenesInforme/Circuito1.png)



      3. Procedemos a hallar el valor de la corriente que pasa en cada malla, para ello procedemos a conectar las puntas al inicio del resistor R1(Malla1), R2 (Malla 2), R3 (Malla 3).


      ![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe2/blob/main/ImagenesInforme/Corrientes.png)
      
      
      ![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe2/blob/main/ImagenesInforme/VoltajeCorriente.png)



      4.  Una vez conectados las puntas en cada malla, presionamos el botón verde (RUN)


      ![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe2/blob/main/ImagenesInforme/123i.jpg)



      5. Recolectamos los datos en una tabla donde nos ayudara a comparar con el análisis tanto de los valores medidos (Simulados), como los valores calculados (Teóricos).
      
                
      ![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe2/blob/main/ImagenesInforme/Simulador.jpg)



      6. Una vez analizados los datos obtenidos, calculamos el margen de erros que existe en la presente practica.
	     

      ![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe2/blob/main/ImagenesInforme/Datos.png)	     
      
      
      
	     
7.	Descripción De Prerrequisitos Y Configuración 


8.	Tabulación de Datos

      ![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe2/blob/main/ImagenesInforme/Datos.png)
      
                         1. Tabla 2.1. Resultados obtenidos para el circuito de la figura 2.1.       

9.	Cálculos 

      
	●	Los Calculos se encuentran en carpeta Anexos.
	
	https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe2/blob/main/Anexos/Desarrollo_Circuito_Analisis_Mallas.pdf

10.	Aportaciones 

	●	En esta práctica se hicieron medidas de tensionen los componentes de un 	circuito para determinar su desfase relativo y comprobar la aplicabilidad e las 	herramientas teóricas brindadas en el curso. Adicionalmente se comprobó el teorema 	de superposición de forma experimental

	●	Se comprueba mediante las fórmulas ya conocidas V=IR (Ley de Ohm), 	que 	ambas leyes tanto de corriente y voltajes en un circuito cerrado son cero. Es decir 	que el uso adecuado de las fórmulas y el planteamiento adecuado de las corrientes al 	usar el método de mallas nos facilita mejor la comprensión del circuito y las leyes en sí. 	Esto ocurre igual en la sumatoria de los voltajes del circuito.  

	●	Aplicando la teoría de análisis de mallas, damos cuenta de que está bien   	fundamentada y puede ser aplicable demo do general a cada circuito plano que se 	pueda presentar. 

11.	Conclusiones 

	●	Al haber armado los circuitos tanto físicamente como en el simulador donde se 	obtienen las corrientes con valores teóricos, los prácticos y los simulados, dando a 	conocer el funcionamiento del método de análisis de malla que sólo es aplicable a 	circuitos planos, es decir, donde no exista cruce de ramas.

	●	Observamos que no hay un porcentaje de error significativo entre un   	fundamento simulado y teórico, respecto a uno experimental,   puesto que los   	elementos usados durante la práctica no interfieren bastante en la toma de valores.

	●	Debemos tomar en cuenta el sentido ya sea de corriente o voltaje, en 	el cual 	vamos a calcular los distintos datos ya que estos no servirán para comprobar el 	método de análisis de malla que se están estudiando en esta presente 	práctica.  


12.	Bibliografía 


	●	https://dademuch.com/ (2019), Método de Mallas – Análisis de Circuitos, recuperado de : 	https://dademuch.com/2019/11/05/metodo-de-mallas-analisis-de-circuitos/ 

	●	 Nilsson, James W., & Riedel, Susan A. (2002). Introductory Circuits for Electrical           and Computer Engineering. New Jersey: Prentice Hall.  https://es.wikipedia.org/wiki/An%C3%A1lisis_de_mallas 

	●	SN (2018). Ley de Kirchhoff: Análisis de mallas, recuperado de: 	https://hetpro-store.com/TUTORIALES/ley-de-kirchhoff-analisis-de-mallas/ 

	●	Wikipedia.com (2020), Análisis de Mallas, recuperado de: 	https://analisisdecircuitos1.wordpress.com/parte-1-circuitos-resistivos-cap-21-a-30-en-construccion/capitulo-21-analisis-de-mallas/.


13.	Anexo
        
	
	![](https://github.com/JuanSVasquezH/FCE_LAB_4872_Informe2/blob/main/ImagenesInforme/NodosVSMallas.jpg)
	
	Diferencias Entre Analisis de Mallas y Nodos

