# Capitulo 5 - Identificar los problemas de seguridad de la Inteligencia Artificial

## 5.1 - Explorar el uso malicioso de la IA

La inteligencia artificial (IA) tiene un gran potencial y está creciendo rápidamente, pero también plantea preocupaciones importantes sobre seguridad y responsabilidad. Los principales riesgos incluyen el uso malicioso (como la difusión de noticias falsas y ciberataques), problemas de seguridad en el funcionamiento de la IA, uso inadecuado de datos personales y el impacto ambiental.
Un ejemplo destacado de uso malicioso son los "deepfakes", medios sintéticos creados con IA que pueden manipular imágenes, audio y video de forma convincente. Esto plantea riesgos de desinformación generalizada.
Para protegerse, se recomienda usar el sentido común, pensar críticamente, cuestionar las fuentes, verificar la información en múltiples sitios y utilizar plataformas de verificación de hechos.
El texto también menciona la importancia de la gobernanza de la IA para fomentar el desarrollo de sistemas seguros y responsables. Se sugiere que en los próximos capítulos se explorarán más a fondo estos temas y se discutirán consideraciones para un uso responsable de la IA.


## 5.2 - Ciberataques

### Aquí tienes el resumen del texto:

La IA está siendo utilizada cada vez más por ciberdelincuentes para realizar ataques más sofisticados. Los principales tipos de ataques incluyen:

1. Ataques de phishing: La IA ayuda a identificar víctimas potenciales y personalizar correos electrónicos fraudulentos. Herramientas como SNAP_R generan tweets de phishing realistas con altas tasas de éxito.

2. Suplantación de identidad: Tecnologías como "Deep voice" pueden imitar voces usando muestras de audio. Un ejemplo es el fraude de $35 millones a un banco en Hong Kong usando una voz de IA.

3. Ataques de extremo a extremo: La IA puede realizar todas las etapas de un ciberataque, desde el reconocimiento hasta la exfiltración de datos.

`Los desafíos de seguridad en la IA incluyen:`

- Comportamientos inesperados y potencialmente peligrosos.
- Creciente autonomía e impredecibilidad de los sistemas.
- Falta de inversión en seguridad de IA por parte de empresas y gobiernos.

`Los principales problemas de seguridad en IA son:`
1. Robustez
2. Explicabilidad
3. Definición de propósito

Estos desafíos podrían ser cruciales en el siglo XXI y requieren mayor atención y recursos.

## 5.3 - Problema N.°1: Falta de robustez en la IA

La robustez en sistemas de IA mide su fiabilidad ante situaciones desconocidas. Estos sistemas, basados en correlaciones estadísticas, pueden fallar al enfrentar escenarios no incluidos en su entrenamiento. Por ejemplo, un sistema entrenado para reconocer perros podría equivocarse con una raza desconocida.

Esta vulnerabilidad es explotada en los "ataques adversarios", donde pequeñas modificaciones en los datos de entrada engañan al sistema. Un caso preocupante es la alteración de señales de tráfico para confundir a vehículos autónomos, lo que podría resultar en interpretaciones peligrosamente erróneas.

La falta de robustez plantea serios riesgos de seguridad, especialmente en aplicaciones críticas. Es crucial mejorar la capacidad de los sistemas de IA para manejar situaciones imprevistas de manera segura y confiable.

## 5.4 - Problema N.°2: explicabilidad en la IA

La explicabilidad y la transparencia de un sistema de IA permiten a un humano comprender y analizar cómo funciona para garantizar que funcione de la manera deseada. Hoy en día, la mayoría de los sistemas de IA que utilizan Machine Learning son “cajas negras” que operan de manera autónoma sin que nadie sepa cómo ni por qué. Los sistemas de IA de Machine Learning utilizan datos y métodos de razonamiento estadístico para aprender correlaciones. Sin embargo, estas correlaciones no indican necesariamente una relación causal.
Por ejemplo, un sistema de Machine Learning en medicina examinará muchos casos diagnosticados previamente para establecer correlaciones en lugar de llegar a un diagnóstico médico aplicando conocimiento específico del dominio y reglas preconcebidas. Así es como algunos sistemas de IA para diagnosticar el cáncer han "aprendido" a distinguir entre imágenes de tumores malignos y benignos en función de si la imagen contiene una regla graduada. Entre las imágenes de tumores prediagnosticados que se les proporcionaron, las imágenes de tumores malignos a menudo contenían una regla graduada, que se utilizaba para medir el tamaño del tumor. ¡Se demostró la correlación entre la regla y el diagnóstico de cáncer!
 
En el caso del algoritmo automatizado de clasificación de lesiones cutáneas, una mayor explicabilidad y transparencia permiten a las personas comprender cómo funciona el modelo de IA y detectar cuándo no funciona correctamente.

## Tema 5.5 - Problema N.°3: Definir los objetivos correctos para un Sistema de IA
Cuando un modelo interactúa con personas, tiene que llevar a cabo acciones o tomar decisiones que afectan al mundo. Por lo tanto, debemos definir sus objetivos correctamente, o las acciones y decisiones no cumplirán nuestras expectativas.

Sin embargo, en la práctica, es difícil traducir la complejidad y el matiz de los objetivos humanos al lenguaje informático. Es fácil para una máquina malinterpretar la intención detrás de las instrucciones humanas al aplicarlas de manera demasiado literal.

Por ejemplo, al decirle a una IA que no pierda en un juego de Tetris, el modelo identificó la mejor forma de cumplir con la instrucción sin cumplir las expectativas de los diseñadores: pausa el juego tan pronto como cree que perderá. En un ejemplo menos trivial, muchas plataformas de video en línea intentan sugerir videos “que el usuario querrá ver” dándole a la IA el objetivo de ofrecer videos que el usuario verá de principio a fin.

Sin embargo, definir el objetivo de la IA de esta manera hace que el algoritmo favorezca videos cortos y sensacionales o refleje las opiniones fuertes del usuario. Es más probable que el usuario los vea de principio a fin, pero aún necesita ver los videos que más desea. ¿Cómo le explicas a una máquina lo que quieres decir con “videos que el usuario querrá ver”? No es tan simple.


[volver al inicio](README.md)