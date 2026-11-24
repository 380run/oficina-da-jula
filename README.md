# Oficina da Jula

Página única e interativa que ensina às crianças, em 3D, para que serve cada peça da **Jula**, a Chevrolet C10 1977 do livro *Jula: quase tudo tem conserto* ([julathetruck.com.br](https://www.julathetruck.com.br/)).

- Modelo 3D pintado à mão que se **desmonta em vista explodida**, com etiquetas nas peças.
- 10 peças: cabine e caçamba, chassi, motor, radiador, bateria, faróis, retrovisores, cardã e diferencial, freio a disco, rodas e pneus.
- Explicação curta, curiosidade e **narração** de cada peça (gravações em `audio/`; sem elas, usa a voz do aparelho).
- Brincadeira **“Ache a peça”**.
- Funciona sem instalar nada: HTML, CSS e JavaScript puros, com [three.js r128](https://threejs.org/) incluído em `js/` (licença MIT).

## Links diretos (para os QR codes do livro)

Acrescente o nome da peça depois de `#`:

| Peça | Endereço |
| --- | --- |
| Cabine e caçamba | `.../#carroceria` |
| Chassi | `.../#chassi` |
| Motor | `.../#motor` |
| Radiador | `.../#radiador` |
| Bateria | `.../#bateria` |
| Faróis | `.../#farol` |
| Retrovisores | `.../#retrovisor` |
| Cardã e diferencial | `.../#eixo` |
| Freio a disco | `.../#freio` |
| Rodas e pneus | `.../#rodas` |

## Publicar no GitHub Pages

1. Crie um repositório (por exemplo `oficina-jula`) e envie todos estes arquivos para a branch `main`.
2. Em **Settings → Pages**, escolha *Deploy from a branch*, branch `main`, pasta `/ (root)`.
3. Em alguns minutos a página fica em `https://<seu-usuario>.github.io/oficina-jula/`.
4. Opcional: para usar `oficina.julathetruck.com.br`, crie um arquivo `CNAME` com esse endereço e um registro CNAME no Registro.br apontando para `<seu-usuario>.github.io`.

## Narração

Os 11 áudios em `audio/` (apresentação + 10 peças) foram gerados com a voz neural brasileira **Francisca** (Microsoft, `pt-BR-FranciscaNeural`, velocidade −8%), a partir dos textos `say` do `index.html`. Os roteiros estão em `roteiros.md`.

Para trocar uma narração, substitua o MP3 com o mesmo nome (`intro.mp3`, `motor.mp3`…). Se algum arquivo faltar, a página usa a voz do aparelho só para aquela peça.

---
Modelo ilustrativo, fora de escala. Textos e projeto: Projeto Jula · Bruno Azevedo.
