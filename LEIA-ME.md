# Wilcom Academy — apresentação visual

Pasta independente, pronta para Vercel. Inclui HTML, CSS, JavaScript, imagens e excertos de aulas. Não precisa de Remotion, compilação ou serviços externos.

## Vercel

Importa esta pasta como um projeto Git no Vercel. Framework Preset: Other. Root Directory: esta pasta. Build Command: vazio. Output Directory: . (raiz). Não há variáveis de ambiente. Também podes executar vercel dentro desta pasta, se já tiveres a CLI instalada.

## Pré-visualização local

Com Node instalado, abre um terminal nesta pasta e executa node preview.mjs. Abre http://127.0.0.1:4180. Para vídeos e imagens funcionarem corretamente, usa o servidor ou o site publicado.

## Apresentar no OBS

Abre o site no navegador a 1920 × 1080 e usa Captura de Janela no OBS. Assim podes controlar o navegador enquanto partilhas a imagem. A Fonte de Navegador também funciona: usa Interagir para dar foco e controlar a apresentação. Não apresentes o editor ou um terminal.

Setas: próximo/anterior. Home/End: início/fecho. F: ecrã inteiro. P: reproduzir/pausar vídeo. M: ativar/desativar som. V: trocar o excerto no slide inicial de demonstração. Clicar numa imagem: ampliar. Esc: fechar ampliação. Na comparação, arrasta a divisória. No telemóvel, desliza horizontalmente.

Se usares Captura de Janela, encaminha o áudio do navegador através da captura de áudio da aplicação no OBS. Verifica uma vez o som, o microfone e os níveis antes da live para evitar eco.

Os vídeos novos começam sem som; ativa-o com M quando quiseres mostrar um excerto. Os preços aparecem apenas nos dois slides finais. Oferta: Academy Completa 447,33 €, limitada a 20 vagas. Conteúdo em português de Portugal, sem contagem de aulas.

As imagens e os vídeos são capturas reais do curso de Wilcom. Não são demonstrações de operação da máquina.

## Fluxo atual da live

A apresentação principal foi reorganizada para uma live de cerca de 45 minutos, com 25 slides. Segue o ficheiro ROTEIRO-DA-LIVE.md para as falas, tempos, perguntas ao chat e transições. Os vídeos principais são sequência, suporte e letras; os restantes ficam como material de apoio. Para regenerar a página principal a partir deste roteiro, executa node fluxo-live.mjs nesta pasta.

Animações: transições suaves, entradas por etapas e barra de progresso. D destaca os pontos de uma lista durante a fala. A preferência do navegador por movimento reduzido é respeitada.

