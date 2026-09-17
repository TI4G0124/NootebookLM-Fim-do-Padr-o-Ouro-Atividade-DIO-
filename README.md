# Fim do Padrão-Ouro: Miniguia de Estudo com NotebookLM

## Contexto

Este projeto explora o fim do padrão-ouro no contexto do colapso do sistema de Bretton Woods, entre 1971 e 1973.

O estudo foi desenvolvido no NotebookLM com fontes históricas abertas e institucionais. A proposta foi utilizar a IA como ferramenta de aprendizagem ativa: selecionar fontes confiáveis, formular perguntas estratégicas, comparar respostas, registrar limitações e consolidar o aprendizado em um miniguia reutilizável.

Link do NotebookLM: https://notebook.google.com/notebook/e9ba0c96-015d-45ca-8925-5b8625ed943a
Fontes: https://www.federalreservehistory.org/essays/bretton-woods-launched , https://history.state.gov/milestones/1969-1976/nixon-shock , https://www.federalreservehistory.org/essays/gold-convertibility-ends

## Objetivos de Estudo

- Explicar como funcionava o sistema de Bretton Woods.
- Compreender a relação entre dólar, ouro e taxas de câmbio fixas.
- Identificar as causas do enfraquecimento do sistema durante a década de 1960.
- Analisar o Choque de Nixon, anunciado em 15 de agosto de 1971.
- Diferenciar o fechamento da janela do ouro, em 1971, do abandono do regime de câmbio fixo, em 1973.
- Relacionar o fim de Bretton Woods ao funcionamento do sistema monetário fiduciário atual.

## Curadoria de Fontes

As fontes foram escolhidas por serem abertas, institucionais e complementares: uma apresenta o funcionamento do sistema, outra detalha o encerramento da conversibilidade e outra organiza a cronologia política e diplomática.

1. [Federal Reserve History — Launch of the Bretton Woods System](https://www.federalreservehistory.org/essays/bretton-woods-launched)

2. [Federal Reserve History — Nixon Ends Convertibility of U.S. Dollars to Gold and Announces Wage/Price Controls](https://www.federalreservehistory.org/essays/gold-convertibility-ends)

3. [U.S. Department of State, Office of the Historian — Nixon and the End of the Bretton Woods System, 1971–1973](https://history.state.gov/milestones/1969-1976/nixon-shock)

### Registro de troubleshooting

Foram tentadas também duas fontes do FMI, mas o NotebookLM apresentou erro de importação para um PDF e uma página XML. Por esse motivo, essas fontes não foram utilizadas como evidência no miniguia final.

## Perguntas Estratégicas

Durante o estudo, foram priorizadas perguntas que estimulassem relação de causa e consequência, verificação de datas e comparação entre conceitos.

- Como funcionava a conversibilidade do dólar em ouro no sistema Bretton Woods?
- Por que o aumento de dólares no exterior pressionava as reservas de ouro dos Estados Unidos?
- Quais fatores explicam o Choque de Nixon em 1971?
- Por que o fechamento da janela do ouro não significou o fim imediato de Bretton Woods?
- Qual foi o papel do Acordo Smithsonian?
- O que mudou definitivamente em 1973?
- Quais limites existem nas fontes selecionadas?

## Engenharia de Prompts e Cicatrizes

### Variação 1: resumo automático do NotebookLM

**Pergunta implícita:**  
> Qual é a visão geral destas fontes?

**Resultado:**  
O resumo inicial identificou corretamente os elementos principais: sistema de Bretton Woods, déficit externo dos EUA, aumento de dólares em circulação, suspensão da conversibilidade em ouro em 1971 e transição para o câmbio flutuante.

**Limitação identificada:**  
A resposta era útil como introdução, mas não distinguia com precisão o evento de 1971 do desfecho institucional de 1973. Também não apresentava a sequência causal em profundidade.

### Variação 2: prompt estruturado

**Prompt utilizado:**

> Com base exclusivamente nas fontes selecionadas, produza um miniguia de estudo em português sobre o fim do padrão-ouro/Bretton Woods. Estruture em: tese central; linha do tempo 1944, década de 1960, 15/08/1971, dezembro/1971 e 1973; mecanismo causal em 5 etapas; consequências; glossário de 10 termos; 5 perguntas de revisão com respostas curtas. Para cada seção, use citações das fontes. Diferencie explicitamente a suspensão da conversibilidade em 1971 do abandono do regime de câmbio fixo em 1973 e indique incertezas ou limites das fontes.

**Resultado:**  
A resposta apresentou estrutura mais clara, citações vinculadas às fontes, linha do tempo, glossário, perguntas de revisão e limites do material.

### Aprendizados

- Pedir respostas baseadas exclusivamente nas fontes reduz extrapolações da IA.
- Exigir citações facilita a verificação das afirmações.
- Pedir uma distinção explícita entre 1971 e 1973 evita uma simplificação histórica comum.
- A IA deve apoiar a análise, não substituir a leitura crítica das fontes.
- A curadoria precisa considerar perspectivas diferentes: as fontes usadas têm foco institucional norte-americano.

## Miniguia de Estudo

### Tese central

O sistema de Bretton Woods entrou em crise porque a expansão internacional do dólar passou a superar a capacidade dos Estados Unidos de garantir sua conversibilidade em ouro. O acúmulo de dólares fora dos EUA, os déficits na balança de pagamentos, a inflação e a perda de confiança no dólar pressionaram as reservas de ouro americanas.

Em 15 de agosto de 1971, o presidente Richard Nixon suspendeu a conversibilidade do dólar em ouro. Essa decisão encerrou a base monetária do sistema, mas o regime de câmbio fixo ainda foi temporariamente mantido por meio de novas paridades. O abandono definitivo ocorreu em 1973, quando as principais economias passaram a adotar taxas de câmbio flutuantes.

### Linha do tempo

| Período | Evento | Importância |
|---|---|---|
| 1944 | Conferência de Bretton Woods | Criação de um sistema de câmbio fixo, com moedas vinculadas ao dólar e dólar vinculado ao ouro. |
| Década de 1960 | Crescimento dos déficits externos dos EUA | A quantidade de dólares no exterior aumentou e passou a pressionar as reservas de ouro. |
| 15 de agosto de 1971 | Choque de Nixon | Suspensão da conversibilidade do dólar em ouro, congelamento temporário de salários e preços e sobretaxa sobre importações. |
| Dezembro de 1971 | Acordo Smithsonian | Tentativa de reorganizar paridades fixas e preservar temporariamente o sistema. |
| Março de 1973 | Flutuação das moedas | Abandono prático do regime de câmbio fixo de Bretton Woods. |

### Mecanismo causal em cinco etapas

1. **Expansão de dólares no exterior**  
   Gastos militares, investimentos e ajuda externa dos EUA aumentaram a circulação internacional de dólares.

2. **Perda de confiança na conversibilidade**  
   Bancos centrais estrangeiros acumulavam dólares que poderiam ser convertidos em ouro, enquanto as reservas americanas eram limitadas.

3. **Inflação e pressões especulativas**  
   A política monetária expansionista dos EUA e a inflação aumentaram a desconfiança sobre a paridade de US$ 35 por onça de ouro.

4. **Fechamento da janela do ouro em 1971**  
   Nixon suspendeu a conversibilidade para proteger as reservas americanas e conter a crise cambial.

5. **Fracasso do Acordo Smithsonian e câmbio flutuante**  
   As novas paridades não resistiram às pressões de mercado; em 1973, o sistema de taxas fixas foi abandonado.

### 1971 não é igual a 1973

- **1971:** os EUA suspenderam a conversibilidade do dólar em ouro. O padrão dólar-ouro foi rompido.
- **1973:** o regime de paridades cambiais fixas foi abandonado pelas principais economias, consolidando o câmbio flutuante.

Essa diferença é essencial: o sistema não acabou em um único dia; ele se desintegrou em etapas.

### Consequências

- Transição das principais moedas para regimes de câmbio flutuante.
- Consolidação do sistema monetário fiduciário, sem conversibilidade oficial em ouro.
- Maior volatilidade cambial.
- Persistência de pressões inflacionárias durante a década de 1970.
- Mudança no papel do dólar: deixou de ser conversível em ouro, mas permaneceu como principal moeda de reserva internacional.

## Glossário

| Termo | Definição |
|---|---|
| Bretton Woods | Sistema monetário internacional criado em 1944, baseado em taxas de câmbio fixas ajustáveis. |
| Padrão-ouro | Sistema em que a moeda possui valor definido ou conversível em ouro. |
| Janela do ouro | Mecanismo pelo qual autoridades estrangeiras podiam converter dólares em ouro nos EUA. |
| Conversibilidade | Possibilidade de trocar uma moeda por outro ativo ou moeda sob condições definidas. |
| Choque de Nixon | Conjunto de medidas econômicas anunciadas por Richard Nixon em agosto de 1971. |
| Acordo Smithsonian | Tentativa de reorganizar as taxas fixas de câmbio após o Choque de Nixon. |
| Câmbio fixo | Regime em que o valor de uma moeda é vinculado a outra moeda ou ativo. |
| Câmbio flutuante | Regime em que o valor da moeda varia conforme oferta e demanda. |
| Dilema de Triffin | Contradição entre fornecer liquidez internacional e preservar a confiança na moeda de reserva. |
| Moeda fiduciária | Moeda sem lastro em uma mercadoria, baseada na confiança e na autoridade do emissor. |

## Perguntas de Revisão

1. Qual era a paridade oficial do dólar em ouro no sistema Bretton Woods?  
   **Resposta:** US$ 35 por onça de ouro.

2. Por que o excesso de dólares no exterior enfraquecia o sistema?  
   **Resposta:** Porque aumentava a possibilidade de conversão dos dólares em ouro, pressionando as reservas americanas.

3. O que foi o Choque de Nixon?  
   **Resposta:** A decisão de suspender a conversibilidade do dólar em ouro, acompanhada de medidas internas de controle econômico e sobretaxa sobre importações.

4. O Acordo Smithsonian restaurou Bretton Woods de forma definitiva?  
   **Resposta:** Não. Foi uma tentativa temporária de reorganizar as paridades fixas.

5. O que ocorreu em 1973?  
   **Resposta:** O sistema de câmbio fixo foi abandonado e as principais moedas passaram a flutuar frente ao dólar.

## Prompts Reutilizáveis

```text
Explique [tema] em cinco etapas causais, citando somente as fontes selecionadas.
Crie uma linha do tempo de [tema] com data, evento, causa e consequência. Cite cada item.
Compare [conceito A] e [conceito B] em uma tabela com definição, mecanismo, exemplo histórico e limite.
Monte dez flashcards sobre [tema], com pergunta, resposta curta e referência à fonte.
Crie um simulado com cinco questões discursivas sobre [tema]. Aguarde minhas respostas e corrija usando apenas as fontes selecionadas.
Aponte o que as fontes não permitem concluir sobre [tema] e indique quais evidências adicionais seriam necessárias.
