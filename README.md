#Simulación de Tiempos de Espera en una Planta de Concreto

Este proyecto utiliza el método de **Simulación Monte Carlo** para modelar y analizar el sistema de carga de camiones en una planta de concreto. Se busca evaluar el tiempo de espera que se genera cuando los camiones llegan aleatoriamente a cargar materiales y hay una cantidad limitada de silos en operación.

---

## Objetivo General

Simular y analizar el comportamiento del sistema de carga de camiones, evaluando los tiempos de espera bajo condiciones aleatorias.

---

## Objetivos Específicos

- Simular la llegada y carga de camiones.  
- Calcular el tiempo promedio de espera.  
- Evaluar el rendimiento del sistema con 2 silos.  
- Proponer mejoras operativas con base en los resultados.

---

## Descripción del Problema

En una planta de concreto, los camiones llegan en distintos momentos del día a cargar materiales. Cuando hay más demanda que capacidad de carga (silos disponibles), se generan tiempos de espera que pueden afectar la logística de entrega. La simulación permite visualizar cómo se comporta este sistema.

---

## Modelo Matemático y Supuestos

- 20 camiones llegan de forma aleatoria (0 a 60 minutos).  
- Cada camión tiene un tiempo de carga aleatorio (5 a 10 minutos).  
- Hay 2 silos disponibles, cada uno atiende a un solo camión a la vez.  
- No hay prioridades ni fallas.  
- Se utiliza distribución uniforme para todos los datos aleatorios.

---

## Tecnologías Usadas

- Python  
- NumPy  
- pandas  
- Matplotlib  
- Jupyter Notebook

---

## Resultados

- Gráficas de tiempo de espera por camión y espera acumulada.  
- Análisis de comportamiento del sistema con diferentes condiciones de carga.  
- Identificación de momentos críticos de saturación.

---

## Conclusiones

- El sistema opera aceptablemente con 2 silos, pero puede presentar momentos de congestión.  
- El uso de Monte Carlo permitió simular sin datos históricos reales.  
- Se sugiere mejorar la logística programando mejor los horarios de llegada.


## Colaboradores

- Diego Solorzano 
- Alejandra Anguiano  
