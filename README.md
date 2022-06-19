# Teste_t_teste_de_hipotese

Neste trabalho usaremos como fonte de dados  o  dataset  “sleep” disponível  no  pacote datasets em R. 

Esse dataset é resultado de um trabalho de  pesquisa  com  pacientes que  possuem dificuldades para dormir. Os pacientes foram separados em 2 grupos e cada 
grupo recebeu um medicamento diferente para tratar distúrbios no sono e ajudar a aumentar o tempo dormindo. 
O dataset possui 3 variáveis:

extra – Variável numérica que indica quantas horas a mais ou a menos o paciente dormiu após receber o medicamento. Esta será a nossa variável dependente;

Group – Variável do tipo fator (categórica) que indica o medicamento usado pelo paciente (1 ou 2). Esta será a nossa variável independente;

ID – Identificação do paciente.

Nosso objetivo neste estudo é responder a seguinte pergunta:

“Existe diferença significativa na média de sono dos 2 grupos de pacientes, ou seja, há diferença significativa entre os dois medicamentos que ajudam no 
distúrbio do sono?”

Como temos duas amostras (dois grupos), podemos aplicar o Teste t para responder à pergunta. Mas para aplicar o Teste t, primeiro precisamos validar suas suposições, e para isso precisamos do Teste de Shapiro-Wilke do Teste F.
Definimos assim as hipóteses para nosso teste:

•H0 (Hipótese Nula) =Não há diferença significativa entre as médias dos 2 grupos.

•Há (Hipótese Alternativa) =Há diferença significativa entre as médias dos 2 grupos.

A interpretação do resultado do Teste t ajudará a definir se devemos ou não rejeitar a H0 e responder a pergunta de negócio deste estudo de caso.

ESPAÑOL:

En este trabajo utilizaremos como fuente de datos el conjunto de datos de "sleep" disponible en el paquete de conjuntos de datos en R.

Este conjunto de datos es el resultado de un trabajo de investigación con pacientes que tienen dificultad para dormir. Los pacientes fueron divididos en 2 grupos y cada uno
grupo recibió un fármaco diferente para tratar los trastornos del sueño y ayudar a aumentar el tiempo de sueño.
El conjunto de datos tiene 3 variables:

extra – Variable numérica que indica cuántas horas más o menos durmió el paciente después de recibir el medicamento. Esta será nuestra variable dependiente;

Grupo – Variable tipo factor (categórica) que indica el fármaco utilizado por el paciente (1 ó 2). Esta será nuestra variable independiente;

ID – Identificación del paciente.

Nuestro objetivo en este estudio es responder a la siguiente pregunta:

“¿Hay una diferencia significativa en el sueño promedio de los 2 grupos de pacientes, es decir, hay una diferencia significativa entre los dos medicamentos que ayudan en la
desorden del sueño?"

Como tenemos dos muestras (dos grupos), podemos aplicar la prueba t para responder la pregunta. Pero para aplicar la prueba t, primero debemos validar sus suposiciones, y para eso necesitamos la prueba Shapiro-Wilke de la prueba F.
Definimos las hipótesis para nuestra prueba de la siguiente manera:

•H0 (Hipótesis Nula) =No hay diferencia significativa entre las medias de los 2 grupos.

•Hay (Hipótesis Alternativa) =Hay una diferencia significativa entre las medias de los 2 grupos.

La interpretación del resultado de la prueba t ayudará a definir si rechazar o no H0 y responder a la pregunta comercial de este caso.
