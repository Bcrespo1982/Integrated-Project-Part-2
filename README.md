Análise de Comportamento do Usuário & Teste A/A/B
Visão Geral do Projeto

Neste projeto, analisei o comportamento dos usuários de um aplicativo de produtos alimentícios e avaliei os resultados de um teste A/A/B. Os objetivos principais foram:

Análise do Funil de Vendas – Entender como os usuários percorrem o funil de vendas, identificar os pontos de maior desistência e medir a proporção de usuários que chegam à etapa de compra.

Teste A/A/B – Avaliar o impacto da mudança da fonte do aplicativo. Os usuários foram divididos em três grupos: dois grupos de controle com a fonte antiga (A/A) e um grupo de teste com a nova fonte (B). O objetivo era verificar se o novo design melhorava o engajamento sem afetar negativamente a usabilidade.

Descrição dos Dados

O conjunto de dados (logs_exp_us.csv) contém logs de eventos dos usuários:

EventName – Nome do evento

DeviceIDHash – Identificador único do usuário

EventTimestamp – Data e hora do evento

ExpId – Grupo do experimento (246 e 247 são grupos de controle, 248 é grupo de teste)

Metodologia

Preparação dos Dados

Renomeação das colunas para facilitar a análise

Verificação de valores ausentes e tipos de dados

Criação de colunas separadas para data e hora

Análise Exploratória

Contagem de eventos totais e usuários únicos

Cálculo da média de eventos por usuário

Determinação do período representado pelos dados

Análise do Funil de Eventos

Identificação de todos os eventos e sua frequência

Cálculo do número e da proporção de usuários que realizaram cada ação

Medição das taxas de desistência entre etapas do funil

Determinação da porcentagem de usuários que completaram o funil inteiro

Avaliação do Teste A/A/B

Verificação da similaridade entre os dois grupos de controle (A/A) para garantir a validade do teste

Comparação da proporção de usuários que realizaram eventos-chave nos grupos de controle e teste

Testes de significância estatística para cada evento

Ajuste do nível de significância considerando múltiplos testes de hipótese

Conclusão sobre o impacto da mudança de fonte no engajamento dos usuários

Principais Resultados

Identificação dos pontos críticos de desistência no funil de vendas

Confirmação de que os grupos de controle eram estatisticamente semelhantes

Determinação do efeito da mudança de fonte no comportamento dos usuários do grupo de teste
