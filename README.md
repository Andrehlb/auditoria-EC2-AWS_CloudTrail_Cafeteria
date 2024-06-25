# Auditoria em instância EC2, usando AWS CloudTrail

**Introdução**

Este repositório GitHub documenta a auditoria realizada nas ações executadas na conta AWS usando o AWS CloudTrail. O objetivo é identificar quem modificou o site da cafeteria Café. A investigação se concentra em uma instância Amazon Elastic Compute Cloud (Amazon EC2) chamada Café Web Server, que executa um aplicativo web que hospeda o site.

**Etapas**

1. **Coleta de Registros do CloudTrail:**
    * Acessar o console do AWS CloudTrail.
    * Navegar até a seção "Eventos de eventos".
    * Definir um intervalo de tempo para a auditoria, coincidente com o período em que as modificações no site da cafeteria podem ter ocorrido.
    * Filtrar eventos por tipo de evento, região e nome da instância EC2 "Café Web Server".
    * Exportar os resultados da pesquisa para um arquivo CSV.

2. **Análise dos Registros:**
    * Abrir o arquivo CSV exportado em um editor de planilhas ou software de análise de dados.
    * Identificar eventos relevantes relacionados a modificações no site da cafeteria, como alterações em arquivos, configurações ou logs.
    * Observar os campos "Usuário" e "Fonte de evento" para cada evento relevante.

3. **Investigação:**
    * Utilizar os campos "Usuário" e "Fonte de evento" para identificar os indivíduos ou serviços que realizaram as modificações no site da cafeteria.
    * Consultar logs de acesso, ferramentas de gerenciamento de identidade e acesso (IAM) e outras fontes de informação para confirmar as atividades e responsabilidades dos usuários.
    * Documentar as descobertas e conclusões da investigação.

**Resultados Esperados**

* Identificar os indivíduos ou serviços responsáveis pelas modificações no site da cafeteria Café.
* Determinar a natureza das modificações realizadas.
* Avaliar o impacto das modificações na segurança e na operação do site.
* Documentar as descobertas e conclusões da investigação para fins de auditoria e aprendizado.

**Recursos Adicionais**

* Documentação do AWS CloudTrail [URL inválido removido]
* Tutoriais do AWS CloudTrail [URL inválido removido]
* Melhores práticas para o AWS CloudTrail [URL inválido removido]

**Observações**

* Este README.md é um ponto de partida para a auditoria. Adapte as etapas e os recursos de acordo com suas necessidades específicas.
* Certifique-se de ter as permissões e o acesso adequados para realizar a auditoria na conta AWS.
* Siga as políticas e procedimentos de segurança da sua organização ao realizar a investigação.

**Próximos Passos**

* Complete a coleta e análise dos registros do CloudTrail.
* Realize a investigação para identificar os responsáveis pelas modificações no site da cafeteria.
* Documente as descobertas e conclusões da auditoria.
* Implemente as medidas corretivas necessárias para garantir a segurança e a integridade do site da cafeteria.
