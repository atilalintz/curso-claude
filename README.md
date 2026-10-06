# Curso: Aprendendo o Claude na prática

Curso curto e prático para quem **nunca usou o Claude** (da Anthropic). Pouco conceito, muito exercício. Começa pelo **Dia 1**.

## Público-alvo

Iniciantes, sem exigir conhecimento técnico. A base é o **plano gratuito**; quando um recurso depender de plano pago, a aula avisa.

## Como o curso é entregue

- **Site** com as aulas
- **Apostila** para baixar (gerada a partir dos arquivos deste repositório)
- **Este repositório**, que é a fonte única do material (aulas em Markdown)

## Padrão de cada aula

Objetivo · tempo estimado · passo a passo prático · exercício · critério para o aluno saber que acertou.

## Glossário (termos fixos)

- **Conversa**: cada diálogo com o Claude. "Chat" é a mesma coisa; usamos sempre "conversa".

## Dia 1: esqueleto e decisões

Duração total prevista: 80 minutos.

| # | Passo | Tempo | Situação |
|---|-------|-------|----------|
| 1 | Configurar o ambiente (idioma, tom e nível) | 10 min | Aula escrita |
| 2 | Pedir bem: pedido vago vs. pedido claro | 20 min | Aula escrita |
| 3 | Anexar arquivos e pedir uma revisão | 15 min | Desenho fechado |
| 4 | Gerar algo de verdade com Artifacts e ajustar em 2 ou 3 pedidos | 20 min | Desenho fechado |
| 5 | Revisar e aprender: pedir que o Claude explique o que fez e conferir o resultado | 10 min | Desenho fechado |
| 6 | Fechamento: guardar o que produziu em uma pasta e anotar o que aprendeu (Git opcional) | 5 min | Desenho fechado |

### Decisões já tomadas

- **Passo 1:** a configuração vem primeiro, e o **idioma** é o primeiro item. O aluno escreve as preferências **com as próprias palavras** (com um modelo para guiar), e a aula avisa que o Claude pode ajudar a escrevê-las. A criação de arquivos também é ligada aqui, porque os passos 3 e 4 dependem dela.
  - *Critério de acerto (proposta, a confirmar):* o aluno abre uma conversa nova, escreve "oi" e recebe resposta em português, no tom que pediu.
- **Passo 2:** o pedido é **fixo e igual para todos**: um e-mail pedindo folga. O aluno abre **duas conversas novas e separadas** (a separação evita que o primeiro pedido influencie o segundo): primeiro o pedido vago, depois o pedido claro (com destinatário, motivo, datas, tom e tamanho). Ele compara as respostas e **descobre sozinho** o que mudou, guiado por perguntas (por exemplo: "qual resposta você poderia enviar sem mudar nada?"). Só depois a apostila nomeia os elementos de um bom pedido: contexto, objetivo, restrições e formato.
  - *Textos fixos (aprovados):* pedido vago: "Escreva um e-mail pedindo folga." Pedido claro: "Escreva um e-mail para o meu chefe, o Carlos, pedindo folga nos dias 14 e 15 de dezembro, para resolver um assunto pessoal. O tom deve ser educado e formal. Use no máximo 5 linhas, inclua uma linha de assunto e termine agradecendo."
  - *Critério de acerto (proposta, a confirmar):* o aluno consegue dizer, com as próprias palavras, pelo menos dois elementos do pedido claro que melhoraram a resposta.
- **Passo 3:** o aluno escolhe um assunto de que gosta, o Claude cria um arquivo curto com erros de propósito, e o aluno anexa o arquivo de volta e pede uma revisão. O exercício com **código de programação fica fora do Dia 1** (aula futura, "Claude para quem programa").
  - *Critério de acerto (proposta, a confirmar):* o Claude listou ao menos 3 problemas e o aluno consegue explicar um deles com as próprias palavras.
- **Passo 4:** o aluno escolhe entre **3 ideias simples** listadas na apostila (por exemplo: divisão de conta, conversor de medidas culinárias, quiz). Todas funcionam **sem guardar dados**, para que ninguém peça algo que o plano gratuito não permite. O aluno faz 2 ou 3 pedidos de ajuste.
  - *Critério de acerto:* o resultado mudou conforme os pedidos de ajuste.
- **Passo 5:** além de pedir ao Claude uma **explicação em linguagem simples** do que ele fez, o aluno **confere** o resultado: testa o artifact com um caso de resposta conhecida (por exemplo, 100 dividido por 4 dá 25) e aprende a pedir ao Claude que aponte onde pode ter errado. A mensagem central: o Claude pode errar, e quem confere é você.
  - *Critério de acerto:* o aluno testou com um caso conhecido e consegue dizer se o resultado estava certo.
- **Passo 6:** dois níveis. **Para todos:** guardar os arquivos do dia (o texto do passo 3, o artifact, as respostas de que gostou) em uma pasta no computador, com um arquivo de anotações do que aprendeu. **Opcional:** Git, para quem quiser ir além.

## Confirmado na documentação oficial

- Artifacts estão disponíveis nos planos Free, Pro, Max, Team e Enterprise, mas exigem que a execução de código e a criação de arquivos estejam ligadas em Configurações > Capacidades.
- O armazenamento persistente de artifacts é só dos planos Pro, Max, Team e Enterprise (não do gratuito).
- O idioma da tela se muda pelo ícone do perfil, no canto inferior esquerdo, em "Idioma" (web e desktop). Português do Brasil está entre os idiomas aceitos, e o Claude responde na língua que o aluno usar.
- O modo de voz tem um ajuste de idioma separado.

## Pendências de verificação

Nada abaixo entra na apostila antes de confirmado na documentação oficial ou em teste real:

- [ ] Preferências de perfil no plano gratuito (a documentação oficial não deixa claro)
- [ ] Projetos no plano gratuito (a documentação se contradiz: uma versão diz só pagos, outra diz até cinco gratuitos)
- [ ] Criação de arquivos e Artifacts: testar em conta gratuita de verdade (a documentação diz que o botão precisa estar ligado em Configurações > Capacidades)
- [ ] Passos de configuração no celular (a documentação de idioma cobre só web e desktop)
- [ ] Confirmar os critérios de acerto dos passos 1, 2 e 3 (hoje são propostas)
- [ ] Definir o formato do Git opcional do passo 6 (extra do Dia 1 ou aula futura)
- [ ] Escolher as 3 ideias de artifact do passo 4

## Próximos passos

1. Escrever as aulas restantes do Dia 1 em Markdown, uma por passo (passos 1 e 2 já escritos, em `aula-01/`), seguindo o padrão de cada aula
2. Testar as pendências em uma conta gratuita
3. Montar o site e gerar a apostila
