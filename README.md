🤖 Agente de Atendimento

Criei um agente de IA que realiza o atendimento automatizado para uma clínica de estética.

🧠 Como funciona?

O agente de IA é integrado ao WhatsApp do usuário por meio de uma API do WhatsApp (no meu caso, utilizei a Evolution API).

Através dessa integração, o agente recebe webhooks com as mensagens dos usuários, que podem ser enviadas em formato de texto, áudio ou imagem para análise. Após o recebimento, o agente processa o conteúdo e responde de forma inteligente — por texto ou áudio — com base em probabilidades e contexto.

Além de responder dúvidas, o agente também realiza o agendamento de consultas, analisa imagens, e encaminha casos urgentes para as autoridades competentes.

Para o tratamento e armazenamento de dados, as informações dos clientes são registradas em uma planilha do Google Sheets, utilizada como banco de dados. Os agendamentos são realizados automaticamente no Google Calendar, e o agente conta ainda com uma ferramenta de lembretes automáticos, que envia notificações periódicas aos pacientes sobre suas consultas.

O treinamento do agente foi realizado com diversos documentos, incluindo FAQs, simulações de atendimento, documentos de personalidade, regras de negócio, entre outros materiais.

Para otimizar e simplificar o fluxo de funcionamento, foram utilizados servidores MCP desenvolvidos por mim, responsáveis pela integração com o Google Sheets, Google Calendar e módulos de treinamento do agente.
