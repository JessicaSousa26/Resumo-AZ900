# Resumo-AZ900
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab Az-900 na DIO

**Lição 1 - Localizando Serviços por Categoria**

Ter a conta criada;
É a mesma visualização para empresas e usuários;
Trial - pode haver a limitação de uso dos recursos ou regiões;
Há algumas opções para personalizar a aparência, idioma;
Há inúmeras categorias e recursos para utilizar;
Bastião ao acesso seguro das máquinas (on-premises virtualizado);
Cuidado com versão previa pois é como se fosse uma demo e pode sair do ar de repente.
Previa não tem SLA e garantia que vai continuar;
A nuvem é para todas as profissões.

**Lição 2 - Benefícios da Nuvem**

**Alta disponibilidade** - SLA - garantia do serviço no tempo estabelecido. A Microsoft se responsabiliza pelo problema. Quantidade de 9 envolvidos: 99%, 99.9%, 99.95% - contratos precisam ser cumpridos e recebe créditos senão foi fornecido o que estava estabelecido. Entender o fluxo de funcionamento é fundamental para cumprimento do contrato. Se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos qu possam ocorrer.

**Escalabilidade** - refere-se à capacidade de ajustar recursos para atender à demanda. A capacidade de escalar significa que voê poderá adicionar mais recursos para lidar melhor com o aumento da demanda.

Ajustar a capacidade do ambiente para uma determinada demanda.
Não paga além do necessário pelos serviços
Paga somente pelo que usa.
Se a demanda cair pode reduzir os recursos e assim os custos.

**Elasticidade** - tem um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente). Ex: crescimento de acessos no site das lojas na blackfriday.

Pode dimensionar o ambiente conforme requisições (acima de 75% - máximo de máquinas a utilizar)
Queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente(de maneira automática ou manual).
Cresce ou aumenta conforme a demanda

**Confiabilidade** - Pode criar recursos em qualquer lugar que possui acesso e pode pagar. Consegue acompanhar ativamente. Traz em poucas ações. É um ambiente amigável para TI e cliente. Ao passar por desastres continua funcionando.

Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente. Criar em diversos locais.
Com um design descentralizado, a nuvem permite que voê tenha recursos implantados em várias regiões do mundo. Cria ambientes altamente disponíveis através de um ambiente confiável, contendo replicações, desastrer recovery errado fica minimamente fora. 

**Previsibilidade** - prever o tempo, confiança e desempenho dos recursos.

Permite avançar na confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo Microsoft Azure Well-Architected Framework.
Confiar que vai ter os melhores recursos, apoio da Microsoft. Cases de Sucesso.

**Segurança** - é divida entre a empresa e o provider. É necessário investir bastante. Área em crescimento. A implementação **NÃO** é responsabilidade da Microsoft.

A nuvem oferece ferramentas de segurança, mas, a implementação é pelo cliente, apólice para usuários não acessarem o painel de controle, não alterar a hora do relógio, não poderem acessar o CMD. Associa o modelo, o que faz o que. Microsoft faz a segurança de recursos e tudo funcionando. Sua função previnir de ataques internos ou externos, atualizar a máquina - sua maior gestão.RBAC já está na máquina, Microsoft Defender for Identity tem um custo.

Se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas, permitirá que voê gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.

Responsabilidades
Provider - oferecer recursos e serviços para atender a minha demanda.
Empresa - aplicar os recursos de segurança oferecidos.

**Governança** - gerir os recursos e padrões a serem seguidos. Seguir padrões do nicho do mercado, auditoria, gestão. 
Mitigação - resolução de problemas. Caminha junto com segurança. 

A auditoria baseada em nuvem ajuda a sinalizar qualquer recursos que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação. 

Dependendo do seu modelo operacional, patches de software e atualização também podem ser aplicacados automaticamente, o que ajuda na governança e na segurança.

Apólice - serve para definir padrões de gestão na nuvem. Restringir a região onde não quer tenha acessos. Relatórios. Governo, Mercados e Requisitos Mercadológicos, Orgãos Governamentais.

Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.

**Gerenciabilidade** - os programas e recursos que utiliza já são demandas de serviços para nuvem. Tem o resultado de facilitar o gerenciamento para os usuários (empresa, recursos, Usa coisas da Microsoft).

Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem que você aprenderá nesta série e ambos trazem excelentes benefícios.
Powershell, Terraform(ferramenta a parte), Portal

O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Por exemplo:
Escalar automaticamente a implantação de recursos com base na necessidade. 
1 máquina ok, um ambiente melhor automatizar para evitar demora e falhas humanas. 
Não pular etapas senão for desenvolvedor não ir direto para código, primeiro portal e depois codificar. Melhor curva de aprendizado. Automatizar ARM, bicep, arquivo json. 

Criação através do Portal, Interface de linhas de comando, usando (APIs) e Power Shell.

Nem só de portal viverá o profissional de cloud.

**Revisão**
Benefícios da alta disponibilidade e da escalabilidade na nuvem
Benefícios da confiabilidade e da previsibilidade na nuvem
Benefícios da segurança e da governnça na nuvem 
Benefícios da capacidade de gerenciamento na nuvem.

**Links Úteis para Estudar**
https://learn.microsoft.com/training/modules/describe-benefits-use-cloud-services/2-high-availability-scalability-cloud 
https://learn.microsoft.com/training/modules/describe-benefits-use-cloud-services/3-reliability-predictability-cloud 
https://learn.microsoft.com/training/modules/describe-benefits-use-cloud-services/4-security-governance-cloud 
https://learn.microsoft.com/training/modules/describe-benefits-use-cloud-services/5-manageability-cloud 
![image](https://github.com/user-attachments/assets/6aa52de8-3ea1-4baa-8044-dcd2cbe8fc92)

**Lição 3 - Criando Máquinas Virtuais na Azure**

![image](https://github.com/user-attachments/assets/0e193211-6528-462c-b6c8-49c66052826f)

Ter um SLA de 99% nos da um tempo de inatividade por semana de até 1.68 hora, pode pensar que não será muito bom. Pode ocorrer, não quer dizer que vai acontecer. Talvez o de 99,9% seja melhor para para atender o serviço. 

Se faz a criação no Azure de um recurso nativo que já obedece SLA e ele fica indisponível além deste tempo a Microsoft precisa te ressarcir. Ex: A Entra Id que é a plataforma que gerencia os usuários tem um SLA.

Os serviços já possuem 1 SLA definido, caso crie uma máquina virtual o SLA é contado a partir da requisição.
Quando cria recurso que fica indisponível além deste tempo a Microsoft precisa te ressarcir. 
A Microsoft não vai precisar te ressarcir porque escolheu criar em determinado modelo.
Por isto é necessário saber o tempo de inatividade para cada SLA, destes 9.

Quando se recebe uma requisição para e é solicitado determinado tipo de serviço. A primeira coisa que precisa saber é o tempo de inatividade aceitável. 
Não tem 100 em nenhum local.
Sempre trabalha com a possibilidade do recurso ficar indisponível.
Sempre questionar o SLA que precisa entregar, pois, com base na sua solicitação vou criar nesta arquitetura é preciso ter definido o SLA desejado para desenhar as estruturas, comunicações, onde fica cada coisa.
Teste pode ser 99%, menos recursos.
99,99% saber os requisitos necessários.
- 9 mais tempo indisponível vai ter, +9 menos tempo indiponível vai ter

Ao clicar em um recurso tem um i ao lado das opções para esclarecimento.
Também há o docs para saber mais.
Replicando datacenters em regiões - menos tempo de indisponibilidade - escrevendo e copiando para regiões, custo.
Sempre entender o propósito real da criação do recurso, teste, produção, ter orçamento pre-definido.
A nuvem entrega isto, que tem os acordos de nível de serviço e dependendo da forma como crio minhas aplicações isto vai estar sendo disponibilizado. 
O profissional para atender uma demanda deve questionar,  sempre deve ter algo a ser melhorado e quem solicita nem sempre sabe dessas opções. Não ser somente o robô que fecha ticket. 











