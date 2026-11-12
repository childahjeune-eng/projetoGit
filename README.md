# projetoGit

## 1. Criar uma pasta
para começar entre no powershell atravez do windows

utilize mkdir projetoGit para criar a pasta

## 2. Entrar na pasta
Para acessar a pasta criada, utilize:

bash
cd ProjetoGit

## 3. Criar um arquivo
Para criar um arquivo, utilize:

bash
type nul > arquivo.txt

## 4. Se identificar no Git
Configure seu nome e e-mail:

bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@email.com"

## 5. Iniciar o Git
Para iniciar um repositório Git dentro da pasta, utilize:

bash
git init

## 6. Modificar um arquivo
Abra o arquivo `arquivo.txt`, escreva alguma informação, salve e feche.

## 7. Adicionar arquivos
Para adicionar os arquivos ao controle de versão, utilize:

bash
git add .

## 8. Fazer um commit
Para registrar as alterações, utilize:

bash
git commit -m "Primeiro commit"
