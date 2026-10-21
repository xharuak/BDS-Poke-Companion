Prévia **0.9.10** do BDS Poké Companion para **Firefox e Zen Browser para computador**.

### Download

Baixe o [ZIP da prévia 0.9.10](https://github.com/xharuak/BDS-Poke-Companion/raw/refs/heads/main/downloads/BDS-Poke-Companion-v0.9.10-firefox.zip). Extraia e carregue `manifest.json` em `about:debugging#/runtime/this-firefox` → **Carregar complemento temporário…**. Recarregue as páginas do jogo com F5.

**Este ZIP não é assinado pela Mozilla e a instalação é temporária.** É necessário carregá-lo novamente após reiniciar o navegador. Para instalação permanente, use a [versão disponível no Mozilla Add-ons](https://addons.mozilla.org/en-US/firefox/addon/bds-pok%C3%A9-companion/).

### Acesso

Crie sua conta BDS, confirme seu e-mail e solicite a liberação manual em **fernando-petta@outlook.com**. O download não libera o acesso automaticamente. Use sua própria senha; não a envie ao suporte.

### Correções do Hunt Analyzer

- Corrigida a extrapolação de XP entre mapas que gerava estimativas irreais, como 360kk em Ancient Marowak.
- Kanto e Outland mostram monstros individuais: 16 spawns são 16 monstros. Grupos de quatro ficam restritos a Orre e Nightmare.
- Estimativas usam XP/abate e respawn observados no próprio alvo, com a configuração atual da conta. Sem dados suficientes, aparece aguardando medição.
- O tempo de combate respeita a cadência de ataques e a área observada. TMs sem amostra não acrescentam dano presumido.
- Leitura passiva do Hunt Analyzer nativo para exibir sua taxa e conferir os abates no mesmo intervalo.
- Mantida a identificação do exemplar, TMs, Golden Bicycle e Golden Lure Apricorn da conta.

Validação local: **175 testes automatizados e 31 verificações em um perfil isolado do Zen**, com quatro contas simuladas. As estimativas não reproduzem integralmente o servidor do jogo.

Confira o hash do ZIP em [SHA256SUMS.txt](downloads/SHA256SUMS.txt). [Instruções completas e recursos](https://github.com/xharuak/BDS-Poke-Companion#readme).
