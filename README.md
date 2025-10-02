![Hello Kitty](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.nicepng.com%2Fmaxp%2Fu2q8a9a9i1e6a9o0%2F&psig=AOvVaw321p8wYYu_mZ80pqQSwfc5&ust=1759527177802000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCMi61tS7hpADFQAAAAAdAAAAABAL)

# 🌸 Guia de Comandos Linux 🌸  

✨ Bem-vinda(o) ao **guiaLinux**, um repositório útil para quem deseja aprender e revisar comandos fundamentais do Linux!  🌷💻  

---

## 📑 Sumário  
- [Introdução](#introducao)  
- [Comandos de Navegação 🧭](#comandos-de-navegacao)  
- [Comandos de Arquivos e Diretórios 📂](#comandos-de-arquivos-e-diretorios)  
- [Comandos de Usuários 👩‍💻](#comandos-de-usuarios)  
- [Comandos de Processos ⚙️](#comandos-de-processos)  
- [Comandos de Rede 🌐](#comandos-de-rede)  
- [Comandos de Permissões 🔑](#comandos-de-permissoes)  
- [Comandos de Pacotes 📦](#comandos-de-pacotes)  
- [Outros Comandos Úteis ✨](#outros-comandos-uteis)  
- [Conclusão 💖](#conclusao)  

---

<a id="introducao"></a>
## 🌺 Introdução  
O Linux é um dos sistemas operacionais mais poderosos e utilizados no mundo dos servidores.  
Neste guia, reuni **50+ comandos essenciais**, explicados de forma objetiva, para facilitar os estudos na disciplina de DevOps.

---

<a id="comandos-de-navegacao"></a>
## 🧭 Comandos de Navegação  

| Comando | Descrição |
|---------|-----------|
| `pwd` | Mostra o diretório atual 🌷 |
| `ls` | Lista arquivos e pastas |
| `ls -l` | Lista arquivos com detalhes |
| `ls -a` | Mostra inclusive arquivos ocultos ✨ |
| `cd` | Navega entre diretórios |
| `cd ..` | Volta um diretório |
| `tree` | Exibe a estrutura de diretórios em formato de árvore 🌳 |
| `echo $HOME` | Mostra o diretório do usuário |

---

<a id="comandos-de-arquivos-e-diretorios"></a>
## 📂 Comandos de Arquivos e Diretórios  

| Comando | Descrição |
|---------|-----------|
| `touch arquivo.txt` | Cria um arquivo vazio |
| `cat arquivo.txt` | Mostra o conteúdo de um arquivo |
| `more arquivo.txt` | Exibe conteúdo página por página |
| `less arquivo.txt` | Similar ao more, mas com mais recursos |
| `head arquivo.txt` | Mostra as 10 primeiras linhas |
| `tail arquivo.txt` | Mostra as últimas 10 linhas |
| `nano arquivo.txt` | Edita arquivos no terminal ✍️ |
| `vim arquivo.txt` | Editor avançado no terminal |
| `mkdir pasta` | Cria uma pasta |
| `rmdir pasta` | Remove uma pasta vazia |
| `rm -r pasta` | Remove pasta e conteúdos |
| `cp origem destino` | Copia arquivos/pastas |
| `mv origem destino` | Move ou renomeia arquivos |
| `find / -name "arquivo"` | Busca arquivos pelo nome 🔍 |
| `wc -l arquivo.txt` | Conta linhas de um arquivo |

---

<a id="comandos-de-usuarios"></a>
## 👩‍💻 Comandos de Usuários  

| Comando | Descrição |
|---------|-----------|
| `whoami` | Mostra o usuário atual |
| `id` | Mostra ID do usuário |
| `who` | Lista usuários logados |
| `groups` | Mostra grupos do usuário |
| `adduser nome` | Adiciona um novo usuário |
| `passwd nome` | Altera senha do usuário 🔐 |
| `su nome` | Troca de usuário |
| `sudo comando` | Executa comando como root |

---

<a id="comandos-de-processos"></a>
## ⚙️ Comandos de Processos  

| Comando | Descrição |
|---------|-----------|
| `ps` | Lista processos ativos |
| `ps aux` | Mostra todos os processos |
| `top` | Exibe processos em tempo real |
| `htop` | Exibe processos (interface interativa 🌸) |
| `kill PID` | Encerra processo pelo PID |
| `killall nome` | Encerra todos processos pelo nome |
| `jobs` | Lista processos em background |
| `fg` | Traz processo para foreground |

---

<a id="comandos-de-rede"></a>
## 🌐 Comandos de Rede  

| Comando | Descrição |
|---------|-----------|
| `ping google.com` | Testa conectividade |
| `ifconfig` | Mostra configuração de rede |
| `ip a` | Mostra interfaces de rede |
| `netstat -tuln` | Exibe portas abertas |
| `ss -tuln` | Alternativa moderna ao netstat |
| `wget url` | Baixa arquivos da web 🌸 |
| `curl url` | Faz requisições HTTP |
| `scp arquivo user@host:/destino` | Copia arquivos entre máquinas |
| `ssh user@host` | Conecta em servidor remoto |

---

<a id="comandos-de-permissoes"></a>
## 🔑 Comandos de Permissões  

| Comando | Descrição |
|---------|-----------|
| `ls -l` | Mostra permissões de arquivos |
| `chmod 755 arquivo` | Modifica permissões |
| `chown user arquivo` | Troca dono de arquivo |
| `chgrp grupo arquivo` | Troca grupo de arquivo |

---

<a id="comandos-de-pacotes"></a>
## 📦 Comandos de Pacotes  

(Exemplo com **Debian/Ubuntu**)  

| Comando | Descrição |
|---------|-----------|
| `apt update` | Atualiza lista de pacotes |
| `apt upgrade` | Atualiza pacotes instalados |
| `apt install nome` | Instala pacote |
| `apt remove nome` | Remove pacote |
| `dpkg -i pacote.deb` | Instala pacotes `.deb` |
| `snap install nome` | Instala pacotes via Snap 🌸 |

---

<a id="outros-comandos-uteis"></a>
## ✨ Outros Comandos Úteis  

| Comando | Descrição |
|---------|-----------|
| `history` | Mostra histórico de comandos |
| `clear` | Limpa o terminal |
| `date` | Mostra a data atual |
| `cal` | Exibe calendário |
| `uptime` | Mostra tempo ligado do sistema |
| `df -h` | Mostra uso de disco |
| `du -h` | Mostra tamanho de arquivos/pastas |
| `free -h` | Mostra memória usada |
| `uname -a` | Mostra informações do sistema |
| `reboot` | Reinicia sistema |
| `shutdown now` | Desliga sistema |

---

<a id="conclusao"></a>
## 💖 Conclusão  

🌸 Este guia reúne os **principais comandos Linux** que você precisa conhecer para administração de sistemas e estudos de DevOps.   
Feito com muito 💕 e terminal `~$` mágico ✨  

---
