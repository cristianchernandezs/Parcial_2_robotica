
# ROBOT UR5
![2222](https://github.com/cristianchernandezs/Parcial_2_robotica/blob/main/fondo.png)

# Parcial 2 robotica industrial

## Descripción 📃
el robot seleccionado fue el "UR5" de la compañia universal robots .Es un robot colaborativo industrial ligero construido para aplicaciones de servicio medio (hasta 5 kg). Los propósitos generales del desarrollo de este robot son la versatilidad y la adaptabilidad.


## work space 🎯
![2223](https://github.com/cristianchernandezs/Parcial_2_robotica/blob/main/espacio.png)
>El espacio de trabajo del robot UR5 ocupa 850 mm desde la junta de la base.Mover la herramienta cerca
del volumen cil´ındrico debe evitarse en lo posible, porque hace que las juntas se
muevan rapido aunque la herramienta se mueva lentamente, lo que hace que el ´
robot trabaje de forma ineficiente
>>![2223](https://github.com/cristianchernandezs/Parcial_2_robotica/blob/main/Captura%20de%20pantalla%202021-10-09%20234718.png)
## Programa en python en el cual el gripper realiza la letra "j" 📋
### planteamiento de trayectorias
1. inicialmente se importan las librerias que requiere python para ejecutar el codigo satisfactoriamente.
 
  ![2223](https://github.com/cristianchernandezs/Parcial_2_robotica/blob/main/imagenes%20github/CODIGO1.png)
1. importar el robot "UR5" de las librerias y visualizarlo.

  ![2223](https://github.com/cristianchernandezs/Parcial_2_robotica/blob/main/imagenes%20github/CODIGO2.png)
1. aplicar cinematica inversa de fordward

  ![2223](https://github.com/cristianchernandezs/Parcial_2_robotica/blob/main/imagenes%20github/CODIGO3.png)
1. planteamiento de trayectorias para que el robot haga la letra "j".
  ![2223](https://github.com/cristianchernandezs/Parcial_2_robotica/blob/main/imagenes%20github/CODIGO4.png)
1. imprimimos la cordenadas cartesianas.
  ![2223](https://github.com/cristianchernandezs/Parcial_2_robotica/blob/main/imagenes%20github/CODIGO5.png)
1. se pasan las coordenada de milimetros a centimetros y se calcuran nuevamente las coordenadas cartesianas 
![2223](https://github.com/cristianchernandezs/Parcial_2_robotica/blob/main/imagenes%20github/CODIGO6.png)
1. se calcula la cinematica inversa, para obtener los valores que debe tomar cada una de las articulaciones
![2223](https://github.com/cristianchernandezs/Parcial_2_robotica/blob/main/imagenes%20github/CODIGO7.png)
1. aplicando el metodo "jtraj", se calcula un polinomio de grado 5 para cada articulacion 
![2223](https://github.com/cristianchernandezs/Parcial_2_robotica/blob/main/imagenes%20github/CODIGO8.png)
1. se visualiza el movimiento final del robot 
![2223](https://github.com/cristianchernandezs/Parcial_2_robotica/blob/main/imagenes%20github/CODIGO9.png)






  
 


## Autores ✒️

_Las siguientes personas colaboraron con el desarrollo del proyecto_

* **Juan Felipe Cañas** - [JuanCañas](https://github.com/jcscorpion)
* **Cristian Hernandez** - [CristianHernandez](https://github.com/cristianchernandezs)
 
