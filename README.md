RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 01/07/2024
Empresa: Abstergo Industries
Responsável: Leandro Magalhães

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Leandro Magalhães. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de aumentar a segurança na empresa.

Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: Implementação do AWS Identity and Access Management (IAM)

Descrição do caso de uso: O AWS IAM foi configurado para gerenciar o acesso aos recursos da AWS de forma segura. Foram criadas políticas de acesso baseadas nos princípios de menor privilégio, permitindo que os funcionários tenham acesso apenas aos recursos necessários para suas funções específicas.
Etapas da Implementação:
Análise das necessidades de acesso dos funcionários.
Criação de usuários e grupos no IAM.
Definição e aplicação de políticas de acesso.
Implementação de autenticação multifator (MFA) para usuários com acesso privilegiado.
Medida 2: Configuração do AWS CloudTrail

Descrição do caso de uso: O AWS CloudTrail foi configurado para monitorar e registrar todas as ações realizadas nos recursos da AWS. Isso permite auditoria e rastreamento de atividades, ajudando a identificar comportamentos suspeitos e não autorizados.
Etapas da Implementação:
Ativação do CloudTrail em todas as regiões da AWS utilizadas pela empresa.
Configuração de logs para serem armazenados de forma segura no Amazon S3.
Integração com Amazon CloudWatch para monitoramento em tempo real.
Configuração de alertas para atividades suspeitas.
Medida 3: Implementação do AWS Key Management Service (KMS)

Descrição do caso de uso: O AWS KMS foi implementado para gerenciar e proteger chaves de criptografia usadas para proteger dados em trânsito e em repouso. Isso garante que os dados confidenciais da empresa estejam sempre protegidos.
Etapas da Implementação:
Criação e gerenciamento de chaves de criptografia no KMS.
Integração com serviços da AWS que suportam criptografia, como Amazon S3 e Amazon RDS.
Definição de políticas de rotação de chaves para garantir segurança contínua.
Treinamento da equipe de TI sobre o uso e gestão das chaves de criptografia.
Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado o aumento da segurança dos dados e a redução de riscos de acesso não autorizado. Isso resultará em maior eficiência e produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Anexos
Manual de Usuário do AWS IAM.
Guia de Configuração do AWS CloudTrail.
Documentação do AWS KMS.
Planilha de Controle de Acessos.
Assinatura do Responsável pelo Projeto:

Leandro Magalhães
