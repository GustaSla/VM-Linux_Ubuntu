# COMANDOS PARA USAR NO TERMINAL DO LINUX 🦇
### CRTL + ALT + T para abrir terminal <br> 
sudo apt update <br>
Utilizado para "baixar" os arquivos padrões do Linux <br>

sudo apt upgrade <br>
Utilizado para "executar" os arquivos padrões do Linux <br>

sudo reboot <br>
Reinicia a máquina <br>

sudo apt update && sudo apt upgrade <br>
Faz os dois comandos ao mesmo tempo

sudo apt install build-essential dkms linux-headers-$(uname -r) <br>
Instala dois "pacotes" para o Linux, o build-essential e o dkms

cd /media/$USER/VBox_GAs_7.0.6 <br>
Leva até o diretório onde está o aplicado para instalar recursos adicionais de convidado<br>

sudo ./VBoxLinuxAdditions.run<br>
Executa a aplicação disponível no diretório que acessou e instala os recursos<br>

lsmod | grep vbox<br>
Lista módulos que estão no Kernel <br>

echo $USER<br>
Ira listar quem é o usuario do Linux<br>

sudo adduser $USER vboxsf<br>
Adiciona usuario na VBOX

cat (arquivo de text)<br>
Ira ler o texto desse arquivo pelo terminal<br>

echo "seu texto" > (nome do arquivo)<br>
Ira colocar uma escrita, nesse caso, "seu texto" nesse arquivo, para escrever algo que não sobrepoe o texto anterior, utilize >>, se não existir um arquivo com esse nome, ele sera criado automaticamente com o texto que você selecionou <br>

cd /media <br>
Você ira entrar em uma pasta criada no windows, tendo o diretorio sf_(nome da pasta criada)<br>

sudo apt install vim<br>
Instala o programa Vim<br>

ls -l <br>
Detalha a listagem, respectivamente: o usuario proprietario, grupo proprietario, tamanho da pasta (kb), o mês, dia e horario que o arquivo foi criado/alterado pela ultima vez <br>

sudo groupadd nome_do_grupo <br>
Criar grupos no SO<br>

sudo usermod -aG (nome do usuario que vai ser adicionado) (nome do grupo que vai receber)<br>
Adicionar o usuario no grupo<br>

sudo usermod -aG nome_do_grupo1 nome_do_grupo2 $USER <br>
Adicionar o mesmo usuario para varios grupos <br>

sudo adduser $USER alunos <br>
Adicionar usuario dentro de um grupo <br>

sudo mkdir home/(nome da pasta) <br>
Cria um novo diretório<br>

sudo chown :alunos pasta_alunos<br>
Mudou o proprietário do diretorio

comando groups <br>
Mostra os grupos

cat /etc/group <br>
Encontra todos os grupos existentes

sudo chmod 750 pasta_docentes <br>
Muda as possibilidades do que os usuarios, grupos e outros podem fazer nessas pastas

> [!NOTE]
> Quase todos os comandos podem ser usados em qualquer Linux

## Glossário <br>
- sudo: grupo padrão do Linux <br>
- root: é o administrador, gerencia outros usuários  <br>
- grep: é um filtro que vai pesquisar apenas o que você deseja(vbox, pastas, etc) <br>
- vbox: prefixo que inicia normalmente os nomes dos módulos do VirtualBox<br>
- apt: arquivos padrões do Linux <br>
- $USER: usuário da maquina
- build essentials: ferramento que compila código-fonte <br>
- dkms: recompilador de aplicações para ser compativel com o Kernel do Guest<br>
- ls: listar algo
- cd: entrar em pastas/diretórios
- cat: utiliza para ler arquivos
- echo: grava frases em arquivos
- clear: limpa tela do terminal
- nano e vim: editam texto, sendo dois programas basicos de edição de texto do Linux
- cd ../: volta para a pasta anterior que esta sendo acessada pelo terminal
- kernel: é basicamente o "cérebro" do sistema operacional
- chmod: altera permissões
- chown: mudar o proprietário
- groups: mostra os grupos do SO
- etc: fica o diretorio "group"
- -aG: -usuario, append(anexar), Group(grupo)
- drwxr: D: diretorio, R: read, W: write, X: execute
- diretório etc: aonde vc encontra os grupo nos quais o usuário logado faz parte
- rwx: r:4, w:2, x:1 (valores octais)
# COMANDOS PARA USAR NO VIM
- :q!: sair sem salvar
- :wq: salvar e sair
- set number: numera as linhas do arquivo

## Glossário do vim
- q: quit
- w: write
