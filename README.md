# LauncherAIAPK
Distribuição do Aura Launcher e da Luna para computador.

## Celular — 1.182.1 (474)

[Baixar o APK](https://raw.githubusercontent.com/Villamediana/LauncherAIAPK/main/aura.apk). Instale sobre a versão atual para preservar seus dados.

Atualize também o computador para receber os resultados visuais do Palco entre aparelhos.

<!-- luna-desktop -->
## Luna no computador

A mesma Luna do celular, no Windows e no Linux. Instala sem senha de administrador.

**Windows** — [LunaSetup-0.7.2.exe](https://github.com/Villamediana/LauncherAIAPK/releases/download/desktop-v0.7.2/LunaSetup-0.7.2.exe) · instala só pra você, em `%LOCALAPPDATA%\Programs\Luna`.
O Windows pode avisar "O Windows protegeu o computador": clique em **Mais informações → Executar assim mesmo** (o instalador ainda não é assinado; isso não pede senha).
Se o computador bloquear instaladores, use a versão que roda de qualquer pasta: [Luna-0.7.2-win-portable.zip](https://github.com/Villamediana/LauncherAIAPK/releases/download/desktop-v0.7.2/Luna-0.7.2-win-portable.zip) — descompacte e abra `Luna.exe`.

**Linux** — [Luna-0.7.2-x86_64.AppImage](https://github.com/Villamediana/LauncherAIAPK/releases/download/desktop-v0.7.2/Luna-0.7.2-x86_64.AppImage) · `chmod +x` e abra; `./Luna-0.7.2-x86_64.AppImage --install` coloca no menu.

Depois de instalada, a Luna se atualiza sozinha: baixa a versão nova em segundo plano e ela entra ao reiniciar a Luna. Reabrir a janela da Luna ainda rodando na bandeja mostra a instância atual imediatamente.

`Ctrl+Shift+Espaço` em qualquer lugar: um toque abre a barra, segurar fala com ela. Fechar a janela deixa a Luna na bandeja.

Memória, conversa e chaves ficam em `%APPDATA%\Luna` (Windows) ou `~/.local/share/luna` (Linux).
<!-- /luna-desktop -->

## Correções 0.7.2 / 1.182.1

- Pareamento salvo antes de confirmar, preservado ao fechar o painel e protegido contra avisos antigos de despareamento.
- Instalação do `luna-hands` corrigida; a primeira atualização usa o pacote completo para reparar o launcher anterior.
- Presença entre aparelhos antes das memórias, tentativas de reconexão mais rápidas e retomada ao recuperar/trocar a rede do celular.
- Reabertura nativa da Luna já rodando, com ajustes, barra e ondas de voz preservados.

Instale sobre a versão atual e reinicie a Luna no PC. Se o vínculo já foi apagado pela versão anterior, pareie uma vez novamente.

## Novidades da integração

- Interface refinada mantendo ajustes, barra e ondas de voz; temas claro/escuro e opção de reduzir movimento.
- Correções de pareamento, sincronização, cancelamento e entrega entre aparelhos.
- Palco com criações, calculadoras, piano, acordes e arquivos no computador, incluindo resultados enviados pelo celular.
- Novas ações para buscar/abrir arquivos e pastas, usar o explorador e o clipboard, pesquisar na web, navegar, abrir configurações, arrastar e ajustar janelas.

Acesso a recursos exclusivos do celular continua pelo aparelho pareado. Controle nativo de Wayland, LAN direta e sincronização nativa de notas/tarefas no PC seguem pendentes. Fluxos físicos do Windows, voz e aparelhos reais ainda precisam ser conferidos no hardware.
