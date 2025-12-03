[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=bvanessalopezp/Proyecto-final-MSF)

# Proyecto: Actividad eléctrica del útero

## Información de la estudiante

Brianna Vanessa Lopez Pardo\[22212261]; l22212261@tectijuana.edu.mx

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos

1. Convertir el diagrama mecánico al diagrama eléctrico.
2. Calcular la función de transferencia aplicando el principio de superposición.
3. Calcular el error en estado estacionario y la estabilidad en lazo abierto.
4. Emular y simular la respuesta del circuito en Simulink/Simscape a la señal impulso unitario.
5. Sintonizar las ganancias de un controlador PID para eliminar el error entre la entrada y la salida del sistema control-caso.

## Descripción detallada del sistema

El circuito mostrado representa un modelo eléctrico equivalente del útero enfocado en la contracción muscular y en la actividad eléctrica que ocurre en las fibras musculares del miometrio. Cada componente del circuito traduce un fenómeno fisiológico a un elemento eléctrico, lo que permite analizar el comportamiento del tejido a través de herramientas de circuitos eléctricos. El primer elemento es la resistencia R, la cual representa la impedancia eléctrica del tejido uterino. Esta resistencia refleja la oposición intrínseca del tejido biológico al paso de corrientes bioeléctricas y agrupa, en un solo parámetro, los efectos de la conductividad, las pérdidas energéticas y las modificaciones estructurales del tejido. En patologías como la endometriosis, es común que este valor aumente debido a fenómenos inflamatorios, fibrosis o cambios en la arquitectura celular que limitan el flujo de la señal eléctrica.

El inductor L, por su parte, representa la propagación del potencial de acción a través de las fibras musculares. En el plano fisiológico, la inductancia se interpreta como la inercia y el retardo temporal con el que la señal eléctrica se desplaza entre las células, permitiendo la sincronización y coordinación del proceso contráctil uterino. Alteraciones en este parámetro reflejan cambios en la velocidad o en la calidad de la conducción eléctrica del miometrio. Ri representa la oposición al flujo de iones dentro del tejido uterino y describe qué tan difícil resulta para la señal eléctrica desplazarse entre las fibras musculares del miometrio. Cuando este parámetro aumenta, la conducción eléctrica se vuelve más lenta y menos eficiente, lo que afecta la coordinación de la actividad contráctil. En la endometriosis, Ri tiende a elevarse debido a procesos de inflamación crónica, fibrosis y alteraciones en las uniones celulares, los cuales reducen la conductividad del tejido y dificultan el paso de corriente iónica; por ello, esta patología se asocia con una propagación eléctrica alterada y patrones de contracción menos organizados.

Finalmente, el capacitor CT aparece conectado en paralelo respecto a la rama formada por RI y L. Este capacitor modela los procesos de despolarización y repolarización de la membrana de las fibras musculares uterinas. La capacitancia CT es análoga al comportamiento eléctrico de la membrana celular, que almacena y libera carga durante cada ciclo de activación eléctrica. Al encontrarse en paralelo, CT representa un camino alterno mediante el cual el tejido puede almacenar carga sin necesidad de recorrer la dinámica asociada al tono muscular o a la propagación del potencial. Esto permite diferenciar claramente el comportamiento rápido y local de la membrana (despolarización y repolarización) del comportamiento más lento asociado al tono y a la propagación eléctrica. Cambios en el valor de CT indican variaciones en la excitabilidad celular, en su capacidad de respuesta o en la dinámica eléctrica de la membrana. De esta manera, la topología del circuito refleja de manera más fiel la fisiología del miometrio, separando los fenómenos de conducción, tono muscular y excitabilidad de la membrana.



Palabras clave:Aparato reproductor femenino; Controlador PID; Endometriosis; Control; Caso

## Lista de archivos incluidos en el repositorio

1. Cuaderno computacional de MATLAB \[.mlx].
2. Modelo de Simulink \[.slx].
4. Imagen con los parámetros del controlador.
5. Imágenes de las simulaciones \[.pdf y .png].
6. Evidencia del análisis matemático: función de transferencia, error en estado estacionario y estabilidad en lazo abierto.

## Referencias

\[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

\[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 4, Page 93.

\[3] N. S. Nise, Control Systems Engineering, 8th ed. Hoboken, New Jersey, USA: John Wiley \& Sons, 2020.
