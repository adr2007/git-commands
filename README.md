# git-commands
Comandos e testes

---
## Termos

- **Commit:** Basicamente é nome dado ao registro de uma alteração
- **Local:** O dispositivo onde as alterações são feitas
- **Remoto:** Onde o repositório está hospedado

---
## Comandos básicos

Os comandos mais comuns do GitHub são:

| Comando | Descrição |
| ------- | --------- |
| `git status` | Lista todos os arquivos alterados e indica quais serão enviados junto ao próximo commit |
| `git add [nome-arquivo.txt]` | Define um arquivo para ser enviado no próximo commit |
| `git add -A` | Define que todos os arquivos alterados no diretório serão enviados no próximo commit |
| `git log` | Lista o histórico de commits local (independente da conta utilizada para envio remoto) |
| `git commit -m "[Mensagem de Commit]"` | Registra uma alteração |
| `git commit -m "[Titulo]" -m "[Descrição]"` | Registra uma alteração com descrição |
| `git push` | Envia todos os commits para remoto (Github) |

---
## Trocar ou Remover uma conta GitHub do Windows

Caso tenha uma conta GitHub e precisa trocar por outra ou atualizar os dados de uma conta, basta seguir esse guia.

### Passo 1: Acesse o Gerenciador de Credenciais do Windows

Existem várias maneiras de fazer isso:

- **Opção 1:** Clique no botão "Iniciar" e procure por "Gerenciar Credenciais do Windows" e clique no resultado correspondente.

- **Opção 2:** Acesse o "Painel de Controle" e procure por "Gerenciador de Credenciais" e depois "Credenciais do Windows" 

![Localizando as Credenciais do GitHub](./images/image1.png)

### Passo 2: Localizando as Credenciais do GitHub

Na janela de Gerenciamento de Credenciais, procure pela seção "Credenciais Genéricas". Role a lista até encontrar as credenciais relacionadas ao GitHub.

### Passo 3: Removendo as Credenciais do GitHub

Selecione as credenciais do GitHub que deseja remover e clique no botão "Remover". Confirme a remoção, se solicitado.

![Localizando as Credenciais do GitHub](./images/image2.png)

Repita esse processo para todas as credenciais do GitHub.

---
