<p align="center"><img src="multidrive.svg" width="128" alt="Ícone do MultiDrive"></p>

<h1 align="center">MultiDrive</h1>
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

<p align="center">© 2026 Paulo Xytake — Todos os direitos reservados.<br>
Uso gratuito. Não é permitido copiar, modificar, redistribuir ou vender o programa sem autorização do autor.<br>
Usa o <a href="https://rclone.org">rclone</a> (MIT) e o <a href="https://www.qt.io/qt-for-python">Qt for Python</a> (LGPL v3), baixados das fontes oficiais.</p>
