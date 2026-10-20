# Arquitetura — Marketing Intelligence AI

## Visão geral
O plugin privado v1.0.2 organiza suas respostas em cinco competências: Marketing Estratégico, Marketing Analytics, Social Media e Conteúdo, SEO e Copywriting, e Inteligência Comercial.

## Fluxo conceitual
1. Receber contexto, objetivos e dados fornecidos pelo usuário.
2. Identificar a competência aplicável e verificar informações faltantes.
3. Consultar a referência documental MIA quando pertinente à análise.
4. Calcular indicadores, formular hipóteses e elaborar recomendações.
5. Submeter decisões comerciais e execução à avaliação humana.

## Metodologia MIA
**Dados → Agregação → KPIs → Regras de negócio → Diagnóstico → Recomendações → Decisão.**

O [MIA original](https://github.com/MCLG1661/Analista-de-Marketing-Inteligente) implementa cálculos e regras determinísticas em JavaScript. O plugin utiliza uma síntese documental da metodologia: não executa diretamente o motor JavaScript e não está integrado à aplicação original ou a APIs externas.

## Limites
As análises dependem da qualidade dos dados informados. Regras e limiares são configuráveis, não benchmarks universais. A arquitetura é conceitual, não uma implantação de microsserviços.
