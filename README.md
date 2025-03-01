# Para se criar uma pesquisa com o Azure AI Search deve-se seguir o seguinte Passo a Passo:

1. Crie o Serviço de Pesquisa no Azure
  - Acesse o portal do Azure.
  - Pesquise por "Azure AI Search" e clique em Criar.
  - Escolha uma Subscrição, Nome, Grupo de Recursos, Localização (recomendado não usar Brasil) e um Plano de Preço (de preferência o Basic).
  - Clique em "Revisar e Criar" e aguarde a implantação.

2. Conectar e Ingerir os Dados
  - No painel do Azure AI Search, clique em Import data.
  - Escolha a origem dos dados (Azure SQL, Blob Storage, Cosmos DB, etc.{sejam eles importados ou inseridos manualmente}).
  - Configure a conexão e selecione os campos importantes.
  - Defina chaves primárias e os campos pesquisáveis.
  - Clique em Avançar e depois Concluir para importar os dados.

3. Criar e Configurar um Índice
  - Vá para Índices e clique em Novo Índice.
  - Defina os campos (ex: título, descrição, data, categoria).
  - Marque os campos relevantes como filtráveis, ordenáveis e pesquisáveis.
  - Habilite cognitive skills (caso precise de IA para análise de texto/imagem).
  - Salve o índice.

4. Criar um Indexador
  - No painel do serviço, vá para Indexadores e clique em Adicionar Indexador.
  - Escolha o índice e os dados de origem.
  - Configure a frequência de atualização (ex: diária, semanal).
  - Salve e execute para iniciar o processo.

5. Testar e Consultar os Dados
  - Vá para Explorador de Pesquisa.
  - Insira palavras-chave para testar a busca.
  - Use filtros e ordenações para refinar os resultados.
  - Se precisar, ajuste o índice e reindexe os dados.

# Insights e Aprendizados adquiridos com essa experiência:

- Automação e Eficiência: Atualizações automáticas mantêm os dados sempre otimizados.
- Pesquisa Inteligente: Habilitar IA melhora a precisão na busca de informações.
- Grande Facilidade de Integração: Pode ser usado com chatbots, sites, aplicativos e painéis BI.
- Alta Escalabilidade: Suporta grandes volumes de dados sem perda de performance.
- Análise de Sentimentos e OCR: Pode extrair texto de imagens e analisar sentimentos em textos.

# Ferramentas que se Beneficiam do Azure AI Search
- Chatbots e Assistentes Virtuais = Para buscar respostas em grandes bases de conhecimento.
- E-commerce = Para melhorar pesquisas e recomendações de produtos.
- Sistemas de Gestão de Conteúdo = Encontrar rapidamente documentos e artigos.
