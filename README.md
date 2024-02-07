# Aula-linux-7/2/2024
EX.1- Criar um container com Debian e que seja interativo, que dentro dele tenha neofetch.
Comandos:
1- podman pull debian
2- podman run -it debian
3- apt update && apt install neofetch
4- (selecionar:"y" para continuar)
5- neofetch

EX.2- Criar um container com o Debian destacável, que tenha python.
Comandos:
1- podman run -dt debian 
2- podman exec -it NOME DO CONTAINER bash
3- apt install python3.11
4- (selecionar: "y" para continuar)

EX.3- Criar um container Fedora, interativo que tenha python e que tenha a ferramenta yt-dlp.
Comandos:
1-  podman pull fedora
2- podman run -it fedora
3- dnf update && dnf install python.3
4- (selecionar "y" para continuar)
5- sudo dnf install yt-dlp
6- (selecionar "y" para continuar)

Ex.4- Criar um container Fedora, interativo que tenha python e que tenha a ferramenta gallery-dl.
Comandos:
1-  podman pull fedora
2-  podman run -it fedora
3-  dnf update && dnf install python.3
4- (selecionar "y" para continuar)
5- sudo dnf install gallery-dl
6- (selecionar "y" para continuar)






