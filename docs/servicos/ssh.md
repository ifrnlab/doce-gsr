---
icon: lucide/square-terminal
---

# SSH

Questionário 5W1H para Implantação e Configuração de SSH no Linux

## What (O quê?)

1. Qual é o objetivo da implantação do SSH?
1. O SSH será utilizado para administração remota, transferência de arquivos (SCP/SFTP) ou ambos?
1. Quais servidores ou equipamentos terão o serviço SSH habilitado?
1. Quais usuários precisarão de acesso SSH?
1. Será utilizada autenticação por senha, chave pública ou ambos?
1. O serviço SSH utilizará a porta padrão (22) ou uma porta personalizada?
1. Haverá necessidade de tunelamento SSH ou redirecionamento de portas?
1. Quais níveis de acesso serão permitidos aos usuários?

## Why (Por quê?)

1. Por que o acesso remoto via SSH é necessário?
1. Quais processos administrativos dependem do SSH?
1. Existe a necessidade de substituir métodos menos seguros de acesso remoto?
1. Há requisitos de segurança ou auditoria que justifiquem a configuração do serviço?
1. Quais benefícios são esperados com a centralização do acesso remoto?

## Where (Onde?)

1. Em quais servidores Linux o SSH será implantado?
1. O acesso será realizado apenas pela rede interna ou também pela Internet?
1. Existem sub-redes ou localidades específicas que necessitam de acesso SSH?
1. O SSH será utilizado em ambientes de produção, homologação ou desenvolvimento?
1. Haverá restrições de acesso por endereço IP ou segmento de rede?

## When (Quando?)

1. Quando o serviço SSH deverá ser implantado?
1. Existe uma janela de manutenção para a configuração?
1. Quando os testes de conectividade e autenticação serão realizados?
1. Qual a data prevista para entrada em produção?
1. Haverá cronograma para migração dos acessos atuais para SSH?

## Who (Quem?)

1. Quem será responsável pela administração do serviço SSH?
1. Quais usuários ou equipes terão acesso remoto?
1. Quem aprovará as permissões de acesso?
1. Quem realizará os testes e validação da configuração?
1. Quem será responsável pelo monitoramento e auditoria dos acessos SSH?
1. Quem autorizará a criação, alteração ou remoção de usuários?

## How (Como?)

1. Como será realizada a autenticação dos usuários?
1. Como serão gerenciadas as chaves públicas e privadas?
1. Como será controlado o acesso privilegiado (sudo ou acesso root)?
1. Como será feita a restrição de acesso por IP, grupo ou usuário?
1. Como serão registrados e monitorados os logs de acesso?
1. Como será realizado o backup das configurações do SSH?
1. Como serão aplicadas atualizações e correções de segurança?
1. Como será tratado o bloqueio de tentativas de acesso indevidas (Fail2Ban, por exemplo)?
1. Como será garantida a disponibilidade do serviço em caso de falhas?
1. Como será realizado o procedimento de recuperação em caso de perda de acesso?

## Outras perguntas

O acesso direto do usuário root será permitido?

- [ ] Sim
- [ ] Não

Qual método de autenticação será adotado?

- [ ] Senha
- [ ] Chave SSH
- [ ] Multifator (MFA)
- [ ] Combinação dos métodos

Haverá restrição de acesso por IP?

- [ ] Sim
- [ ] Não

O serviço utilizará uma porta personalizada?

- [ ] Sim
- [ ] Não
Porta: __________

Será implementado mecanismo de proteção contra ataques de força bruta?

- [ ] Sim
- [ ] Não

## Extra

Qual implementação de SSH será utilizada?

- [ ] OpenSSH (recomendado e padrão na maioria das distribuições Linux)
- [ ] Dropbear SSH
- [ ] Outra: __________
- [ ] A definir após análise técnica
