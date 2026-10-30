# Sennda ERP — consolidação das três conversas

## Objetivo consolidado

Produzir uma primeira série de 24 microaulas operacionais, numeradas, com 60 a 180 segundos por arquivo, MP4 H.264/AAC, 1920×1080 e narração em português brasileiro. O foco é a implantação e a operação: localizar a rotina, reconhecer os campos, concluir e conferir.

## Decisões recuperadas

- **Prompt para apresentação ERP:** origem da jornada Retaguarda → cadastro → estoque → PDV → venda → integração → financeiro → relatórios → implantação. Contém a grade de 24 temas, mantida nesta edição.
- **Proposta de microvídeo cadastro:** aprovação do formato didático do vídeo 02, com identificação, dados comerciais, referência à tributação, salvar e conferir.
- **Branch · Configuração fiscal do produto:** aula 03 centrada em localizar os campos fiscais, conferir e salvar. Exemplos de CST/CSOSN e CFOP não são apresentados como regras universais.
- **Pedido atual:** duração entre 1 e 3 minutos e entrega de arquivos MP4. Essa orientação prevalece sobre o limite antigo de 60 segundos do vídeo 01 e sobre a primeira sugestão de vídeos de 45 segundos.

## Padrão aplicado

- Título e número da aula sempre visíveis, indicação da etapa e continuidade didática.
- Gravações reais e recortes de telas do manual; pausas de imagem para acompanhar a explicação.
- Narração local com Microsoft Maria Desktop (PT-BR), sem dependência de créditos do Higgsfield.
- Montagem e codificação locais com FFmpeg; roteiro e relação de trechos preservados na pasta de produção.
- Os produtos originais das gravações foram preservados. Não foi inserido artificialmente “PRODUTO TREINAMENTO 001” nas telas existentes.
- As capturas originais têm resolução menor que Full HD. O arquivo final é 1920×1080, mas a ampliação não recupera detalhes ausentes na gravação.

## Tratamento das fontes

As conversas foram preservadas em JSON. Os anexos locais foram copiados para a pasta fontes; duplicatas com o mesmo nome foram reunidas. Os manuais de produto e grupos, entrada de estoque e o Guia Sennda foram cruzados com as telas das gravações. O arquivo chamado FAZER_NFE_DE_ENTRADA contém instruções de venda e foi interpretado pelo conteúdo, não pelo nome.

As apresentações audiovisuais derivadas de NotebookLM são materiais explicativos auxiliares; seus desenhos não substituem as telas do sistema. O arquivo de gameplay de 29/08 não foi utilizado nas aulas. Referências a PDF/PPTX nas conversas que não retornaram como anexos locais não foram tratadas como arquivos efetivamente inspecionados.

## Limites da primeira edição

- **03 e 04:** o manual desktop e as gravações da interface web apresentam organização e nomes diferentes. As telas do manual estão identificadas.
- **07:** a opção Entrada XML está comprovada visualmente. A seleção do arquivo e a importação completa não estão demonstradas pelo recorte utilizado; a aula sinaliza a etapa a validar.
- **17:** explica os pontos para conferir a baixa, sem fingir uma comparação controlada do mesmo produto antes e depois da mesma venda.
- **21:** a opção Curva ABC aparece no menu e sua finalidade é descrita no guia. O resultado exemplificado em tela é o de Giro de estoque.
- **24:** é um roteiro de teste de implantação com recortes reais, e não uma declaração de que um ambiente de cliente passou por esse teste.

Esses limites permanecem visíveis no material. A existência dos 24 arquivos não equivale à homologação operacional da série para todas as versões do sistema.
