# Como contribuir com o Mural da Turma

Que bom que você chegou aqui! Este guia explica, passo a passo, como colocar o seu cartão no mural. Leia tudo antes de começar: o professor vai conferir se o seu Pull Request segue estas regras.

> **Resumo:** faça um fork, crie a branch `mural/seu-usuario`, adicione o arquivo `alunos/seu-usuario.md` e abra um Pull Request para este repositório.

---

## 1. Antes de começar

- [x] Tenho uma conta no GitHub com a **autenticação em dois fatores (2FA)** ativada.
- [x] Li este CONTRIBUTING.md inteiro.
- [x] Li a seção [Regras de convivência](#6-regras-de-convivência).

Você **não é colaborador** deste repositório, então não consegue editar nada direto aqui. É por isso que vamos usar o **fork**: você trabalha na sua cópia e depois pede para a sua mudança entrar no mural da turma.

---

## 2. Passo a passo

### 2.1 Faça o fork

1. No topo deste repositório, clique em **"Star"** (opcional, mas o mural agradece).
2. Clique em **"Fork"** e depois em **"Create fork"**.
3. Você será levado para a sua cópia, no endereço `github.com/seu-usuario/mural-da-turma`.

### 2.2 Crie a sua branch

1. **No seu fork**, clique no seletor de branch (o botão que mostra `main`).
2. Digite o nome da branch no padrão:

   ```
   mural/seu-usuario
   ```

   Exemplo: `mural/ana-souza`

3. Clique em **"Create branch: mural/seu-usuario from main"**.
4. **Confira no seletor** que você está na sua branch antes de continuar.

### 2.3 Crie o seu cartão

1. Entre na pasta `alunos`.
2. Clique em **"Add file" › "Create new file"**.
3. Dê ao arquivo o nome **exatamente igual ao seu usuário do GitHub**, em minúsculas, terminando em `.md`:

   ```
   seu-usuario.md
   ```

   Exemplo: `ana-souza.md`

4. Copie o modelo do arquivo [`alunos/_modelo.md`](alunos/_modelo.md) e preencha com as suas informações.
5. Use a aba **"Preview"** para conferir como o texto vai ficar.
6. Clique em **"Commit changes..."** e escreva a mensagem:

   ```
   Adiciona cartão de seu-usuario
   ```

### 2.4 Abra o Pull Request

1. Volte para a página inicial do **seu fork**.
2. Clique em **"Contribute" › "Open pull request"**.
3. **Confira as setas** no topo da tela. Precisa estar assim:

   ```
   base repository: usuario-do-professor/mural-da-turma   base: main
                    ←
   head repository: seu-usuario/mural-da-turma            compare: mural/seu-usuario
   ```

   Se a base for o seu próprio fork, você vai abrir o PR para você mesmo. Troque a base antes de continuar.

4. **Título** do PR, no padrão:

   ```
   Adiciona cartão de seu-usuario
   ```

5. A **descrição** já vem preenchida com um modelo. Preencha todas as partes e marque a checklist.
6. Clique em **"Create pull request"**.

### 2.5 Acompanhe a revisão

O professor vai revisar o seu PR e pode:

| O que aparece | O que significa | O que você faz |
|---|---|---|
| ✅ **Approved** | Está tudo certo | Aguarde o merge |
| 🔁 **Changes requested** | Precisa de ajuste | Corrija e responda o comentário |
| 💬 **Comment** | Uma dica ou pergunta | Leia e responda |

**Para fazer um ajuste:** volte ao **seu fork**, confira que está na branch `mural/seu-usuario`, edite o arquivo e faça um novo commit. O commit aparece sozinho no mesmo PR. **Não abra outro PR.**

Depois de corrigir, responda o comentário do professor explicando o que você mudou, por exemplo: "Ajustado! Troquei o título por um ##."

### 2.6 Depois do merge

1. Seu cartão está no mural. Parabéns! 🎉
2. No seu fork, clique em **"Sync fork" › "Update branch"** para trazer os cartões dos colegas para a sua cópia.
3. Você pode apagar a branch `mural/seu-usuario` do seu fork: ela já cumpriu o papel.

---

## 3. Regras do cartão

O seu arquivo precisa ter:

- [x] **Um título** com `#` e o seu apelido.
- [x] **Um hobby.**
- [x] **Uma música ou um jogo favorito.**
- [x] **Uma meta para o curso.**
- [x] Pelo menos **uma lista** (`-`) e **um trecho em negrito** (`**texto**`).

E **não pode** ter:

- ❌ Telefone, endereço, CPF, RG, data de nascimento ou e-mail.
- ❌ Fotos ou nomes completos de outras pessoas.
- ❌ Links para redes sociais pessoais.
- ❌ Palavrões, piadas sobre colegas ou qualquer coisa que você não mostraria para a turma inteira.

> **Lembre:** este repositório é **público**. Qualquer pessoa na internet pode ver o seu cartão, e o histórico guarda todas as versões. Apagar depois **não apaga do histórico**.

---

## 4. Uma pessoa, um arquivo

Cada aluno mexe **somente no próprio arquivo** dentro de `alunos/`.

- Não edite o README, este CONTRIBUTING, o modelo nem o cartão de colegas.
- Não crie pastas novas.

**Por quê?** Se duas pessoas alteram o mesmo arquivo ao mesmo tempo, o GitHub gera um **conflito**. Com um arquivo por pessoa, 30 alunos conseguem contribuir ao mesmo tempo sem atrapalhar ninguém.

Achou um erro no README ou neste guia? Abra uma **issue** em vez de editar.

---

## 5. Padrões de nome (resumo)

| O quê | Padrão | Exemplo |
|---|---|---|
| Branch | `mural/seu-usuario` | `mural/ana-souza` |
| Arquivo | `alunos/seu-usuario.md` | `alunos/ana-souza.md` |
| Mensagem de commit | `Adiciona cartão de seu-usuario` | `Adiciona cartão de ana-souza` |
| Commit de ajuste | `Ajusta ...` / `Corrige ...` | `Corrige título do cartão` |
| Título do PR | `Adiciona cartão de seu-usuario` | `Adiciona cartão de ana-souza` |

---

## 6. Regras de convivência

Este mural é um espaço da turma. Ao contribuir, você concorda em:

- **Respeitar todo mundo.** Nada de comentários ofensivos, apelidos que a pessoa não escolheu ou zoeira com o cartão dos colegas.
- **Comentar sobre o trabalho, não sobre a pessoa.** Se for comentar no PR de alguém, seja específico e gentil.
- **Fazer o seu próprio cartão.** Copiar o cartão de um colega aparece no histórico e conta como plágio.
- **Proteger a privacidade.** A sua e a dos outros.

Contribuições que desrespeitarem estas regras serão fechadas sem merge.

---

## 7. Problemas comuns

**"Não aparece o botão Contribute."**
Você provavelmente está no repositório do professor, não no seu fork. Confira o endereço: precisa ter o **seu** usuário.

**"Meu PR mostra arquivos que eu não mexi."**
Você criou a branch a partir de algo diferente da `main`, ou editou outros arquivos. Avise o professor no próprio PR.

**"Editei na main do meu fork sem querer."**
Sem problema, o PR ainda funciona. Na próxima vez, confira o seletor de branch antes de editar.

**"Apareceu: This branch has conflicts."**
Você mexeu em um arquivo que não é o seu. Releia a [seção 4](#4-uma-pessoa-um-arquivo) e peça ajuda ao professor.

**"O professor pediu ajuste e eu abri outro PR."**
Feche o PR novo e faça os ajustes na branch do primeiro.

---

Dúvidas? Abra uma **issue** com a label `question`. 💬
