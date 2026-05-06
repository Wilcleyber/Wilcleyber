👋 Wilcleyber (Wil)
🚀 Backend & AI Developer (Junior)

Construo sistemas onde linguagem natural vira ação real — agendamentos, automações e decisões de negócio.

📂 Projetos em Destaque
# ✨ Lumière Agentbot: Sua Clínica Nunca Fecha!
![Lumière Agentbot](./media/Lumiere_Agentbot.gif) 
[🔗 Testar Agente Virtual (Vercel)](https://lumiere-agentbot.vercel.app/) | [📊 Ver no Dashboard Lumière](https://lumiere-ten-vert.vercel.app) | [📁 Repositório](https://github.com/Wilcleyber/lumiere_agentbot.git)

💡 O que isso resolve?

Um agente de IA que atende clientes, entende linguagem natural e converte conversas em agendamentos reais automaticamente.

🧠 Como funciona (diferencial técnico)
LLM usado como interpretador de intenção (extração semântica estruturada em JSON)
Controle de estado via backend (fluxo por etapas: serviço → horário → dados → confirmação)
Prompts dinâmicos por fase → redução significativa de tokens (~60–80% vs abordagem com JSON completo por requisição)
Coleta progressiva de dados → preenchimento automático de formulário
Validação em tempo real com banco (slots disponíveis)

🏗️ Arquitetura (simplificada)

Cliente → LLM (interpretação) → Backend (regra de negócio) → Banco → Dashboard (Realtime)

⚙️ Stack

Next.js, TypeScript, Node.js, Vercel AI SDK, Llama 3 (Groq), Supabase (PostgreSQL)

# 💎 Lumière: Ecossistema de Gestão Estética
![Lumière Demo](./media/Lumière.gif)  
[🔗 Testar Aplicação](https://lumiere-ten-vert.vercel.app) | [📁 Repositório do Projeto](https://github.com/Wilcleyber/Lumiere.git)

Sistema de gestão pensado para escalar múltiplas clínicas com contextos independentes.

💡 O que isso resolve?

Centraliza e gerencia todos os agendamentos (automáticos via IA ou manuais) em tempo real.

🧠 Diferencial técnico
Arquitetura multi-tenant (cada clínica possui seus próprios dados: clientes, serviços, agenda e financeiro)
Integração direta com agente de IA (o bot se adapta ao contexto da clínica logada)
Atualização em tempo real (Realtime DB)
Base preparada para escalar para múltiplos negócios simultaneamente
🛠️ Stack (Visão rápida)

Backend: Node.js, FastAPI, PostgreSQL
Frontend: Next.js, React, TypeScript
IA: LLMs (Llama 3, Gemini), Vercel AI SDK
Infra: Supabase, Docker, Vercel

📌 Sobre mim

Estagiário na Vale S.A., atuando com dados e automação.

Focado em migrar para engenharia de software com ênfase em backend e IA aplicada.

## ✉️ Contato

[![E-mail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:wilcleyber2@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wilcleyber/)
