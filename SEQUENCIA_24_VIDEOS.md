# Sennda ERP — sequência de produção

Formato definido: 24 MP4 numerados, 1920×1080, 16:9, narração PT-BR, entre 60 e 180 segundos. Os tempos abaixo são referências de planejamento; a duração final depende da locução e da demonstração. Partes adicionais, se necessárias, serão identificadas sem ocultar mudanças na contagem.

01 — Conhecendo Retaguarda e PDV.

Sim. A série deve funcionar como um **curso progressivo**, não como 24 vídeos isolados. O vídeo 01 apresenta a lógica Retaguarda ↔ PDV; do 02 em diante, cada aula deve ensinar uma operação que prepara a próxima.

Eu organizaria as outras **23 partes em 6 blocos didáticos**, sempre com a mesma lógica: **“o que vamos fazer → por que isso importa → execução na tela → conferência do resultado → ligação com a próxima aula”**.

| # | Microvídeo | Objetivo didático e conteúdo da narração | Demonstração na tela | Duração |
|---|---|---|---|---:|
| **02** | **Cadastrar um produto** | Explicar que o produto é a base das operações seguintes. Ensinar onde acessar o cadastro e quais informações precisam ser preenchidas para criar um produto utilizável no sistema. | Retaguarda → Controle de Estoque → Lista de Produtos → Novo Produto. Mostrar descrição, unidade, código de barras e demais campos. Salvar e localizar o produto cadastrado. | 2:00 |
| **03** | **Preencher NCM, CST e CFOP** | Explicar que, além dos dados comerciais, o produto possui informações fiscais necessárias para as operações fiscais. Mostrar onde ficam NCM, CST e CFOP, sem transformar o vídeo em uma aula tributária. | Abrir o produto criado no vídeo 02 → localizar campos fiscais → preencher exemplo → salvar. | 1:30 |
| **04** | **Criar Grupo e Subgrupo** | Mostrar por que organizar produtos em grupos facilita cadastro, consulta e gestão. Ensinar criação e associação do produto. | Criar Grupo → descrição/código → Subgrupo → salvar → voltar ao produto e associá-lo. | 1:30 |
| **05** | **Configurar preço, custo e estoque inicial** | Explicar a diferença entre custo e preço de venda e mostrar os campos disponíveis, incluindo margem, preço B, estoque mínimo e estoque inicial quando aplicáveis. | Abrir produto → custo → preço → margem → estoque mínimo/inicial → salvar. | 1:30 |
| **06** | **Fazer entrada manual no estoque** | Agora que o produto existe, ensinar como registrar fisicamente sua chegada. Explicar que cadastrar produto não significa necessariamente ter mercadoria disponível. | Movimentação de Estoque → Entrada Manual → Novo documento → produto → quantidade → adicionar → salvar/continuar → conferir saldo. | 1:30 |
| **07** | **Importar nota de compra por XML** | Apresentar uma segunda forma de entrada: utilizar o XML da compra. Explicar a relação entre documento de compra e movimentação de estoque conforme demonstrada no Sennda. | Abrir importação → selecionar XML → mostrar informações reconhecidas → concluir → verificar documento/estoque. Somente etapas presentes no material. | 2:00 |
| **08** | **Consultar movimentação e saldo** | Ensinar a responder duas perguntas básicas: “quanto tenho?” e “de onde veio essa movimentação?”. | Pesquisar produto → saldo atual → movimentações → demonstrar entrada e, posteriormente, saída. | 1:30 |
| **09** | **Abrir o PDV e abrir o caixa** | Fazer a transição didática da Retaguarda para a operação. Explicar que agora os produtos preparados anteriormente serão vendidos. | Abrir PDV → carregar base/login conforme sistema → operador → abertura do caixa → valor inicial quando aplicável → confirmar. | 1:30 |
| **10** | **Realizar uma venda** | Ensinar a operação central do PDV: localizar produto, lançar item, quantidade, conferir venda e preparar a finalização. | Produto/código de barras → adicionar → quantidade → conferir itens e total → avançar para pagamento. | 2:00 |
| **11** | **Excluir/cancelar item** | Mostrar como corrigir uma venda antes de concluí-la e por que o sistema solicita justificativa quando aplicável. | Criar venda de exemplo → selecionar item → cancelar/excluir → informar justificativa → confirmar → mostrar venda corrigida. | 1:00 |
| **12** | **Dinheiro, cartão e Pix** | Explicar que a venda só é concluída depois de informar como o cliente pagará. Demonstrar as formas disponíveis e mencionar combinação de pagamentos somente quando demonstrada pelo sistema. | Mesma venda → pagamento → dinheiro/cartão/Pix → mostrar total recebido e conclusão. | 1:30 |
| **13** | **DAV, NFC-e e NF-e** | Explicar de forma operacional que diferentes situações podem gerar documentos diferentes. Não aprofundar tributação. Ensinar o que o usuário encontra no Sennda. | Venda finalizada → documento correspondente → DAV/PDF e opções fiscais demonstradas no sistema. | 1:30 |
| **14** | **Cadastrar cliente pelo PDV** | Mostrar quando identificar o cliente e ensinar cadastro rápido durante a operação. | Localizar cliente → novo cliente → nome/razão social → CPF/CNPJ → telefone/endereço quando necessários → salvar → selecionar na venda. | 1:30 |
| **15** | **Fechar o caixa** | Encerrar o ciclo operacional iniciado no vídeo 09. Explicar que fechamento permite conferir o movimento do período/operador. | Acessar fechamento → conferir informações apresentadas → finalizar caixa → mostrar resultado. | 1:30 |
| **16** | **Conferir venda na Retaguarda** | Retomar o conceito do vídeo 01: demonstrar concretamente que aquilo que aconteceu no PDV chega à administração. | Venda feita anteriormente → Retaguarda → localizar venda/cupom → conferir produto, valor e pagamento. | 1:30 |
| **17** | **Verificar baixa automática do estoque** | Demonstrar a consequência da venda sobre o estoque. Comparar quantidade antes e depois para tornar o conceito visual. | Mostrar saldo anterior → venda → sincronização → saldo posterior na Retaguarda. | 1:00 |
| **18** | **Criar conta a receber** | Introduzir o financeiro somente depois que o aluno entende vendas. Mostrar como registrar um valor que ainda será recebido. | Financeiro → Contas a Receber → incluir → valor → cliente → vencimento/parcelamento e forma disponível → salvar. | 1:30 |
| **19** | **Dar baixa e emitir recibo** | Continuar exatamente a operação anterior: agora o cliente pagou. Ensinar localizar o título e registrar o recebimento. | Localizar conta criada no vídeo 18 → receber/dar baixa → confirmar → gerar recibo quando disponível. | 1:30 |
| **20** | **Dashboard e DRE** | Mudar da operação para gestão. Mostrar que os dados cadastrados nos vídeos anteriores alimentam indicadores administrativos. | Dashboard → filtro de período → vendas/DRE → vendas por hora → ranking → formas de pagamento. | 1:30 |
| **21** | **Giro de estoque e Curva ABC** | Ensinar o gestor a interpretar quais produtos têm maior relevância/movimentação, sem aprofundar teoria além do necessário para utilizar os relatórios. | Relatórios → Giro de Estoque → Curva ABC → alterar período → mostrar resultados. | 1:30 |
| **22** | **Produtos sem movimento** | Mostrar como localizar mercadoria que permanece sem movimentação e como essa informação pode apoiar decisões de estoque. | Relatório correspondente → período/filtros → produtos encontrados → explicar leitura. | 1:00 |
| **23** | **Sugestão de compra** | Fechar o ciclo de estoque: depois de cadastrar, comprar e vender, mostrar como o sistema auxilia a identificar necessidade de reposição. | Relatório Sugestão de Compra → estoque atual/mínimo → itens sugeridos → interpretação. | 1:30 |
| **24** | **Teste completo antes do Go-Live** | Revisão prática de todo o curso. Em vez de explicar novamente cada tela, executar uma operação curta de ponta a ponta e conferir se a implantação está funcionando. | Produto cadastrado → saldo positivo → PDV aberto → venda teste → pagamento → sincronização → venda na Retaguarda → baixa de estoque → reflexo financeiro. | 2:00 |

### A lógica pedagógica da série

**Bloco 1 — Preparação do produto:** vídeos **01–05**. O aluno entende o sistema e prepara corretamente aquilo que será comercializado.

**Bloco 2 — Mercadoria e estoque:** vídeos **06–08**. O produto deixa de ser apenas um cadastro e passa a possuir movimentação e saldo.

**Bloco 3 — Operação do PDV:** vídeos **09–15**. O aluno abre o caixa, vende, corrige erros, recebe, identifica clientes, gera documentos e encerra o caixa.

**Bloco 4 — Integração:** vídeos **16–17**. Aqui comprovamos visualmente a promessa apresentada no vídeo 01: **PDV → Retaguarda**.

**Bloco 5 — Financeiro e gestão:** vídeos **18–23**. Depois de aprender a operar, o aluno passa a entender o que fazer com os dados produzidos pela operação.

**Bloco 6 — Implantação:** vídeo **24**. O implantador executa o teste de ponta a ponta antes de liberar a operação.

Há ainda uma regra que melhoraria bastante o curso: **usar o mesmo produto fictício durante toda a série**. Por exemplo, no vídeo 02 cadastramos “Produto Treinamento 001”; no 03 configuramos seus dados fiscais; no 06 entram 10 unidades; no 10 vendemos 2; no 17 verificamos que restaram 8. Assim, em vez de 24 demonstrações desconectadas, teremos **uma única história operacional acompanhada do início ao fim**.

Isso também torna o vídeo 24 muito mais forte, porque ele funciona como a prova final de que o aluno compreendeu o ciclo completo:

**Cadastro → Fiscal → Estoque → PDV → Venda → Pagamento → Documento → Baixa → Financeiro → Gestão.**
