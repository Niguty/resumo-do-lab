# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

Concluí recentemente um certificado de Introdução à Computação em Nuvem, onde pude consolidar conceitos fundamentais sobre cloud computing e seus modelos.

Durante o aprendizado, entendi a diferença entre CAPEX (custos de investimento físico, comuns em ambientes on-premises) e OPEX (custos operacionais baseados em consumo, característicos da nuvem). Também aprofundei os modelos de implantação, como nuvem pública, privada e híbrida, além do conceito de on-premises e sua integração com ambientes em cloud.

Outro ponto importante foi o entendimento do modelo de responsabilidade compartilhada, percebendo como as responsabilidades variam entre cliente e provedor conforme o modelo de serviço (IaaS, PaaS e SaaS).

Mais um passo importante para fortalecer minha base em infraestrutura moderna e computação em nuvem ☁️
Seguimos evoluindo.

Beneficios da nuvem -

Serviços de Nuvem: (LaaS, PaaS, SaaS)

LaaS - O cliente aluga o hardware da Microsoft e providencia sua disponibilidade.
PaaS - O provedor de nuvem mantem a infraestrutura e mantém a funcionalidade em geral, mantendo segurança por meio de atualizações e patches.
SaaS - Provedor com maior responsabilidade, usuário provem os dados para o sistema e pelos dispositivos a se conectarem e usuários a terem acesso.

Benefícios da Nuvem Azure:

Alta disponibidlidade  sempre funcionando confiabilidade; flexibilidade.
->  Contratado = termos

Termos da Azure? -> Oferece serviço, Manutenção, Honra contrato.

Alta disponibilidade = SLA (Contrato/Acordo de serviço medido em porcentagem EX: 99% Disponível)

Escalabilidade: Ajustar a capacidade do ambiente para atender uma determinada demanda, sendo o caso de adicionar mais recursos.

X

Elasticidade: Incerteza no crescimento risco de disponibilidade do serviço adição de recursos por meio da necessidade de requisição a partir no momento que chega a uma porcentagem ou media aumenta ou diminui a aplicação de recursos.

Confiabilidade = Resiliência: para se recuperar de falhas criando recursos disponíveis para possíveis recovery (Tudo graças ao conceito de design descentralizado)

Previsibilidade = Fator ligado a confiabilidade onde é necessário ofertar disponibilidade aos recursos dependendo desempenho crescente ou redução relacionando a avaliação de custo.

Segurança = A nuvem oferece ferramentas de segurança que atendem as necessidades dos clientes. Regras/Limitações no acesso para não comprometer a segurança e para manter disponibilidade e evitar ataques internos/externos. 
     |
interligados?
     |
Governança = Gestão?: Padrões/Auditoria - (Cenário mais presente de big tech e empresas em crescimento) Linha de quem faz o quê, quem cria.

*Auditoriia* ponto onde irá sinalizar a anomalia e fornece estrategia de mitigação.

Gerenciabilidade: Capacidade de gerenciamento é o principal beneficio de se utilizar a computação em nuvem e a capacidade de se utilizar meios automatizados por meio de desenvolvimento por meio de (Code Line, API's e Script Powershell)

laaS (infraestrutura como serviço)

PaaS (plataforma como serviço)

SaaS (software como serviço)

* Arquitetura e serviços do Azure. (AZ-900) *

Regiões (Recurso e disponibilidade)

- Divergência de valores em regiões, dificuldade de trafego indisponibilidade em determinadas regiões

- Os recursos podem se conectados entre regiões podendo se relacionar matriz e afilial.

(Azure) Conta trial - regiões de baixa disponibilidade

3 datacenter's por região (zona de disponibilidade)

Aplicação do conceito de back boné onde há comunicação entre os datacenters = região (zona de disponibilidade)

Queda de Datacenter = Lentidão mas funcionalidade e disponibilidade.

Disaster recovery = ambiente fora, ativação em outra região.

recovery seria duplicar os dados entre os datacenters da região para reduzir a latência.

LGPD - Garantia de responsabilidade pelos dados

Zona de disponibilidade (Host - receber recursos) = Máquinas virtuais.

Disponibilidade = custo manutenção

Indisponibilidade = perca lucrativa

(A ideia dos datacenters é que se ajudam, se um cair outro assume)

Pares de Regiões (Zona segundária - Auxiliar)

Disastery recover = indisponibilidade em uma região auxiliar de uma segunda região para evitar interrupção.

Região pares = regiões que irão dar apoio a possível indisponibilidade da região principal.

Regiões soberanas (Exclusivas)

Regiões despolitizada para área militar (restrita/isolada)

Recursos do Azure China: Garantia de isolamento de dados (governo chinês)

Recursos do Azure
 -> Grupo de Recursos (Organização) / ideia de caixinha e agrupamento
   - Esse grupo é de serviços
   - Esse grupo é de máquinas

Grupos podem existir em apenas um grupo de recursos e em diferentes regiões.

Uma conta da Azure pode estar envolta a diversas assinaturas e diversas podem estar associada a uma assinatura.

Para cada conta = diversas assinaturas

Por que criar diversas contas - para cada grupo de trabalho uma assinatura diferente para organização?

assinaturas pode haver várias em uma única conta, afirmação!


*Criação de grupo de recursos*

Seleção previa da nossa assinatura

Grupo de recursos é obrigatório ter nome e região  especificada

Marcações subtítulo recursos tageados (Rastreabilidade)

Iam (gestão de acesso)

log de atividade (auditoria)

Visualização dos recursos

Eventos (automatizações)
