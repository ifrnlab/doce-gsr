---
icon: lucide/chart-line
---

# Zabbix

![Tela inicial do Zabbix](./imagens/zabbix-tela-inicial.png)

Questionário 5W1H para Implantação de um Sistema de Monitoramento (Zabbix ou Nagios)

## What (O quê?)

1. Qual é o objetivo da implantação do sistema de monitoramento?
1. Qual ferramenta será adotada?
    - [ ] Zabbix
    - [ ] Nagios
    - [ ] Icinga
    - [ ] Outra: __________
    - [ ] A definir após análise técnica
1. Quais ativos serão monitorados?
    - [ ] Servidores Linux
    - [ ] Servidores Windows
    - [ ] Equipamentos de rede
    - [ ] Banco de dados
    - [ ] Aplicações
    - [ ] Serviços em nuvem
1. Quais métricas deverão ser acompanhadas?
- [ ] CPU
- [ ] Memória
- [ ] Disco
- [ ] Rede
- [ ] Disponibilidade
- [ ] Logs
- [ ] Outras
1. Haverá necessidade de dashboards personalizados?
1. Será necessário envio de alertas automáticos?

## Why (Por quê?)

1. Por que a organização deseja implantar um sistema de monitoramento?
1. Quais problemas atuais a solução pretende resolver?
1. Existe dificuldade em identificar falhas e indisponibilidades?
1. Há necessidade de monitoramento proativo?
1. Existem exigências de auditoria ou conformidade?
1. Quais benefícios são esperados após a implantação?

## Where (Onde?)

1. Onde a solução será instalada?
    - [ ] Ambiente local (On-Premises)
    - [ ] Nuvem
    - [ ] Ambiente híbrido

1. Quais localidades, filiais ou datacenters serão monitorados?
1. Existem dispositivos remotos que também deverão ser monitorados?
1. Onde serão armazenados os dados históricos de monitoramento?
1. O monitoramento abrangerá somente a rede interna ou também serviços externos?

## When (Quando?)

1. Quando o sistema deverá ser implantado?
1. Existe uma janela de manutenção prevista?
1. Quando os testes de monitoramento deverão ser realizados?
1. Quando o ambiente entrará em produção?
1. Existe cronograma para inclusão gradual de ativos?

## Who (Quem?)

1. Quem será responsável pela administração da ferramenta?
1. Quem será responsável pela análise dos alertas?
1. Quem receberá notificações de falhas?
1. Quem realizará a homologação da solução?
1. Quem aprovará os dashboards e relatórios?
1. Quem decidirá a ferramenta a ser utilizada?
    - [ ] Administradores de Sistemas
    - [ ] Equipe de Infraestrutura
    - [ ] NOC
    - [ ] Gestão de TI
    - [ ] Outro

## How (Como?)

1. Como os ativos serão cadastrados no sistema?
1. Como será realizado o monitoramento?
    - [ ] Agentes
    - [ ] SNMP
    - [ ] ICMP (Ping)
    - [ ] APIs
    - [ ] Scripts personalizados

1. Como os alertas serão enviados?
    - [ ] E-mail
    - [ ] SMS
    - [ ] Microsoft Teams
    - [ ] Telegram
    - [ ] WhatsApp
    - [ ] Outro

1. Como será realizado o backup da configuração?
1. Como serão gerenciadas as permissões dos usuários?
1. Como serão gerados relatórios de disponibilidade?
1. Como será realizado o monitoramento de aplicações críticas?
1. Como será feita a retenção dos dados históricos?
1. Como serão realizadas as atualizações e manutenções da ferramenta?
1. Como será garantida a alta disponibilidade do sistema de monitoramento?
1. Perguntas Técnicas Complementares
1. Escopo do Monitoramento
1. Quantos servidores serão monitorados inicialmente?
1. Existe previsão de crescimento do ambiente?
1. Quantos dispositivos de rede deverão ser monitorados?
1. Será necessário monitorar serviços em nuvem (Azure, AWS, Google Cloud)?
1. Alertas e Notificações
1. Qual deverá ser o horário de funcionamento do monitoramento?
1. Haverá escalonamento automático de incidentes?
1. Qual o tempo máximo aceitável para identificação de falhas?

### Segurança

1. Quem terá acesso administrativo ao sistema?
1. Haverá integração com LDAP ou Active Directory?
1. Será utilizada autenticação multifator (MFA)?
1. Os acessos serão auditados?

### Relatórios

1. Quais relatórios deverão ser gerados?
1. Com qual frequência?
    - [ ] Diário
    - [ ] Semanal
    - [ ] Mensal
    - [ ] Sob demanda

1. Quais indicadores devem aparecer nos relatórios?
1. Pergunta Adicional sobre a Ferramenta

1. Qual sistema de monitoramento será adotado pela organização?

    - [ ] Zabbix
    - [ ] Nagios
    - [ ] Icinga
    - [ ] LibreNMS
    - [ ] Outra: __________
    - [ ] A definir após análise técnica dos administradores de sistemas

## Critérios para Escolha

- [ ] Facilidade de instalação e administração.
- [ ] Escalabilidade.
- [ ] Recursos de monitoramento nativos.
- [ ] Dashboards e visualização de dados.
- [ ] Integração com LDAP/Active Directory.
- [ ] Integração com sistemas de chamados.
- [ ] Recursos de alertas e notificações.
- [ ] Suporte a alta disponibilidade.
- [ ] Custos de implantação e manutenção.
- [ ] Curva de aprendizado da equipe.
