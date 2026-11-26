# Comparador de Legendas

**Compare duas versões de uma legenda e veja exatamente o que mudou: texto, tempo, pontuação, itálico e mais.**

O Comparador de Legendas coloca a versão original e a modificada lado a lado, pareia as legendas automaticamente e classifica cada diferença. Serve para conferir revisões, entender o que o QC alterou ou checar atualizações de template.

## Formatos aceitos
SRT, DFXP, TTML, PXTT e TTAL (os dois arquivos podem estar em formatos diferentes), em UTF-8, UTF-16 ou Windows-1252. Lê corretamente timecode drop-frame (29,97), estilos sobrepostos de TTAL e legendas SRT com linha em branco no meio do texto.

## Funcionalidades
- **Pareamento inteligente** por texto e tempo, mesmo quando legendas foram adicionadas, removidas ou deslocadas.
- **Detecta legendas mescladas e divididas** (várias legendas de um lado viraram uma do outro, e vice-versa).
- **Diferença palavra por palavra:** trechos removidos em vermelho e acrescentados em verde; espaços e quebras de linha aparecem visíveis quando mudam.
- **Resumo no topo:** quantas linhas foram comparadas, quantas mudaram (e a porcentagem), quantas mudanças há em cada grupo e as categorias mais comuns.
- **Categorias de mudança, com contador, em grupos** (clique no nome do grupo para marcar todas):
  - Estrutura: adicionadas, removidas, linhas mescladas e divididas
  - Tempo: entrada e saída
  - Texto e formatação: palavras, pontuação e maiúsculas, quebra de linha, itálico/negrito/sublinhado, outras tags e posicionamento, espaços em branco e outras diferenças
  - Sem alteração
- **Números originais das legendas** nos dois lados de cada linha (ex.: “Orig. #12 · Mod. #13”, ou “#3–4” quando há legendas unidas ou divididas).
- **Tempos:** só a parte do timecode que mudou fica destacada, com a diferença em ms ou em frames.
- **Filtros:** clique nas categorias para ver só aquelas; escolha se a legenda precisa ter qualquer uma ou todas as categorias marcadas.
- **Tolerância de tempo** em milissegundos ou em frames (usando o frame rate do arquivo ou um escolhido) para ignorar diferenças pequenas.
- **Exibir somente mudanças** ou o arquivo todo.
- **Contexto:** mostra as legendas vizinhas de cada mudança, com botões para ver mais antes e depois.
- **Baixar relatório** em TXT, HTML ou XLSX (Excel) com as linhas que aparecem com os filtros atuais: números, tempos, categorias e o texto das duas versões.
- Trocar os lados (original ↔ modificada) e limpar tudo.
- Tema claro e escuro automático.

## Privacidade
Tudo roda no seu navegador. Nenhum arquivo é enviado para lugar nenhum.
