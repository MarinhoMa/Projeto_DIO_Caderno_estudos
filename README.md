# Caderno de Estudos: GitHub para Iniciantes

## Contexto e Objetivos

### Contexto
Para quem está iniciando no universo da tecnologia e do desenvolvimento de software, o domínio de ferramentas de controle de versão é um dos primeiros e mais importantes passos. Por isso, o assunto escolhido para este caderno temático é **Git e GitHub para Iniciantes**. 

Este material reúne meus primeiros passos, anotações práticas e conceitos fundamentais, consolidados de forma didática com o suporte da inteligência artificial do Google NotebookLM. Ele funciona como o meu guia centralizado de consultas para perder o medo da linha de comando e entender como o ecossistema funciona.

### Objetivos de Estudo
Os objetivos principais com este material e repositório são:
* **Entender a Base:** Compreender de forma clara a diferença entre o Git (o sistema de controle de versão no computador) e o GitHub (a plataforma na nuvem onde guardamos os projetos).
* **Perder o Medo do Terminal:** Praticar e dominar os comandos mais básicos e essenciais do dia a dia (`git init`, `git status`, `git add`, `git commit`, `git push`), entendendo o que acontece com os arquivos em cada etapa.
* **Aprender a Compartilhar Projetos:** Descobrir como enviar códigos e projetos locais do meu computador diretamente para o GitHub, deixando-os salvos na nuvem de forma segura.
* **Desenvolver Habilidades de Documentação:** Praticar a escrita de documentações profissionais desde o início, aprendendo a usar a sintaxe Markdown para criar arquivos `README.md` organizados e visualmente atraentes.


## Como Criar o seu Próprio Repositório no GitHub

Se você é iniciante e quer criar o seu próprio repositório para guardar este caderno de estudos (ou qualquer outro projeto), siga o guia prático abaixo:

### 1. Pela Plataforma Web (Site do GitHub)
1. Acesse sua conta no [GitHub](https://github.com) (se não tiver, crie uma gratuitamente).
2. No canto superior direito, clique no ícone de **`+`** e selecione **New repository** (Novo repositório).
3. No campo **Repository name**, escolha um nome amigável (ex: `meu-caderno-github`).
4. (Opcional) Adicione uma breve descrição sobre o seu projeto.
5. Escolha se o repositório será **Public** (público) ou **Private** (privado).
6. Clique no botão verde **Create repository** ao final da página.

---

### 2. Enviando os Arquivos (Via Linha de Comando / Terminal)
Se você quer praticar o uso do terminal (como o Git Bash), abra-o dentro da pasta onde salvou os arquivos no seu computador e execute a seguinte sequência de comandos:

```bash
# 1. Inicialize o Git na sua pasta local
git init

# 2. Adicione todos os seus arquivos para a área de preparação
git add .

# 3. Faça o seu primeiro commit (carimbe suas alterações)
git commit -m "feat: adiciona caderno de estudos inicial"

# 4. Conecte sua pasta local ao repositório que você criou no site
# (Substitua pelo link real do seu repositório!)
git remote add origin [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)

# 5. Envie os arquivos para a nuvem do GitHub
git push -u origin main

```

## Curadoria de Fontes (Materiais Utilizados)

Para garantir a qualidade e a segurança das informações deste caderno de estudos, foram selecionadas e carregadas no Google NotebookLM as seguintes fontes oficiais e abertas:

1. **[Turorial básico GitHub: Tutorial basico GitHub](https://github.com/MarinhoMa/Projeto_DIO_Caderno_estudos/blob/main/tutorial_github.pdf)**
   * *Descrição:* Tutorial basico sobre o GitHub e Git.
2. **[Documento com dicas sobre dicas no uso do Git e GitHub)](https://github.com/MarinhoMa/Projeto_DIO_Caderno_estudos/blob/main/github-git-cheat-sheet.pdf)**
   * *Descrição:* Dicas sobre dicas no uso do Git e GitHub.
3. **[Versionamento GitHub](https://github.com/MarinhoMa/Projeto_DIO_Caderno_estudos/blob/main/Controlando%20Vers%C3%B5es%20com%20Git%20e%20GitHub%20-%20Autor%20(Casa%20do%20C%C3%B3digo).pdf)**
   * *Descrição:* Documento sobre como realizar o versionamento dentro do GitHub.

---
*(Nota: Se você fez o upload de arquivos PDFs próprios que estão salvos no seu computador, lembre-se de colocá-los na pasta `documentos/` do seu repositório para que outras pessoas também possam baixá-los e usá-los no NotebookLM delas!)*

---

## Perguntas Feitas ao Caderno & Respostas Obtidas

Nesta seção estão documentadas as dúvidas que fiz ao NotebookLM e as respostas geradas pela IA para facilitar o entendimento de quem está começando:

### 1. Como posso criar um novo repositório no GitHub para inserir esse meu caderno de estudos?

> **Resposta do NotebookLM:**
> Para criar um novo repositório no GitHub para o seu caderno de estudos, você deve seguir alguns passos simples, começando pela plataforma web e depois vinculando-a aos seus arquivos locais.
> **1. Criando o repositório no site do GitHub:**
> Primeiramente, acesse sua conta no GitHub. Se ainda não possui uma, você deve criá-la acessando github.com, preenchendo seu e-mail, definindo uma senha e um nome de usuário. Após estar logado, siga estas etapas:
> * Clique no botão "New repository" (Novo repositório) ou no ícone de "+" no canto superior da tela e selecione "New repository".
> * No campo "Repository name", digite um nome para o seu projeto (por exemplo, `caderno-estudos-github`).
> * Você pode adicionar uma descrição opcional no campo "Description".
> * Escolha entre "Public" (qualquer pessoa pode ver seu código) ou "Private" (apenas você e quem você autorizar podem ver).
> * Clique no botão "Create repository" ao final da página.
> 
> 
> **2. Enviando seu caderno de estudos (via Linha de Comando):**
> Uma vez criado o repositório remoto, você precisa enviar os arquivos que estão no seu computador. No seu terminal (como o Git Bash), navegue até a pasta onde está seu caderno e use os seguintes comandos:
> * Inicialize o Git localmente: `git init`.
> * Adicione seus arquivos: `git add .` (isso prepara todos os arquivos para o envio).
> * Faça o seu primeiro "commit": `git commit -m "Meu caderno de estudos inicial"`.
> * Conecte ao repositório do GitHub: `git remote add origin https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git`.
> * Envie os arquivos: `git push -u origin master` (ou `main`, dependendo da configuração da sua branch principal).
> 
> 
> **3. Alternativa: GitHub Desktop (Interface Visual):**
> Se você preferir não usar comandos de texto, pode utilizar o GitHub Desktop:
> * Após instalar a ferramenta e logar na sua conta, clique em adicionar um novo repositório.
> * Você pode criar o repositório diretamente pela ferramenta preenchendo o nome e o caminho local da pasta.
> * Para enviar alterações, basta digitar um resumo no campo "Summary" e clicar em "Commit to master", seguido de "Publish Repository" ou "Sync".
> 
> 
> Dessa forma, seu caderno ficará salvo na nuvem do GitHub, servindo como um backup seguro e permitindo que você acesse seus estudos de qualquer lugar.


### 2. Qual a diferença entre repositório público e privado?
> **Resposta do NotebookLM:**
> A principal diferença entre um repositório público e um privado no GitHub reside na visibilidade e no controle de acesso ao código-fonte.
> 
> * **Repositório Público:** Qualquer pessoa na internet pode encontrar o repositório, visualizar seu histórico e ter acesso ao código-fonte. Este tipo de repositório é ideal para projetos *open source* (código aberto), permitindo que desenvolvedores de todo o mundo colaborem com melhorias e correções.
> * **Repositório Privado:** O acesso é restrito apenas ao proprietário e a pessoas ou equipes especificamente autorizadas. Ninguém mais na plataforma consegue ver o conteúdo do repositório. Essa opção é a preferida por empresas ou desenvolvedores que possuem projetos com regras de negócio restritas ou códigos que não podem ser expostos publicamente por questões de segurança.
> 
> **Considerações sobre planos e custos:**
> Atualmente, o plano gratuito do GitHub permite a criação de **repositórios públicos e privados ilimitados** para projetos individuais. Os planos pagos são voltados para empresas ou equipes que necessitam de recursos avançados de colaboração e segurança.
> 
> *Vale ressaltar que você pode alterar a visibilidade do seu repositório (mudar de público para privado ou vice-versa) a qualquer momento nas configurações (**Settings**) do projeto.*

---

## Miniguia de Estudo

Esta seção consolida o conhecimento essencial adquirido ao longo desta jornada de aprendizado, servindo como uma base sólida para consultas rápidas e revisões eficientes.

### 1. Fundamentos de Git e GitHub O Git funciona como uma "máquina do tempo" para o código, permitindo que desenvolvedores rastreiem o histórico de alterações e trabalhem em equipe sem perder informações
. O GitHub é uma plataforma online que hospeda esses repositórios, facilitando o compartilhamento de projetos e a colaboração global
. O fluxo de trabalho padrão envolve inicializar um repositório local, adicionar arquivos à área de stage, realizar commits para gravar as mudanças permanentemente e usar o push para enviar as alterações para o servidor remoto
.
### 2. Ferramentas e Processos de Colaboração Para organizar o desenvolvimento, utilizam-se branches, que permitem criar linhas de trabalho independentes para novas funcionalidades ou correções sem afetar o código principal
. A integração de código entre diferentes desenvolvedores é feita por meio de Pull Requests, Forks e sincronizações como pull e fetch
. Além da linha de comando tradicional, existem interfaces visuais como o GitHub Desktop, que simplificam o gerenciamento de arquivos e a sincronização com a nuvem para iniciantes

## Glossário / Principais conceitos

### Repository (Repositório): É a "pasta inteligente" do seu projeto. Ela não guarda apenas os arquivos atuais, mas também todo o histórico de alterações que você já fez desde o início da criação do caderno.

### Commit: Funciona como um ponto de salvamento ou um "Save Game" da sua jornada. Cada vez que você faz um commit, você tira uma foto do estado atual dos seus arquivos e deixa registrado o que foi alterado e por quê (a mensagem de commit).

### Branch (Ramificação): É uma linha de desenvolvimento separada. A sua linha principal é a main. Se você quiser testar algo novo sem correr o risco de estragar o que já está funcionando no seu caderno, você cria uma nova branch.

### Push: É a ação de "empurrar" ou enviar. Esse comando pega os commits que você fez localmente no seu computador e faz o upload deles para o servidor na nuvem do GitHub.

### Pull: É a ação inversa do push. Ele "puxa" e traz as atualizações que estão salvas lá no site do GitHub para atualizar a pasta correspondente dentro do seu computador.

### Clone: É o ato de baixar uma cópia exata e completa de um repositório que já existe na internet (no GitHub) para a sua máquina local pela primeira vez.

## Prompt de comando reutilizavel:

### O que eu preciso aprender para utilizar o github para controle de versão?

### Quais os principais Conceitos que preciso aprender para utilzar o GitHub corretamente.
