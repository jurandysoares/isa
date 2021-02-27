# Roteiro de 26 de fevereiro de 2021

Nesta aula vamos aprender a usar o aplicativo Termux no celular Android e, dentro dele, usar os comandos do 

1. Abrir o aplicativo [Termux](https://play.google.com/store/apps/details?id=com.termux&hl=pt_BR&gl=US)
2. Instalar o pacote Git no Termux
   - `apt update`
   - `apt install git`
4. Clonar este repositório no Termux
   - `cd`
   - `git clone https://github.com/jurandysoares/isa.git`
5. Entrar no diretório do dia
   - `cd ~/isa/roteiro/2021-02-26/`
6. Listar as atividades do dia
   - `ls`
7. Atualizar os arquivos recém publicados pelo professor
   - `git pull`
8. Instalar o *bat*
   - `apt install bat`
9. Instalar o *asciinema*
    - `apt show asciinema`
    - `apt show asciinema | bat -l yaml`
    - `apt install asciinema`
10. Testar o *asciinema*
   - Execute: `asciinema rec -t "Testando"`
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
 
11. Testando o *asciinema* mais uma vez
   - `apt install bat`
   - `apt install figlet cowsay`
  
12. Baixar roteiro passado pelo professor
    - `cd`
    - `wget jurandy.net/roteiros/isa/isa-2021-02-26.sh`
    - `bat isa-2021-02-26.sh`
    - `chmod +x isa*.sh`
    - `./isa-2021-02-26.sh`

