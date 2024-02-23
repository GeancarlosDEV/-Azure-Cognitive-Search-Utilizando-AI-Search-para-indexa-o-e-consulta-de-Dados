# -Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados

**Explorando um Índice no Azure AI Search (UI): Minha Experiência**

# Configurando Recursos no Azure: Uma Caminhada Passo a Passo

1. **Azure AI Search:**
   - No [portal do Azure](https://portal.azure.com), crie um recurso Azure AI Search, escolhendo um nome exclusivo, vinculando à assinatura e alocando em um grupo de recursos Básico.

2. **Serviços de IA do Azure:**
   - Crie um recurso de Serviços de IA do Azure na mesma região do Azure AI Search para enriquecer os dados posteriormente.

3. **Conta de Armazenamento:**
   - Crie uma conta de armazenamento, permitindo acesso anônimo de Blob. Isso é crucial para armazenar documentos brutos e outras coleções.

4. **Carregando Documentos:**
   - Faça o download das avaliações de café, extraia para a pasta correspondente e crie um contêiner de acesso público chamado "Coffee-Reviews".

# Configurando o Índice: Enriquecendo a Busca

1. **Importar Dados:**
   - No recurso Azure AI Search, vá para "Importar dados", conecte-se ao Armazenamento de Blobs do Azure, escolha a conta e o contêiner "Coffee-Reviews".

2. **Habilidades de IA:**
   - Anexe o recurso de Serviços de IA do Azure, adicionando habilidades cognitivas, como extração de locais, frases-chave e detecção de sentimento.

3. **Salvar em Armazenamento de Conhecimento:**
   - Configure o armazenamento de conhecimento para projeções e documentos, criando um contêiner chamado "Knowledge-Storage".

4. **Configurar Índice e Indexador:**
   - Personalize o índice com campos filtráveis e crie um indexador agendado para execução única.

# Consultando o Índice: Descobrindo Tesouros Ocultos

- Use o Search Explorer para testar consultas JSON, desde localizações em Chicago até avaliações negativas.

# Revisando o Armazenamento de Conhecimento: Lições Aprendidas

- Explore o armazenamento de conhecimento para encontrar projeções e tabelas enriquecidas pelas habilidades de IA, incluindo frases-chave extraídas das avaliações.

# Insights e Possibilidades Futuras

- Ferramentas como projeções de imagem, detectores de sentimento e extração de entidades abrem portas para insights personalizados.

# Considerações Finais: Uma Experiência Enriquecedora

Em resumo, configurar e explorar o Azure AI Search foi uma experiência fascinante, revelando o potencial de transformar dados brutos em conhecimento valioso. A flexibilidade dessa ferramenta oferece um campo vasto para aprimorar a análise de dados e proporcionar insights valiosos aos usuários.

