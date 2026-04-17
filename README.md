# Laboratório Virtual de Métodos Numéricos (LAVIME)

## Apresentação

O LAVIME é um repositório digital aberto que agrega recursos de aprendizagem em métodos numéricos aplicados, tendo por base a visão de uma "engenharia computacional holística" para a era dos dados (leia o artigo [_Engenharia computacional para um mundo centrado em dados_](https://tril.ci.ufpb.br/2021/10/16/engenharia-computacional-para-um-mundo-centrado-em-dados/)). O LAVIME é essencialmente composto por um livro e por tópicos complementares diversos, escritos no formato de cadernos interativos (arquivos `.ipynb`). São cobertos não apenas os assuntos clássicos que costumam ser ensinados em disciplinas equivalentes em qualquer curso superior de universidades nacionais ou estrangeiras, mas também tópicos modernos que se entrelaçam para produzir uma engenharia cada vez mais centrada em dados. Vale citar: 

- exemplos teóricos e aplicados;
- bancos de dados reais de pequena escala;
- algoritmos demonstrativos;
- receitas de código; 
- sessões de práticas dedicadas;
- dicas de programação e
- recortes suplementares.

Pretende-se mostrar que conceitos tradicionais são a base para os _métodos numéricos de nova geração_, que criam interdisciplinaridade com temáticas do estado-da-arte, tais como aprendizado de máquina científico, redes neurais informadas pela física, modelos de ordem reduzida e técnicas que fazem interface com a ciência da computação e outras áreas aplicadas.

O conteúdo básico é ensinado na disciplina _Cálculo Numérico_ (GDCOC0072) ministrada pelo [Prof. Gustavo Oliveira](https://gcpeixoto.github.io) ao longo de um semestre, atendendo tanto os cursos de graduação do Centro de Informática da UFPB, quanto de outros centros. Neste rol incluem-se:

- Ciência da Computação;
- Ciência de Dados e Inteligência Artificial;
- Engenharias (todas, exceto Renováveis);
- Estatística;
- Física; e
- Matemática.

## História e impacto

O material começou a ser desenvolvido pelo professor no âmbito do [Projeto Numbiosis](http://numbiosis.ci.ufpb.br/pt/inicio/) em 2017. Em 2019, foi lançada a versão _web_. Até o ano de 2020, recebeu suporte do Programa Institucional de Monitoria com contribuições ativas. De 2021 a 2024, o projeto teve suporte reduzido com atualizações esporádicas. A partir de 2025, uma nova etapa de melhorias foi iniciada para contemplar extensões de conteúdo para aplicações voltadas a dados e modernizações para um espectro novo de ciência e engenharia computacional. Em 2026, o material passou por uma nova atualização tecnológica de interface. 

Empregado semestralmente, o LAVIME (anteriormente LVMN) já alcançou mais de 600 discentes dos oriundos dos diversos cursos de graduação em ciências exatas da UFPB. Há diversos relatos de discentes que testemunham o impacto do LAVIME em sua formação e como os materiais aqui dispostos lhes proporcionaram outra perspectiva de formação.

## Objetivos

Os objetivos gerais do LAVIME são:

- Apresentar o universo dos métodos numéricos a estudantes de graduação em ciências exatas e no eixo STEM;
- Estimular a aprendizagem ativa através da resolução de projetos aplicados; e 
- Fomentar a maturidade do pensamento computacional e as habilidades de programação através do ecossistema Python para métodos numéricos; 


## Estrutura e Programa 

O curso é normalmente realizado em 4 módulos, totalizando 60h de carga horária. O módulo especial é adotado como complementar e ensinado sob demanda. Cada módulo possui cadernos, sessões de código e avaliações como seus componentes. Nos cadernos estão os capítulos do conteúdo principal do curso. As sessões de código (_code sessions_) são aulas dedicadas ao estudo de funções de utilidade predefinidas em módulos Python para resolução direta de problemas aplicados. Essas funções são apresentadas como "receitas prontas" que abrem caminhos para implementações de maior complexidade. 

A estrutura resumida segue abaixo:

- Módulo 1 (5h)
    - Conteúdo (4h)
    - Avaliação: Quiz (1h)

- Módulo 2 (15h)
    - Conteúdo (13h)
    - Avaliação: Prova (2h)

- Módulo 3 (20h)
    - Conteúdo (16h)
    - Avaliação: Projeto Computacional (4h)

- Módulo 4 (20h)
    - Conteúdo (16h)
    - Avaliação: Projeto Computacional Sorteado (4h)

- Módulo Especial
    - Sob demanda


O programa do curso segue abaixo:

### Módulo 1

- Modelagem integrada e engenharia computacional

    - [Caderno 1 - Modelagem Integrada: Uma Ferramenta para Compreender e Simular o Mundo Real](aula-00-modelagem-programacao.ipynb) (1h)
    - [Caderno 2 - Métodos Numéricos: Necessidade, Evolução e Profissão](aula-01-introMetnum.ipynb) (2h)    
    - [Caderno 3 - Do Contínuo ao Computável: Discretização e Erros Numéricos](aula-02-erros.ipynb) (1h)
    - Avaliação: Quiz (1h)

### Módulo 2

- Determinação de raízes de equações não lineares unidimensionais 

    - [Caderno 3 - Do Contínuo ao Computável: Discretização e Erros Numéricos](aula-02-erros.ipynb) (1h)
    - [Caderno 4 - Domando Equações Não Lineares: Inspeção e Descobrimento de Raízes](aula-03-analise-grafica.ipynb) (2h)
    - [_Code session 1_ - roots e polyval](./code-sessions/codeSession-1-polyval.ipynb) (2h)
    - [Caderno 5 - Método da Bisseção: A Arte de Cindir e Convergir](aula-04-bissecao.ipynb) (2h)
    - [_Code session 2_ - bisect](./code-sessions/codeSession-2-bisect.ipynb) (2h)
    - [Caderno 6 - Método de Newton: Sair pela Tangente sem Perder o Rumo](aula-05-newton.ipynb) (2h)
    - [_Code session 3_ - newton](./code-sessions/codeSession-3-newton.ipynb) (2h)
    - Avaliação: Prova (2h)


### Módulo 3

- Resolução de sistemas de equações multidimensionais

    - [Caderno 7 - Do Vetor ao Sistema Linear: Computação Vetorizada Na Prática](aula-06-matrizes-vetores.ipynb) (2h)
    - [Caderno 8 - Sistemas Lineares na Prática Computacional: Métodos Diretos e Fatoração LU](aula-07-fatoracao-lu.ipynb) (4h)
    - [_Code session 4_ - solve](./code-sessions/codeSession-4-solve.ipynb) (2h)
    - [Caderno 9 - Sistemas Lineares na Prática Computacional: Métodos Iterativos](aula-08-jacobi-seidel.ipynb) (2h)
    - [Caderno 10 - Método de Newton para sistemas não-lineares](aula-09-newton-nao-linear.ipynb)
    - [_Code session 5_ - fsolve](./code-sessions/codeSession-5-fsolve.ipynb)
    - Avaliação: Projeto Computacional (4h)

### Módulo 4 

- Teoria da aproximação

    - [Caderno 11 - Em Busca do Desconhecido: Interpolação Polinomial](aula-10-interpolacao-newton.ipynb) (2h)
    - [Caderno 12 - Ajuste de Curvas por Mínimos Quadrados](aula-11-minimos-quadrados.ipynb) (2h)
    - [Caderno 13 - Regressão não linear](aula-12-ajusteNaoLinear.ipynb) (2h)
    - [_Code session 6_ - interp](./code-sessions/codeSession-6-interp.ipynb) (2h)
    - [_Code session 7_ - fit](./code-sessions/codeSession-7-fit.ipynb) (2h)

- Integração numérica 

    - [Caderno 14 - Integração Numérica: Regras de Newton-Cotes](aula-13-integracao-newtonCotes.ipynb) (4h)
    - [Caderno 15 - Quadratura Gaussiana](aula-14-quadratura-gaussiana)
    - [_Code session 8_ - integrate](./code-sessions/codeSession-8-integrate.ipynb)
    - Avaliação: Projeto Computacional (4h)


### Módulo especial

- Diferenciação numérica e resolução de equações diferenciais

    - [Caderno 16 - Diferenciação numérica](aula-15-diferenciacao-numerica.ipynb)
    - [Caderno 17 - Solução numérica de EDOs](aula-16-solucoes-edo.ipynb)
    - [Caderno 18 - Método de Euler](aula-17-metodo-euler.ipynb)
    - [Caderno 19 - Métodos de Taylor e Runge-Kutta de 2a. ordem](aula-18-taylor-rungeKutta.ipynb)
    - [_Code session 9_ - solve_ivp](code-sessions/codeSession-9-solve_ivp.ipynb)

## Desenvolvimento

Este material é desenvolvido continuadamente no âmbito do [Projeto Numbiosis](https://numbiosis.ci.ufpb.br) pelo Prof. Gustavo Oliveira, UFPB/CI/DCC. Os seguintes alunos deram colaboradores relevantes:

- Turma 2020 (CT): Thiago Ney Rodrigues
- Turma 2017 (CI): Smith Lima e Vinícius Veríssimo


## Metodologia de Avaliação

A disciplina é composta por 4 avaliações, organizadas de acordo com o seguinte quadro:

| Módulo | ID | Modalidade | Tipo | Peso | Descrição |
|:---:|:---:|:---:|:---:|:---:|:---|
| 1 | P1 | Prova | Individual | 1/3 | Ver manual de orientação |
| 2 | P2 | Prova | Individual | 1/3 | Ver manual de orientação |
| 3 | P3 | Projeto | Equipe | 1/3 | Ver manual de orientação |
| 4 | P4 | Projeto | Equipe | 1/3 | Ver manual de orientação |

Das 4 avaliações, extraem-se as 3 maiores notas para cálculo da média final.

### Manuais de orientação

- Para provas, clique [aqui](https://drive.google.com/file/d/1cSI8ROuixGP-Gg2CcB3d7RuYqTRjSl1z/view?usp=share_link).
- Para projetos, clique [aqui](https://drive.google.com/file/d/1A7A8IpBZ1jXxOuxMs7Tw6bjdhNwQtgEZ/view?usp=sharing).

### Exemplos de projetos

- Para exemplo de projetos _high-grade_, clique [aqui](https://drive.google.com/drive/folders/1sJmXAr5zc3OqJ3ZjWpQmA439nNgmI5g9?usp=sharing).

### Cálculo da nota final

A nota final do curso, $NF$, é dada pela seguinte média ponderada:

$$
NF = \sum_{i=1}^{M} p_i N_i - pN
$$

com $N = \min\{{N_i}\}_{i=1}^M$,

onde:

- $M$: quantidade de módulos
- $p_i$: peso da $i$-ésima avaliação
- $p$: peso da avaliação $N$ 

## Conteúdo Complementar 

Alguns materiais complementares não contemplados no curso regular ou não explorados com maior detalhamento são fornecidos aqui para aguçar o interesse de estudantes para temas que orbitam ao redor dos métodos numéricos e são úteis para aplicações gerais.

### Apostila introdutória de Python

Python é a linguagem escolhida para o curso devido à sua disponibilidade gratuita, versatilidade e facilidade de aprendizagem. Como forma de nivelamento dos estudantes que não possuem experiência com Python, a apostila [Introdução à Linguagem Python para Ciências Computacionais e Engenharia](https://gcpeixoto.github.io/lecture-ipynb/indice.html), traduzido pelo professor a partir dos trabalhos do Prof. Hans Fanghor (Universidade de Southampton/UK), tem o propósito de fornecer conhecimento básico da linguagem para uso no curso e uma oportunidade de estudo paralelo. Caso você se enquadre neste grupo de estudantes, não deixe de consultar este material.

### Tópicos 

- [Números em ponto flutuante e seus problemas](extra/extra-pontoFlutuante.ipynb)
- [Método do ponto fixo](extra/extra-pontoFixo.ipynb)
- [Método da secante](extra/extra-secante.ipynb)
- [Método de Müller](extra/extra-muller.ipynb)
- [Malhas numéricas](extra/extra-malhasNumericas.ipynb)
- [Plotagem com _matplotlib_: tópicos especiais](extra/extra-matplotlibTopicos.ipynb)
- [Campos de direção para EDOs](extra/extra-camposDirecaoEDO.ipynb)
- [Melhoramentos do método de Euler](extra/extra-eulerMelhorado.ipynb)
- [Estabilidade do método de Euler](extra/extra-estabilidadeEuler.ipynb)
- [Método de Euler implícito](extra/extra-eulerImplicito.ipynb)
- [Métodos de múltiplos passos: _Adams-Bashfort_](extra/extra-multistep-adamsBashfort.ipynb)
- [EDOs de ordem superior](extra/extra-edoSuperior.ipynb)
- [Sistemas de EDOs](extra/extra-sistemasEDO.ipynb)
- [Transformada de Fourier](extra/extra-fft.ipynb)
- [Otimização de código](extra/extra-numba.ipynb)
- [Documentação de código](extra/extra-docstrings.ipynb)

### Recortes

Os recortes contemplam curiosidades ou anedotas sobre tópicos variados. Acesse-os pela barra lateral de navegação.

_Obs.: este conteúdo está sendo gradualmente incorporado no livro-texto e será descontinuado no futuro_.

## Como contribuir?

O material passa por revisões periodicamente, mas possui suporte limitado. O projeto Numbiosis não recebe financiamento direto para bolsas. Todo o conteúdo é desenvolvido pelo Prof. Gustavo Oliveira e discentes (monitores e/ou tutores bolsistas ou voluntários, bem como aqueles que se matriculam no curso e contribuem com melhorias). Caso queira contribuir com melhorias, apontamento de erros ou sugestões diversas, fale com o professor.

## Orientações acadêmicas

Consulte projetos do Prof. Gustavo nos horizontes estratégicos do [TRIL Lab](http://tril.ci.ufpb.br). Saiba mais na [página pessoal](https://gcpeixoto.github.io) do Prof. Gustavo.

### Temas para TCCs 

Você é de algum curso do Centro de Informática e deseja trabalhar com alguma tecnologia ou materiais digitais para ensino? Em particular, no âmbito do projeto Numbiosis e do LVMN existem vários tópicos possíveis, tais como: 

- Implementação de gráficos interativos para visualização 3D de processos iterativos. 
- Desenvolvimento e refatorações de códigos demonstrativos em Python com aplicações diversas para fins didáticos.
- Geração de material didático portável (projeto de ensino).
- Integração de ferramentas de _autograding_.
- Programação orientada a objetos para criação de _smart courses_ (módulos para geração de questões customizadas, avaliações e compilações em Latex).
- Desenvolvimento de códigos para paradigmas modernos (métodos informados por física, aprendizado de máquina).
- Métodos numéricos guiados por modelos de linguagem.

## Outros Materiais do Professor

Seguem abaixo links para livros produzidos exclusivamente para outros cursos e disciplinas da UFPB:

- [Introdução à Ciência de Dados](https://gcpeixoto.github.io/DATAVIZ/)
- [Introdução à Visualização de Dados](https://gcpeixoto.github.io/ICD/)
- [Matemática Discreta](https://gcpeixoto.github.io/DISCMATH/)
- [Métodos Computacionais](https://gcpeixoto.github.io/METCOMP/)
