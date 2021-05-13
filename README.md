# linux-diversos

# UPGRADE
```
/ETC/APT/SOURCES.LIST
```

# iniciar noip
- [sudo]  /usr/local/bin/noip2

# link simbolico (alias)
- ln -s /var/log/boot.log /home/usuario/novoarquivo -> cria um referencia dentro /home/usuario/novarquivo apontando para o boot.log
- ls -lah (mostra o link)

# liberar firewall
- install ufw
- ufw disable / enable
- ufw allow 3389/tcp

# instalar version (R)
- library(devtools)
- install_version(package, version=)

# PROCURAR PALAVRA EM ARQUIVO
```
sudo grep -Ril "texto" /
ack "texto" (apt intall ack-grep)
ou 

find / -type f -exec grep -H 'text-to-find-here' {} \;
```
# CRONTAB
```
alterar permissao do arquivo com chmod +x arquivo.sh

Minuto: 0-59 
Hora: 0-23 
Dia do mês: 1-31 
Mês: 1-12 
Dia da semana: 0-6, onde domingo = 0, segunda = 1 etc

00  00 * * * /home/phdrisk/arquivo.sh

opcoes [-e - edita, -l - lista, -r - deleta]

```

