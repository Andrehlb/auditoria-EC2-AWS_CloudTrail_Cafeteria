# Auditoria em instância EC2, usando AWS CloudTrail

**Introdução**

Este repositório GitHub documenta a auditoria realizada nas ações executadas na conta AWS usando o AWS CloudTrail. O objetivo é identificar quem modificou o site da cafeteria Café. A investigação se concentra em uma instância Amazon Elastic Compute Cloud (Amazon EC2) chamada Café Web Server, que executa um aplicativo web que hospeda o site.

**Resumo**

A equipe da Cafeteria Café descobriu que um hacker havia acessado indevidamente a instância EC2 que hospeda o site da cafeteria e modificado a imagem de um item do menu. Além disso, o hacker criou uma conta de usuário na AWS e abriu a porta 22 no grupo de segurança para toda a internet.

**Lições Aprendidas**

A importância de ter medidas de segurança robustas em vigor.
O valor do CloudTrail para auditar atividades e identificar atividades suspeitas.
A necessidade de ter um plano de resposta a incidentes.

**Ações Tomadas**

Identificação do Hacker: A equipe utilizou o CloudTrail para identificar o usuário "chaos" como responsável pelas modificações.
Remoção do Hacker: O hacker foi removido da instância EC2 e sua conta de usuário da AWS foi excluída.
Restauração do Site: A imagem original do item do menu foi restaurada e a porta 22 foi fechada no grupo de segurança.
Fortalecimento da Segurança: As políticas de segurança da AWS foram revisadas e fortalecidas.

**Próximos Passos**

Continuar monitorando as atividades da conta AWS usando o CloudTrail.
Treinar os membros da equipe sobre práticas de segurança de TI.
Implementar medidas adicionais de segurança, como autenticação multifator e criptografia de dados.

**Conclusão**

Ao tomar medidas proativas para resolver o incidente e aprender com a experiência, a equipe da Cafeteria Café está melhor posicionada para proteger seu site e seus dados contra futuros ataques.

**Recomendações Finais**

Revisar e atualizar periodicamente as políticas de segurança da AWS.
Realizar treinamentos de conscientização sobre segurança da informação para os membros da equipe.
Implementar soluções de segurança em camadas, como firewalls, sistemas de detecção de intrusão e criptografia de dados.
Manter os sistemas e softwares atualizados com os últimos patches de segurança.
Ao tomar medidas proativas e seguir as melhores práticas de segurança, a Cafeteria Café pode minimizar o risco de futuros ataques e proteger seus ativos valiosos.
