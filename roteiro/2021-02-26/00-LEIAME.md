# Roteiro de 26 de fevereiro de 2021

1. Abrir o aplicativo [Termux](https://play.google.com/store/apps/details?id=com.termux&hl=pt_BR&gl=US)
2. Instalar o pacote Git no Termux
   - `pkg install git`  
4. Clonar este repositório no Termux
   - `cd`
   - `git clone https://github.com/jurandysoares/isa.git`
5. Entrar no diretório do dia
   - `cd ~/isa/roteiro/2021-02-26/`
6. Listar as atividades do dia
   - `ls`
7. Atualizar os arquivos recém publicados pelo professor
   - `git pull`
8. Instalar o *asciinema*
   - `apt update`
   - `apt install asciinema`
9. Testar o *asciinema*
   - Execute: `asciinema rec -t "1, 2, 3, testando"`
   - Você verá a mensagem:
     ```
     asciinema: recording asciicast to /tmp/tmpcphny1sd-ascii.cast
     asciinema: press <ctrl-d> or type "exit" when you're done
     ```
   - `# Digitar vários comandos`
   - Execute: `exit`
     ```
     asciinema: recording finished
     asciinema: press <enter> to upload to asciinema.org, <ctrl-c> to save locally
     ```
   - Pressione a tecla `ENTER`
10. Testando o *asciinema* mais uma vez
   - `apt install bat`
   - `apt install figlet cowsay`
  
11. Baixar roteiro passado pelo professor
    - `cd`
    - `wget https://mange.ifrn.edu.br/roteiros/isa/isa-2021-02-26.sh`
    - `. isa-2021-02-26.sh`

