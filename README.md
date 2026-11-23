##Desafio Criativo: Do Alerta à Resposta: Prompt para Investigar um Achado do Amazon GuardDutyesafio-criativo-aws-guard-duty
###Contexto do Achado (Dados do Console GuardDuty):
• Tipo (Finding Type): UnauthorizedAccess:IAMUser/ConsoleLoginSuccess.B
• Recurso Afetado: Usuário IAM deploy-cicd-prod (Account ID: 1234-5678-9012)
• Severidade: Alta (7.0)
• Quando aconteceu: 23/11/2026 às 03:14 UTC (00:14 BRT), originado de um IP localizado em Frankfurt, Alemanha (18.192.XX.XX).
###Contexto do Ambiente:
• Esta conta AWS hospeda o ambiente de produção do nosso e-commerce.
• O usuário deploy-cicd-prod é uma conta de serviço usada apenas via API/CLI por pipelines automatizados; ele nunca deveria fazer login no Console Web da AWS.
• Nossa equipe de engenharia e operações trabalha 100% no Brasil e não utiliza VPNs ou servidores na Alemanha.
###Público-Alvo (Quem recebe a análise):
• Escreva a análise para um desenvolvedor júnior que acabou de assumir a gestão desta conta AWS, não tem experiência prévia com resposta a incidentes de segurança e precisa de instruções passo a passo claras, sem jargões complexos de SOC.
###Tarefa:
Analise a gravidade deste alerta considerando o contexto fornecido e liste as 3 primeiras ações imediatas de contenção que esse profissional deve executar no console da AWS.
