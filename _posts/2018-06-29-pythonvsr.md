---
layout: post
title:  Python vs R?
date:   2018-06-15 18:05:55 +0300
image:  '/images/r-vs-python.jpg'
tags:   [Portugues, Tecnologia]
---

## Python vs R

Pensando em ciência de dados, inteligência artificial e aprendizado de máquina, qual é a melhor linguagem? Python ou R?
Não tenho por objetivo comparar códigos, pois já deve existir outros artigos sobre isso.

Quando o meu interesse por programação e ciência de dados começou eu ainda estava na faculdade de física, descobri que o mundo de análise de dados e ciência de dados é gigante e um pouco assustador no início, e a minha dúvida maior era, qual é a melhor linguagem? R ou Python? 

A resposta é bem direta, você deve aprender Python e R, também aprenda sobre banco de dados SQL e afins. Mas se tu for pensar bem mais adiante, dê aquela chance para o Java e Scala por exemplo.

Mas como assim aprender? Quero dizer que, devemos aprender sobre conceitos fundamentais e controlar estruturas de fluxo, o que são aplicáveis em qualquer linguagem de programação. Isso também inclui aprender tarefas comuns com dados como carregamento, consulta, análise, filtragem, extração, classificação, agregação, visualização e análise exploratória de dados. A questão às vezes nem sempre é qual linguagem devemos aprender é como e quando aprender uma linguagem específica e quando aprendê-la em qual grau de conhecimento e porque usar determinada linguagem e pacote para atingir tais objetivos.

### Linguagens de programação, suas características e seus paradigmas:
Sabemos que a maioria das linguagens tem muitos conceitos, paradigmas e estruturas de algoritmos.
Linguagens de programação diferem por design e atributos diferentes, processamento e execução de código (digitação e paradigma). Às vezes após ser digitado os códigos são pré processados antes da sua execução, em outros casos o código é executado diretamente pelo compilador (traduz o alto nível para o baixo nível), após é compilado, executado por um mecanismo ou por tempo de execução.
As linguagens interpretadas são executadas na hora sem exigir a compilação por um interpretador, para um protótipo de códigos elas são mais rápidas, mas podem não ter alguns “benefícios” de otimização e desempenho da execução do código compilado. Mas geralmente as linguagens compiladas são fortemente tipadas, ou seja, todas as variáveis e dados do código sejam explicitamente declaradas com um tipo específico e devem ser consistentes durante o fluxo de código e execução.
As linguagens compiladas possuem variação em tempos de compilação para verificar os erros, e esse mecanismo também promove a segurança do tipo.

### Paradigmas comuns das linguagens de programação:
Scripting ou programação de script: acredito que é o paradigma mais simples, onde o código é escrito em arquivos de script que são executados pelo mecanismo de execução da linguagem, onde geralmente é o interpretador. Ao carregar e executar um arquivo de script por meio de um terminal por exemplo que executa o ambiente interativo do loop REV (read-eval- print loop) da linguagem, onde a(o) programadora(o) execute via linha de comando. 
Procedural: organizada, acoplamento de escopo de dados do código, é escrito de forma para realizar o código por meio de funções bem definidas, módulos que trabalham juntos para fornecer a funcionalidade do programa/aplicativo. O nome procedural é porque esses módulos têm funções que também são chamadas de procedimentos, essas funções podem ser reutilizadas em todos o código e a maioria das vezes recebem uma entrada para gerar uma ou mais saídas. Com o código organizado em módulos, cada um contendo a sua funcionalidade, com interfaces definidas (API’s) menos acoplado ele fica. Escopo de dados da visibilidade a acesso de dados a módulos e funções individuais. A maioria das vezes um vai definir os dados (variáveis) que são locais globais nesse escopo, esses dados podem ser vistos e usados pelo código em qualquer lugar no programa, mas os dados do escopo local são compreendidos por e estão disponíveis em uma única função.
Orientação a objeto: é a ideia de um objeto no código, que são criadas a partir de classes, esses objetos possuem propriedades e métodos independentes. Eu acho muito difícil de explicar orientação de objetos, então vou dar um exemplo: vamos criar um aplicativo para vender sapatos, e esse vai ser o nosso modelo de objeto de sapatos da classe. As propriedades do objeto são valores que o caracterizam, enquanto os métodos do objeto (funções) são as funcionalidades ou ações. Um objeto de sapatos da classe sapatos e lhe dar propriedades como tipo, marca, tamanho, preço e etc. Enquanto todos os sapatos desse aplicativo terão essas propriedades e cada objeto de sapatos terá valores diferentes. 

### Python
Linguagem de programação multiparadigma, caracterizada como uma linguagem tipada dinamicamente, com script, procedural, interpretada e orientada a objetos. Python tem uma biblioteca padrão muito abrangente. É multifuncional, pode ser usada pra tudo, ciência de dados até administração de sistemas de redes. aplicações web, execução de scripts e etc. Python é simples, e foi bem fácil aprender quando quis “trocar” o C e a comunidade é enorme, tem vários recursos e tutoriais online. Python é um ingresso na área de ciência de dados, inteligência artificial e aprendizado de máquina por causa da produção direta de pacotes e módulos poderosos e de qualidade. Esses pacotes podem executar análise exploratória de dados, estatísticas, análise preditiva, aprendizado de máquina, redes neurais, aprendizagem profunda, sistemas de recomendações e etc. 
    
A falta de pacotes e funcionalidades já foi muito discutida há muito tempo, isso comparado ao R. A comparação dos pacotes de R e Python geralmente precisam ser obtidas do próprio fornecedor ou com um gerenciador de pacotes como Anaconda, Miniconda ou PIP. A falta de um repositório central de pacotes do Python que o R possui não é bem uma coisa ruim, talvez precise de mais envolvimento na hora de fazer instalação e atualização.

### R
Também é uma linguagem multiparadigma, é tipado dinamicamente, de script, procedural e interpretada, também pode suportar um tipo de programação orientada a objetos. É considerado um software estatístico, é especializado e adequado para estatísticas, análise e visualização de dados. 
Comparando ao Python, é bem menos flexível e diversificado e também possui uma comunidade focada na linguagem. Não é difícil aprender mas é bem estranha. 
R se diferencia do Python na sua implementação natual e suporte a aritmética matricial e estruturas de dados associados, com vetores e matrizes, bem próximo ao matlab. Já o Python usa o numpy para isso. Tem gente que diz que o R é superior ao Python tanto para estatísticas quanto para visualização em termos de pacotes, detalhes de implementação e resultados estéticos finais para visualização - mas tudo isso, depende. O CRAN é o repositório de muitos pacotes do R, ele é centralizado e bem “cuidado”, onde ficam todos os pacotes disponíveis para o R e que inclui pacotes para um grande número de tarefas. Mas, não é tão claro quase pacotes são melhores para cada tarefa, tem muitos pacotes bons, muitos mais que o Python, mas são altamente especializados e obscuros. Onde já no Python os pacotes são mais diretos, fáceis de identificar e começar.

### IDE’s
Ambas linguagens possuem várias interfaces de linha de comando, que podem ser por meio de um terminal que executa o ambiente interativo.
Para o R o mais conhecido é o RStudio, sou suspeita pra falar pois acho ele impressionante, programas e tarefas podem ser executados a partir de um arquivo de texto simples em combinação com um terminal executando o ambiente R. Muitas opções de notebook são usadas, e são bem populares entre o R e o Python, para o R os mais comuns é as ferramentas de relatório são o RMarkdown e o KnitR.
Já para o Python não existe uma IDE “oficial”, vejo como as mais comuns pelo Spyder e o PyCharm (onde a versão communit é open source), mas qualquer editor pode ser considerado uma IDE, os scripts também podem ser executados através do ambiente. O notebook mais comum do Python é o Jupyter, o qual já vi pessoas o utilizando como IDE. 

### Qual usar, quando e porque?
Em ambas as linguagens tem diversos pacotes que são bem sólidos e altamente capazes, não é errado querer começar com R ao invés de Python. Eu sempre digo para quem quer iniciar na área que é melhor começar com Python, pois é fácil de aprender e começar a trabalhar de forma rápida.
Importante citar que tarefas de ciência de dados, são executadas em desktops, notebooks ou servidores (nuvem ou sistemas distributivos). Entre a execução de uma tarefa para desenvolvimento ou produção, onde as implementações tem um conjunto exclusivo de considerações, desafios e requisitos que envolvem empacotamento, DevOps, confiabilidade do site, monitoramento e etc. 
E a partir de uma perspectiva de requisitos, também devemos considerar as implantações que produzem o resultado em tempo real (ou quase) e também se o fornecimento de uma tarefa, como por exemplo sistemas de recomendações, é preparado para um destino a nível de desempenho offline ou online.

Espero ter de alguma forma ter ajudado sobre pequenas diferenças entre essas duas linguagens mais utilizadas no ramo de ciência de dados. 
Vale lembrar que as coisas mudam com o tempo (não tão rápido quanto um framework para JavaScript - risos), e nem sempre existirá uma solução para cada caso. Experimentação e testes são necessários para encontrar uma solução ideal. 

***