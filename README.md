# 📊 Como Criar um Portfólio de Dados no GitHub

Um guia direto ao ponto pra estruturar seu perfil e seus projetos de dados no GitHub, do jeito que recrutadores e times técnicos realmente avaliam.

## Sumário

- [Por que isso importa](#por-que-isso-importa)
- [Parte 1: Configurando seu perfil](#parte-1-configurando-seu-perfil)
- [Parte 2: Criando o README do perfil](#parte-2-criando-o-readme-do-perfil)
- [Parte 3: Documentando um projeto de dados](#parte-3-documentando-um-projeto-de-dados)
- [Template de README de projeto](#template-de-readme-de-projeto)
- [Regras de ouro](#regras-de-ouro)
- [Erros comuns](#erros-comuns)
- [Como usar o arquivo plano.html](#como-usar-o-arquivo-planohtml)
- [Checklist final](#checklist-final)

---

## Por que isso importa

Seu GitHub é o seu currículo técnico. Antes mesmo da entrevista, é comum que recrutadores e tech leads deem uma olhada no seu perfil pra entender como você pensa, como você documenta e como você trabalha. Um perfil bem estruturado conta uma história melhor do que qualquer lista de skills no LinkedIn — porque mostra evidência, não só afirmação.

Isso vale ainda mais pra dados: um projeto de dbt, uma pipeline de ingestão ou uma análise em SQL só tem valor de portfólio se a pessoa que olha consegue entender o problema, a solução e o resultado em poucos minutos.

---

## Parte 1: Configurando seu perfil

Antes de pensar em projetos, ajuste as informações básicas do seu perfil:

- **Foto de perfil**: uma foto real, profissional, é suficiente. Evite ícones genéricos.
- **Nome**: use seu nome completo ou o nome que você usa profissionalmente (LinkedIn, currículo).
- **Bio**: uma linha curta dizendo quem você é. Ex: "Engenheira de Dados | Snowflake, dbt, Python" ou "Analista de Dados em transição para Engenharia de Dados".
- **Localização**: cidade e país bastam. Não precisa de endereço completo.
- **Fuso horário**: ative essa opção no perfil. Ajuda quem for entrar em contato a saber se está enviando mensagem às 3h da sua manhã.
- **Links**: coloque seu LinkedIn e, se tiver, portfólio pessoal ou blog. E-mail direto no perfil é opcional — muita gente evita pra não receber spam, já que o contato pode vir pelo LinkedIn.
- **Status**: pode usar algo como "🟢 Aberto a oportunidades" ou "📚 Estudando Engenharia de Dados".

---

## Parte 2: Criando o README do perfil

Esse é o texto que aparece no topo da sua página do GitHub, antes de qualquer repositório.

**Como criar:**

1. Crie um novo repositório.
2. Nomeie o repositório com **exatamente o mesmo nome do seu usuário do GitHub**. Isso é o que faz o GitHub entender que esse README deve aparecer na sua página de perfil.
3. Marque a opção de adicionar um `README.md` na criação.
4. Edite o arquivo com o ícone de lápis.

**O que incluir:**

- Uma apresentação curta: quem você é e o que você faz com dados.
- Suas principais ferramentas e tecnologias (SQL, Python, dbt, Snowflake, Airflow, Power BI, etc.).
- Um ou dois projetos que você tem mais orgulho, com link direto pro repositório.
- Forma de contato (LinkedIn é suficiente).

**O que evitar:**

- Banners gigantes, muitos badges decorativos, ou gráficos de linguagem que não agregam nada.
- Textos longos demais. Ninguém lê um perfil como se fosse uma carta de apresentação.

A regra prática: qualquer pessoa que caia no seu perfil deveria entender quem você é e o que você faz em **10 segundos**. A maioria dos recrutadores nem é técnica — clareza vale mais que sofisticação visual.

---

## Parte 3: Documentando um projeto de dados

Aqui está o ponto que mais separa um portfólio mediano de um portfólio forte: **como você documenta cada projeto**.

A pergunta que deve guiar sua escrita é: *se alguém novo entrasse nesse projeto hoje, essa pessoa entenderia o que foi feito e por quê?*

Um bom README de projeto de dados normalmente cobre:

1. **O que é o projeto** — uma ou duas frases sobre o problema resolvido.
2. **Stack utilizada** — linguagens, ferramentas, banco de dados, orquestrador.
3. **Fonte dos dados** — de onde vieram os dados (API, CSV público, banco simulado, etc.).
4. **Arquitetura / pipeline** — como os dados fluem, de preferência com um diagrama simples.
5. **Principais decisões técnicas** — por que você modelou daquele jeito, por que escolheu aquela ferramenta.
6. **Como rodar o projeto** — passos objetivos pra alguém reproduzir localmente.
7. **Resultados / aprendizados** — o que esse projeto demonstra sobre sua capacidade técnica.
8. **Print ou vídeo curto** — se o projeto tem um dashboard ou output visual, mostre.

Não precisa de todos esses pontos em todo projeto. Um projeto simples pode ter só descrição, stack, como rodar e um print. Um projeto mais robusto pode ter todos os itens acima. O importante é a clareza, não o tamanho.

---

## Template de README de projeto

Copie e adapte esse modelo pros seus projetos de dados:

```markdown
# Nome do Projeto

Uma frase curta descrevendo o que o projeto faz e o problema que resolve.

## 🛠️ Stack utilizada
- Linguagem: Python / SQL
- Banco de dados: Snowflake / PostgreSQL / BigQuery
- Transformação: dbt
- Orquestração: Airflow (se aplicável)
- Visualização: Power BI / Tableau / Streamlit (se aplicável)

## 📂 Fonte dos dados
Descreva de onde vieram os dados: API pública, dataset do Kaggle, dados simulados, etc.

## 🏗️ Arquitetura
Descreva ou desenhe o fluxo: ingestão → transformação → camada final → consumo.

## 💡 Principais decisões
- Por que modelou dessa forma (ex: dimensional modeling, incremental load)
- Trade-offs considerados

## ▶️ Como rodar o projeto
Passos objetivos, com comandos, pra alguém reproduzir localmente.

## 📈 Resultados
O que esse projeto entrega ou demonstra. Prints do dashboard, se houver.

## 📚 Aprendizados
O que você aprendeu ou o que faria diferente numa próxima versão.
```

---

## Regras de ouro

- **Clareza acima de estética.** Um README simples e bem organizado vence um cheio de elementos visuais sem função.
- **Badges sim, followers não.** Badges conquistados por contribuições e desafios mostram envolvimento real. Número de seguidores não diz nada sobre competência técnica.
- **Documente como se fosse pro seu time.** Escreva pensando em alguém que vai dar manutenção no seu código, não só em quem vai "julgar" o projeto.
- **Menos projetos, mais profundidade.** Três projetos bem documentados valem mais que dez projetos com um README de duas linhas.

---

## Erros comuns

- README vazio ou só com o texto padrão que o GitHub gera.
- Código sem nenhuma explicação de contexto — sem dizer o problema que está sendo resolvido.
- Excesso de emojis, banners ou badges decorativos que não comunicam nada técnico.
- Não mostrar o resultado final (print, vídeo, link do dashboard).
- Histórico de commits com uma única entrada tipo "primeiro commit" — não mostra processo, só entrega.

---

## Bônus: mostrando domínio de Git no seu portfólio

Saber usar `git merge` e `git rebase` corretamente é um diferencial que poucos juniors dominam — e é algo que dá pra deixar evidente no seu portfólio, seja no histórico de commits de um projeto, seja numa seção explicando suas decisões técnicas.

### A diferença entre os dois

Ambos servem pra trazer as alterações de uma branch pra outra, mas de formas diferentes:

- **`git merge`** cria um novo commit que junta os dois históricos. É uma operação não destrutiva — nenhum commit original é apagado ou reescrito. É o que acontece por trás de um `git pull` padrão.
- **`git rebase`** reescreve o histórico: pega os commits da sua branch e os reaplica como se tivessem sido criados depois das alterações mais recentes. Isso gera um histórico linear e mais limpo, mas os commits originais são substituídos por novos (com hashes diferentes).

### A regra de ouro

**Nunca faça rebase em branch pública** — ou seja, qualquer branch compartilhada por outras pessoas do time (`main`, `development`, `staging`). Como o rebase reescreve hashes de commits, um `push --force` depois disso pode sobrescrever ou até apagar o trabalho de colegas que já basearam código nesses commits.

Rebase só é seguro na sua própria branch de trabalho, que mais ninguém está usando. Se precisar atualizar sua branch pessoal com o que mudou na branch principal, rebase é uma boa opção. Se for integrar seu trabalho de volta pra branch principal, o caminho mais seguro é merge.

### Prática recomendada: backup antes de operações arriscadas

Antes de rodar um rebase (ou um reset) em que você não tem certeza do resultado, crie uma branch de backup:

```bash
git checkout -b nome-da-branch-backup
git checkout nome-da-branch-original
git rebase development
```

Se algo sair errado, seu backup está intacto e você pode voltar pra ele sem perder trabalho.

### Como isso vira portfólio

Documentar esse tipo de decisão — por que você escolheu merge em vez de rebase numa situação específica, como resolveu um conflito — em um `PRATICA.md` ou na descrição de um PR mostra maturidade técnica real. É exatamente o tipo de raciocínio que diferencia quem só "sabe os comandos" de quem entende o **porquê** de cada um.

---

## Como usar o arquivo index.html que contem os exercícios praticos de dia a dia 

Esse repositório inclui o `index.html`, um material visual com os exercícios práticos de Git (conflitos, merge, rebase) mencionados na seção anterior. Para usa-lo é só acessar: https://alanasarah01.github.io/git-na-pratica/

---

## Checklist final

- [ ] Perfil com nome, bio, localização e fuso horário preenchidos
- [ ] README de perfil criado no repositório com o mesmo nome do seu usuário
- [ ] Pelo menos 2-3 projetos com README completo seguindo o template acima
- [ ] Histórico de commits organizado, não só um commit único por projeto
- [ ] Links de contato (LinkedIn) visíveis no perfil
- [ ] Nenhum projeto "solto" sem explicação do que ele faz

---

Boa sorte construindo seu portfólio! 🚀
