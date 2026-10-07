# TRICOMA · Clareira Zero

RPG de criaturas em pixel art para jogar com os amigos: cada um entra com o próprio personagem, captura e treina seus Terpmons, enfrenta os treinadores das rotas e duela ou caça junto com quem está na mesma sala.

Este repositório guarda só as versões prontas do jogo, para baixar.

## Baixar

- [Windows (64 bits)](https://github.com/AuggieAlmeida/tricoma/releases/latest/download/Tricoma-Windows-x86_64.zip)
- [Linux (64 bits)](https://github.com/AuggieAlmeida/tricoma/releases/latest/download/Tricoma-Linux-x86_64.zip)
- [macOS (Intel e Apple Silicon)](https://github.com/AuggieAlmeida/tricoma/releases/latest/download/Tricoma-macOS-universal.zip)

Todas as versões ficam em [Releases](https://github.com/AuggieAlmeida/tricoma/releases).

## Como abrir

**Windows:** extraia o ZIP inteiro numa pasta sua (por exemplo, Documentos) e abra `Tricoma.exe`. O executável não é assinado, então o Windows pode pedir confirmação na primeira vez.

**Linux:** extraia o ZIP e execute `./Tricoma.x86_64`. Se o sistema tiver tirado a permissão de execução, rode antes `chmod +x ./Tricoma.x86_64`.

**macOS:** extraia o ZIP e arraste o `Tricoma.app` para a pasta Aplicativos antes de abrir. O app não é notarizado pela Apple, então na primeira vez o macOS avisa que não consegue verificá-lo: vá em Ajustes do Sistema › Privacidade e Segurança e clique em **Abrir mesmo assim**. Em versões anteriores ao macOS 15, clique com o botão direito no app e escolha **Abrir**. Isso só é preciso uma vez; as atualizações seguintes abrem direto.

Não precisa instalar mais nada.

## Jogar com os amigos

Na tela inicial, um jogador escolhe **Hospedar** e os outros **Entrar**, com o IP do anfitrião (da rede local ou de uma rede virtual, como Tailscale ou Radmin VPN) e a mesma porta UDP, 24567 por padrão. O firewall de quem hospeda precisa liberar UDP nessa porta; no Mac, se o firewall estiver ligado, ele pergunta na primeira vez que o jogo hospeda. Todos na sala usam a mesma versão do jogo.

## Atualizações

Ao abrir, o jogo procura a versão mais nova, baixa sozinho, confere o arquivo e mostra **Reiniciar para atualizar**. Os personagens ficam salvos no computador, fora da pasta do jogo, e passam intactos pela atualização. O que mudou em cada versão aparece em **Novidades**, na tela inicial.

Achou um bug ou tem uma ideia? Use o botão **Bugs e ideias**, na tela inicial ou nos Ajustes.

---

Feito com o [Godot Engine](https://godotengine.org/license).
