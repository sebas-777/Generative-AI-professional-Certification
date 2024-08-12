# Capitulo 8 - Identificar las diferentes etapas de un proyecto de Inteligencia Artificial.

## 8.1 Identificar las Diferentes Etapas de un Proyecto de Inteligencia Artificial.

Ahora que estás más familiarizado con los conceptos clave de la inteligencia artificial, descubramos lo que sucede detrás de escena en un proyecto real de inteligencia artificial. Para ayudarte a comprender mejor cómo desarrollar un proyecto de IA, imaginemos que eres un director de proyecto en un importante fabricante de automóviles. Tu objetivo es reducir el consumo de energía. Un grupo de investigación ya ha realizado varios análisis exhaustivos y ha descubierto que una forma de abordar el problema es utilizar la IA para anticipar el consumo futuro de energía. Nos adentraremos en las bases, utilizando términos técnicos y científicos, ¡pero no entres en pánico! Tómate el tiempo para leer los siguientes capítulos, vuelve a ver los videos si es necesario y toma notas.

Como antes, encontrarás un resumen de la información clave al final de cada sección. Aquí están las principales etapas de un proyecto de IA que podrías organizar:

 ![An image](./img/IMG-23.png) 

 Para que este proyecto sea un éxito, necesitarás un equipo con muchas habilidades diferentes:  

- `Habilidades industriales:` Personas que se especializan en tu sector empresarial específico (en este caso, la fabricación). Su conocimiento será crucial para encontrar la solución adecuada.  
- `Habilidades de TI:` En particular, un arquitecto de software y algunos desarrolladores de software.    
- `Habilidades de IA:` Un experto en IA (perfil senior) y científicos de datos (profesionales de datos y AI). 
- `Habilidades de gobernanza de datos:` Un DPO (oficial de protección de datos), alguien del departamento legal (para garantizar el cumplimiento de la gestión de datos) y un oficial de RSE (responsabilidad social corporativa) para garantizar que se cumplan los objetivos ambientales.  

## 8.2 -Definir los Parámetros de tu Proyecto de IA.  

Ahora que tu equipo está en su lugar, debes asegurarte de que gestionas adecuadamente el proyecto. Para un proyecto de IA, esto significa que debes completar el análisis:  

- `Define los parámetros comerciales relevantes:` Define los parámetros comerciales relevantes: ¿Qué problema estás abordando? ¿Para quién es? ¿Cuál es el presupuesto? ¿Cuál es el costo? ¿Cuál es tu retorno de inversión (ROI)?  
- `Define tus objetivos:` Por ejemplo, ¿Cuáles son los objetivos de RSE (responsabilidad social corporativa) de la solución? ¿Cuál es el modelo económico de la solución?  
-`Evaluar impactos:` Éticos, sociales, seguridad personal.  
-`Proporciona gobernanza de datos:` Define los datos, su disponibilidad, usabilidad, consistencia y controles de usuario.  
-`Diseñala solución:` Define la arquitectura y el nivel de seguridad de datos.
-`Industrializa la solución:` Esto incluye el seguimiento de resultados, la gestión de usuarios, la comunicación y la gestión del cambio.  

`Recopilar datos`   
¡Tu proyecto será tan bueno como los datos que utilices! En esta fase, es importante recopilar la mayor cantidad de datos posible.   

Los datos son el combustible de un proyecto de ciencia de datos. ¡Sin ellos, tu proyecto no tendrá éxito!  

Recuerda, tu objetivo aquí es mejorar la eficiencia energética de una planta de fabricación. Entonces, podrías recopilar datos sobre el consumo de electricidad en períodos específicos de semanas y meses. También querrás obtener datos de los equipos de producción en sí (cuánta energía consume cada máquina, cuánto tiempo funciona al día, etc.).  

Tu planta también está equipada con muchos sensores que miden y registran diversos tipos de información, como la cantidad de veces que alguien entra a la fábrica, la temperatura de las diferentes habitaciones, el uso del elevador, etc. ¡También puede ser una fuente de datos! Querrás recopilar la mayor cantidad de datos posible en esta etapa, incluso si no estás seguro de cuánto usarás. El objetivo es obtener una comprensión completa del uso de energía de la planta. Incluso podrías considerar obtener datos más generales, como el informe diario del clima local. Los datos relacionados con las horas de sol, la precipitación, el viento, la temperatura, etc., probablemente serán útiles para determinar el uso de energía. Tu equipo tendrá la oportunidad de verificar esto más adelante. Como puedes ver, hay una gran cantidad de datos que puedes recopilar. En la era del big data, los costos de almacenamiento son relativamente bajos. Los edificios modernos y los sitios industriales están cada vez más equipados con sensores. El término “Internet de las cosas” (IoT, por sus siglas en inglés) a menudo se refiere a estos objetos instalados en nuestros entornos, que recopilan datos de forma continua.  

`Limpia tus Datos`
Tú y tu equipo han recopilado una gran cantidad de datos. Antes de poder usarlos, debes asegurarte de que sean confiables. Puedes verificar la confiabilidad de varias maneras:  

`Verifica si falta algún dato. Es probable que tus datos no sean exhaustivos.`    

Por ejemplo, después de un mal funcionamiento de la computadora, es posible que algunos sensores no hayan registrado el consumo de energía.  

`Asegúrate de que no haya valores atípicos.`  
Por ejemplo, al mirar los datos de temperatura, notas que se registró un día con temperaturas extremadamente altas que no pueden ocurrir. ¡Podría ser solo un error aleatorio de la computadora! En ambos casos, los datos en cuestión no son satisfactorios. Sin embargo, el científico de datos de tu equipo puede reemplazar los datos faltantes o erróneos utilizando herramientas estadísticas conocidas como imputación estadística.

Has llegado al final de esta etapa. Ahora tienes datos de alta calidad listos para usar. ¡Sigamos con el siguiente paso!  

`Explora tus datos.`  
Ahora estás listo para examinar las características únicas de tus datos. Esta exploración se llama exploración de datos o minería de datos. El científico de datos de tu equipo trabajará con expertos en tu industria y fuentes de datos para desarrollar una imagen más clara en esta etapa.  

Tu objetivo es comprender el uso de energía de la planta. Los datos ayudarán a responder preguntas como:  

¿Cuánta energía se consume en promedio, todos los días, semana a semana y mes a mes?
¿Cuándo consume la planta más energía?
Explorar los datos te permitirá validar hipótesis o intuiciones. Por ejemplo, el equipo puede creer que cuando más empleados trabajan un lunes, el consumo de energía es más alto durante toda la semana. Esta hipótesis se puede validar o invalidar mediante la tabulación cruzada de los datos.

La visualización de datos se utiliza a menudo en esta etapa e implica el uso de métodos y herramientas para representar los datos de manera gráfica e interactiva. Para darte una idea de cómo se ve esto, echa un vistazo a esta galería de paneles de control.  

`Modela tus datos.`
¡Y ahora finalmente podrás usar algunas herramientas de IA! 

Tu objetivo es predecir el consumo futuro de electricidad de la planta de la manera más precisa posible.  

Para hacerlo, aplicarás el Machine Learning, del cual aprenderás más en el próximo capítulo. En términos concretos, modelarás el consumo de electricidad en función de todas las variables a tu disposición.  

Un modelo es la representación matemática de un problema.  

Usemos un ejemplo para ilustrar lo que esto significa. Supongamos que hipotetizas que la temperatura tiene un impacto en el uso de energía. Cuando hace frío afuera, las personas tienden a usar más energía para calentar los edificios. Por otro lado, cuando hace calor, el consumo de electricidad disminuye.

Puedes reducir todo esto a fórmulas matemáticas que permitan a tu modelo anticipar el uso futuro de energía según las previsiones locales del clima. En este ejemplo, el modelo se basa únicamente en datos meteorológicos. En tu modelo final, utilizarás más variables, como la fecha y el uso de energía en días anteriores.  

 
`El modelado de datos consta de dos fases:`  
La fase uno es el aprendizaje. En esta fase, entrenarás tu modelo con ejemplos, proporcionando al sistema datos meteorológicos y datos sobre el consumo de electricidad en períodos anteriores.  
La fase dos es la predicción. Tu sistema está listo y puedes usarlo para predecir el consumo futuro de energía.
Aprenderás más sobre estas fases de aprendizaje y predicción en el próximo capítulo.  

`Evaluar e Interpretar tus Datos.`  
Acabas de desarrollar un modelo inicial que te permite predecir el consumo futuro de energía.  

Pero, ¿cómo sé que este modelo es confiable?  

Debes evaluar el modelo, es decir, confirmar que es útil y proporciona predicciones confiables. Para hacerlo, lo probarás al predecir el consumo de electricidad durante un período para el que tu sistema de IA no ha sido entrenado, como el mes anterior. Ya tienes los resultados para este período. Los estás utilizando para verificar la fiabilidad de las predicciones realizadas por el modelo que construiste.  

`Implementa tu Modelo.` 
¡Tu sistema de inteligencia artificial está listo para su uso en el mundo real! Permitirá que la planta controle y utilice la energía de la manera más eficiente posible.  

Para asegurarte de que tu sistema cumple con este objetivo, tu equipo de proyecto evaluará su rendimiento después de un período piloto. ¿Es relevante el sistema de IA? En particular, ¿agrega valor comercial?  

Una vez que se implementa un sistema de IA de este tipo, debe ser monitoreado. Lo verificarás a diario para asegurarte de que esté produciendo resultados útiles. A intervalos regulares, también realizarás un mantenimiento del sistema, durante el cual podrás ajustar los parámetros del sistema para garantizar que continúe produciendo buenos resultados.  

[volver al inicio](README.md)

 