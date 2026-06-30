# agendapro-beauty

O projeto simula uma demanda real de mercado: digitalização de agendamento de um salão
de beleza que atualmente realiza agendamentos manualmente (WhatsApp ou telefone),
enfrentando conflitos de horários, retrabalho e falta de controle gerencial.
Ao final do desafio, espera-se que os participantes sejam capazes de:
● Desenvolver uma aplicação web completa com autenticação e controle de acesso;
● Implementar sistema de agendamento com regras de disponibilidade;
● Criar integração entre front-end e back-end via API REST;
● Modelar e estruturar banco de dados relacional;
● Implementar regras de negócio (cancelamentos, bloqueio de horários, confirmação
de agendamento);
● Organizar, documentar e versionar o código;
● Trabalhar em equipe utilizando metodologia ágil;
● Demonstrar evolução técnica ao longo do período da residência.

Escopo do Sistema – Visão do Produto (MVP)
Funcionalidades para o Cliente:
• Cadastro e login de usuários
• Visualização de serviços oferecidos
• Visualização de profissionais disponíveis
• Filtro por área do salão (cabelo, manicure, estética facial, corporal etc.)
• Escolha de data e horário disponíveis

• Confirmação automática de agendamento
• Cancelamento ou reagendamento dentro de regras definidas
Funcionalidades Administrativas:
• Cadastro de profissionais
• Cadastro de serviços (com duração e valor)
• Organização por áreas do salão
• Definição de horários de trabalho de cada profissional
• Bloqueio manual de horários
• Visualização de agenda por profissional
• Dashboard simples com:
● Total de agendamentos
● Serviços mais solicitados
● Profissionais mais requisitados
Regras de Negócio do MVP:
• Impedir conflito de horários
• Considerar duração do serviço para bloqueio automático da agenda
• Permitir cancelamento com antecedência mínima configurável
• Controlar status do agendamento (Confirmado, Cancelado, Concluído)
Persistência e Estrutura:
• Banco de dados relacional
• API REST estruturada
• Controle básico de segurança e autenticação

Divisão de Responsabilidades
Back-end:
• Modelagem do banco de dados
• Implementação das regras de negócio de agendamento
• Criação da API REST
• Controle de autenticação e autorização
• Persistência e segurança dos dados
• Lógica de disponibilidade de horários
• Gestão de status dos agendamentos

Front-end:
• Desenvolvimento da interface pública do site
• Tela de agendamento intuitiva e responsiva
• Interface administrativa (painel interno)
• Experiência do usuário (cliente e administrador)
• Consumo da API
• Validação de dados no lado do cliente
• Organização visual das áreas e serviços

Tecnologias Sugeridas (Opcional)
• Front-end: React, Vue ou HTML/CSS/JS
• Back-end: Node.js, Python ou Java
• Banco de Dados: PostgreSQL ou MySQL
• Versionamento: Git e GitHub
• Metodologia: Scrum ou Kanban

Resultado Esperado ao Final da Residência
Ao final dos 3 meses, espera-se a entrega de:
• Sistema funcional
• Código organizado e versionado
• Documentação básica do projeto (README + documentação da API)
