# 🔍 Azure Cognitive Search: Indexação e Consulta com AI Search

Projeto prático do bootcamp **Bradesco Java Cloud Native** (DIO), demonstrando como utilizar o Azure Cognitive Search para indexar e consultar dados enriquecidos com inteligência artificial.

## 🎯 Objetivo

Implementar uma solução de busca inteligente utilizando o Azure Cognitive Search, incluindo:

- Criação de fontes de dados e índices
- Configuração de conjuntos de habilidades (skillsets) para enriquecimento de dados
- Criação de indexadores para automatizar o processo de indexação
- Consulta eficiente aos dados indexados

## 🛠️ Etapas do Projeto

1. **Criar uma Fonte de Dados**
   - Utilize o Azure Blob Storage como origem dos dados.
   - Carregue documentos de exemplo no contêiner do Blob Storage.

2. **Definir um Conjunto de Habilidades (Skillset)**
   - Configure habilidades cognitivas como:
     - OCR (Reconhecimento Óptico de Caracteres)
     - Detecção de idioma
     - Extração de frases-chave
     - Reconhecimento de entidades nomeadas

3. **Criar um Índice de Pesquisa**
   - Defina o esquema do índice com campos apropriados para os dados enriquecidos.

4. **Configurar um Indexador**
   - Associe a fonte de dados, o conjunto de habilidades e o índice.
   - Agende execuções periódicas para manter o índice atualizado.

5. **Consultar o Índice**
   - Utilize o portal do Azure ou APIs REST para realizar buscas nos dados indexados.

## 📊 Resultados Esperados

- Dados não estruturados transformados em informações pesquisáveis.
- Implementação de um pipeline de enriquecimento de dados com IA.
- Capacidade de realizar consultas eficientes e relevantes nos dados processados.
