## Pensamento computacional:computer:

###### Professora: Juliana Mascarenhas

[Material de apoio](https://drive.google.com/file/d/1vemC6G790JNte1882V53DAKEawJzVIWL/view)

O pensamento computacional é o processo, uma estratégia para achar soluções e resolver problemas, de maneira que sejam capazes de resolver tanto Humanos quanto máquinas, de forma eficiente.

E  é baseado em <strong>4 pilares </strong>:

- **Decomposição** - Dividir um problema complexo, em subproblemas.

  > Exemplo: Definir componentes e etapas = desenvolvimento mais eficiente.

  Na decomposição possuem duas ordens para a execução de tarefas: <strong> sequêncial e paralelo </strong>.

  - *Sequencial* - executadas em filas, dependência entre tarefas.
  - *Paralelo* - podem ser executadas concomitantemente, + eficiência - tempo.

  ###### Como decompor?

  Identificar ou coletar dados :arrow_right:agregar dados :arrow_right: Funcionalidade.

  

- **Reconhecimento de padrões** - Identificar padrões ou tendências. Usa da similaridades e diferença. O intuito é generalizar, com objetivo de obter resoluções para problemas diferentes.

  > Exemplo de aplicações: Inteligência artificial, reconhecimento de imagens, classificação de documentos... 

- **Abstração** - Extrapolar o conceito do problema para uma forma generalista. Você cria um modelo para determinar como funciona algo que não é concreto.

  ###### Como classificar os dados?

  - Características

  - Pontos essenciais

  - Generalizar x detalhar

    ![](C:\Users\Gabriela\Documents\Capturar.JPG)

  > Exemplo: Busca binária, linguagens de programação.

- **Algoritmos** - Sequência de passos com objetivos definidos.  Definir passo a passo a solução do problema. Precisa de instruções detalhadas e não opera sozinha.

  ```mermaid
  graph LR 
  A[o que precisa ser feito] -->   C
  B[Qual a ordem de execução] -->  C
  C[Instruções]
  
  ```

  

  As <strong>intruções</strong> necessitam que sejam entendidas simultaneamente por <strong>humano e máquina</strong>.

  **COMO CONSTRUIR UM ALGORITIMO?**
  Compreensão do problema = pontos mais importantes;

  Definição dados de entrada = dados fornecidos e cenários;

  Definir processamento = cálculos e restrições;

  Definir dados de saída = após processamento;

  Método de construção e refinamento.

  Testes e diagnósticos.

   ```mermaid
   graph LR
   C[Narrativa] --> |diversas interpretaçõespossíveis| D
   B[Fluxograma] --> |conhecimento prévio da estrutura e símbolos| D
   A[Pseudocódigo] --> |Portugol| D
   
   ```

  

  ## Habilidades complementares para o pensamento computacional 

  **Raciocínio Lógico**

  É uma forma que permite encontrar a conclusão ou determinar a resolução de um problema.

  ```mermaid
  graph TD
      C[Raciocínio lógico / Classificação]
      C -->|Indução| D[Leis e teorias - ciências experimentais]
      C -->|Dedução| E[Leis e teorias - ciências exatas]
      C -->|Abdução| F[Conclusão/ Premissa ]
      D --> G
      E --> G
      G[Sintética]
      F --> H
      H[Analítica]
  ```

  

  ------

  

  #### APERFEIÇOAMENTO 

  A partir de uma solução, determinar pontos de melhora e refinamento. O ato de aperfeiçoar <strong>otimiza processos, encontra o melhor uso para recursos</strong> e <strong>define funções, auxilia na melhoria dos códigos e algoritmos.</strong>

  ------

  

  # Lógica de programação

######        Seres humanos podem prever comportamentos, computadores não.

​       Por isso, são necessárias instruções detalhadas.

**Técnica Linear**

- Modelo tradicional
- Execução sequenciada
- Recursos limitados
- Única dimensão

Ex.: Acordar :arrow_right: Fazer Café :arrow_right:Tomar café

**Técnica Estruturada**

Processamento de dados.

- Escrita ( programas)
- Entendimento
- Validação
- Manutenção ( intuito de tornar mais fácil)

Ex.: Acordar :arrow_right: Fazer o café ou fazer um suco :arrow_right:Tomar café

**Técnica Modular**

Partes independentes, controlada por um conjunto de regras.

<strong>Metas</strong> : 

- Simplificação
- Decompor problema
- Verificação do módulo

Ex.: Módulo preparar acordar :arrow_right:Módulo preparar bebida :arrow_right:Módulo tomar café.

Considerando que cada módulo possui suas regras independentes, para a solução do mesmo problema final: Tomar café.



# TIPOLOGIAS E VARIÁVEIS

#### Variáveis

**Qual a função do computador?**

Informação = Dados e instruções.

Sendo que:

**Dados** - Tratados e processados ( numéricos, caracteres, lógicos).

-  Numéricos: Inteiros ou reais.
- Caracteres: Tudo que não é numérico( letras, símbolos)
- Lógico: Verdadeiro ou Falso

**E o que é uma variável?**

Que pode assumir qualquer um dos valores de um determinado conjunto de valores.

Para isso existem **regras**:

- Atribuição de um ou mais caracteres 
- Primeira letra - não número
- Sem espaços em branco
- vedado a utilização de palavras reservadas.
- Caracteres e números.

E a **variável constante**? É a variável invariável, que não muda.

### Estruturas de repetição :repeat:

Trecho de um programa que segue um loop, malhas de repetição.

**Condições de parada**:

- Número de repetições pré-fixada
- Condição a ser satisfeita.

**Mas não é só repetir o código**? - Com as estruturas de repetição, auxilia na redução de linhas, compreensão facilitada e redução de erro.

Exemplo:

![](C:\Users\Gabriela\Documents\Capturar.JPG)

## Vetores e Matrizes

-  Coleção de variáveis

- Contiguas em memória

- Índices

  Operações: Definição, Atribuição e Leitura.

## Entrada/Saídas

Dados ( quais tipos e como inserir ) :arrow_right: <strong>Processamento</strong> :arrow_right: Resultado(como exibir meu resultado)

Arquivos: Arquivos de acesso ao usuário - Log do sistema

Dispositivos de saída: Híbrido.

**Existem dois tipos de saída**

-  Saída programada: Condicional e Incondicional
  - Condicional: aguarda o dispositivo.
- Saída periférica: definida pelos periféricos.

**Saída na programação** :arrow_right: **código**

# COMO O COMPUTADOR ENTENDE O PROGRAMA :computer:



Um programa é um amontoado de palavras senão for possível que o computador entenda.

Programa Fonte ( linguagem de alto nível) :arrow_right:Compilador :arrow_right: Programa objeto(Assembly)

**TRADUÇÃO** 

Execução mais rápida, programas menores.

1. Geração do programa objeto
2. Execução do programa objeto

Ex.: C++, Java

**INTERPRETAÇÃO**

Maior flexibilidade.

Programa fonte executado diretamente.

Ex.: JavaScript, Ruby

#### Para o desenvolvimento de programas é importante:

1. Legibilidade - Facilidade de leitura, coerência das informações, definição adequada das estruturas.

2. Redigibilidade - Simplicidade da escrita, suporte à abstração, reuso do código.

3. Confiabilidade - Verificação de tipos, trata excessões, uso de ponteiros, **faz o que foi programado para fazer**

4. Custo - Treinamento, codificação, compilação, execução, infra-estrutura.

   

