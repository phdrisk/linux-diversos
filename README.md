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
