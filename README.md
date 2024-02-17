# Azure-Cognitive-Serach-Dio
Desafio DIO  - Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

# Configurando uma Pesquisa Azure AI Search

## Passo a Passo:

### 1. Criar Recursos no Azure:

- Crie um recurso do Azure AI Search para gerenciar a indexação e consulta dos dados.
- Provisione um recurso Azure AI Services no mesmo local que o recurso Azure AI Search. Esse recurso fornecerá serviços de IA para enriquecer os dados com insights gerados por IA.

### 2. Criar uma Conta de Armazenamento:

- Crie uma conta de armazenamento no Azure para armazenar os documentos brutos e outras coleções de dados.
- Permita acesso anônimo a blobs na conta de armazenamento para facilitar o acesso aos documentos.

### 3. Importar Documentos para o Armazenamento:

- Baixe os arquivos de análise de café do link fornecido e extraia-os para uma pasta chamada "reviews".
- Faça upload desses documentos para um contêiner no armazenamento de blobs do Azure.

### 4. Indexar os Documentos:

- Utilize o Azure AI Search para extrair insights dos documentos, criando um índice e importando os documentos do armazenamento.
- Configure o índice para enriquecer os documentos com habilidades de IA, como extração de localizações, frases-chave e detecção de sentimentos.

### 5. Consultar o Índice:

- Utilize a ferramenta Search Explorer no portal do Azure para escrever e testar consultas no índice.
- Experimente filtrar os resultados por localização ou sentimento para obter insights específicos dos documentos indexados.

#
O Azure AI Search facilita a extração de insights importantes de grandes conjuntos de dados, como avaliações de clientes.
Ferramentas como o Language Studio podem traduzir automaticamente avaliações para diferentes idiomas, ampliando a análise.


