# COMANDOS PARA USAR NO TERMINAL DO LINUX
CRTL + ALT + T para abrir terminal <br> 
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
Echo ira fazer com que apareça o nome do usuario, mas pode ser usado também para mostrar mais informações de alguma operação ou repetir palavras e frases como "Hello World"<br>

> [!NOTE]
> Comandos podem ser usados em qualquer Linux pois se tratam do mesmo Kernel(Cérebro)

## Glossário <br>
- sudo: grupo padrão do Linux <br>
- root: é um administrador, gerencia outros usuários  <br>
- grep: é um filtro que vai pesquisar apenas o que você deseja(vbox, pastas, etc) <br>
- vbox: prefixo que inicia normalmente os nomes dos módulos do VirtualBox<br>
- apt: arquivos padrões do Linux <br>
- $USER: usuário da maquina
- build essentials: ferramento que compila código-fonte <br>
- dkms: recompilador de aplicações para ser compativel com o Kernel do Guest<br>
- ls: listar algo

