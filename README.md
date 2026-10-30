# Mídia e Performance

O cara no vaso atravessa o painel de mídia até a CONVERSÃO, desviando do T-rex
e do maluco. Junte 3 estrelas e o criativo 300x250 de 150KB, bombado no limite
do peso, entra na frente segurando tudo.

## Arquivos

- `index.html`: o jogo completo, o que abre pelo link. Usa o mesmo motor do
  Vai dá PT (tela cheia na horizontal, dificuldade, arraste analógico, → corre,
  ← segura), copiado pra cá; o jogo original não foi mexido. Roda sem ranking.
- `banner/index.html`: a peça 300x250 jogável, versão compacta pra mídia.
- `midia-e-performance-300x250.zip`: o banner pronto pra subir no Google Ads /
  DV360 / CM360 (HTML5, com `ad.size` e `clickTag`, que aponta pro jogo
  completo). Regere o zip sempre que mexer no `banner/index.html`.
- `trex-original.png` e `maluco-original.png`: os prints originais, de onde
  saem os recortes embutidos nos dois HTML.

## Rodar

Abrir o `index.html` no navegador resolve. Atalhos de teste: `?meta=300`
encurta a travessia e `?escudo=1` já começa com o criativo em campo (o banner
aceita `?escudo=1`).

## Controles

Celular deitado: toque e arraste pra mover entre as raias; arrastar pros lados
acelera ou segura. Teclado: ↑ ↓ (ou W/S) trocam de raia, → corre, ← segura,
P pausa, M silencia.
