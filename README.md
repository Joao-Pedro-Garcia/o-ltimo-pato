# O Último Pato

Jogo 2D de caça aos patos em primeira pessoa, com terror psicológico progressivo.
Tudo em **um único arquivo**: `index.html` (HTML + CSS + JavaScript puro, sem dependências, sem internet).

## Como jogar
Abra `index.html` no navegador do celular, na horizontal. Funciona offline.

- Arraste para mirar · toque para atirar (ou modo "Toque direto" nas configurações)
- 6 cartuchos, recarga manual · 7 vidas, cada pato que escapa custa 1
- Cada pato que escapa leva o lago a um novo nível de tensão (7 níveis); o 7º escape provoca o colapso final
- Acertos seguidos aumentam o multiplicador (até x5); errar zera
- Pontos viram moedas para a loja de skins da arma (algumas skins só saem por conquistas)
- 14 conquistas e um tutorial interativo (menu → 🎓 Tutorial)
- Fique atento ao lago…

No computador: mouse mira/atira, `R` recarrega, `P`/`Esc` pausa.

## Balanceamento
Todos os valores (dificuldades, tipos de pato, tensão, multiplicador, moedas, skins)
ficam nos objetos `CONFIG` e `SKINS` no início do script.
