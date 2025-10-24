# Sistema-de-Agendamento
# Barber Shop Automation

Sistema de automação inteligente para barbearias, integrando **WhatsApp**, **Google Sheets**, **Google Calendar** e um **Dashboard Web**.

Os clientes podem marcar horários diretamente pelo WhatsApp, enquanto o sistema registra tudo automaticamente e exibe os dados no painel de controle.

---

## Funcionalidades

- Agendamento via WhatsApp com mensagens automáticas  
- Cadastro automático de clientes no Google Sheets  
- Inteligência artificial para interpretar mensagens  
- Integração com Google Calendar  
- Dashboard com estatísticas e status em tempo real  

---

## Como funciona

1. O cliente envia uma mensagem no WhatsApp  
2. O fluxo no **n8n** interpreta com **IA (Groq Chat Model)**  
3. O sistema consulta e atualiza **Google Sheets** e **Google Calendar**  
4. O Dashboard exibe os agendamentos e seus respectivos status  

---

## Tecnologias utilizadas

| Função | Ferramenta |
|--------|-------------|
| Automação | n8n |
| Inteligência Artificial | Groq Chat Model |
| Banco de dados | Google Sheets |
| Agendamentos | Google Calendar |
| Comunicação | WhatsApp (Evolution API) |
| Interface | Dashboard Web (HTML, CSS, JS) |

