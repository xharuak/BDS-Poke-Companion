# BDS Poké Companion

Extensão para quem joga **Poke Idle World** e quer consultar Pokémon, IVs, drops, ginásios e informações da hunt em um painel dentro do jogo. Compatível com **Firefox e Zen Browser para computador**.

## Baixar e instalar

**[Instalar pelo Mozilla Add-ons](https://addons.mozilla.org/en-US/firefox/addon/bds-pok%C3%A9-companion/)**

Essa é a opção para instalação permanente e atualizações pela loja. Em 21/10/2026, a versão disponível no Mozilla Add-ons é a **0.9.8**.

**[Baixar a prévia 0.9.10 para Firefox/Zen](https://github.com/xharuak/BDS-Poke-Companion/raw/refs/heads/main/downloads/BDS-Poke-Companion-v0.9.10-firefox.zip)** · [Notas da prévia](https://github.com/xharuak/BDS-Poke-Companion/blob/main/NOTAS-0.9.10.md)

A prévia inclui as correções mais recentes do Hunt Analyzer. O ZIP não é assinado pela Mozilla e deve ser carregado temporariamente, seguindo as instruções abaixo.

## Cadastro e liberação de acesso

A instalação é gratuita. Para usar os recursos:

1. Abra a extensão e crie sua conta **BDS**, independente da conta do jogo.
2. Confirme seu e-mail pelo link recebido.
3. Aguarde a aprovação manual. Instalar a extensão ou confirmar o e-mail não libera o acesso automaticamente.

Cada pessoa cria a própria senha. Não envie sua senha ao suporte. Esta versão não tem cobrança integrada; a autorização pode ter prazo.


## Começar a usar

1. Com sua conta BDS liberada, abra [Poke Idle World](https://poke.idleworld.online/play).
2. Clique no ícone BDS do navegador e em **Ativar nas contas abertas**. Autorize o acesso ao site do jogo quando solicitado.
3. Abra a Pokédex, o inventário/equipe e os ginásios no jogo para iniciar as respectivas leituras.
4. Use o botão **+** da barra para abrir as abas e **Ctrl + clique** sobre um Pokémon para analisá-lo.
5. Na prévia 0.9.10, deixe o **Hunt Analyzer do próprio jogo** aberto para acompanhar a taxa nativa e conferir os abates. A medição de referência exige pelo menos 2 minutos e 20 abates após a punição de entrada.

## Instalar a prévia 0.9.10 temporariamente

1. Baixe o ZIP acima e extraia-o para uma pasta.
2. No Firefox ou Zen, abra `about:debugging#/runtime/this-firefox`.
3. Clique em **Carregar complemento temporário…** e selecione o arquivo `manifest.json` da pasta extraída.
4. Atualize as páginas do jogo com **F5** e faça o cadastro/login BDS.

O carregamento temporário precisa ser repetido após reiniciar o navegador. Para recarregar enquanto o navegador está aberto, use **Recarregar** na extensão em `about:debugging` e depois atualize as páginas do jogo. Para conferir o arquivo baixado, veja [SHA256SUMS.txt](downloads/SHA256SUMS.txt).

## Como funciona

A extensão observa informações recebidas ou exibidas pelo jogo e faz consultas e cálculos locais. Não executa automaticamente combates, capturas, compras, vendas ou movimentação do personagem.

As simulações e estimativas dependem dos dados disponíveis e não garantem vitória ou XP/h. Na prévia 0.9.10, Kanto e Outland usam monstros individuais; Orre e Nightmare usam grupos de quatro. Mapas sem medição suficiente ficam aguardando dados, sem uma taxa de XP inventada.

O login BDS usa Firebase para autenticação e controle de acesso. Os dados das contas do jogo permanecem no navegador. Leia a política em **Dados e privacidade**, dentro da extensão, ou na página do Mozilla Add-ons.
