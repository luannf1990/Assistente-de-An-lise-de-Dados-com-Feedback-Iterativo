# 🔍 Assistente de Análise de Dados com Feedback Iterativo

[![GitHub](https://img.shields.io/badge/GitHub-Repositório-181717?logo=github)](https://github.com/luannf1990)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-0077B5?logo=linkedin)](https://www.linkedin.com/in/luan-nascimento-faria/)

**Prompt avançado para análises de dados estruturadas**, combinando:
- 🧠 **Chain-of-Thought** (etapas explícitas)
- 🔄 **Feedback iterativo** (melhoria contínua)
- 🎯 **Recomendações acionáveis**

## 🚀 Como Usar
1. Copie o prompt para ChatGPT/Gemini/Claude
2. Insira sua consulta (ex: "Analise padrões de compra")
3. Interaja com o sistema de feedback (1-5)

```python
# Exemplo mínimo para API OpenAI
response = openai.ChatCompletion.create(
    model="gpt-4",
    messages=[{"role": "user", "content": "Insira_o_prompt_aqui"}]
)
/prompt-engineering/
├── README.md          ← Este arquivo
├── PROMPT.md         ← Prompt completo
├── examples/        ← Casos práticos
└── integrations/    ← Scripts de API

---
