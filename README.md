# 🤖 Qualificação Inteligente de Leads com IA

MVP desenvolvido para automatizar a **análise, classificação e priorização de leads** utilizando **n8n + Inteligência Artificial**.

O sistema recebe os dados de um potencial cliente, analisa sua mensagem com IA, gera um **Lead Score** e direciona automaticamente o contato de acordo com sua prioridade.

## ⚙️ Como funciona

```text
Lead → Webhook → IA → Lead Score → Classificação → Ação
```

Os leads são classificados em três níveis:

* 🔥 **Quente** — alta intenção de compra e prioridade.
* 🟡 **Morno** — demonstra interesse, mas necessita acompanhamento.
* ❄️ **Frio** — baixo interesse ou intenção de compra no momento.

A partir da classificação, o **n8n executa automaticamente a ação correspondente**.

## 🛠️ Tecnologias

* **n8n** — automação e gerenciamento do workflow
* **Google Gemini** — análise das mensagens com IA
* **Webhook** — entrada dos leads
* **Google Sheets** — registro e organização dos dados
* **Gmail** — notificações automatizadas

## 🧠 Objetivo

Demonstrar como **IA e automação** podem ajudar equipes comerciais a identificar oportunidades mais relevantes, reduzir tarefas manuais e priorizar leads com maior potencial de conversão.

## 🚀 Possíveis melhorias

* Integração com CRM e WhatsApp
* Dashboard de acompanhamento
* Follow-up automático
* Métricas de conversão
* Aprimoramento do Lead Score com dados reais

## 📌 Status

✅ **MVP funcional**

## 👨‍💻 Autor

**Pedro Leite**

Projeto desenvolvido para aplicação prática de conhecimentos em **Inteligência Artificial, automação de processos e n8n**.

