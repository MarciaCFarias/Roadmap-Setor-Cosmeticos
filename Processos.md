# 📌 Processos – Oportunidades de Automação Fiscal (TO BE)

Este documento reúne os processos levantados na descoberta e as etapas estruturadas para avaliação e priorização no contexto fiscal.  
A estrutura foi organizada em formato macro, sem detalhamento operacional, garantindo visão clara e objetiva do fluxo end-to-end.

---

# 1. Processos Levantados (Etapa de Entendimento)

Durante o discovery foram identificados os seguintes processos ativos da área fiscal:

1. **Gerar Relatório Resumo Fiscal**
2. **Conciliação Contábil x Conta ICMS**
3. **Geração de Livros Fiscais DIFAL**

Abaixo, cada processo é apresentado com suas macroetapas, seguindo o formato padrão utilizado em documentações internas.

---

# 2. Macroetapas dos Processos Identificados

## 2.1 Gerar Relatório Resumo Fiscal
### **2.1.1 Preparar Ambiente**
- Validar dados e período analisado.
- Verificar diretórios e arquivos base.
- Confirmar disponibilidade de informações.

### **2.1.2 Consultar Informações Fiscais**
- Acessar dados consolidados.
- Filtrar por período e tipo de operação.
- Validar consistência dos registros.

### **2.1.3 Gerar Relatório Fiscal**
- Aplicar filtros e critérios fiscais.
- Consolidar resultados.
- Formatá-los conforme padrão.

### **2.1.4 Finalizar e Disponibilizar**
- Registrar observações relevantes.
- Salvar o relatório no diretório padrão.
- Comunicar responsáveis.

---

## 2.2 Conciliação Contábil x Conta ICMS
### **2.2.1 Levantar Dados Contábeis**
- Identificar contas do período.
- Consultar lançamentos.
- Validar integridade dos dados.

### **2.2.2 Levantar Dados Fiscais**
- Consultar movimentações de ICMS.
- Validar bases utilizadas.
- Identificar possíveis divergências.

### **2.2.3 Realizar Conciliação**
- Cruzar dados contábeis x fiscais.
- Identificar divergências.
- Classificar diferenças conforme tipo.

### **2.2.4 Consolidar Resultados**
- Gerar relatório final.
- Registrar pendências.
- Encaminhar para validação.

---

## 2.3 Geração de Livros Fiscais DIFAL
### **2.3.1 Reunir Dados do Período**
- Levantar operações sujeitas a DIFAL.
- Validar documentos envolvidos.
- Garantir consistência da base.

### **2.3.2 Processar Informações**
- Calcular valores e bases.
- Classificar operações conforme regra.
- Preparar dados para geração.

### **2.3.3 Gerar Livro Fiscal**
- Aplicar layout padrão.
- Verificar campos obrigatórios.
- Criar arquivo final.

### **2.3.4 Finalizar**
- Registrar logs.
- Salvar arquivo final.
- Disponibilizar responsáveis.

---

# 3. Fluxo Geral TO BE (12 Etapas)

A seguir, o fluxo completo e padronizado utilizado no discovery:

## **Etapa 1 – Planejamento**
- Definir escopo.
- Alinhar responsáveis.
- Organizar cronograma.

## **Etapa 2 – Levantamento Inicial**
- Coletar informações básicas.
- Identificar processos críticos.
- Registrar demandas principais.

## **Etapa 3 – Entendimento Detalhado**
- Reuniões com responsáveis.
- Registro de entradas e saídas.
- Mapeamento do cenário atual.

## **Etapa 4 – Mapeamento das Atividades**
- Listar etapas de cada processo.
- Identificar retrabalhos e riscos.
- Verificar dependências.

## **Etapa 5 – Classificação das Tarefas**
- Identificar atividades manuais.
- Categorizar por tipo (consulta, conferência, extração, cálculo).
- Avaliar padronização.

## **Etapa 6 – Análise de Viabilidade**
- Avaliar volume e frequência.
- Verificar repetitividade.
- Identificar riscos.

## **Etapa 7 – Análise Técnica**
- Avaliar complexidade da automação.
- Verificar restrições técnicas.
- Validar estabilidade do processo.

## **Etapa 8 – Pontuação e Priorização**
- Aplicar matriz impacto × esforço.
- Atribuir pontuação.
- Calcular viabilidade final.

## **Etapa 9 – Construção do Ranking**
- Ordenar oportunidades.
- Identificar quick wins.
- Analisar retorno.

## **Etapa 10 – Consolidação**
- Registrar análises.
- Documentar recomendações.
- Estimar ganhos.

## **Etapa 11 – Validação**
- Apresentar resultados.
- Ajustar pontuações.
- Registrar aprovações.

## **Etapa 12 – Entrega Final**
- Entregar o mapa final de oportunidades.
- Publicar documentos.
- Orientar próximos passos.

---

# 4. Melhorias Implementadas
- Padronização da metodologia de análise.
- Redução de subjetividade nas decisões.
- Ganho de clareza sobre processos críticos.
- Criação de estrutura replicável para novos levantamentos.
- Consolidação das informações em modelo único.
- Maior previsibilidade e organização da análise fiscal.

---

# 5. Pontos de Atenção
- Regras muito interpretativas podem limitar automação.
- Mudanças constantes exigem revisões periódicas.
- Falta de padronização reduz viabilidade.
- Processos dependentes de validação humana têm baixa automação imediata.

---

# 6. KPIs Sugeridos

| Indicador | Descrição | Objetivo |
|----------|-----------|----------|
| % de Processos Mapeados | Quantidade mapeada x planejado | Monitorar avanço |
| Nº de Oportunidades Identificadas | Total de oportunidades | Medir potencial |
| Índice de Viabilidade | Média geral das pontuações | Avaliar maturidade |
| Tempo Médio de Análise | Tempo por oportunidade | Medir eficiência |
| Impacto Estimado | Redução potencial de horas | Auxiliar priorização |
| Aderência ao Modelo | Conformidade com metodologia | Garantir consistência |

---

# 7. Observações Gerais
- O fluxo TO BE deve ser revisto periodicamente.
- A documentação auxilia decisões estratégicas e técnicas.
- O ranking final direciona, mas não substitui análise de desenvolvimento.
- A estrutura pode ser aplicada a outras áreas além do fiscal.

---

## 5. Observações Gerais
- O modelo foi pensado para atender diferentes cenários fiscais, adaptável conforme maturidade e volume operacional.
- A priorização final não substitui avaliação técnica detalhada durante a fase de desenvolvimento.
- Processos que envolvem interpretações fiscais podem exigir dupla homologação antes de avançar para automação.
