# Módulo 7 — Construindo o Primeiro MVP

Com o benchmark em mãos, chegamos ao ponto de execução. A tentação natural de um desenvolvedor é abrir o editor de código e listar funcionalidades: sistemas de login complexos, perfis detalhados com upload de imagem e microsserviços de notificação.

No entanto, nenhuma dessas ferramentas testa a hipótese mais importante primeiro: qual é a única suposição que, se for falsa, derruba todo o resto do negócio? Antes de escrever uma linha de código, você precisa isolar essa hipótese central, geralmente relacionada a um comportamento humano que você está apostando que vai acontecer, e testá-la da forma mais barata e rápida possível. Se essa premissa for falsa, nenhuma arquitetura limpa ou interface bonita salvará o produto.

**No nosso caso, a hipótese central é direta:** os usuários voltam a se exercitar com mais constância quando existe um componente social e competitivo? Se isso for falso, todo o resto (perfis, notificações, gamificação) é irrelevante.

---

## Pensando no Menor Experimento Possível

Antes de construir qualquer código, desenhe uma validação manual, simples e trabalhosa. O objetivo do MVP (*Minimum Viable Product*) não é ser escalável, é ser um ambiente de aprendizado rápido.

Para testar essa hipótese, o MVP inicial não precisa de um app na Google Play ou App Store. Ele pode ser apenas:

1. Um grupo fechado no **WhatsApp** com 15 pessoas do segmento-alvo.
2. Uma planilha do **Google Sheets** compartilhada, atualizada manualmente por você ao final do dia com os treinos que a galera mandou no grupo, gerando um ranking semanal.

Se esse experimento manual, que levou 20 minutos para ser configurado, gerar engajamento, conversas no grupo e disputa, a hipótese de negócio está validada. Só então faz sentido automatizar o processo criando o produto de software real.

---

## Perspectiva de Mercado: E se meu foco for B2B ou Consultoria?

Se a sua ideia de negócio está mapeada para resolver dores de Pequenas e Médias Empresas (PMEs), a lógica do MVP permanece idêntica.

Imagine que você identificou que líderes de operação perdem horas na triagem manual de relatórios operacionais. Grandes fintechs resolvem isso com automações preditivas e dashboards complexos de IA. Em vez de desenvolver um software caro e demorado agora, você desenha um MVP manual: cria formulários gratuitos (Google Forms) integrados a uma planilha para consolidar as informações em um único painel que você mesmo alimenta.

Isso resolve a dor de tempo do cliente imediatamente, valida se os gerentes realmente consumiriam esses dados diariamente e blinda o caixa da sua startup contra o desperdício de recursos de desenvolvimento.

---

## Quando o Código Faz Parte da Hipótese

O princípio deste módulo não é "nunca escreva código para validar uma ideia". Em alguns produtos, a tecnologia faz parte da própria hipótese e, portanto, é impossível validá-la sem desenvolvimento.

Imagine um aplicativo que utiliza visão computacional para contar repetições de exercícios automaticamente. A principal dúvida não é se as pessoas fariam exercícios, mas se a tecnologia consegue identificar os movimentos com precisão suficiente para gerar valor. Nesse caso, será necessário desenvolver um protótipo técnico para testar essa hipótese.

O mesmo vale para produtos baseados em inteligência artificial, algoritmos de recomendação, processamento de imagens, criptografia ou qualquer solução cujo diferencial dependa diretamente da tecnologia.

Mesmo nesses cenários, o princípio continua o mesmo: desenvolva apenas o mínimo necessário para responder à principal incerteza do produto. Se a hipótese é que o algoritmo funciona, construa apenas o algoritmo. Se a hipótese é que as pessoas querem usar a solução, valide primeiro o comportamento antes de investir em funcionalidades como autenticação, notificações, perfis completos ou infraestrutura de produção.

Antes de começar a desenvolver, faça sempre uma última pergunta:

> **O que exatamente estou tentando validar com este código?**

Se você não consegue responder essa pergunta com clareza, provavelmente ainda está construindo funcionalidades antes da hora.

---

## Quando Começar a Desenvolver?

Uma dúvida comum é em que momento parar de validar e começar a programar. A resposta é simples: quando o código passa a resolver um problema do experimento, e não apenas uma vontade de construir.

Enquanto você ainda está tentando descobrir se as pessoas realmente têm aquela dor, se elas se importam com a solução e se voltariam a utilizá-la, escrever software dificilmente acelera o aprendizado. Na maioria das vezes, ele apenas aumenta o custo e o tempo investidos em uma hipótese que ainda pode estar errada.

O desenvolvimento começa a fazer sentido quando o processo manual deixa de ser suficiente. Se você já validou que existe interesse, as pessoas estão utilizando a solução de forma consistente e a operação manual começa a consumir tempo, gerar erros ou limitar o crescimento do experimento, a automação passa a ser o próximo passo natural.

Em outras palavras, **o primeiro código do seu produto não deve servir para validar uma hipótese, mas para escalar uma hipótese que já demonstrou sinais concretos de funcionar.** Até esse momento, seu maior objetivo não é desenvolver mais rápido, e sim aprender mais rápido.

---

## Exercício Prático: O Experimento Sem Código

Chegou a hora de definir o MVP do seu projeto. Você vai desenhar um teste que possa ser executado sem abrir o editor de código.

Crie o arquivo `exercicio-modulo-07.md` no seu repositório de acompanhamento e estruture os seguintes pontos:

### Passo 1: Declare sua Hipótese Central

Escreva a afirmação principal do seu negócio em uma única frase, utilizando obrigatoriamente o formato abaixo:

> **"Acreditamos que** `[Segmento de Clientes]` **vai** `[Comportamento Esperado]` **quando** `[Condição/Solução Manual]`**.**

**Exemplo:**

> Acreditamos que **adultos que treinam sozinhos** vão **fazer 3 ou mais treinos por semana** quando **estiverem competindo em um ranking manual via WhatsApp com seus amigos**.

### Passo 2: Desenhe o Experimento Manual

Descreva, em até 5 linhas, como você vai testar essa hipótese usando ferramentas gratuitas e processos manuais (WhatsApp, Planilhas, Notion, Formulários, Instagram etc.).

> **Lembre-se:** proibido codar aqui.

### Passo 3: Defina a Métrica de Sucesso (Critério de Parada)

Qual é o número mínimo que prova que as pessoas realmente se importam com a sua solução?

**Exemplo:**

> Pelo menos 60% das pessoas do grupo atualizarem seus treinos por duas semanas seguidas.

---

[Próximo módulo ➡️](./08-pitch-perfeito.md)
