<h1 align="center" id="title">Prouni 2005-2019</h1>

<p id="description">Dashboard interativo criado para  demonstrar minhas hablidades manipulando dados com python e a vizualização dos mesmos com Power BI, atraves estudo da escolha de cursos de pessoas de 18 a 30 anos que ingressaram no ensino superior utilizando o Prouni.</p>

O objetivo do Dashboard é responder as seguintes perguntas:
*   Quais os cursos mais escolhidos e sua evoluçao com o tempo
*   Quais os estados que mais utiliaram do programa e sua evoluçao com o tempo 
*   Quantas Bolsas ja foram concedidas no total e por ano
*   Quantos cursos diferentes o Progrma contempla


Fonte do Dataset:
https://www.kaggle.com/datasets/lfarhat/brasil-students-scholarship-prouni-20052019

<p> Desafios Encontrados:<p>
 Os nomes de cada curso nao seguiam um padrão, podendo cada universidade colocar para um mesmo id de curso nomes diferentes ex. Administração,Administracao,administração,etc. Tembem pelo jeito em que a tabela foi feita fez com que todos os caracteres diferentes do ingles como o ã foram transformados em A, sendo necessario um trabalho de manipulaçao e limpeza desses dados para elaboraçao do dashboard. 

<p> Conclusão:<p>
Os cursos historicamente mais escolinhos foram Administraçao, Direito, Pedagogia e Enfermagem, com concentração no sudeste. Houve um forte crescimento a partir do ano de 2017 na escolha por Educaçao Fisica e Ciencias Contabeis porem administração e direito continuam sendo os mais escolhidos.
Foram distibuidas ate 2019 um total de 1.4 milhão de bolsas para pessoas de 18 a 30 anos divididos em 1258 cusos diferentes.

<p> Considerações finais:<p>
O desafio de tratar essa quantidade de dados me levou a considerar diversos metodos diferentes, porem pelo tempo optei de maneira normal atraves de diversas funções. Um modelo de machine learning poderia ser aplicado, porem nao existe um modelo convencional para ciar uma rede neural para strings. Caso tivesse  mais tempo investido refinaria as funçoes para o reconhecimento e agrupamento de cursos com nomes parecidos fazendo uma leitura mais fiel da realidade, melhoraria o wallpaper do dashboard e o adptaria para dispositivos mobile.
