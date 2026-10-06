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

| # | Passo | Tempo | Situação |
|---|-------|-------|----------|
| 1 | Configurar o ambiente (idioma, tom e nível) | 10 min | Desenho fechado |
| 2 | Pedir bem: pedido vago vs. pedido claro | 20 min | Em discussão |
| 3 | Anexar arquivos e pedir uma revisão | 15 min | Desenho fechado |
| 4 | Gerar algo de verdade com Artifacts e ajustar em 2 ou 3 pedidos | 20 min | A detalhar |
| 5 | Revisar e aprender: pedir que o Claude explique o que fez | 10 min | A detalhar |
| 6 | Fechamento: salvar tudo em um repositório Git com README | 5 min | A detalhar |

### Decisões já tomadas

- **Passo 1:** a configuração vem primeiro, e o **idioma** é o primeiro item. O aluno escreve as preferências **com as próprias palavras** (com um modelo para guiar), e a aula avisa que o Claude pode ajudar a escrevê-las.
- **Passo 3:** o aluno escolhe um assunto de que gosta, o Claude cria um arquivo curto com erros de propósito, e o aluno anexa o arquivo de volta e pede uma revisão. O exercício com **código de programação fica fora do Dia 1** (aula futura, "Claude para quem programa").
- **Critério de acerto do passo 3 (proposta):** o Claude listou ao menos 3 problemas e o aluno consegue explicar um deles com as próprias palavras.

## Pendências de verificação

Nada abaixo entra na apostila antes de confirmado na documentação oficial ou em teste real:

- [ ] Preferências de perfil no plano gratuito (a documentação oficial não deixa claro)
- [ ] Projetos no plano gratuito (a documentação se contradiz: uma versão diz só pagos, outra diz até cinco gratuitos)
- [ ] Criação de arquivos: a documentação diz que vem ativada por padrão nos planos gratuitos, mas indica onde ligar; testar em conta gratuita
- [ ] Passos de configuração no celular (a documentação de idioma cobre só web e desktop)
- [ ] Pedido do passo 2: fixo para todos ou escolhido pelo aluno

## Próximos passos

1. Fechar o desenho do passo 2 e depois dos passos 4, 5 e 6
2. Escrever as aulas do Dia 1 em Markdown
3. Montar o site e gerar a apostila
