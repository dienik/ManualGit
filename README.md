## Manual Git e GitHub

Este guia fornecerá instruções passo a passo desde a criação de uma conta no GitHub até a execução de comandos básicos e avançados com o Git. Vamos lá!

### 1. Criando uma Conta no GitHub:

1. Acesse [GitHub](https://github.com/).
2. Clique em "Sign up" para criar uma nova conta.
3. Preencha as informações necessárias e siga as instruções para verificar seu e-mail.

### 2. Criando um Repositório no GitHub:

1. Faça login na sua conta GitHub.
2. Clique em "New" no canto superior direito.

![Localização do botão](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/1w5o0ite8fzm03ztzp1s.png)


3. Preencha os detalhes do repositório e clique em "Create repository".

![Criação de repositório](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/fuiaz4jvt4x7amlpzckn.png)


4. Copie a URL do repositório, você precisará dela para clonar o repositório localmente.


![Clonando repositório, basta clicar em no icone de copiar ao lado do link](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/mmmwbjcjloocvr0q2bwc.png)



### 3. Instalando o Git no Computador:

#### Windows:
1. Baixe o instalador do Git para Windows [aqui](https://gitforwindows.org/).
2. Execute o instalador e siga as instruções.

#### Linux:
- **Debian/Ubuntu:**
  ```bash
  sudo apt-get update
  sudo apt-get install git
  ```

- **Fedora:**
  ```bash
  sudo dnf install git
  ```

- **Arch Linux:**
  ```bash
  sudo pacman -S git
  ```

### 4. Configurando o Git:

1. Configure seu nome e e-mail globalmente:
   ```bash
   git config --global user.name "Seu Nome"
   git config --global user.email "seu@email.com"
   ```
### 5. Clonando o Repositório Localmente:

1. Abra o terminal no seu computador.
2. Use o comando `git clone URL-do-repositorio` para clonar o repositório para sua máquina.
### 

6. Navegando até o Repositório Clonado:

```bash
cd nome-do-repositorio
```

### 7. Comandos Básicos do Git:

#### Status e Mudanças:
- `git status`: Mostra o estado atual do seu repositório.
- `git add arquivo`: Prepara um arquivo para o próximo commit.
- `git diff`: Exibe as diferenças nas alterações.

#### Commits:
- `git commit -m "Mensagem do commit"`: Registra as mudanças.
- `git log`: Exibe o histórico de commits.

#### Ramos (Branches):
- `git branch nome-do-ramo`: Cria um novo ramo.
- `git checkout nome-do-ramo`: Muda para um ramo específico.
- `git merge nome-do-ramo`: Combina alterações de um ramo de volta ao principal.

### 8. Comandos Avançados do Git:

#### Remoto:
- `git remote add origin URL`: Conecta seu repositório local ao repositório remoto.
- `git push origin nome-do-ramo`: Envia alterações para o repositório remoto.
- `git pull origin nome-do-ramo`: Recebe alterações do repositório remoto.

#### Desfazer Alterações:
- `git checkout -- arquivo`: Desfaz alterações não confirmadas.
- `git reset HEAD~1`: Desfaz o commit mais recente.
- `git revert SHA-do-commit`: Desfaz um commit existente.

#### GitHub:
- Siga as instruções no site para criar Pull Requests, Issues, e explorar recursos colaborativos.

Este guia abrange desde a criação de uma conta no GitHub até a execução de comandos avançados com o Git. Explore a documentação oficial do Git e GitHub para aprender mais: [Git Documentation](https://git-scm.com/doc), [GitHub Documentation](https://docs.github.com/).
