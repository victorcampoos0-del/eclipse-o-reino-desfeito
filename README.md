# ECLIPSE — O Reino Desfeito (v2 independente)

Protótipo jogável HTML5 sem dependências externas obrigatórias. Abra `index.html` diretamente para jogar em desktop; para PWA/service worker use um servidor HTTP estático. Na Vercel, configure a raiz do projeto como a raiz do repositório e use deploy estático, sem comando de build.

## Controles

- Teclado: A/D ou setas movimenta; Espaço/W/↑ pula; J/K ataca/interage; L esquiva; I cura; P/Esc pausa.
- Toque: joystick esquerdo e losango de ações à direita (△ pular, □ atacar/interagir, × esquivar, ○ curar). Botões suportam toques simultâneos e cancelamento.
- Landscape é recomendado; a interface pede rotação em telas estreitas na vertical.

## Conteúdo desta fatia

- Região inicial industrial desenhada localmente em Canvas, com plataformas, partículas, luzes, ruínas e protagonista original de braço mecânico à esquerda.
- Movimento com aceleração, gravidade, plataformas e esquiva com invulnerabilidade; ataques com alcance, custos, recuperação e inimigos telegráficos.
- Cura limitada, dois checkpoints, morte/retorno, salvamento local versionado, menu, pausa e primeiro chefe com fases e telegraph.
- Manifest e cache offline básico do shell. Salvamento usa localStorage versão 1; não promete persistência absoluta no iOS.

## Limitações conhecidas

- Este primeiro vertical slice não representa o conteúdo final da visão mestre. A arte é ilustração procedural em Canvas, não spritesheet final; áudio, diálogos interativos, inventário, caminhos com habilidades e conclusão narrativa expandida estão pendentes.
- O deploy deve ser validado após a conexão do repositório ao Vercel; o erro 404 anterior não prova a causa sem inspeção do deploy original.
- Sem iPhone físico disponível, validação tátil deve ser feita em Safari real antes de declarar compatibilidade física.

## Decisões narrativas preservadas

O protagonista continua sendo um experimento ligado à tentativa de vencer a morte. Elias Veyr, Lucien Veyr e Vespera não recebem explicações novas aqui. A incerteza entre memória e continuidade pessoal permanece aberta. O primeiro chefe, o Carcereiro de Bronze, é uma sentinela original do complexo industrial, sem revelar a identidade do protagonista.