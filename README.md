# Curso: Aprendendo o Claude na prática

Curso curto e prático para quem **nunca usou o Claude** (da Anthropic). Pouco conceito, muito exercício. Cada dia tem 6 passos e 80 minutos. Já estão escritos o **Dia 1** e o **Dia 2**.

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

## Pastas do aluno no computador

O aluno guarda o que produz em uma pasta **`Curso de Claude`**, com uma subpasta por dia: **`Dia-01`**, **`Dia-02`**, **`Dia-03`** e assim por diante. No repositório, as aulas ficam em `aula-01`, `aula-02` etc.

## Arquivos do repositório

- `README.md`: este arquivo (visão geral, decisões e pendências)
- `aula-01/01-configurar-ambiente.md`
- `aula-01/02-pedir-bem.md`
- `aula-01/03-anexar-arquivos.md`
- `aula-01/04-criar-com-artifacts.md`
- `aula-01/05-revisar-e-aprender.md`
- `aula-01/06-fechamento-dia-01.md`
- `aula-02/01-resumir-documento.md`
- `aula-02/02-perguntar-e-conferir.md`
- `aula-02/03-extrair-e-reorganizar.md`
- `aula-02/04-pesquisar-na-internet.md`
- `aula-02/05-documento-final.md`
- `aula-02/06-fechamento-dia-02.md`
- `aula-02/ata-reuniao-cafe-girassol.pdf`: ata fictícia usada nos passos 1 a 3 e 5 do Dia 2

As aulas de fechamento seguem o padrão `06-fechamento-dia-NN.md` (por exemplo, `06-fechamento-dia-03.md` no Dia 3), para o nome ser diferente em cada dia.

## Dia 1: passos e decisões

Duração total prevista: 80 minutos.

| # | Passo | Tempo | Situação |
|---|-------|-------|----------|
| 1 | Configurar o ambiente (idioma, tom e nível) | 10 min | Aula escrita |
| 2 | Pedir bem: pedido vago vs. pedido claro | 20 min | Aula escrita |
| 3 | Anexar arquivos e pedir uma revisão | 15 min | Aula escrita |
| 4 | Gerar algo de verdade com Artifacts e ajustar em 2 ou 3 pedidos | 20 min | Aula escrita |
| 5 | Revisar e aprender: pedir que o Claude explique o que fez e conferir o resultado | 10 min | Aula escrita |
| 6 | Fechamento: guardar o que produziu em uma pasta e anotar o que aprendeu | 5 min | Aula escrita |

### Decisões já tomadas

- **Passo 1:** a configuração vem primeiro, e o **idioma** é o primeiro item. O aluno escreve as preferências **com as próprias palavras** (com um modelo de 4 perguntas para guiar: idioma, tom, nível e tamanho/formato, mais uma dica opcional sobre o que evitar), e a aula avisa que o Claude pode ajudar a escrevê-las. A criação de arquivos também é conferida aqui, porque os passos 3 e 4 dependem dela.
  - *Critério de acerto (proposta, a confirmar):* o aluno abre uma conversa nova, escreve "oi" e recebe resposta em português, no tom que pediu.
- **Passo 2:** o pedido é **fixo e igual para todos**: um e-mail pedindo folga. O aluno abre **duas conversas novas e separadas** (a separação evita que o primeiro pedido influencie o segundo): primeiro o pedido vago, depois o pedido claro (com destinatário, motivo, datas, tom e tamanho). Ele compara as respostas e **descobre sozinho** o que mudou, guiado por perguntas (por exemplo: "qual resposta você poderia enviar sem mudar nada?"). Só depois a apostila nomeia os elementos de um bom pedido: contexto, objetivo, restrições e formato.
  - *Textos fixos (aprovados):* pedido vago: "Escreva um e-mail pedindo folga." Pedido claro: "Escreva um e-mail para o meu chefe, o Carlos, pedindo folga nos dias 14 e 15 de dezembro, para resolver um assunto pessoal. O tom deve ser educado e formal. Use no máximo 5 linhas, inclua uma linha de assunto e termine agradecendo."
  - *Critério de acerto (proposta, a confirmar):* o aluno consegue dizer, com as próprias palavras, pelo menos dois elementos do pedido claro que melhoraram a resposta.
- **Passo 3:** o aluno escolhe um assunto de que gosta, e o Claude cria um **documento do Word (.docx)** de uma página com 5 problemas escondidos (3 de ortografia ou gramática, 1 informação errada e 1 trecho confuso). O aluno baixa o arquivo, tenta achar 2 problemas sozinho e, em uma **conversa nova**, anexa o arquivo e pede a revisão (a conversa nova evita que o Claude já conheça os erros, e a apostila explica isso ao aluno). A apostila avisa que criar arquivos gasta mais do limite do plano gratuito. O exercício com **código de programação fica fora do Dia 1** (aula futura, "Claude para quem programa").
  - *Critério de acerto (proposta, a confirmar):* o Claude listou ao menos 3 problemas e o aluno consegue explicar um deles com as próprias palavras.
- **Passo 4:** o aluno escolhe entre **3 ideias simples** listadas na apostila (divisão de conta, conversor de medidas culinárias e quiz). Todas funcionam **sem guardar dados**, para que ninguém peça algo que o plano gratuito não permite. O aluno faz 2 ou 3 pedidos de ajuste, um de cada vez, escolhendo entre uma lista curta de sugestões por ideia e podendo criar um ajuste só dele. O pedido inicial de cada ideia já traz os 4 elementos do passo 2.
  - *Critério de acerto:* o resultado mudou conforme os pedidos de ajuste.
- **Passo 5:** feito na **mesma conversa do passo 4** (ao contrário do passo 3), porque o Claude precisa lembrar do que fez. O aluno pede uma **explicação em linguagem simples** e depois pede que o Claude aponte onde a ferramenta pode ter erros (a apostila avisa que essa autocrítica é só um ponto de partida). O ponto central é a **conferência**: o aluno testa a ferramenta com um caso de resposta conhecida (A: 100 reais entre 4 pessoas; B: uma conversão que ele conhece, com o aviso de que medidas de cozinha variam entre fontes; C: uma pergunta cuja resposta ele sabe, e a conferência da pontuação). A mensagem central: o Claude pode errar, e quem confere é você. No fim, o aluno anota uma frase do que aprendeu, que alimenta o passo 6.
  - *Critério de acerto:* o aluno testou com um caso conhecido e consegue dizer se o resultado estava certo.
- **Passo 6:** o aluno cria a pasta **`Curso de Claude`** e, dentro dela, a pasta **`Dia-01`**, e guarda na `Dia-01` o documento do Word do passo 3 e um **arquivo de anotações** com 4 partes: suas preferências, o que fazia o pedido claro funcionar melhor, qual ferramenta criou e onde achá-la (aba Artifacts, na barra lateral), e a frase aprendida. A ferramenta do passo 4 **não vai para a pasta**, porque a documentação não deixa claro como baixar um artifact comum no plano gratuito. O **Git** aparece só como uma menção curta no fim, para uma aula futura (assumido, a confirmar).
  - *Critério de acerto (proposta, a confirmar):* a pasta tem o documento do passo 3 e o arquivo de anotações com as 4 partes preenchidas.

## Dia 2: passos e decisões

Tema: **documentos e informação**. Duração total prevista: 80 minutos. O documento de exemplo é uma **ata de reunião fictícia** (Café Girassol, 12 de agosto de 2026), em PDF, fornecida com a aula.

| # | Passo | Tempo | Situação |
|---|-------|-------|----------|
| 1 | Enviar um documento e pedir um resumo | 15 min | Aula escrita |
| 2 | Perguntar sobre o documento e conferir no original | 15 min | Aula escrita |
| 3 | Extrair e reorganizar: tabela de tarefas e pendências | 15 min | Aula escrita |
| 4 | Pesquisar na internet com o Claude e conferir uma fonte | 20 min | Aula escrita |
| 5 | Juntar tudo em um documento final (Word) | 10 min | Aula escrita |
| 6 | Fechamento: pasta Dia-02 e anotações | 5 min | Aula escrita |

### Decisões já tomadas

- **Documento de exemplo:** fictício, fornecido por nós (para o critério de acerto ser objetivo e ninguém precisar enviar nada pessoal), com convite opcional no fim para o aluno repetir o exercício com um documento próprio, avisando para não enviar dados pessoais sensíveis. Formato **PDF**. A ata traz de propósito alguns pontos de conferência: o orçamento aprovado não é o mais barato, uma decisão ficou pendente e uma tarefa não tem prazo escrito.
- **Passo 1:** o aluno anexa a ata, pede primeiro um resumo simples ("Resuma esta ata.") e depois **melhora o pedido na mesma conversa**, aplicando os 4 elementos do Dia 1 com um modelo de apoio, e compara. Decisão provisória ("por enquanto").
  - *Critério de acerto (proposta, a confirmar):* o resumo melhorado menciona as decisões aprovadas (obra e horário) e a decisão pendente (cardápio), e o aluno diz o que mudou no pedido.
- **Passo 2:** na mesma conversa, 5 perguntas fixas com resposta conhecida mais uma **sexta pergunta cuja resposta não está na ata** (preço do fogão novo), para o aluno aprender a conferir antes de aceitar qualquer resposta. Depois pede o trecho de origem de cada resposta e confere no PDF. A aula traz as respostas de referência ao final, com aviso para olhar só depois de conferir.
  - *Critério de acerto (proposta, a confirmar):* o aluno conferiu ao menos 3 respostas no PDF, incluindo a sexta, e sabe dizer o que a ata diz (ou não diz) sobre ela, independentemente do que o Claude respondeu.
- **Passo 3:** na mesma conversa, o aluno pede uma **tabela de tarefas** (tarefa, responsável, prazo) e uma **lista de pendências**, mostradas na própria conversa (o Excel profissional fica para outro momento), e confere duas linhas no PDF. A tarefa do Tiago não tem prazo escrito.
  - *Critério de acerto (proposta, a confirmar):* tabela e lista presentes, duas linhas conferidas e o aluno sabe dizer qual tarefa não tem prazo.
- **Passo 4:** o aluno **escolhe um assunto** que muda com o tempo (regra simples mais lista curta de sugestões, podendo inventar o dele), pede a pesquisa com as fontes e **abre pelo menos uma fonte** para conferir. A aula avisa que a pesquisa gasta o limite diário do plano gratuito e que não se deve tomar decisões importantes só com a resposta.
  - *Critério de acerto (proposta, a confirmar):* o Claude pesquisou e mostrou as fontes, e o aluno abriu uma e diz se confirma, não confirma ou confirma em parte; vale mesmo que a fonte diga algo diferente do Claude.
- **Passo 5:** na mesma conversa dos passos 1 a 3, o Claude cria um **documento do Word** de uma página só com o que é da ata (resumo, tabela de tarefas e pendências), usando apenas informações da ata e escrevendo "não informado" quando faltar. O aluno baixa, confere ao menos 3 dados e corrige.
  - *Critério de acerto (proposta, a confirmar):* o documento tem as 3 partes, o aluno conferiu ao menos 3 dados e corrigiu o que estava errado ou confirmou que estava certo.
- **Passo 6:** o aluno cria a pasta **`Dia-02`** dentro de `Curso de Claude`, guarda o Word final e um arquivo de anotações com 4 partes (pedir bem de novo, conferir, pesquisar, o que aprendeu), e recebe o convite opcional de repetir o exercício com um documento próprio.
  - *Critério de acerto (proposta, a confirmar):* a pasta `Dia-02` tem o Word final e as anotações com as 4 partes preenchidas.

## Confirmado na documentação oficial

- Artifacts estão disponíveis nos planos Free, Pro, Max, Team e Enterprise, mas exigem que a execução de código e a criação de arquivos estejam ligadas em Configurações > Capacidades.
- No plano gratuito é possível criar artifacts em uma conversa. Os **modelos** (Design, Slides e Docs), a conexão de apps e o **armazenamento de dados** em artifacts são só dos planos pagos.
- O artifact abre em uma janela ao lado da conversa, e tudo que o aluno cria fica salvo na aba **Artifacts**, na barra lateral.
- Se um artifact der erro, há um botão "Try fixing with Claude" perto da mensagem de erro; o Claude tenta corrigir, sem garantia de sucesso.
- A exportação descrita (Word, PDF e outros formatos) vale para artifacts de modelos e para artifacts "legados" (criados em conversa antes de 16 de setembro de 2026). Não está claro como baixar um artifact comum criado agora no plano gratuito.
- O idioma da tela se muda pelo ícone do perfil, no canto inferior esquerdo, em "Idioma" (web e desktop). Português do Brasil está entre os idiomas aceitos, e o Claude responde na língua que o aluno usar.
- O modo de voz tem um ajuste de idioma separado.
- Execução de código e criação de arquivos está disponível em todos os planos, inclusive o gratuito, e vem **ligada por padrão** nos planos Free, Pro e Max. O botão fica em Configurações > Capacidades ("Code execution and file creation"). No celular, o caminho descrito é: tocar no nome ou nas iniciais na barra lateral > Configurações > Capacidades.
- Formatos que o Claude cria: Excel (.xlsx), PowerPoint (.pptx), Word (.docx) e PDF. Texto simples (.txt) **não** aparece na lista. O limite é de 30 MB por arquivo, em envios e downloads.
- Criar arquivos consome mais do limite de uso do plano do que uma conversa comum (relevante para o plano gratuito).
- A pesquisa na internet está disponível em todos os planos, inclusive o gratuito, e as pesquisas contam para o limite de uso. Dependendo da versão da página de ajuda, há um botão para ligá-la ou o Claude decide sozinho quando pesquisar; pedir "pesquise na internet" no texto ajuda nos dois casos. O Claude mostra as fontes.
- Envio de arquivos: pelo botão "+" perto do campo de mensagem (canto inferior esquerdo) ou arrastando o arquivo. A conversa aceita até 20 arquivos, e PDFs de até 1000 páginas. Nos documentos que não são PDF, o Claude lê só o texto. A versão da página que li lista PDF, DOCX, CSV, TXT, HTML, ODT, RTF, EPUB, JSON e XLSX (XLSX exige a criação de arquivos ligada). O limite de tamanho por arquivo varia entre versões da página (30 MB e 500 MB), por isso a apostila não cita número.

## Pendências de verificação

Nada abaixo entra na apostila antes de confirmado na documentação oficial ou em teste real:

- [ ] Preferências de perfil no plano gratuito (a documentação oficial não deixa claro)
- [ ] Projetos no plano gratuito (a documentação se contradiz: uma versão diz só pagos, outra diz até cinco gratuitos)
- [ ] Criação de arquivos e Artifacts: testar em conta gratuita de verdade (a documentação diz que vem ligada por padrão e que o botão fica em Configurações > Capacidades)
- [ ] Como baixar ou exportar um artifact comum no plano gratuito (decide se o passo 6 poderá guardar a ferramenta na pasta)
- [ ] Passos de idioma e preferências no celular (a documentação de idioma cobre só web e desktop; para a criação de arquivos o caminho no celular está descrito)
- [ ] Confirmar os critérios de acerto dos passos 1, 2, 3 e 6 do Dia 1 e de todos os passos do Dia 2 (hoje são propostas)
- [ ] Confirmar o Git opcional do passo 6 como menção curta (assumido)
- [ ] Confirmar as 3 ideias de artifact do passo 4 (divisão de conta, conversor de medidas culinárias e quiz), assumidas como aprovadas
- [ ] Revisar os textos dos pedidos dos passos 3, 4 e 5 do Dia 1 e dos 6 passos do Dia 2 (são rascunhos)
- [ ] Decidir se a aula do passo 4 ganha as dicas confirmadas (o artifact abre ao lado da conversa e o botão de correção de erros)
- [ ] Testar as 12 aulas (Dia 1 e Dia 2) em uma conta gratuita (os itens específicos do plano gratuito continuam sem confirmação)
- [ ] Dia 2: conferir na interface em português o botão de anexar e o botão de pesquisa na internet, e testar se o Claude lê bem o PDF da ata e se mostra as fontes da pesquisa
- [ ] Dia 2: confirmar a lista de sugestões de assunto do passo 4 e o convite opcional do passo 6

## Próximos passos

1. Testar as aulas do Dia 1 e do Dia 2 em uma conta gratuita e resolver as pendências acima
2. Montar o site e gerar a apostila (PDF) a partir dos arquivos Markdown
3. Desenhar o Dia 3
4. Planejar as aulas futuras já citadas: "Claude para quem programa", uma aula de Git e uma tabela profissional no Excel como exemplo
