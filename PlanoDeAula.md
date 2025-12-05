# Plano de Aula

## Preparação do ambiente
Para preparar o ambiente para fazer uma aula com o labirinto é necessário realizar os seguintes passos:
- Na máquina que será utilizada, instale o projeto pelo github em formato zip;
- Extraia o arquivo instalado e entre na pasta do projeto;
- Abra o arquivo `.html` com o navegador de preferência.
Será necessário seguir estes passos em todas as maquinas aonde o labirinto será jogado


## Desenvolvimento Metodológico
A aula será conduzida utilizando uma abordagem ativa, onde os alunos aprendem conceitos de programação resolvendo os desafios propostos pelo software "Labirinto". A aula será dividida em três etapas:

### 1. Introdução e Contextualização (10 min)
* **Apresentação:** O professor introduzirá brevemente o conceito de **Algoritmo** como uma sequência de passos para resolver um problema.
* **Demonstração:** Utilizando um projetor, o professor demonstrará a interface do jogo, identificando a *Área do Labirinto* (onde a execução ocorre) e a *Área de Montagem* (onde os blocos lógicos são encaixados).
* **Exploração Inicial:** Os alunos serão instruídos a abrir o arquivo `.html` e observar a introdução ao labirinto, onde o jogo explica como o comando deve ser executado, reforçando a explicação do professor.

### 2. Prática Progressiva (30 - 35 min)
Os alunos avançarão pelos níveis do jogo, que estão estruturados para introduzir conceitos de forma incremental:

* **Sequenciamento (Níveis 1 e 2):**
    * **Atividade:** Os alunos devem guiar o personagem utilizando comandos sequenciais simples (`Avançar`, `Virar`).
    * **Objetivo:** Compreender a lógica de passo-a-passo e lateralidade (esquerda/direita).

* **Repetição / Loops (Níveis 3 e 4):**
    * **Conceito:** Introdução do bloco `Repetir até chegar em 🟩`.
    * **Atividade:** Os alunos enfrentarão corredores longos ou padrões de escada onde o uso de múltiplos blocos individuais seria ineficiente.
    * **Objetivo:** Entender como automatizar tarefas repetitivas e otimizar o código.

* **Condicionais (Níveis 5, 6 e 7):**
    * **Conceito:** Introdução dos blocos `Se caminho...` e `Se caminho... Se não`.
    * **Atividade:** Os níveis apresentarão armadilhas e bifurcações onde o personagem precisa "decidir" o caminho correto de forma autonoma, baseado em sensores, sem que o aluno saiba previamente o caminho exato ou seguro apenas olhando.
    * **Objetivo:** Desenvolver a lógica de tomada de decisão dinâmica.

### 3. Discussão e Encerramento (5 - 10 min)
* **Debate:** O professor mediará uma breve discussão sobre as soluções encontradas.
* **Perguntas guiadas:**
    * "Como o bloco de repetição facilitou a resolução da fase da escada?"
    * "Como o uso dos blocos de condição mudam o jeito que você pensa na solução?"
* **Conclusão:** Recapitulação de como computadores utilizam essas estruturas (Loops e Condicionais) para processar dados no dia a dia.


## Avaliação
A avaliação será contínua e formativa, focada no processo de aprendizagem e não apenas no resultado final. O professor observará o desempenho dos alunos com base nos seguintes critérios:

* **Aplicação de Conceitos:** Verificar se o aluno conseguiu substituir sequências longas por **Repetições** (Loops) e se utilizou **Condicionais** (Se/Senão) para resolver labirintos com caminhos variáveis.
* **Capacidade de Depuração (Debugging):** Avaliar como o aluno reage ao erro (ex: quando o personagem bate na parede ou cai na armadilha). O aluno consegue reler seu código, identificar a falha e corrigir?
* **Autonomia e Leitura:** Observar se o aluno interagiu com o botão de dica "?" se estava preso na fase e consultou o botão "Bloco Novo" para compreender as novas mecânicas sem depender exclusivamente do professor.
* **Conclusão dos Níveis:** Êxito na finalização dos desafios propostos, demonstrando domínio da lógica exigida para cada fase.