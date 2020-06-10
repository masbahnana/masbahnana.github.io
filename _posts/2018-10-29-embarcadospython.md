---
layout: post
title:  Sistemas Embarcados Com Python
date:   2018-06-15 18:05:55 +0300
image:  '/images/embedded.jpg'
tags:   [Portugues, Tecnologia]
---

Provavelmente você deve estar fazendo a mesma cara que eu em relação ao título desse artigo, mas depois de alguns dias pesquisando vi como o python pode ser um grande aliado quando usado como intermediário de comunicação entre usuário e sistema.
    
Nós já sabemos que a linguagem que domina o desenvolvimento de sistemas embarcados é C/C++, já o Python vem cheio de pontos fortes e diversos estudos estão apontando a linguagem para o desenvolvimento de sistemas embarcados.
C/C++ são linguagens compiladas, ambas já existem a bastante tempo, o C surgiu em 1969 e o C++ foi desenvolvida em 1983, logo depois em 1989 surgiu o Python que é uma linguagem interpretada e tem se tornado uma das linguagens mais utilizadas, com todas as suas versões open source e distributiveis.

### O Python:
A linguagem tem se tornado introdutória em diversas faculdades, e é uma das mais compreensíveis em grupos de recém formados e de uma comunidade forte. É bem mais provável que um formando hoje aprenda a programar em Python do que em C/C++. Também não podemos esquecer que, existe uma parcela de desenvolvedores que utilizam python como hobbie.
Mas quando o assunto é sistemas embarcados a diferença é gritante! Cerca de 95% dos códigos são escritos em C/C++, é difícil imaginar que o Python um dia possa ultrapassar o legado do C/C++, mas com o grande número de desenvolvedores em Python podem ultrapassar o C/C++ no futuro.
Python não é só a linguagem mais comum para quem está em início de carreira/faculdade, é também a linguagem que mais cresce quando o assunto é ciência de dados, inteligência artificial e computação incorporada. Pode parecer estranho mas quando vamos olhar os números percebe-se que a linguagem que vem crescendo mais rápido, onde 5% dos demais códigos para sistemas embarcados não são C/C++, mas quem sabe o Python não “rouba” esse monopólio nos próximos anos? 
Quem está migrando para a indústria com experiências em desenvolvimento focado em drones ou robôs tem uma certa afinidade com Arduíno e Raspberry Pi, essas pessoas em algum momento tiveram contato com o Python e também com alguma programação de sistemas embarcados.
C/C++ é um pouco lento de se escrever, propenso a erros e as vezes é ilegível, o Python é conhecido pela sua capacidade de escrita, redução de erros e legibilidade e sinceramente legibilidade é fundamental para manter o código, ainda mais quando se trata de trabalhos em equipe. Tem que ser fácil e decifrável, com prazos apertados ninguém está disposto a gastar mais tempo em depuração, garantia e qualidade. O design do Python supera muito o C/C++ e reutilização em ambientes ágeis pode fazer a diferença em relação a concorrência. Os algoritmos estão ficando cada vez mais complexos, loops de controle estão sendo substituídos por redes neurais e outros processos que ajudaram o Python a embarcar nessa área, Python tem bibliotecas como a Theano que otimizam o código para esses processos, mas tudo bem que o Theano seja escrito em C/C++, mas o Python tem bibliotecas de altíssimo desempenho e muito mais amigável. O índice de pacotes o Python tem enésimos módulos que vem aumentando a produtividade dos programadores, nos dando a opção de pular etapas, pois as funções já vem estabelecidas em seu próprio código.

### E o C/C++???
É bem óbvio: ele gera códigos de tempo de execução de forma compacta e rápida, e é a linguagem escolhida por 95% dos desenvolvedores de sistemas embarcados, portanto, é uma história que talvez o Python demore a superar. 
Mas e quando se trata de velocidade? A velocidade do tempo de execução não é o único aspecto do desenvolvimento a ser considerado, também consideramos a velocidade do desenvolvimento. O Python possa ser menos eficiente que o C/C++ em tempo de execução, durante o desenvolvimento é muito mais eficiente. Os intérpretes lêem cada linha de código, analisam e fazem verificações de tempo de execução e rotinas de chamada para executar as operações no código. Isso é muito mais atividade do que o que você obtém ao executar o código C / C ++, onde a mesma linha de código pode ser compilada em apenas algumas instruções. Isso pode levar a velocidades de tempo de execução mais lentas e maior consumo de energia com o Python.

### A velocidade do Python:
O principal argumento contra o Python em relação ao C/C++ é a sua velocidade de tempo de execução, mas existem diversas maneiras de melhorar o código e deixá-lo mais eficiente, além das bibliotecas também existem extensões para o Python como por exemplo o Cython, que é basicamente Python com digitação estática para executar a matemática mais rápido. O Cython é tipado estaticamente, podemos compilar para C/C++ e executar nas velocidades de C/C++.
Os Just In Time são outra maneira de melhorar a velocidade de execução do Python, esses tipos de compiladores trabalham em paralelo com o interpretador do Python, ele gera instruções de máquina compilada para loops do código, isso faz com o que os passes subsequentes sejam executados pelo interprete de forma mais rápida. O compilador PyPY JIT pode aumentar a velocidade de execução do Python em quase um fator de dois. Lembrando que os compiladores JIT só devem ser utilizados se houver espaço, já que os sistemas embarcados não tem muito disco de sobra.

### Então, qual é a melhor otimização?
É utilizar de estruturas de dados e algoritmos melhores, mas isso pode se tornar a tarefa mais difícil na implementação de software, então, é melhor utilizar as ferramentas citadas acima.

### Comunicação do Python com sistemas embarcados: 
O Python pode ser uma forte ferramenta quando utilizada como um intermediário de comunicação entre o usuário e o sistema embarcado trabalhado, o envio de mensagens pelo Python para um embarcado permite que o usuário automatize seus testes. 
O Python também pode ser usado para receber dados do sistema embarcado que podem ser armazenados para análise. Os programadores podem usar o Python para desenvolver parâmetros e outros métodos de análise desses dados.
Mas enfim? O que é mais importante para a sua equipe? Deixando um pouco de lado o debate entre Python e C/C++, futuramente, pode não caber aos programadores de Python defender seu uso em sistemas embarcados, mas sim aos designers/arquitetos de sistemas embarcados para descobrir como acomodar a popularidade crescente do Python.

***