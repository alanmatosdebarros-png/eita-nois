# Eita nóis · estúdio de conteúdo

Plataforma da equipe de social media: post em vídeo (briefing, revisão com linha do tempo e entrega), estáticos, motion graphics, projetos, quadro da equipe, calendário, oportunidades, acervo, Search Lab, insights e marcas criadas pela própria equipe.

- Roda inteira no navegador (Google Chrome). Os vídeos são lidos direto do computador de quem usa.
- A chave da API fica só no navegador de quem cola em Configurações.
- Fontes e logos licenciados das marcas não vão pro repositório: ficam salvos no navegador.

## Apps pro (pasta `apps/`)

Versões web oficiais, sem alteração no código, destes projetos de código aberto do time ArtCraft (licença MIT ou Apache-2.0, à escolha; os textos das licenças estão em cada pasta):

- `apps/photocraft` · PhotoCraft 0.9.0 · https://github.com/storytold/photocraft
- `apps/vectorcraft` · VectorCraft 0.11.0 · https://github.com/storytold/vectorcraft
- `apps/filmcraft` · FilmCraft 0.8.0 · https://github.com/storytold/filmcraft
- `apps/effectcraft` · EffectCraft 0.10.0 · https://github.com/storytold/effectcraft
- `apps/designcraft` · DesignCraft 0.8.0 · https://github.com/storytold/designcraft

Única mudança: o arquivo `.wasm` de cada app vai comprimido em gzip e dividido em partes (o envio pelo GitHub limita o tamanho de cada arquivo), e o `index.html` de cada app junta as partes antes de iniciar. Copyright (c) 2026 ArtCraft Team e contribuidores. O nome e a marca ArtCraft são do ArtCraft Team e não fazem parte desta plataforma.

Biblioteca de fontes: Google Fonts (variáveis) e Annotation Mono (OFL).
