# Stara — Uma história de evolução

Apresentação interativa em HTML, CSS, JavaScript e SVG, pronta para GitHub e Vercel.
Inclui 13 narrações, trilha instrumental com clima de fazenda e interface adaptada para celular.
Reprodução em 1,25×. Narração do primeiro capítulo em 60% do volume original.

## 1. Colocar no GitHub

1. Extraia o ZIP no computador.
2. Crie um repositório no GitHub (ex.: `stara-apresentacao`).
3. No repositório, use **Add file → Upload files**.
4. Envie todos os arquivos e as pastas extraídos. O arquivo `index.html` deve aparecer diretamente na raiz do repositório, junto com `vercel.json`, `README.md`, `audios/` e `img/`.
5. Clique em **Commit changes**.

Envie o conteúdo extraído, não o ZIP. Preserve as pastas `audios/` e `img/` e os nomes dos arquivos.

## 2. Publicar no Vercel

1. Acesse https://vercel.com e entre com sua conta do GitHub.
2. Selecione **Add New → Project** e importe o repositório.
3. Use **Framework Preset: Other** e mantenha **Root Directory** na raiz (`./`).
4. Mantenha **Build Command** e **Install Command** vazios e **Output Directory** como `.`.
5. Clique em **Deploy**.

O arquivo `vercel.json` já define essas opções. Esta apresentação é estática e não precisa de `package.json`, npm, frameworks ou variáveis de ambiente.

Documentação oficial: https://vercel.com/docs/builds/configure-a-build

## 3. Abrir e compartilhar

Abra o endereço gerado pelo Vercel e toque em **Começar** para liberar o áudio.
Compartilhe esse endereço pelo WhatsApp. Assim, o destinatário abre tudo pelo navegador, com imagens, áudio e trilha carregados no mesmo endereço.
No celular, gire o aparelho para a horizontal para ampliar a imagem.

## Organização dos arquivos

- `index.html`: apresentação e controles.
- `vercel.json`: configuração de publicação.
- `audios/01.mp3` a `audios/13.mp3`: narrações na ordem definida.
- `audios/trilha-sonora.mp3`: trilha instrumental.
- `img/`: logo e imagens utilizadas.
- `ordem-dos-audios.json`: relação das narrações com os arquivos originais.

## Personalizar

No `index.html`, edite `NOMES_DO_GRUPO` e `TURMA` para exibir os participantes.
Os valores `VELOCIDADE`, `VOLUME_PRIMEIRO_CAPITULO` e `VOLUME_DA_TRILHA` controlam reprodução e volumes.

## Verificar após publicar

Abra o link no computador e no celular. Toque em Começar, pause, troque de capítulo e confirme o áudio e a trilha.
Se faltar imagem ou áudio, confira se as pastas foram enviadas por inteiro, com a mesma capitalização dos nomes.
