<p align="center"><img src="multidrive.svg" width="128" alt="Ícone do MultiDrive"></p>

<h1 align="center">MultiDrive</h1>
<p align="center">🇧🇷 Português · <a href="#-english">🇺🇸 English</a></p>
<p align="center"><b>Dropbox, OneDrive e Google Drive num lugar só — no Linux, do jeito que funciona no Windows.</b></p>

<p align="center"><a href="https://github.com/pauloxytake-pixel/multidrive-atualizacoes/releases/latest"><b>⬇️ Baixar a versão mais nova</b></a></p>

---

## Para que serve

O MultiDrive junta **todas as suas contas de nuvem** — quantas quiser, de Dropbox, OneDrive e Google Drive — numa
janela só, e também direto no gerenciador de arquivos (Dolphin, Arquivos, Nemo…).

Você **vê tudo o que está na nuvem sem baixar nada** e escolhe o que quer no computador:

- ☁️ **Só na nuvem** — aparece na lista, mas não ocupa espaço no PC.
- 🔵 **Baixado por um tempo** — dois cliques abre o arquivo; ele sai do PC sozinho depois de um tempo sem uso.
- ✅ **Neste PC** — botão direito → *Manter neste PC*: fica uma cópia fixa, sincronizada nos dois sentidos.
- ↩️ **Deixar só na nuvem** — libera o espaço no PC na hora, sem apagar nada da nuvem.

## O diferencial

No Linux, os aplicativos gratuitos de nuvem fazem **uma coisa só**:

| | Serviços | Sem baixar tudo | Janela própria | Várias contas | Grátis |
|---|---|---|---|---|---|
| **MultiDrive** | **Dropbox + OneDrive + Google Drive** | **✅** | **✅** | **✅** | **✅** |
| Clientes oficiais / OneDriveGUI | um serviço só | ❌ baixam a pasta inteira | ✅ | parcial | ✅ |
| onedriver, Maestral | um serviço só | parcial | parcial | ❌ | ✅ |
| Integração do KDE/GNOME | só Google Drive | ✅ | ❌ | ✅ | ✅ |
| rclone | todos | ✅ | ❌ só terminal | ✅ | ✅ |
| Insync | vários | parcial | ✅ | ✅ | ❌ pago |

E mais:

- **Nuvens na lateral do gerenciador de arquivos**, com ícones mostrando o que está na nuvem e o que está no PC,
  e um menu **MultiDrive** no clique direito.
- **Miniaturas** de fotos e vídeos vindas da própria nuvem, sem baixar os arquivos.
- **Pesquisa** na pasta e em todas as subpastas.
- **Painel de atividade**: o que está subindo e descendo, com andamento, velocidade e tempo restante.
- **Proteção contra exclusão em massa** e **cópias de conflito** — nada se perde.
- **Limite de velocidade** de download e envio, para não pesar a internet.
- Fica perto do relógio, **inicia com o sistema** e **se atualiza sozinho**.
- **Manual completo em português** dentro do app (tecla F1).

## Instalação fácil — sem terminal

1. Baixe o arquivo **`MultiDrive-…-instalador.run`** em [Versões](https://github.com/pauloxytake-pixel/multidrive-atualizacoes/releases/latest).
2. **Dois cliques** nele → **Executar**.
3. Escolha as opções (atalho na área de trabalho, iniciar com o sistema) → **Instalar**.

Pronto: o MultiDrive aparece no menu de aplicativos. O instalador **não pede senha**, instala só para o seu
usuário e baixa sozinho o que faltar. Feito para funcionar em CachyOS/Arch, Ubuntu, Debian, Mint, Fedora, openSUSE e outros.

> Se os dois cliques abrirem o arquivo num editor de texto: botão direito nele → **Propriedades** → **Permissões**
> → marque **“É executável”** e tente de novo. Ou, no terminal: `sh MultiDrive-…-instalador.run`

**Atualizar:** o MultiDrive avisa quando houver versão nova — é só clicar em *Atualizar agora*.
**Desinstalar:** botão direito no MultiDrive no menu de aplicativos → *Desinstalar o MultiDrive*.

## Privacidade

Sua senha fica só com o serviço (o login é feito no site oficial dele). O MultiDrive recebe apenas uma autorização
de acesso, guardada **somente no seu computador**. Nada é enviado a servidores de terceiros.

---

<h1 align="center">🇺🇸 English</h1>
<p align="center"><b>Dropbox, OneDrive and Google Drive in one place — on Linux, the way it works on Windows.</b></p>

<p align="center"><a href="https://github.com/pauloxytake-pixel/multidrive-atualizacoes/releases/latest"><b>⬇️ Download the latest version</b></a></p>

## What it does

MultiDrive brings **all your cloud accounts** — as many as you want, from Dropbox, OneDrive and Google Drive — into a
single window, and right into your file manager (Dolphin, Files, Nemo…).

You **see everything in the cloud without downloading anything** and choose what stays on your computer:

- ☁️ **Cloud only** — shows up in the list but takes no space on your PC.
- 🔵 **Downloaded for a while** — double-click opens the file; it leaves your PC on its own after a while unused.
- ✅ **On this PC** — right-click → *Keep on this PC*: a pinned copy, synced both ways.
- ↩️ **Cloud only again** — frees the space on your PC at once, without deleting anything from the cloud.

## What makes it different

On Linux, the free cloud apps each do **one thing**:

| | Services | Without downloading everything | Own window | Multiple accounts | Free |
|---|---|---|---|---|---|
| **MultiDrive** | **Dropbox + OneDrive + Google Drive** | **✅** | **✅** | **✅** | **✅** |
| Official clients / OneDriveGUI | one service | ❌ sync the whole folder | ✅ | partial | ✅ |
| onedriver, Maestral | one service | partial | partial | ❌ | ✅ |
| KDE/GNOME integration | Google Drive only | ✅ | ❌ | ✅ | ✅ |
| rclone | all | ✅ | ❌ terminal only | ✅ | ✅ |
| Insync | several | partial | ✅ | ✅ | ❌ paid |

Plus:

- **Clouds in your file manager's sidebar**, with icons showing what is in the cloud and what is on your PC, and a
  **MultiDrive** right-click menu.
- **Thumbnails** of photos and videos straight from the cloud, without downloading the files.
- **Search** in the folder and all its subfolders.
- **Activity panel**: what is uploading and downloading, with progress, speed and time left.
- **Mass-deletion protection** and **conflict copies** — nothing gets lost.
- **Download and upload speed limits**, so it doesn't hog your internet.
- Lives next to the clock, **starts with the system** and **updates itself**.
- Built-in **user manual** (F1) — currently in Brazilian Portuguese.

## Easy install — no terminal

1. Download **`MultiDrive-…-instalador.run`** from [Releases](https://github.com/pauloxytake-pixel/multidrive-atualizacoes/releases/latest).
2. **Double-click** it → **Run**.
3. Pick the options (desktop shortcut, start with the system) → **Install**.

Done: MultiDrive shows up in your app menu. The installer **asks for no password**, installs for your user only
and downloads whatever is missing. Made to work on CachyOS/Arch, Ubuntu, Debian, Mint, Fedora, openSUSE and others.

> If double-clicking opens the file in a text editor: right-click it → **Properties** → **Permissions** → tick
> **“Is executable”** and try again. Or, in a terminal: `sh MultiDrive-…-instalador.run`

**Update:** MultiDrive tells you when a new version is out — just click *Atualizar agora* (Update now).
**Uninstall:** right-click MultiDrive in the app menu → *Desinstalar o MultiDrive* (Uninstall).

> Note: the app's interface is currently in Brazilian Portuguese.

## Privacy

Your password stays with the service (you sign in on its official website). MultiDrive only receives an access
authorization, stored **only on your computer**. Nothing is sent to third-party servers.

---

<p align="center">© 2026 Paulo Xytake · <a href="LICENSE.md">PolyForm Noncommercial 1.0.0</a> + <a href="COPYRIGHT">permissão adicional</a><br>
🇧🇷 <b>Uso gratuito para todos, inclusive empresas.</b> Pode estudar, modificar e compartilhar sem fins comerciais, mantendo o crédito.
<b>É proibido vender</b> o MultiDrive ou partes do código — a venda é exclusiva do autor.<br>
🇺🇸 <b>Free to use for everyone, companies included.</b> You may study, modify and share it for noncommercial purposes, keeping the credit.
<b>Selling</b> MultiDrive or any part of its code <b>is not allowed</b> — selling is reserved to the author.<br><br>
Usa / uses <a href="https://rclone.org">rclone</a> (MIT) e/and <a href="https://www.qt.io/qt-for-python">Qt for Python</a> (LGPL v3).</p>
