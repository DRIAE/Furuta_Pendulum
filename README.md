# **Péndulo de Furuta**

**Integrantes:**  
Christian Ricardo Conchari Cabrera  
Hamed Emmerson Quenta Alvarez  
Franklin Josué Ticona Coaquira  

**Docente:**  
Mgr. Gabriel Antonio Rojas Silva

## Modelo 3D

![Simscape](https://github.com/DRIAE/Furuta_Pendulum/blob/master/assets/3dview.png)

## Esquema

![Esquema](https://github.com/DRIAE/Furuta_Pendulum/blob/master/assets/esquema.png)

## **Espacio de estados**

![State Space](https://github.com/DRIAE/Furuta_Pendulum/blob/master/assets/espaciodeestados.png)

## **Datos del sistema**

![Datos](https://github.com/DRIAE/Furuta_Pendulum/blob/master/assets/datos.png)

## **Espacio de estados con datos reemplazados**

![State Space1](https://github.com/DRIAE/Furuta_Pendulum/blob/master/assets/espaciodeestados1.png)

## **Sistema en open-loop**

![open-loop](https://github.com/Rod5919/Pendulo-invertido/blob/main/assets/Grafica_open-loop.jpg)

## **Controladores implementados**

1. PID
2. LQR
3. LQG

## **Ganancias de cada controlador**

### **PID**

~~~matlab
kp = -2.2468
ki= -0.063624
kd= -14.626
~~~

### **LQR**

~~~matlab
K = [-48.4768 -64.0586 -241.576 -54.3824]
~~~

## **LQG**

## **Gráficas resultantes**

### **PID**

![Grafica_PID](https://github.com/Rod5919/Pendulo-invertido/blob/main/assets/Grafica_PID.jpg)

### **LQR**

![Grafica_LQR](https://github.com/Rod5919/Pendulo-invertido/blob/main/assets/Grafica_LQR.jpg)

### **LQG**

![Grafica_FC](https://github.com/Rod5919/Pendulo-invertido/blob/main/assets/Grafica_FC.jpg)

## **Datos de respuesta ante un step**

### **Ángulo Theta**

|Dato         |PID        |LQR       |FLC       |
|-------------|:---------:|:--------:|:--------:|
|RiseTime     |     0.0114|0.2708    |0.0861    |
|SettlingTime |     2.4134|7.4297    |3.9158    |
|Overshoot    | 6.7919e+06|1.7434e+06|1.0349e+05|
|Peak         |     0.3014|0.1047    |0.1047    |

