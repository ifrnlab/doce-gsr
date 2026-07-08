---
icon: lucide/brick-wall-fire
---

# Firewall

Segue um pequeno questionário 5W1H para Implantação de Firewall Linux.

## What (O quê?)

1. Qual é o objetivo principal da implantação do firewall?
1. Quais serviços devem ser protegidos (SSH, HTTP, HTTPS, DNS, banco de dados etc.)?
1. Quais portas e protocolos precisam ser liberados?
1. Quais portas e protocolos devem ser bloqueados?
1. Qual ferramenta será utilizada: iptables, UFW ou firewalld?
1. Existem requisitos de registro (logs) para auditoria e monitoramento?

## Why (Por quê?)

1. Por que o firewall está sendo implantado?
1. Há alguma exigência de segurança, compliance ou auditoria?
1. Quais riscos se deseja mitigar com a solução?
1. Existe histórico de incidentes de segurança que justifique a implantação?

## Where (Onde?)

1. Em qual ambiente o firewall será implantado (produção, homologação, desenvolvimento)?
1. Em quais servidores ou estações Linux será aplicado?
1. O firewall protegerá acessos internos, externos ou ambos?
1. Há segmentação de rede (DMZ, VLANs, sub-redes)?

## When (Quando?)

1. Qual a data prevista para implantação?
1. Existe uma janela de manutenção definida?
1. Quando os testes de validação deverão ser realizados?
1. Há prazo para entrada em produção?

## Who (Quem?)

1. Quem será o responsável pela administração do firewall?
1. Quem aprovará as regras de acesso?
1. Quem será impactado pelas mudanças?
1. Quem será responsável pelo monitoramento e análise dos logs?

## How (Como?)

1. Como as regras serão definidas e documentadas?
1. Como será realizado o backup da configuração do firewall?
1. Como serão realizados os testes de conectividade e segurança?
1. Como será feita a manutenção e atualização das regras?
1. Como será o processo de contingência em caso de bloqueio indevido?
1. Como será garantida a persistência das regras após reinicializações?

## Extra

Qual ferramenta de firewall Linux será adotada?

- [ ] iptables
- [ ] UFW
- [ ] firewalld
- [ ] A definir após análise técnica

