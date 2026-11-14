<p align="center"><img src="multidrive.svg" width="128" alt="Ícone do MultiDriveX"></p>

<h1 align="center">MultiDriveX</h1>
<p align="center">🇧🇷 Português · <a href="#-english">🇺🇸 English</a></p>
<p align="center"><b>Dropbox, OneDrive e Google Drive num lugar só — no Linux, do jeito que funciona no Windows.</b></p>

<p align="center"><a href="https://github.com/Xytake/MultiDriveX/releases/latest"><b>⬇️ Baixar a versão mais nova</b></a></p>

---

## Para que serve

O MultiDriveX junta **todas as suas contas de nuvem** — quantas quiser, de Dropbox, OneDrive e Google Drive — numa
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
| **MultiDriveX** | **Dropbox + OneDrive + Google Drive** | **✅** | **✅** | **✅** | **✅ uso pessoal** |
| Clientes oficiais / OneDriveGUI | um serviço só | ❌ baixam a pasta inteira | ✅ | parcial | ✅ |
| onedriver, Maestral | um serviço só | parcial | parcial | ❌ | ✅ |
| Integração do KDE/GNOME | só Google Drive | ✅ | ❌ | ✅ | ✅ |
| rclone | todos | ✅ | ❌ só terminal | ✅ | ✅ |
| Insync | vários | parcial | ✅ | ✅ | ❌ pago |

E mais:

- **Nuvens na lateral do gerenciador de arquivos**, com ícones mostrando o que está na nuvem e o que está no PC,
  e um menu **MultiDriveX** no clique direito.
- **Miniaturas** de fotos e vídeos vindas da própria nuvem, sem baixar os arquivos.
- **Pesquisa** na pasta e em todas as subpastas.
- **Painel de atividade**: o que está subindo e descendo, com andamento, velocidade e tempo restante.
- **Proteção contra exclusão em massa** e **cópias de conflito** — nada se perde.
- **Limite de velocidade** de download e envio, para não pesar a internet.
- Fica perto do relógio, **inicia com o sistema** e **se atualiza sozinho**.
- **Manual completo em português** dentro do app (tecla F1).

## Instalação fácil — sem terminal

Baixe **um** dos arquivos abaixo em [**Versões (Releases)**](https://github.com/Xytake/MultiDriveX/releases/latest), de acordo com o seu Linux:

| Seu Linux | Baixe | Como instalar |
|---|---|---|
| **Ubuntu, Linux Mint, Debian, Pop!_OS, Zorin, elementary** | `multidrivex_…_amd64.deb` | Dois cliques no arquivo → abre o instalador do sistema → **Instalar** (pede a sua senha) |
| **Fedora, openSUSE** | `multidrivex-….x86_64.rpm` | Dois cliques no arquivo → abre o instalador do sistema (Programas / YaST) → **Instalar** |
| **CachyOS, Arch, Manjaro, EndeavourOS** ou **qualquer outro** | `MultiDriveX-…-instalador.run` | Dois cliques → **Executar** → escolha as opções → **Instalar** (não pede senha) |

**Na primeira vez que abrir**, o MultiDriveX pode levar alguns minutos preparando o que falta (a biblioteca de janelas
e o rclone) — aparece uma barra de progresso. Depois disso, abre na hora.

Pronto: o MultiDriveX aparece no **menu de aplicativos**. Procure por “MultiDriveX”.

<details>
<summary><b>Os dois cliques não funcionaram?</b></summary>

- **Abriu num editor de texto (arquivo .run):** clique com o botão direito no arquivo → **Propriedades** →
  **Permissões** → marque **“É executável”** / “Permitir executar como programa” → dois cliques de novo.
- **No Ubuntu, o .run não abre com dois cliques:** botão direito no arquivo → **Executar como programa**.
- **O .deb abriu no Gerenciador de arquivos compactados:** botão direito → **Abrir com** → **Instalação de programas**
  (ou “Instalador de pacotes”).
- **Pelo terminal (qualquer caso):**
  - `.deb`: `sudo apt install ./multidrivex_…_amd64.deb`
  - `.rpm`: `sudo dnf install ./multidrivex-….x86_64.rpm`
  - `.run`: `sh MultiDriveX-…-instalador.run`
</details>

**Atualizar:** o MultiDriveX avisa quando houver versão nova — clique em **Atualizar agora**. (Se instalou por .deb ou
.rpm, o sistema pede a sua senha.) Também dá para buscar na hora: botão **Buscar atualizações**.

**Desinstalar:**
- Instalou pelo **.run**: botão direito no MultiDriveX no menu de aplicativos → **Desinstalar o MultiDriveX**.
- Instalou pelo **.deb** ou **.rpm**: pela loja/central de programas do sistema, ou no terminal
  `sudo apt remove multidrivex` / `sudo dnf remove multidrivex`.

Seus arquivos “neste PC” (pasta `~/MultiDrive`) nunca são apagados ao desinstalar.

## Privacidade

Sua senha fica só com o serviço (o login é feito no site oficial dele). O MultiDriveX recebe apenas uma autorização
de acesso, guardada **somente no seu computador**. Nada é enviado a servidores de terceiros.

---

<h1 align="center">🇺🇸 English</h1>
<p align="center"><b>Dropbox, OneDrive and Google Drive in one place — on Linux, the way it works on Windows.</b></p>

<p align="center"><a href="https://github.com/Xytake/MultiDriveX/releases/latest"><b>⬇️ Download the latest version</b></a></p>

## What it does

MultiDriveX brings **all your cloud accounts** — as many as you want, from Dropbox, OneDrive and Google Drive — into a
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
| **MultiDriveX** | **Dropbox + OneDrive + Google Drive** | **✅** | **✅** | **✅** | **✅ personal use** |
| Official clients / OneDriveGUI | one service | ❌ sync the whole folder | ✅ | partial | ✅ |
| onedriver, Maestral | one service | partial | partial | ❌ | ✅ |
| KDE/GNOME integration | Google Drive only | ✅ | ❌ | ✅ | ✅ |
| rclone | all | ✅ | ❌ terminal only | ✅ | ✅ |
| Insync | several | partial | ✅ | ✅ | ❌ paid |

Plus:

- **Clouds in your file manager's sidebar**, with icons showing what is in the cloud and what is on your PC, and a
  **MultiDriveX** right-click menu.
- **Thumbnails** of photos and videos straight from the cloud, without downloading the files.
- **Search** in the folder and all its subfolders.
- **Activity panel**: what is uploading and downloading, with progress, speed and time left.
- **Mass-deletion protection** and **conflict copies** — nothing gets lost.
- **Download and upload speed limits**, so it doesn't hog your internet.
- Lives next to the clock, **starts with the system** and **updates itself**.
- Built-in **user manual** (F1) — currently in Brazilian Portuguese.

## Easy install — no terminal

Download **one** of the files below from [**Releases**](https://github.com/Xytake/MultiDriveX/releases/latest), depending on your Linux:

| Your Linux | Download | How to install |
|---|---|---|
| **Ubuntu, Linux Mint, Debian, Pop!_OS, Zorin, elementary** | `multidrivex_…_amd64.deb` | Double-click it → the system installer opens → **Install** (asks for your password) |
| **Fedora, openSUSE** | `multidrivex-….x86_64.rpm` | Double-click it → the system installer opens (Software / YaST) → **Install** |
| **CachyOS, Arch, Manjaro, EndeavourOS** or **anything else** | `MultiDriveX-…-instalador.run` | Double-click → **Run** → pick the options → **Install** (no password) |

**The first time you open it**, MultiDriveX may take a few minutes preparing what is missing (the window library and
rclone) — a progress bar shows up. After that, it opens instantly.

Done: MultiDriveX shows up in your **app menu**. Search for “MultiDriveX”.

<details>
<summary><b>Double-click didn't work?</b></summary>

- **It opened in a text editor (.run file):** right-click the file → **Properties** → **Permissions** → tick
  **“Is executable”** / “Allow executing as program” → double-click again.
- **On Ubuntu, the .run doesn't open with a double-click:** right-click it → **Run as a Program**.
- **The .deb opened in an archive manager:** right-click → **Open with** → **Software Install**.
- **From a terminal (any case):**
  - `.deb`: `sudo apt install ./multidrivex_…_amd64.deb`
  - `.rpm`: `sudo dnf install ./multidrivex-….x86_64.rpm`
  - `.run`: `sh MultiDriveX-…-instalador.run`
</details>

**Update:** MultiDriveX tells you when a new version is out — click **Atualizar agora** (Update now). (If you installed
the .deb or .rpm, the system asks for your password.) You can also check right away: **Buscar atualizações** button.

**Uninstall:**
- Installed with the **.run**: right-click MultiDriveX in the app menu → **Desinstalar o MultiDriveX** (Uninstall).
- Installed with the **.deb** or **.rpm**: from your system's software center, or in a terminal
  `sudo apt remove multidrivex` / `sudo dnf remove multidrivex`.

Your “on this PC” files (`~/MultiDrive` folder) are never deleted when uninstalling.

> Note: the app's interface is currently in Brazilian Portuguese.

## Privacy

Your password stays with the service (you sign in on its official website). MultiDriveX only receives an access
authorization, stored **only on your computer**. Nothing is sent to third-party servers.

---

<p align="center">© 2026 Paulo Xytake · <a href="LICENSE.md">PolyForm Noncommercial 1.0.0</a> · <a href="COPYRIGHT">resumo</a><br>
🇧🇷 <b>Uso pessoal gratuito</b> — pode usar, estudar, <b>modificar</b> e compartilhar sem fins comerciais.
<b>Créditos:</b> o crédito a Paulo Xytake deve ser sempre mantido, e quem modificar acrescenta o próprio crédito dizendo o que alterou.
<b>Empresas e uso comercial: licença paga</b> — fale com o autor pelo <a href="https://github.com/Xytake">GitHub</a>.
<b>É proibido vender</b> o MultiDriveX ou partes do código.<br>
🇺🇸 <b>Free for personal use</b> — you may use, study, <b>modify</b> and share it for noncommercial purposes.
<b>Credits:</b> the credit to Paulo Xytake must always be kept, and whoever modifies it adds their own credit stating what they changed.
<b>Companies and commercial use: paid license</b> — contact the author on <a href="https://github.com/Xytake">GitHub</a>.
<b>Selling</b> MultiDriveX or any part of its code <b>is not allowed</b>.<br><br>
Usa / uses <a href="https://rclone.org">rclone</a> (MIT) e/and <a href="https://www.qt.io/qt-for-python">Qt for Python</a> (LGPL v3).</p>
