# Módulo 4 — Priorizando Problemas (RICE)

Se você seguiu o exercício do módulo anterior, provavelmente terminou com três a cinco problemas validados. Todos parecem reais e incomodam alguém, e é exatamente aí que mora a próxima armadilha. Um empreendedor iniciante costuma tentar resolver todos ao mesmo tempo. O resultado, quase sempre, é não resolver nenhum deles direito. Antes de escrever qualquer linha de código, é preciso escolher — e escolher bem exige um critério, não um palpite.

---

## O Framework RICE

Nota de contexto: no mercado tradicional de tecnologia, o RICE foi criado pela Intercom e é amplamente utilizado por gerentes de produto para priorizar features e tarefas dentro do backlog de desenvolvimento de um único produto. Aqui, faremos uma inversão estratégica desse framework: usaremos a mesma lógica para priorizar dores e problemas reais de mercado, garantindo que você foque seus esforços na dor que mais gera valor antes mesmo de começar a codar.

O RICE é uma sigla para quatro perguntas fundamentais:

**Reach (Alcance):** quantas pessoas esse problema atinge em um determinado período? Não é opinião, é estimativa de volume.

**Impact (Impacto):** quando o problema é resolvido, o quanto isso altera o dia a dia de quem vive ele? Impacto alto muda comportamento. Impacto baixo apenas reduz incômodo.

**Confidence (Confiança):** o quanto você confia nas suas estimativas? Se você conversou com pessoas que vivem a dor e encontrou padrão consistente, a confiança sobe. Se é suposição, ela cai — mesmo que a ideia pareça boa.

**Effort (Esforço):** quanto esforço seria necessário para validar a hipótese com o menor experimento possível. Aqui não estamos falando de produto completo, mas de teste inicial.

A fórmula:

RICE = (Reach × Impact × Confidence) / Effort

Quanto maior o resultado, maior a prioridade de teste daquela hipótese.

---

## Nota metodológica importante

O RICE não define “a melhor ideia de negócio”. Ele define apenas **qual hipótese deve ser testada primeiro com os recursos atuais**.

Um problema com pontuação menor pode ser extremamente valioso no futuro. Ele só não é prioridade agora dentro do seu contexto de aprendizado e validação.

---

## Moldando o alcance de forma estratégica

A forma como você descreve o problema altera diretamente o Reach.

- “Um grupo de amigos de um bairro sente falta de treinar junto” → alcance local e pequeno
- “Adultos que treinavam socialmente na infância hoje treinam sozinhos sem competição” → alcance massivo e comportamental

Essa diferença muda completamente a priorização.

### Exemplo prático

| Descrição do problema | Reach | Impact | Confidence | Effort | RICE |
|----------------------|------:|-------:|-----------:|-------:|-----:|
| grupo de amigos local | 2 | 7 | 8 | 3 | 37,3 |
| adultos treinando sozinhos | 8 | 7 | 6 | 3 | 112 |

Mesmo problema, escalas diferentes, resultado completamente diferente.

---

## O RICE também compara mercados diferentes

Aqui o framework começa a ser usado de forma mais estratégica.

Você pode ter problemas de naturezas completamente diferentes:

- **B2C:** aplicativo de atividades físicas para adultos que treinam sozinhos  
- **B2B:** automação de processos gerenciais médicos em clínicas pequenas

Esses dois problemas não competem pelo mesmo tipo de usuário, mas competem pelo seu tempo de execução.

### Comparação entre mercados

| Problema validado | Reach | Impact | Confidence | Effort | RICE |
|------------------|------:|-------:|-----------:|-------:|-----:|
| app de atividades físicas (B2C) | 8 | 7 | 6 | 3 | 112 |
| automação de processos médicos (B2B) | 3 | 9 | 7 | 4 | 47,3 |

Aqui entra um ponto importante: B2B costuma parecer “mais sério”, mas isso não significa prioridade automática.

O RICE força você a confrontar isso com números.

- B2B tende a ter maior impacto por cliente
- B2C tende a ter muito mais alcance

Nenhum é melhor por padrão. O contexto define.

---

## Aplicando o RICE

Pegue os problemas validados no módulo anterior e monte uma tabela simples. Para cada um, estime:

- Reach (1 a 10)
- Impact (1 a 10)
- Confidence (1 a 10)
- Effort (1 a 10, onde 10 = maior esforço de validação)

Depois calcule:

RICE = (Reach × Impact × Confidence) / Effort

---

## Exercício

Monte uma tabela com os problemas validados no Módulo 3.

Para cada problema:

1. Atribua notas de 1 a 10 para Reach, Impact, Confidence e Effort  
2. Calcule o RICE final  
3. Justifique em poucas linhas qual problema deve ser testado primeiro e por quê

Esse problema será a base do próximo módulo.

---

[Próximo módulo ➡️](./05-lean-canvasl.md)
