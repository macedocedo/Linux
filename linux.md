
# Comandos CMD

cd = entrar pasta 

cd.. = Voltar pasta

dir = Listar

mkdir = criar pasta

cls  = Limpar

-----------------------------------\\--------------------------------------

# Comandos Linux

$ = usuario comum

. # = permissão de root

~ = home do usuario (/root)

-----------------------------------\\--------------------------------------

# linux----Base

mkdir = criar pasta

touch = criar um arquivo

tree = Estrutura de pasta

rm = deleta arquivo

pwd = mostra diretorio atual

df -h = Exibe informações sobre espaço 

htop / top = Gerenciador de tarefas linux 

cd /var/log = Visualizar arquivos log 

ls -alhS  = Listar pelo tamanho de arquivo  

ls -l = lista

truncate = limpa arquivos temp

cd /temp = Arquivos temporarios

cd /opt = Sistemas instalados

cd /Etc = Configuração de sistema (caso precise passar parametros)

cd /bin || /sbin = comandos root (sbin)

cd /home = Diretorio do usuario

cd /dev || /midia = caso coloque hd ou pendrive

cd /root = adm da maquina

cd /proc = Configuração da maquina

vim = editor de arquivo

cp = copia arquivos || pastas

cat = Leitura do arquivo

find -name = busca o arquivo ou pasta

tail -f = vejo arquivo em tempo real

grep nomedoarquivo * = filtro geral

MV = renomear aquivo

NCDU = verifica seu disco e organiza

uname = versão do SO

lsblk = informações disco

rm -rf dpkg.log. < sempre verificar com outros analistas >

-----------------------------------\\--------------------------------------

# linux----limpar log LINUX / Problema no disco

Acessando via bastian

cd /var/log

tar -cvzf apport.log.2024-01-23 apport.log

truncate -s0 apport.log

tar - cvzf syslog-2024-01-23 syslohh && truncate -s0

history | grep journal

systemctl status walinuxagent = Mostra os ultimos erros

sudo su

df -h

cd /var/log

ls -alhs

truncate -s0 __nomedoarquivo__

systemctl status walinuxagent

Verificar logs / tamanho do log / 

-----------------------------------\\--------------------------------------

# linux----Filtro

-H = Suporte linux

-help = Suporte linux

--verbose = 

-rf > PERMANENTE 

ip a > mostra ip

grep = filtrar nome








