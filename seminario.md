# Volunteer Computing

## Introdução

O custo computacional para prever a formação de proteínas, calcular um número primo ou produzir modelos climáticos é muito alto. Um modo de atacar esses problemas é utilzar servidores enormes com uma infraestrutura tão grande quanto para manter a integridade dos dados computados, um custo absurdo para muitos pesquisadores.

Com o advento da internet e cada vez maior número de máquinas domésticas e interconexão entre as pessoas, surge uma opção esse paradigma de pesquisa, a computação voluntária.

## Objetivo da técnica

Volunteer computing visa utilizar recursos computacionais (armazenamento, poder de processamento, conexão de internet) "doados" por donos de máquinas que possuem alguma quantidade desses recursos disponível em modo ocioso.

Com essa técnica, pessoas que não tem formação acadêmica podem ajudar pesquisadores de todo o mundo a realizar suas pesquisas.

## História

## Implementação

Para a implementação de computação voluntária são utilizados dois conjuntos de máquinas: servidores e clientes.
Os servidores têm como trabalho dividir o problema a ser resolvido em tarefas menores, que são então distribuídas aos clientes. Os clientes, quando ociosos, realizam a tarefa e retornam os resultados obtidos para os servidores. Em posse dos resultados, os servidores devem então montar a resposta para o problema.

Ferramentas como o BOINC estimam a quantidade de operações de ponto flutuante, espaço necessário para armazenamento e conexão de internet necessários para que cada tarefa seja realizada evitando, assim, que tarefas sejam direcionadas a clientes que não podem realizá-las.

Outra técnica comum para a implementação da computação voluntária é a computação replicada. Nessa técnica, uma tarefa é realizada por mais de um cliente e o resultado só é aceito caso todos os clientes que executaram essa tarefa retornem resultado igual, dentro de um intervalo de erro tolerado. Com isso, são evitadoes erros nos resultados decorrente de fraudes nos dados e mal-funcionalmento de clientes.

## Benefícios e Desvantagens

* Conscientizar a população sobre projetos de pesquisa
* Aumentar o engajamento do público
* Permitir métodos de pesquisa mais baratos
* Gerar resultados mais rapidamente
* Utiliza os recursos computacionais de forma mais eficiente

* Tecnologia ainda em desenvolvimento
* Aumento do consumo de energia do doador
* Decréscimo na performance da máquina do doador


## Exemplos

  BOINC: Framework da Universidade de Berkley para realização de computação voluntária. Entres os projetos que podem ser apoiados com o uso do framework estão:

    Folding@home: Projeto criado em Stanford com objetivo de entender
    como funcionam interações entre proteínas e suas relações com doenças.
    O Alzheimer, por exemplo, é causado pela agregação de algumas pequenas
    proteínas chamadas Abeta peptídeos. Esse agregados parecem ser tóxicos
    para os neurônios, causando a morte de várias células neuronais.
    Prevendo a estrutura desses agredados passa a ser possível começar
    a criar drogas para combater a doença, além de ser possível ter ideia
    de como esses agregados se formam, talvez sendo possível impedir
    a formação deles.

    Einstein@home: O projeto procura encontrar estrelas de neutrons
    a partir da análise de dados gerados por detectores de ondas
    gravitationais, rádio-telescópios e satélites de raios-gama.
    Os voluntários do projetos já encontraram cerca de 50 estrelas de
    neutrons. O projeto tem como meta fazer a primeira detecção direta de
    ondas grativacionais emitidas por estrelas de neutrons
    em rotação (pulsares).

## Conclusão

## Referências

* http://www.volunteer-computing.org/
* http://setiathome.berkeley.edu/
* https://pt.wikipedia.org/wiki/BOINC/
* http://folding.stanford.edu/diseases/
* https://einsteinathome.org/pt-br/about
* http://www.wseas.us/e-library/conferences/2007corfu/papers/540-118.pdf
* https://en.wikipedia.org/wiki/Volunteer_computing
* http://www.volunteer-computing.org/EN/why-use-volunteer-computing.html
* https://pdfs.semanticscholar.org/4fbd/68ba641f16d1566d3f1dc7704f2f63b938a3.pdf?_ga=2.980344.89964398.1497913612-119129416.1497913612
