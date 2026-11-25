# OrcaGif – Criador e editor de GIF gratuito e privado

[English](README.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Español](README.es.md) · [العربية](README.ar.md) · [हिन्दी](README.hi.md) · [中文](README.zh.md) · [বাংলা](README.bn.md) · **Português** · [Bahasa Indonesia](README.id.md)

Transforme um vídeo em GIF, edite um GIF que você já tem ou salve o resultado como WebP ou WebM, bem menores. O OrcaGif é um único arquivo HTML. Tudo roda localmente no seu navegador: sem envio de arquivos, sem conta, sem cookies.

## Início rápido
1. Abra `OrcaGif.html` no seu navegador.
2. Escolha uma guia no topo: **🎬 Vídeo para GIF** (criar um GIF a partir de um vídeo) ou **🎨 Editor de GIF** (editar um GIF, imagem, vídeo, WebP ou WebM que você já tem).
3. Escolha o tipo de arquivo (GIF, WebP ou WebM), clique no botão azul e baixe o resultado.

> O guia “Como funciona – guia rápido e perguntas frequentes” no topo da página explica os mesmos passos em palavras simples, nos 10 idiomas.

## Qual tipo de arquivo escolher?
- **GIF** funciona em qualquer lugar (chats, fóruns, e-mail), mas os arquivos são maiores. Na dúvida, escolha GIF.
- **WebP** é bem menor que o GIF, tem melhor aparência e pode ter fundo transparente. Todos os navegadores atuais o exibem; alguns programas antigos não.
- **WebM** é o menor e mais fluido, mas é um vídeo: sem fundo transparente, e criá-lo leva mais tempo do que o próprio trecho (é gravado em tempo real – mantenha a guia em primeiro plano).
- **Qualidade** (WebP e WebM): alta, média ou baixa. Qualidade menor gera um arquivo menor.
- Se WebP ou WebM estiver esmaecido, seu navegador não consegue criar esse formato. Use uma versão atual do Chrome, Edge ou Firefox.

## Criar um GIF a partir de um vídeo – passo a passo
1. Clique na guia **🎬 Vídeo para GIF**.
2. Clique no botão de arquivo à esquerda e escolha um vídeo do seu dispositivo (MP4 e WebM funcionam em todos os navegadores modernos; MKV e HEVC dependem do navegador e do dispositivo). Nada é enviado, e até arquivos de vários GB funcionam.
3. Escolha a parte que quer: arraste na barra abaixo do vídeo, use **Definir início aqui** / **Definir fim aqui** (teclas `I` / `O`) ou digite os tempos. **▶ Reproduzir trecho** mostra uma prévia. Trechos curtos de 2 a 6 segundos funcionam melhor.
4. Defina a **Largura de saída** (a largura do GIF; 480 é um bom começo) e os **FPS** (quadros por segundo; 15 parece fluido). Números menores geram um arquivo menor.
5. Escolha o tipo de arquivo e clique no botão azul. Mantenha a guia em primeiro plano até a barra encher.
6. Clique no botão azul de download. Se for um GIF, você pode antes clicar em **Editar no editor de GIF** para adicionar texto.

## Editar um GIF que você já tem
1. Abra a guia **🎨 Editor de GIF** e escolha seu arquivo à esquerda: um GIF, imagem, vídeo, **WebP animado** ou **WebM**. Arrastar e soltar também funciona.
2. Clique em ▶ para reproduzir. Mova o controle deslizante para ver as imagens uma a uma (quadros).
3. Em **Editar**: **Quadro inicial** / **Quadro final** cortam o começo ou o fim, **Velocidade ×** deixa mais rápido ou mais lento, **Inverter** toca de trás para frente, **FPS** (máx. 50) e **Largura de saída** mudam a fluidez e o tamanho, **Cortar** recorta a imagem.
4. Escolha o tipo de arquivo, clique no botão azul e baixe o resultado. Errou? Clique em **Desfazer** no topo.

## Cortar um GIF
1. Abra um GIF na guia **🎨 Editor de GIF**.
2. Clique em **✂ Cortar** acima da prévia. O GIF inteiro aparece no centro: a parte que fica está clara e o resto escurecido.
3. Arraste uma borda ou um canto da moldura clara para cortar. Arraste dentro da moldura para movê-la. Os números ao lado de **Cortar** e **Largura de saída** acompanham automaticamente.
4. Clique em **✂ Cortar** de novo para voltar à prévia normal. Enquanto corta, as camadas fora da moldura ficam ocultas.

## Adicionar texto, imagens e desenhos
- **+ Texto** coloca palavras sobre o seu GIF. Digite-as na caixa à esquerda, escolha fonte, tamanho e cor e arraste o texto para o lugar certo. **Dê um clique duplo no texto na imagem para editá-lo de novo** (ou clique duas vezes nele na lista de camadas).
- **+ Imagem** adiciona uma imagem sua, por exemplo um logotipo. **✏️ Desenhar** permite desenhar com o mouse ou o dedo.
- Cada texto, imagem ou desenho é uma **camada**. Clique em uma camada na lista para selecioná-la; ▲ ▼ sobem ou descem a camada e ✕ a exclui. **Visível a partir do quadro** / **até o quadro** definem quando ela aparece.
- Roda do mouse sobre a camada = tamanho, Shift + roda = rotação. As camadas também podem ficar fora da imagem (margem escurecida) e voltar depois.

## Colocar os elementos em movimento
- **O jeito rápido:** selecione um texto ou imagem e clique em um efeito: Aparecer, Entrar voando, Pulsar, Balançar, Girar ou Pular.
- **Do seu jeito:** marque **Animar (quadros-chave)**, vá para outro quadro e arraste a camada para outro lugar. O OrcaGif preenche o movimento entre os dois. Escolha uma suavização, se quiser.

## O que significam estas palavras?
- **Quadro (frame)** – uma única imagem de uma animação. Um GIF são vários quadros exibidos rapidamente, um após o outro.
- **FPS** – quadros por segundo. Quanto mais, mais fluido, mas o arquivo fica maior.
- **Largura de saída** – a largura do arquivo final, em pixels (pontinhos da tela).
- **Pontilhado (dithering)** – um GIF só pode usar 256 cores. Esse truque mistura pontinhos para o céu e a pele ficarem mais suaves. Ative para fotos e vídeos e deixe desligado para logotipos e desenhos chapados. (Somente GIF.)
- **Fundo transparente** – as partes transparentes mostram o que está atrás da imagem. Funciona em GIF e WebP.
- **Camada** – um texto, imagem ou desenho que fica por cima do seu GIF.
- **Quadro-chave** – uma posição, tamanho ou ângulo salvo em um momento. O OrcaGif preenche o movimento entre dois quadros-chave.
- **Marca d'água** – o pequeno texto “OrcaGif” em um canto. Vem ativada por padrão – mantenha-a para apoiar esta ferramenta gratuita.

## Meu arquivo está grande demais – e agora?
Use uma **Largura de saída** menor, menos **FPS** ou um trecho mais curto – ou escolha **WebP**. Se as cores de um GIF parecerem manchadas, ative o **pontilhado (dithering)**.

## Projetos
- **Salvar** guarda o projeto no seu navegador para você continuar depois.
- **Arquivo de projeto ↓ / ↑** salva / abre um arquivo real (`.gifproj`).

## Atalhos
`Ctrl+Z` desfazer · `Ctrl+Y` refazer · `Ctrl+S` salvar · `Ctrl+D` duplicar camada · `←` `→` quadro anterior / seguinte · clique duplo em um texto = editá-lo · `I` / `O` início / fim (Vídeo para GIF)

---
Projeto pessoal sem fins comerciais. Contador de visitas anônimo e sem cookies ([GoatCounter](https://www.goatcounter.com)). Contato: Discord (link no rodapé do aplicativo).
