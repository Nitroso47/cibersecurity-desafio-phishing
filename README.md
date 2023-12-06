# Phishing para captura de senhas do Facebook

1- Antes de começar, verificar na VM a opção correta da rede
> Clicar em máquina (kalil - Linux), em seguida configurações, depois em rede e nesta opção selecionar Attached to: Bridge Adapter. Para finalizar a maquina (VM) precisa ser reiniciada.

2- Lista de comandos setoolkit

> Precisa começar como root. Utiliza o comando sudo su (em seguida digita a senha).
> Digita setoolkit (vai abrir o program setoolkit).
> Seleciona o tipo de ataque: no nosso caso a opção 1 (social-
engineering attacks), em seguida clica enter.
> Em seguida serão disponibilizados os vetores de ataque. No nosso caso será selecionado a opção 2 (website attack vectors),
em seguida confirma a opção clicando enter.
> Em seguida são disponibilizadas novas opções de ataque. No nosso caso foi selecionada a opção 3 (credential harvester attack method). Finaliza clicando enter.
> Em seguida foi selecionada a opção 2 (site cloner). Finaliza 
clicando enter.
> Neste momento vai estar rodando um pequeno servidor com a página falsa. Só precisa confirmar o IP da máquina (basta clicar enter).
> Em seguida basta colocar a URL da página a ser clonada. No nosso caso:http://www.facebook.com. Finaliza clicando enter.
> Neste momento ele começa a criar a página falsa (leva alguns minutos para ficar pronto).
> Para acessar basta copiar e colar o IP fornecido na linha:
IP address for the POST back in Harvester/Tabnabbing. O IP foi
colado em uma guia de um navegador ao da VM.
> Assim que é colocado a senha e demais infos começam a surgir
notificações de acesso no teminal do Kalil-Linus.

![Screenshot_2023-12-06_14_44_12](https://github.com/Nitroso47/cibersecurity-desafio-phishing/assets/151847778/0e650700-0713-4f22-ae4d-83be49636598)

