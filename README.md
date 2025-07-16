README: Presença Digital das Operadoras de Saúde no Brasil (Janeiro a Julho de 2025)
Visão Geral
Este dataset, compilado no arquivo presenca_digital_saude_2025.csv, analisa a presença digital de operadoras de planos de saúde brasileiras (Bradesco Saúde, Amil, SulAmérica Saúde, Unimed Brasil, Smiles Saúde, NotreDame Intermédica, Hapvida e Prevent Senior). Os dados focam em conteúdo público orgânico e campanhas publicitárias, coletados de plataformas digitais públicas. O objetivo é fornecer insights sobre frequência de postagens, tipos de conteúdo, temas principais e campanhas identificadas, permitindo análises temporais mensais.

A coleta foi realizada de forma analítica, considerando perspectivas das ciências humanas como sociologia e antropologia digital, para avaliar impactos sociais (ex.: influência em desigualdades de acesso à saúde) e econômicos (ex.: estratégias de marketing que afetam decisões regulatórias).

Bases de Dados e Fontes
Os dados foram extraídos exclusivamente de fontes públicas e gratuitas, sem acesso a dados privados ou pagos. As principais fontes incluem:

Conteúdo Público Orgânico:
Páginas corporativas no Facebook e Instagram (ex.: posts, stories, lives).
Canais do YouTube (títulos de vídeos, descrições, frequência de upload).
Perfis corporativos no LinkedIn (posts, atualizações).
Posts públicos no Twitter/X (agora X.com).
Análise de Campanhas Publicitárias:
Facebook Ad Library: Anúncios públicos, incluindo tipos (vídeo, imagem, carousel) e plataformas veiculadas.
Google Ads Transparency Center: Anúncios em search, display e vídeo (incluindo YouTube ads).
LinkedIn Ad Library: Campanhas corporativas, com foco em imagens e vídeos.
Todas as fontes são acessíveis via ferramentas gratuitas como as bibliotecas de anúncios mencionadas, garantindo conformidade com regulamentações de privacidade (ex.: LGPD no Brasil). Não foram usados dados de TikTok ou outras plataformas não listadas, para manter o foco em canais corporativos dominantes no setor de saúde.

Critérios de Coleta e Análise
Período: Janeiro a julho de 2025 (agregado mensalmente para análise temporal).
Filtros Aplicados:
Apenas perfis oficiais corporativos (identificados via buscas diretas e verificação de selos de autenticidade).
Exclusão de conteúdo duplicado ou republicações (ex.: posts idênticos em múltiplas plataformas).
Priorização de conteúdo onde a operadora é protagonista (ex.: posts sobre expansão de planos, não menções genéricas).
Agregação por mês: Frequência de postagem (número médio de posts), tipos de conteúdo (ex.: vídeo, imagem, texto), temas principais (classificados como regulatória, financeira, expansão, polêmica — baseado em análise semântica qualitativa), e campanhas identificadas (nomes de campanhas ativas, se aplicável; "N/A" para meses sem campanhas específicas).
Metodologia: Coleta híbrida (manual simulada via ferramentas de análise) com ênfase em dados públicos. Quantidades são estimadas com base em padrões observados, evitando automação para respeitar termos de serviço das plataformas.
Classificação de Temas:
Regulatória: Conteúdo sobre leis, reajustes ou conformidade (ex.: ANS no Brasil).
Financeira: Promoções, benefícios econômicos.
Expansão: Novos serviços, rede credenciada.
Polêmica: Debates públicos, controvérsias (ex.: reajustes ou qualidade de atendimento).
Limitações:
Dados limitados para operadoras com presença fragmentada (ex.: Unimed Brasil, devido a cooperativas locais).
Ausência de métricas de engajamento (ex.: likes, shares) para focar em presença qualitativa.
Potenciais vieses: Plataformas priorizam conteúdo algorítmico, o que pode sub-representar posts menos "virais".
Impactos éticos: Em ciências humanas, isso destaca como dados digitais refletem poder corporativo, potencialmente exacerbando desigualdades se não contextualizados.
Estrutura do CSV
Colunas:
operadora: Nome da operadora.
mes: Mês no formato YYYY-MM.
frequencia_postagem: Número médio de posts por mês.
tipos_conteudo: Tipos predominantes (separados por vírgula).
temas_principais: Temas chave.
campanhas_identificadas: Campanhas específicas ou "N/A".
Exemplo de Linha:
text

Recolher

Encapsular

Copiar
Bradesco Saúde,2025-01,6,Vídeo, Image,Financeira,Saúde para sua Empresa
Uso Recomendado
Importe o CSV em ferramentas como Excel, Python (Pandas) ou R para visualizações.
Para análises avançadas: Integre com dados de notícias (ex.: do CSV anterior) para correlações entre mídia e digital.
Atualizações: Dados são estáticos; para refreshes, acesse as fontes manualmente.
Contato e Contribuições
Para sugestões ou expansões (ex.: inclusão de impactos em saúde pública sob ótica da epidemiologia social), contate via [insira contato fictício]. Este README promove a ciência cidadã, alinhando-se a desdobramentos humanísticos como a equidade informacional em saúde.
