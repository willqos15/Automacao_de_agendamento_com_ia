# 🤖 Chatbot de Agendamento Automatizado (n8n + Telegram + IA)

## 📌 Visão Geral
Este projeto implementa um chatbot de automação de agendamentos voltado para clínicas e pequenos negócios que ainda utilizam processos físicos ou manuais. A solução permite que usuários realizem agendamentos por texto ou áudio, inclusive enviando múltiplas informações em uma única mensagem, com centralização automática dos compromissos em uma agenda digital.

O foco do projeto é reduzir custo operacional, erro humano e retrabalho, oferecendo uma alternativa simples, acessível e de fácil manutenção.

---

## 🧩 Arquitetura da Solução
- Telegram como canal de entrada do usuário  
- n8n como orquestrador dos fluxos de automação  
- IA da Groq (LLM) para interpretação de linguagem natural  
- Transcrição automática de áudio  
- Google Calendar como agenda central e auditável  

**Fluxo resumido:**
1. Usuário envia mensagem (texto ou áudio) pelo Telegram  
2. n8n orquestra o fluxo e normaliza os dados  
3. IA interpreta a mensagem e extrai informações do agendamento  
4. Evento é criado ou validado no Google Calendar  
5. Confirmação é retornada ao usuário  

---

## ⚙️ Decisões Técnicas
- Telegram foi escolhido por ser amplamente utilizado e não exigir desenvolvimento ou manutenção de aplicativo próprio  
- n8n permite automações flexíveis com baixo custo operacional, ideal para pequenos negócios  
- IA da Groq viabiliza interpretação de mensagens livres, eliminando formulários rígidos  
- Suporte a áudio amplia acessibilidade sem aumentar a complexidade do sistema  
- Google Calendar funciona como fonte única da agenda, garantindo confiabilidade e histórico  

---

## 🎯 Problemas Resolvidos
- Agendamentos físicos e descentralizados  
- Erros manuais de horário e duplicidade  
- Falta de visibilidade da agenda  
- Dependência excessiva de atendentes  
- Retrabalho operacional  

---

## ✅ Resultados
- Redução do tempo operacional dos atendentes  
- Eliminação de erros comuns de agendamento manual  
- Centralização e organização da agenda  
- Maior previsibilidade e controle dos atendimentos  
- Solução financeiramente viável para pequenas empresas  

---

## 🚀 Possíveis Evoluções
- Suporte a múltiplos profissionais e agendas  
- Painel administrativo com relatórios  
- Integração com CRM ou sistemas de pagamento  
- Confirmações automáticas e lembretes por mensagem  

