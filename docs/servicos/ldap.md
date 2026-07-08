---
icon: lucide/folder-tree
---

# LDAP

Questionário 5W1H para Implantação de LDAP

## What (O quê?)

1. Qual é o objetivo da implantação do LDAP?
1. Qual solução LDAP será utilizada?
    - [ ] OpenLDAP
    - [ ] FreeIPA
    - [ ] 389 Directory Server
    - [ ] Outra: __________
    - [ ] A definir após análise técnica

- Quais informações serão armazenadas no diretório (usuários, grupos, dispositivos, aplicações)?
- Quais sistemas utilizarão o LDAP para autenticação?
- Haverá integração com Active Directory?
- Quais atributos dos usuários precisarão ser gerenciados?
- Será necessário suporte a Single Sign-On (SSO)?
- Haverá necessidade de alta disponibilidade e replicação?

## Why (Por quê?)

- Por que a organização deseja implantar um serviço LDAP?
- Quais problemas atuais a solução pretende resolver?
- Existe necessidade de centralização da autenticação?
- Há exigências de auditoria ou conformidade que justifiquem a implantação?
- O objetivo é reduzir a administração de usuários em múltiplos sistemas?
- Quais benefícios são esperados após a implantação?

## Where (Onde?)

1. Onde o servidor LDAP será instalado?
    - [ ] Ambiente local (On-Premises)
    - [ ] Nuvem
    - [ ] Híbrido

1. Quais servidores, aplicações ou serviços utilizarão o LDAP?
. Em quais localidades ou unidades da organização o serviço será utilizado?
1. O LDAP ficará em uma rede interna ou será acessado externamente?
1. Haverá integração com múltiplos datacenters?

## When (Quando?)

1. Quando será realizada a implantação?
1. Existe uma janela de manutenção definida?
1. Quando ocorrerão os testes de integração?
1. Qual o prazo para entrada em produção?
1. Há cronograma para migração de usuários existentes?
1. Quando será realizada a capacitação da equipe responsável?

## Who (Quem?)

1. Quem será responsável pela administração do LDAP?
1. Quem fornecerá os requisitos dos usuários e grupos?
1. Quem aprovará as políticas de autenticação?
1. Quem realizará os testes e homologação?
1. Quais equipes serão impactadas pela implantação?
1. Quem será responsável pela manutenção e suporte da solução?

## How (Como?)

1. Como será estruturada a árvore LDAP (DIT)?
1. Como os usuários e grupos serão cadastrados?
1. Como ocorrerá a autenticação das aplicações?
1. Como será realizada a migração dos usuários existentes?
1. Como será implementada a segurança da comunicação (LDAP over TLS/SSL)?
1. Como será configurado o controle de acesso (ACLs)?
1. Como será realizado o backup e recuperação do diretório?
1. Como será implementada a replicação entre servidores LDAP?
1. Como será feito o monitoramento do serviço?
1. Como serão tratados incidentes e falhas de autenticação?

## Extra

Antes de iniciar a implantação, recomenda-se incluir a seguinte questão:

1. Qual solução LDAP será adotada pela organização?

    - [ ] OpenLDAP
    - [ ] FreeIPA
    - [ ] 389 Directory Server
    - [ ] Microsoft Active Directory
    - [ ] Outra: __________
    - [ ] A definir após análise técnica
