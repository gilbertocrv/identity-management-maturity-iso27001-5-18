Controle 5.18 – Access Rights

ISO/IEC 27001:2022

Avaliação de maturidade em governança de concessão, revisão e revogação de permissões.

Este módulo faz parte de uma série de estudos sobre Gestão de Acessos (Access Management) baseada nos controles públicos da ISO/IEC 27001:2022.

O foco do controle 5.18 – Access Rights é garantir que o acesso concedido aos usuários seja apropriado à função exercida e proporcional ao risco do negócio.

Uma identidade válida e uma autenticação forte não são suficientes se as permissões atribuídas forem excessivas ou mal controladas.

Permissão não deve ser consequência do tempo de casa.
Deve ser consequência da responsabilidade exercida.

Objetivo do Controle

Estabelecer governança sobre quem pode acessar quais recursos, garantindo que permissões sejam concedidas, revisadas e revogadas de forma controlada.

O controle aborda principalmente:

concessão formal de acessos

aplicação do princípio do menor privilégio

segregação de funções (SoD)

revisões periódicas de acesso

rastreabilidade das aprovações

O objetivo é reduzir riscos operacionais, fraudes internas e exposição desnecessária de informações sensíveis.

Principais Riscos Mitigados

Quando a governança de acesso não está estruturada, permissões tendem a se acumular ao longo do tempo.

Esse fenômeno é conhecido como Privilege Creep.

Alguns padrões comuns incluem:

concessões por conveniência para evitar bloqueios operacionais

usuários que mudam de função mas mantêm acessos antigos

ausência de responsáveis claros pela aprovação de acessos

Consequências frequentes:

fragilidade em auditorias

aumento do risco de fraude interna

dificuldade de rastrear responsabilidades

ampliação da superfície de ataque

Escala de Maturidade (0–5)

O módulo utiliza um modelo simplificado de maturidade para avaliar a governança de direitos de acesso.

Nível	Descrição
0 – Inexistente	Nenhum controle formal de concessão ou revisão de acessos
1 – Ad-hoc	Concessões manuais e reativas sem padrão definido
2 – Documentado	Processo definido, porém execução inconsistente
3 – Padronizado	Processos replicáveis com revisões periódicas
4 – Automatizado	Integração com plataformas de IAM/IGA
5 – Baseado em Risco	Concessões e revisões alinhadas à criticidade do negócio

Governança madura diferencia permissões conforme impacto e risco associado ao acesso.

Conexão com Outros Controles

Este controle faz parte de uma sequência lógica dentro da arquitetura de gestão de identidades e acessos.

Controle	Papel
5.15	Define as políticas de controle de acesso
5.16	Define quem é o usuário (gestão de identidade)
5.17	Protege os mecanismos de autenticação
5.18	Define o que o usuário pode fazer

Sem controle adequado sobre direitos de acesso, os controles anteriores perdem efetividade.

O Limite da Governança

O controle 5.18 trata da governança de permissões, mas existe uma camada adicional quando falamos de acessos privilegiados.

Contas administrativas, credenciais de serviço e acessos com capacidade de alterar o ambiente exigem controle técnico adicional.

Nesse ponto entra o controle:

8.2 – Privileged Access Rights

Enquanto o 5.18 define quem pode possuir privilégio, o 8.2 garante como esse privilégio é controlado tecnicamente.

Governança sem enforcement técnico é política sem garantia.

Deep Dive – Avaliação Prática

Este repositório contém um módulo interativo de avaliação de maturidade focado em:

gestão de concessão de acessos

segregação de funções (SoD)

revisão periódica de permissões

controle de privilégios

rastreabilidade de aprovações

A ferramenta possui caráter educacional e exploratório, voltado à reflexão sobre maturidade organizacional em governança de acessos.

Acesso ao Deep Dive

Interface interativa disponível em:

https://gilbertocrv.github.io/identity-management-maturity-iso27001-5-18/

Aviso

Este projeto:

não reproduz texto da norma ISO

não substitui auditorias formais

não representa metodologia oficial de certificação

Trata-se de um estudo independente sobre maturidade em gestão de acessos.
