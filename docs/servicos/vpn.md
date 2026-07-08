---
icon: lucide/globe-lock
---

# VPN

Questionário 5W1H para Implantação de VPN Linux

## What (O quê?)

1. Qual é o objetivo da implantação da VPN?
1. A VPN será utilizada para acesso remoto de usuários, interligação entre filiais (site-to-site) ou ambos?
1. Qual solução VPN será adotada?
    - [ ] OpenVPN
    - [ ] WireGuard
    - [ ] A definir após análise técnica
1. Quantos usuários utilizarão a VPN?
1. Quais serviços e recursos internos deverão ser acessados pela VPN?
1. Será necessário acesso a servidores, sistemas, bancos de dados ou aplicações específicas?
1. Haverá necessidade de autenticação multifator (MFA)?
1. A VPN deverá registrar logs de acesso para auditoria?

## Why (Por quê?)

1. Por que a organização necessita de uma VPN?
1. Quais problemas de segurança ou conectividade a solução pretende resolver?
1. Existe a necessidade de acesso seguro para trabalho remoto?
1. Há requisitos de conformidade ou auditoria que exigem a utilização de VPN?
1. Quais benefícios são esperados após a implantação?

## Where (Onde?)

1. Onde a VPN será instalada?
    - [ ] Servidor físico
    - [ ] Máquina virtual
    - [ ] Ambiente em nuvem
    - [ ] Outro
1. Quais redes internas estarão disponíveis através da VPN?
1. A VPN será acessada apenas por usuários internos ou também por terceiros?
1. Em quais localidades ou filiais o serviço será utilizado?
1. Há necessidade de comunicação entre diferentes redes ou datacenters?

## When (Quando?)

1. Quando a VPN deverá ser implantada?
1. Existe uma janela de manutenção definida para a instalação?
1. Quando os testes de conectividade e segurança serão realizados?
1. Qual a data prevista para entrada em produção?
1. Há um cronograma para migração dos usuários para a nova VPN?

## Who (Quem?)

1. Quem será responsável pela administração da VPN?
1. Quais usuários ou grupos terão acesso ao serviço?
1. Quem aprovará as permissões de acesso?
1. Quem realizará os testes e homologação?
1. Quem será responsável pelo monitoramento e suporte?
1. Quem decidirá a ferramenta a ser utilizada (OpenVPN ou WireGuard)?
    - [ ] Administradores de Sistemas
    - [ ] Equipe de Segurança
    - [ ] Gestores de TI
    - [ ] Outro

## How (Como?)

1. Como os usuários serão autenticados?
    - [ ] Usuário e senha
    - [ ] Certificados digitais
    - [ ] Chaves criptográficas
    - [ ] MFA

1. Como será realizado o gerenciamento dos acessos?
1. Como serão distribuídas e protegidas as credenciais dos usuários?
1. Como será realizado o monitoramento das conexões?
1. Como serão feitos os backups das configurações da VPN?
1. Como serão gerenciadas as atualizações e correções de segurança?
1. Como será implementada a alta disponibilidade, caso necessária?
1. Como serão tratados incidentes de segurança relacionados à VPN?
1. Como será validado o desempenho da solução após a implantação?

## Extra

Qual solução VPN Linux será adotada pela organização?

- [ ] OpenVPN
- [ ] WireGuard
- [ ] A definir após análise técnica dos administradores de sistemas

## Critérios para a escolha

- [ ] Desempenho da solução.
- [ ] Facilidade de configuração e manutenção.
- [ ] Compatibilidade com sistemas operacionais dos usuários.
- [ ] Requisitos de segurança e criptografia.
- [ ] Escalabilidade.
- [ ] Integração com LDAP, Active Directory ou MFA.
- [ ] Necessidade de suporte a túneis site-to-site e acesso remoto.

