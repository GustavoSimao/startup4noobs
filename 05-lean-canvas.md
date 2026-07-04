# Módulo 5 — Estruturando um Modelo de Negócio (Lean Canvas)

Você já sabe qual problema vai resolver. No Módulo 3, você reuniu evidências desse problema tanto por pesquisa documental quanto por conversas diretas com o mercado, e no Módulo 4 usou o RICE para decidir qual dor merece atenção primeiro. Agora existe uma nova pergunta, mais ampla do que qualquer uma das anteriores: como esse problema se transforma numa estrutura de negócio inteira, com cliente definido, forma de entrega, forma de cobrança e um motivo para não ser facilmente copiado?

O Lean Canvas é uma ferramenta de uma única página criada justamente para responder isso. Ele substitui planos de negócios longos e teóricos por um modelo direto de hipóteses estruturadas, onde cada um dos nove blocos representa uma parte crítica da lógica do negócio.

---

## O Layout do Lean Canvas

Para entender a dinâmica do quadro, veja como os blocos tradicionais são distribuídos visualmente. A numeração representa a ordem lógica recomendada de preenchimento, e essa ordem não é arbitrária: ela começa no Problema e no Segmento de Clientes porque todos os outros sete blocos dependem diretamente dessas duas respostas, e termina na Vantagem Injusta porque esse costuma ser o bloco que você ainda não sabe responder direito no início, e tudo bem que seja o último a amadurecer.


| **1. PROBLEMA** | **4. SOLUÇÃO** | **3. PROPOSTA DE VALOR ÚNICA** | **9. VANTAGEM INJUSTA** | **2. SEGMENTO DE CLIENTES** |
| :--- | :--- | :--- | :--- | :--- |
| Quais são as 3 principais dores que o mercado sente? | Quais são as funcionalidades essenciais que resolvem o problema? | Qual é a sua mensagem clara e direta que explica por que você é diferente? | O que você tem que não pode ser facilmente copiado ou comprado? | Quem é o perfil de cliente ideal que sente essa dor com mais força? |

| | **8. MÉTRICAS-CHAVE** | | **5. CANAIS** | |
| :--- | :--- | :--- | :--- | :--- |
| | Quais números medem o sucesso e o uso do produto? | | Por onde você vai alcançar e vender para o seu cliente? | |

| **7. ESTRUTURA DE CUSTOS** | **6. FONTES DE RECEITA** |
| :--- | :--- |
| Quanto custa para construir e manter o MVP rodando? | Como o negócio vai cobrar e gerar faturamento? |

---

O ponto central do Lean Canvas é a coerência entre os blocos, e essa dependência não se limita ao Problema. O Segmento de Clientes precisa combinar com o Problema descrito. A Solução precisa caber dentro da capacidade desse segmento de adotar algo novo. A Fonte de Receita precisa refletir o que esse mesmo segmento está genuinamente disposto a pagar, não o que seria bom cobrar em teoria. Quando um desses elos quebra, o canvas inteiro perde sustentação, mesmo que cada bloco pareça bem escrito isoladamente.

---

## Exemplo de Quadro Estruturado (Caso de Estudo)

Veja como esse layout se aplica ao problema que estamos acompanhando ao longo do curso, a plataforma de desafios esportivos e socialização.

| **1. PROBLEMA** | **4. SOLUÇÃO** | **3. PROPOSTA DE VALOR ÚNICA** | **9. VANTAGEM INJUSTA** | **2. SEGMENTO DE CLIENTES** |
| :--- | :--- | :--- | :--- | :--- |
| Adultos perderam o contexto social e competitivo que tinham na infância, passando a treinar sozinhos e sem estímulos de comparação, o que reduz a constância e eleva a taxa de desistência nos treinos. | Aplicativo integrado para registro simplificado de treinos, desafios semanais, rankings e **transmissão de lives ao vivo de treinos e corridas** com foco em grupos fechados. | Recriar o contexto social e competitivo da juventude para tornar o exercício diário divertido através de desafios entre amigos, rankings de grupo e forte sentimento de comunidade. | Foco exclusivo na competição social direta e **transmissões ao vivo integradas** entre círculos de amigos já existentes, reduzindo drasticamente a dependência de anúncios tradicionais. | Adultos de 20 a 45 anos com acesso a smartphones que treinam sozinhos em academias, parques ou em casa, mas que possuem histórico de prática esportiva social ou coletiva na juventude. |

| | **8. MÉTRICAS-CHAVE** | | **5. CANAIS** | |
| :--- | :--- | :--- | :--- | :--- |
| | • Usuários ativos semanais (WAU).<br>• Volume de desafios concluídos por grupo.<br>• Minutos de transmissão ao vivo (lives) consumidos. | | • Grupos de corrida e ciclismo ativos.<br>• Comunidades esportivas locais e assessorias de treino.<br>• Mecanismos de indicações orgânicas (*Mouth-to-Ear*). | |

| **7. ESTRUTURA DE CUSTOS** | **6. FONTES DE RECEITA** |
| :--- | :--- |
| Infraestrutura de servidores, banco de dados relacional, consumo de APIs de mapas/biometria, **custo de banda para streaming de vídeo ao vivo**, marketing para aquisição dos usuários iniciais e suporte técnico. | **Modelo Híbrido Combinado:** Receita recorrente via assinaturas premium dos usuários (na faixa de 15 a 30 reais mensais) somada ao patrocínio de desafios pontuais e eventos por marcas esportivas e academias locais. Essa combinação expande o faturamento e usa o fator social para **blindar** o negócio contra a evasão de clientes. |

O Lean Canvas deve ser revisado sempre que aparecer uma inconsistência na estratégia. No mercado de startups em estágio inicial, é comum o processo de pivotar, que consiste em mudar a direção do negócio ao descobrir que uma premissa estava errada. Se durante o curso você notar que um bloco não se conecta com os outros, isso raramente se resolve só reescrevendo aquele bloco, geralmente é sinal de que a premissa por trás dele precisa ser validada de novo, ou substituída. Errar no papel é muito mais barato do que errar no código.

>Nota: não tenha medo de apagar o que você escreveu ontem se hoje você sabe mais do que ontem.



---

## Exercício Prático: Estruture seu Modelo

Agora é sua vez de transformar sua hipótese em estrutura.

Pegue o problema que venceu no RICE (Módulo 4) e crie seu próprio Lean Canvas.

Crie um arquivo chamado `exercicio-modulo-05.md` no seu repositório.

---

## Regras de preenchimento

Ao preencher cada bloco, você deve marcar o nível de validação:

- **[VALIDADO]** → baseado em entrevistas reais ou evidências observadas no Módulo 3  
- **[HIPÓTESE]** → suposição ainda não testada diretamente com o mercado  

Exemplo:
- Segmento de clientes: [HIPÓTESE] adultos que treinam sozinhos...
- Problema: [VALIDADO] observado em entrevistas com praticantes de corrida...

---

>## Atenção
>
>Se você perceber que está preenchendo algum bloco apenas para “não deixar vazio”, pare.
>
>Lean Canvas é uma ferramenta de decisão, não um exercício de preenchimento.
>
>Cada bloco vazio representa uma pergunta que ainda não foi respondida sobre o seu negócio.
> 
>Forçar respostas sem evidência cria uma sensação falsa de clareza e aumenta a chance de decisões baseadas em suposição em vez de respostas validadas.

---

[Próximo módulo ➡️](./06-benchmarking-concorrencial.md)

