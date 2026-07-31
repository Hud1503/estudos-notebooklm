# 📚 Miniguia de Estudos: Educação Financeira para Iniciantes com NotebookLM

> **Projeto prático desenvolvido para o bootcamp da DIO**  
> **Especialista:** Felipe Aguiar | DIO  
> **Ferramentas:** NotebookLM (Google) + GitHub

---

## 🎯 1. Contexto e Objetivos

### Contexto
Este caderno temático foi criado para organizar, resumir e facilitar o aprendizado sobre **Finanças Pessoais e Reserva de Emergência**, utilizando o **NotebookLM** como ferramenta de aprendizagem ativa baseada em fontes confiáveis.

### Objetivos de Estudo
- [ ] Compreender a regra de organização financeira pessoal.
- [ ] Entender a importância, o cálculo do tamanho ideal e a liquidez de uma Reserva de Emergência.
- [ ] Mapear conceitos essenciais de investimentos básicos em renda fixa.

---

## 📚 2. Curadoria de Fontes

Para garantir que a IA não "alucinasse", utilizei apenas materiais de fontes abertas e oficiais:

1. **[PDF] Banco Central do Brasil** - Caderno de Educação Financeira (Gestão de Finanças Pessoais).
2. **[PDF/Link] CVM Educacional** - Guia "Primeiros Passos em Investimentos".
3. **[PDF/Link] Portal do Investidor** - Conceitos Básicos de Renda Fixa e Liquidez.

---

## 🧪 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta seção, registro os testes de prompts feitos no NotebookLM, as variações de perguntas e como corrigi as respostas quando o resultado não foi o esperado.

### 🔴 Teste 1: Prompt muito genérico (Onde deu "ruim")
* **Prompt digitado:** *"Me explica o que é reserva de emergência."*
* **Resultado:** A IA trouxe uma resposta genérica, sem citar os valores exatos ou as orientações específicas contidas no material do Banco Central.
* **Diagnóstico ("Cicatriz"):** Faltou restrição de contexto e instrução sobre o formato de saída.

### 🟢 Teste 2: Prompt ajustado (A "Cura")
* **Prompt ajustado:** *"Com base exclusivamente nas fontes 1 e 2, explique o que é uma Reserva de Emergência. Informe quantos meses de custo de vida a fonte recomenda guardar e em quais tipos de investimentos com alta liquidez esse dinheiro deve ficar."*
* **Resultado:** Resposta precisa, indicando que a recomendação é de 3 a 6 meses de custo de vida em investimentos com liquidez diária, citando os trechos exatos do PDF.

---

## 📖 4. Miniguia de Estudo (Entrega Final)

### 4.1 Resumo Estruturado
- **Pilar 1: Diagnóstico Financeiro** — Mapeamento de receitas e despesas fixas/variáveis.
- **Pilar 2: Reserva de Emergência** — Valor equivalente a 3–6 meses de gastos guardado em ativos de liquidez imediata (ex: Tesouro Selic, CDB 100% CDI).
- **Pilar 3: Investimentos de Curto x Longo Prazo** — Separação por metas de tempo e perfil de risco.

---

### 4.2 Glossário de Conceitos
| Conceito | Definição Simplificada |
| :--- | :--- |
| **Liquidez** | A facilidade e rapidez com que você consegue transformar um investimento em dinheiro na conta. |
| **Taxa Selic** | A taxa básica de juros da economia brasileira, que influencia o rendimento de aplicações de renda fixa. |
| **Renda Fixa** | Categoria de investimento em que as regras de rendimento são definidas no momento da aplicação. |

---

### 4.3 Conjunto de Prompts Reutilizáveis (para futuras revisões)
Para continuar estudando este assunto no futuro, utilize os seguintes prompts no seu NotebookLM:

* **Para Resumos:** *"Gere um mapa mental em formato de tópicos com os passos para sair das dívidas com base no texto."*
* **Para Testar Conhecimento:** *"Crie um quiz com 3 perguntas de múltipla escolha sobre liquidez e renda fixa, com gabarito no final."*
* **Para Explicar para Leigos:** *"Explique a diferença entre poupança e Tesouro Direto como se estivesse ensinando uma criança de 12 anos."*

---

## 🛠️ Como replicar este projeto
1. Baixe os PDFs listados na seção de **Curadoria de Fontes**.
2. Acesse o [NotebookLM](https://notebooklm.google.com/) e crie um novo caderno.
3. Faça upload dos arquivos.
4. Execute os prompts da seção **Prompts Reutilizáveis**.
