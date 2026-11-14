==========================================================================================
  MULTIDRIVE
  Dropbox, OneDrive e Google Drive num lugar só — no Linux, do jeito que funciona no Windows.
==========================================================================================

  >>> BAIXAR A VERSÃO MAIS NOVA:
      https://github.com/Xytake/multidrive-atualizacoes/releases/latest

  (English version below)


PARA QUE SERVE
--------------
O MultiDrive junta todas as suas contas de nuvem — quantas quiser, de Dropbox, OneDrive e
Google Drive — numa janela só, e também direto no gerenciador de arquivos (Dolphin, Arquivos,
Nemo...).

Você vê tudo o que está na nuvem SEM BAIXAR NADA e escolhe o que quer no computador:

  * Só na nuvem ............ aparece na lista, mas não ocupa espaço no PC.
  * Baixado por um tempo ... dois cliques abre o arquivo; ele sai do PC sozinho depois de um
                             tempo sem uso.
  * Neste PC ............... botão direito > "Manter neste PC": fica uma cópia fixa,
                             sincronizada nos dois sentidos.
  * Deixar só na nuvem ..... libera o espaço no PC na hora, sem apagar nada da nuvem.


O DIFERENCIAL
-------------
No Linux, os aplicativos gratuitos de nuvem fazem uma coisa só:

  * MultiDrive ........................ Dropbox + OneDrive + Google Drive, várias contas,
                                        janela própria, não baixa tudo. Grátis para uso pessoal.
  * Clientes oficiais / OneDriveGUI ... um serviço só; baixam a pasta inteira.
  * onedriver, Maestral ............... um serviço só; uma conta.
  * Integração do KDE/GNOME ........... só Google Drive; sem janela própria.
  * rclone ............................ faz tudo, mas só pelo terminal.
  * Insync ............................ vários serviços, mas é pago.

E mais:
  * Nuvens na lateral do gerenciador de arquivos, com ícones mostrando o que está na nuvem e o
    que está no PC, e um menu "MultiDrive" no clique direito.
  * Miniaturas de fotos e vídeos vindas da própria nuvem, sem baixar os arquivos.
  * Pesquisa na pasta e em todas as subpastas.
  * Painel de atividade: o que está subindo e descendo, com andamento, velocidade e tempo.
  * Proteção contra exclusão em massa e cópias de conflito — nada se perde.
  * Limite de velocidade de download e envio, para não pesar a internet.
  * Fica perto do relógio, inicia com o sistema e se atualiza sozinho.
  * Manual completo em português dentro do app (tecla F1).


INSTALAÇÃO FÁCIL — SEM TERMINAL
-------------------------------
Baixe UM dos arquivos em "Versões" (Releases), de acordo com o seu Linux:
https://github.com/Xytake/multidrive-atualizacoes/releases/latest

  Ubuntu, Linux Mint, Debian, Pop!_OS, Zorin, elementary
    Baixe:  multidrive_..._amd64.deb
    Como:   dois cliques no arquivo > abre o instalador do sistema > Instalar (pede a senha)

  Fedora, openSUSE
    Baixe:  multidrive-....x86_64.rpm
    Como:   dois cliques no arquivo > abre o instalador do sistema > Instalar

  CachyOS, Arch, Manjaro, EndeavourOS ou qualquer outro
    Baixe:  MultiDrive-...-instalador.run
    Como:   dois cliques > Executar > escolha as opções > Instalar (não pede senha)

Na primeira vez que abrir, o MultiDrive pode levar alguns minutos preparando o que falta (a
biblioteca de janelas e o rclone) — aparece uma barra de progresso. Depois disso, abre na hora.
Pronto: o MultiDrive aparece no menu de aplicativos. Procure por "MultiDrive".

OS DOIS CLIQUES NÃO FUNCIONARAM?
  * Abriu num editor de texto (arquivo .run): botão direito no arquivo > Propriedades >
    Permissões > marque "É executável" / "Permitir executar como programa" > dois cliques de novo.
  * No Ubuntu, o .run não abre com dois cliques: botão direito > "Executar como programa".
  * O .deb abriu num gerenciador de arquivos compactados: botão direito > Abrir com >
    "Instalação de programas" (ou "Instalador de pacotes").
  * Pelo terminal (qualquer caso):
      .deb:  sudo apt install ./multidrive_..._amd64.deb
      .rpm:  sudo dnf install ./multidrive-....x86_64.rpm
      .run:  sh MultiDrive-...-instalador.run

ATUALIZAR: o MultiDrive avisa quando houver versão nova — clique em "Atualizar agora". (Se
instalou por .deb ou .rpm, o sistema pede a sua senha.) Também dá para buscar na hora: botão
"Buscar atualizações".

DESINSTALAR:
  * Instalou pelo .run: botão direito no MultiDrive no menu de aplicativos >
    "Desinstalar o MultiDrive".
  * Instalou pelo .deb ou .rpm: pela central de programas do sistema, ou no terminal
    "sudo apt remove multidrive" / "sudo dnf remove multidrive".
Seus arquivos "neste PC" (pasta ~/MultiDrive) nunca são apagados ao desinstalar.


PRIVACIDADE
-----------
Sua senha fica só com o serviço (o login é feito no site oficial dele). O MultiDrive recebe
apenas uma autorização de acesso, guardada somente no seu computador. Nada é enviado a
servidores de terceiros.


LICENÇA
-------
(c) 2026 Paulo Xytake — https://github.com/Xytake
Licença PolyForm Noncommercial 1.0.0 (veja LICENSE.txt e COPYRIGHT.txt).
  * Uso pessoal gratuito — pode usar, estudar, modificar e compartilhar sem fins comerciais.
  * Créditos: o crédito a Paulo Xytake deve ser sempre mantido, e quem modificar acrescenta o
    próprio crédito dizendo o que alterou.
  * Empresas e uso comercial: licença paga — fale com o autor pelo GitHub.
  * É proibido vender o MultiDrive ou partes do código.
Usa o rclone (MIT, https://rclone.org) e o Qt for Python (LGPL v3, https://www.qt.io/qt-for-python).



==========================================================================================
  ENGLISH
  Dropbox, OneDrive and Google Drive in one place — on Linux, the way it works on Windows.
==========================================================================================

  >>> DOWNLOAD THE LATEST VERSION:
      https://github.com/Xytake/multidrive-atualizacoes/releases/latest


WHAT IT DOES
------------
MultiDrive brings all your cloud accounts — as many as you want, from Dropbox, OneDrive and
Google Drive — into a single window, and right into your file manager (Dolphin, Files, Nemo...).

You see everything in the cloud WITHOUT DOWNLOADING ANYTHING and choose what stays on your PC:

  * Cloud only ............. shows up in the list but takes no space on your PC.
  * Downloaded for a while . double-click opens the file; it leaves your PC on its own after a
                             while unused.
  * On this PC ............. right-click > "Manter neste PC" (Keep on this PC): a pinned copy,
                             synced both ways.
  * Cloud only again ....... frees the space on your PC at once, deleting nothing in the cloud.


WHAT MAKES IT DIFFERENT
-----------------------
On Linux, the free cloud apps each do one thing:

  * MultiDrive ........................ Dropbox + OneDrive + Google Drive, multiple accounts,
                                        own window, no full download. Free for personal use.
  * Official clients / OneDriveGUI .... one service; sync the whole folder.
  * onedriver, Maestral ............... one service; one account.
  * KDE/GNOME integration ............. Google Drive only; no own window.
  * rclone ............................ does everything, but terminal only.
  * Insync ............................ several services, but paid.

Plus: clouds in your file manager's sidebar with status icons and a right-click menu; thumbnails
straight from the cloud; search in all subfolders; activity panel; mass-deletion protection and
conflict copies; speed limits; lives next to the clock, starts with the system and updates
itself; built-in user manual (F1) — currently in Brazilian Portuguese.


EASY INSTALL — NO TERMINAL
--------------------------
Download ONE of the files from Releases, depending on your Linux:
https://github.com/Xytake/multidrive-atualizacoes/releases/latest

  Ubuntu, Linux Mint, Debian, Pop!_OS, Zorin, elementary
    Download: multidrive_..._amd64.deb
    How:      double-click it > the system installer opens > Install (asks for your password)

  Fedora, openSUSE
    Download: multidrive-....x86_64.rpm
    How:      double-click it > the system installer opens > Install

  CachyOS, Arch, Manjaro, EndeavourOS or anything else
    Download: MultiDrive-...-instalador.run
    How:      double-click > Run > pick the options > Install (no password)

The first time you open it, MultiDrive may take a few minutes preparing what is missing — a
progress bar shows up. After that, it opens instantly.

DOUBLE-CLICK DIDN'T WORK?
  * It opened in a text editor (.run file): right-click > Properties > Permissions > tick
    "Is executable" / "Allow executing as program" > double-click again.
  * On Ubuntu, the .run doesn't open with a double-click: right-click > "Run as a Program".
  * The .deb opened in an archive manager: right-click > Open with > "Software Install".
  * From a terminal:
      .deb:  sudo apt install ./multidrive_..._amd64.deb
      .rpm:  sudo dnf install ./multidrive-....x86_64.rpm
      .run:  sh MultiDrive-...-instalador.run

UPDATE: MultiDrive tells you when a new version is out — click "Atualizar agora" (Update now).
UNINSTALL: .run > right-click MultiDrive in the app menu > "Desinstalar o MultiDrive";
.deb/.rpm > your software center, or "sudo apt remove multidrive" / "sudo dnf remove multidrive".
Your "on this PC" files (~/MultiDrive) are never deleted. Note: the interface is currently in
Brazilian Portuguese.


PRIVACY
-------
Your password stays with the service (you sign in on its official website). MultiDrive only
receives an access authorization, stored only on your computer. Nothing is sent to third parties.


LICENSE
-------
(c) 2026 Paulo Xytake — https://github.com/Xytake
PolyForm Noncommercial License 1.0.0 (see LICENSE.txt and COPYRIGHT.txt).
  * Free for personal use — you may use, study, modify and share it for noncommercial purposes.
  * Credits: the credit to Paulo Xytake must always be kept, and whoever modifies it adds their
    own credit stating what they changed.
  * Companies and commercial use: paid license — contact the author on GitHub.
  * Selling MultiDrive or any part of its code is not allowed.
Uses rclone (MIT) and Qt for Python (LGPL v3).
