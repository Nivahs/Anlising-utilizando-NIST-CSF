## Visão geral da atividade
Nesta atividade, você criará um relatório de incidente usando o conhecimento que adquiriu sobre redes ao longo deste curso para analisar um incidente de rede. Você analisará a situação usando a Estrutura de Segurança Cibernética do Instituto Nacional de Padrões e Tecnologia (NIST CSF). A CSF é uma estrutura voluntária que consiste em padrões, diretrizes e práticas recomendadas para gerenciar o risco de segurança cibernética. A criação de um relatório de incidentes de segurança cibernética de qualidade e a aplicação do CSF podem demonstrar uma abordagem proativa à segurança, melhorando a comunicação e a transparência com as partes interessadas e aprimorando as práticas de segurança em sua organização. Você também pode adicionar o relatório de incidente criado ao seu portfólio de segurança cibernética quando o concluir.

O CSF é escalável e pode ser aplicado em uma ampla variedade de contextos. À medida que continuar a aprender mais e a refinar sua compreensão das principais habilidades de segurança cibernética, você poderá usar os modelos fornecidos nesta atividade em outras situações. Saber como identificar quais medidas de segurança devem ser aplicadas em resposta às necessidades do negócio o ajudará a determinar quais são as melhores opções disponíveis quando se trata de segurança de rede.

Não deixe de concluir esta atividade antes de prosseguir. No próximo item do curso, você poderá fazer uma autoavaliação de sua resposta. Depois disso, haverá um exemplo concluído para comparar com seu próprio trabalho. Isso também lhe dará a oportunidade de responder a perguntas da rubrica que lhe permitirão refletir sobre os principais elementos de sua declaração profissional.

## Cenário
Analise o cenário abaixo. Em seguida, conclua as instruções passo a passo.

Você é analista de segurança cibernética e trabalha para uma empresa de multimídia que oferece serviços de Web design, design gráfico e soluções de marketing de mídia social para pequenas empresas. Sua organização sofreu recentemente um ataque DDoS, que comprometeu a rede interna por duas horas até ser resolvido.

Durante o ataque, os serviços de rede de sua organização pararam de responder repentinamente devido a um fluxo de entrada de pacotes ICMP. O tráfego normal da rede interna não conseguia acessar nenhum recurso da rede. A equipe de gerenciamento de incidentes respondeu bloqueando a entrada de pacotes ICMP, interrompendo todos os serviços de rede não críticos off-line e restaurando os serviços de rede críticos.

Em seguida, a equipe de segurança cibernética da empresa investigou o evento de segurança. Eles descobriram que um agente mal-intencionado havia enviado um ataque flood de pings ICMP para a rede da empresa por meio de um firewall não configurado. Essa vulnerabilidade permitiu que o invasor mal-intencionado sobrecarregasse a rede da empresa por meio de um ataque distribuído de negação de serviço (DDoS).

Para resolver esse evento de segurança, a equipe de segurança de rede implementou:

1. Uma nova regra de firewall para limitar a taxa de entrada de pacotes ICMP

2. Verificação do endereço IP de origem no firewall para verificar se há endereços IP falsos nos pacotes ICMP recebidos

3. Software de monitoramento de rede para detectar padrões de tráfego anormais

4. Um sistema IDS/IPS para filtrar algum tráfego ICMP com base em características suspeitas

Como analista de segurança cibernética, você tem a tarefa de usar esse evento de segurança para criar um plano para melhorar a segurança de rede da sua empresa, seguindo a Estrutura de Segurança Cibernética (CSF) do Instituto Nacional de Padrões e Tecnologia (NIST). Você usará a CSF para ajudá-lo a navegar pelas diferentes etapas de análise desse evento de segurança cibernética e integrar sua análise a uma estratégia geral de segurança. Dividimos a análise em diferentes partes no modelo abaixo. Você pode explorá-las aqui:

1. **Identificar** riscos de segurança por meio de auditorias regulares de redes internas, sistemas, dispositivos e privilégios de acesso para identificar possíveis lacunas na segurança.

2. **Proteger** os ativos internos por meio da implementação de políticas, procedimentos, treinamento e ferramentas que ajudem a mitigar as ameaças à segurança cibernética.

3. **Detectar** possíveis incidentes de segurança e melhorar os recursos de monitoramento para aumentar a velocidade e a eficiência das detecções.

4. **Responder** para conter, neutralizar e analisar incidentes de segurança; implementar melhorias no processo de segurança.

Recuperar os sistemas afetados para a operação normal e restaurar os dados e/ou ativos dos sistemas que tenham sido afetados por um incidente. 
