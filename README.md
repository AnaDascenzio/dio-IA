### Análise de Sentimentos com Language Studio no Azure AI

A **Análise de Sentimentos** no **Azure AI Language Studio** é uma funcionalidade que permite identificar automaticamente o tom (positivo, negativo, neutro ou misto) de textos em diversos idiomas. Essa análise é baseada em modelos de aprendizado de máquina treinados para entender o contexto e a intenção emocional das palavras.

O **Language Studio** é uma interface gráfica no portal do Azure que facilita o uso de recursos de linguagem natural sem necessidade de codificação. Nele, você pode testar, treinar e implantar modelos de análise de sentimentos de forma intuitiva.

A ferramenta pode ser usada para:
- Avaliar feedback de clientes.
- Monitorar menções nas redes sociais.
- Analisar opiniões em pesquisas e avaliações.

Além do sentimento geral, o serviço também pode identificar sentimentos por **frase ou sentença**, analisar aspectos específicos (como "atendimento" ou "preço") e fornecer pontuações de confiança para cada classificação.

### Azure Cognitive Search: Utilizando AI Search para Indexação e Consulta de Dados

O **Azure Cognitive Search** é um serviço de busca hospedado na nuvem que permite criar experiências de pesquisa sofisticadas e inteligentes em grandes volumes de dados estruturados ou não estruturados. Ele combina **indexação de alta performance** com **recursos de inteligência artificial (AI Search)** para enriquecer os dados durante o processo de ingestão.

Com o uso de **modelos de IA integrados**, como **OCR, análise de sentimentos, extração de entidades e tradução**, é possível transformar documentos em fontes pesquisáveis e compreensíveis para o usuário final.

A ferramenta suporta:
- **Indexação automática** de documentos em diversos formatos (PDF, DOCX, imagens, etc.).
- **Consultas avançadas** com filtros, sugestões, sinônimos e ordenação por relevância.
- **Análise semântica** e entendimento do contexto da busca.
- Integração com **Power BI**, **aplicativos personalizados** ou **chatbots**.

É ideal para aplicações como: portais de conhecimento, busca jurídica, pesquisa em acervos digitais, entre outros, permitindo uma navegação mais inteligente e eficaz pelos dados.

Laboratório prático
- Primeiro, criamos uma Azure AI Service com o plano básico, e o AI search
- Depois, vamos em storage account, para criar uma nova, colocando o a assinatura e o resource group. A performance permaneceu em standard.
- depois de criado o storage account, selecionar ele e liberar acesso para acessos anonimos de blob
- Proximo passo é trazer alguns arquivos para dentro do nosso container
- Ir no mecanismo de busca e importar dados - selecionar onde estão as informações dos meus dados cognitivos
- Por fim, pesquisar pelos documentos usando o Search explorer, como opiniões positivas ou negativas ou localizações

- # Resumo sobre IA Generativa e OpenAI

## O que é IA Generativa?

A **IA Generativa** é um ramo da inteligência artificial focado em criar conteúdo novo e original, como texto, imagens, áudio ou vídeo, com base em padrões aprendidos a partir de grandes volumes de dados. Ela pode produzir desde respostas em linguagem natural até imagens artísticas e código de programação.

## Fases Principais da IA Generativa

1. **Tokenização**  
   Processo que divide o texto (ou outros dados) em unidades menores chamadas *tokens* — que podem ser palavras, pedaços de palavras ou caracteres. Essa divisão permite que o modelo processe e compreenda a entrada de forma eficiente.

2. **Codificação e Embeddings**  
   Cada token é convertido em um vetor numérico (embedding) que representa seu significado contextual para que o modelo possa analisar as relações entre eles.

3. **Processamento pelo Modelo**  
   O modelo, geralmente baseado em arquiteturas como *Transformers*, processa esses embeddings para entender o contexto, prever o próximo token ou gerar saídas baseadas na entrada.

4. **Geração de Saída**  
   O modelo gera novo conteúdo token a token, formando texto, imagens ou outras mídias conforme o tipo de IA generativa.

## OpenAI

**OpenAI** é uma organização líder no desenvolvimento de modelos avançados de IA generativa, incluindo:

- **GPT (Generative Pre-trained Transformer):** modelo focado em geração e compreensão de texto.
- **DALL·E:** modelo que gera imagens a partir de descrições textuais.

No **Azure OpenAI Service**, esses modelos são disponibilizados na nuvem, permitindo que empresas integrem IA generativa em seus aplicativos com segurança, escalabilidade e facilidade.


📚 Referências
Documentação oficial do Azure Cognitive Search
https://learn.microsoft.com/azure/search/

Visão geral do Azure AI Search (antigo Cognitive Search)
https://learn.microsoft.com/en-us/azure/search/search-what-is-azure-search

Tutoriais e guias rápidos de implementação
https://learn.microsoft.com/en-us/azure/search/search-get-started-portal

Recursos de enriquecimento cognitivo
https://learn.microsoft.com/en-us/azure/search/cognitive-search-concept-intro

Documentação oficial do Azure OpenAI Service
https://learn.microsoft.com/azure/cognitive-services/openai/

Visão geral dos modelos GPT
https://openai.com/research/gpt-4

DALL·E e geração de imagens por IA
https://openai.com/dall-e

Explicação sobre tokenização e modelos Transformers 
https://jalammar.github.io/illustrated-transformer/

Artigo Microsoft sobre IA responsável e Azure Cognitive Services
https://learn.microsoft.com/azure/ai/responsible-ai
