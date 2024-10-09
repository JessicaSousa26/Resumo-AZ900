# Resumo-AZ900
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab Az-900 na DIO

**Módulo 1**
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
Quanto - 9 mais tempo indisponível vai ter, +9 menos tempo indiponível vai ter

Ao clicar em um recurso tem um i ao lado das opções para esclarecimento.
Também há o docs para saber mais.
Replicando datacenters em regiões - menos tempo de indisponibilidade - escrevendo e copiando para regiões, custo.
Sempre entender o propósito real da criação do recurso, teste, produção, ter orçamento pre-definido.
A nuvem entrega isto, que tem os acordos de nível de serviço e dependendo da forma como crio minhas aplicações isto vai estar sendo disponibilizado. 
O profissional para atender uma demanda deve questionar,  sempre deve ter algo a ser melhorado e quem solicita nem sempre sabe dessas opções. Não ser somente o robô que fecha ticket. 

**Lição 4 - Tipos de Serviço de Nuvem**

IaaS, PaaS, SaaS - Este conceito é geral de nuvem. Pode mudar os nomes e recursos de cada provider.

**IaaS (Infraestrutura Como Serviço)** 

![image](https://github.com/user-attachments/assets/a648fbae-4f58-46cb-916c-e39994162187)

- serviços ou recursos onde tem mais acesso, envolvimento com configuração, monitoramento e backup se está funcionando ou não em contrapartida tem muito mais acesso ao recurso final. Ex: servidores e armazenamento, firewalls/segurança de rede, planta física/edifício do datacenter, backup.

Ex: Cria a máquina com diversas configurações como assinatura, nome, backup, modelo de acesso, redes e depois que a máquina está ligada tem que ficar ligado nas atualizações, monitoramento, tem que verificar com frequência. As coisas não se resolvem sozinhas. Tem mais acesso no contexto de personalização do recurso, mais liberdade para trabalhar.

- Crie uma infraestrutura de TI de pagamento conforme o uso alugando servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais de um provedor de nuvem.

- Criar na nuvem apenas não vai se preocupar com o gerenciamento físico, mas, as configurações são de responsabilidade da empresa.

**Paas(Plataforma Como Serviço)**

![image](https://github.com/user-attachments/assets/a204cbcd-5d4c-4ede-95c1-ea2df1feaa2b)

- Envolve sistemas operacionais, ferramentas de desenvolvedores, base de dados.
- Banco de Dados precisa de servidor performático, melhor tempo de resposta.
Instalar e configurar o banco na nuvem e desenvolvedores acessar (Iaas)
- A máquina não quero me envolver quero o banco solito, assim, sobre a hierarquia. Preocupado com a aplicação e vida que segue (Paas)

- Fornece um ambiente para a criação, o teste e a implantação de aplicativos de software, sem focar no gerenciamento da infraestrutura subjacente.
![image](https://github.com/user-attachments/assets/d58e8c52-a253-4192-9ed6-a32bed22e913)

Se desprende da visão do sistema operacional, não é mais minha responsabilidade. Já fiz minha parte que é configuração. 1º acesso no sistema, 2º subiu nível da aplicação.

**SaaS(Software Como Serviço)**

![image](https://github.com/user-attachments/assets/d313d88f-7108-4098-8a2d-e701e3585d8e)

Aplicativos e Apps instalados - Teams, Office 365
- Teams é um das ferramentas que está disponível no 365 - quando realiza a configuração o que determina é a licença. Ex: 3 modelos de licnça de office 365, se tiver licença somente para o modelo A,  eu logo, crio a conta da organização, importo as contas dos meus colaboradores, crio meus grupos, encaminhamento e faço as regras. Tem acesso a menos botões, pois, está pagando mais barato. Ter acesso a rastreabilidade de e-mails, bloquear usuário, coisas mais a fundo é outra licença. Coisas completas é outra licença, o administrador faz o login no sistema e tem acesso a um painel completasso. O que determina quem ve o que é a tipo da licença, conforme faz o login personalizo para a organização. Subiu mais um nível no degrau se comparado a plataforma como serviço.
- A aplicação já existe, já está pronta e já sabe o que entrega e o que vai determinar o que e como estou vendo é o modelo de licenciamento adquirido. 
- Os usuários se conectam e usam aplicativos com base em nuvem pela Internet: por exemplo, Microsoft Office 365, email e calendários.
_ Neste caso não importa o servidor, memória, espera que esteja funcionando bem para utilizar. Não é sua responsabilidade.Sua responsabilidade é fazer as configurações para os usuários. Sobe mais 1 nível, deixa de ser a configuração exaustiva, nível do Sistema Operacional e chega mais em outro nível onde os anteriores não são minha responsabilidade.

Quanto mais utilizamos aplicações que são de Infraestrutura como serviço, mais isso vai nos demandar atividades, time vai trabalhar mais. Trabalhou para entregar e depois precisa monitorar, pois, muito mais coisas são responsabilidade em relação aos outros. Quando muda para plataforma como serviço isto já diminui bastante e o software como serviço nem se fala, com isto pode identificar melhor o modelo de adoção.

**Modelo de Responsabilidade Compartilhada**

![image](https://github.com/user-attachments/assets/ede375ba-a32b-4842-bbab-1d19509fcf81)

Mentalizar a questão da responsabilidade
Fisico (No local) - toda a responsabilidade é sua (estragou, não passou cabo, sem refrigerador) não terceiriza
IaaS - azul claro responsabilidade da Microsoft (Datacenter físico, Rede física, Hosts Físicos) - tirando o que é físico o restante é responsabilidade do cliente que vai precisar configurar.

PaaS - O sistema operacional é responsabilidade da Microsoft.
Pode optar criar um banco de dados e fazer configurações, mas, não vai ter acesso a uma máquina e configurar o SO. 
Controle compartilhado - Controles de rede (vnet, subnet, exposto na nuvem, balanceador de carga), aplicativos (libera a aplicação e vai configurar e alimentar com os dados) e Infraestrutura de identidade e diretório (oferece a gestão e preenche as lacunas). 

SaaS - a partir daí contas e identidades, dispositivos (móveis e PCs) e Informações e dados são de responsabilidade do cliente. Consegue personalizar. Melhor olhar de cima para baixo para saber quem está excluindo. É o contrário do Iaas 3 responsabilidades empresa e Iaas 3 responsabilidades Microsoft.

Conforme o nível de gestão vai estar ocupando a mente dos colaboradores se cria 2 mil máquinas virtuais tem que se preocupar com atualização, backup, patchs, problemas em relação a outras redes, como está chegando o encaminhamento de serviço, aplicações e tudo. Se olha para as contas da empresa e faz classificação, encaminhamento, grupos e etc, já está tudo pronto e precisa somente personalizar. O trabalho que vai ser demandado de um modelo para outro é bem diferente. Ter mais gestão deixa mais caro, por exemplo ter uma Iaas ela depende do sistema operacional e tudo que vem em decorrencia dele e se torna mais caro. São muitos detalhes para analisar.

**Comparação do serviço de nuvem**

![image](https://github.com/user-attachments/assets/c054f6f7-11ad-4148-97de-ae8f901cf3ae)

**IaaS**
- O serviço de nuvem mais flexível. (maiores poderes, configura, gerencia e personaliza o hardware para suas máquinas)
- Você configura e gerencia o hardware para seu aplicativo.

**PaaS**
- Focado no desenvolvimento de aplicativos. (Sistema Operacional e outros/ Responsabilidade de Microsoft, o que sobra é responsabilidade da empresa).
- O gerenciamento de plataforma é realizado pelo provedor de nuvem.

**SaaS**
-Modelo de preço de pagamento conforme o uso.(pagamento conforme o uso, licenciamento, 365,assinatura, menor controle menos acessos e opções e gestão do que importa).
- Os usuários pagam pelo software que utilizam em um modelo de assinatura.

Quando vai criar um novo recurso não aparece essas plataformas e deve consultar a documentação.

Para a prova não esquecer o nível de gestão (Alto, médio e baixo), contexto para analisar as perguntas já da para entender.

**Módulo 2 - Arquitetura e serviços do Azure**

**Lição 1 - Componentes de arquitetura do Azure**

**Contas do Azure**
Conta do Azure
Conta gratuita do Azure
Conta de estudante gratuita do Azure
Área restrita do Microsoft Learn

**Regiões**

O Azure oferece mais regiões globais do que qualquer outro provedor de nuvem, com mais de 60 regiões representando mais de 140 países.
As regiões são compostas de um ou mais datacenters muito próximos.
Eles fornecem flexibilidade e escala para reduzir a latência do cliente.
As regiões preservam a residência dos dados com uma oferta abrangente de conformidade.

**Zonas de disponibilidade**
Fornece proteção contra tempo de inatividade devido a falha do datacenter.
Separe fisicamente os datacenters dentro da mesma região.
Cada datacenter é equipado com alimentação, resfriamento e rede independentes.
Conectadas por meio de redes privadas de fibra óptica.

**Pares de Regiões**
No mínimo 300 milhas de separação entre pares de regiões.
Replicação automática para alguns serviços.
Recuperação de região priorizada em caso de interrupção.
As atualizações são distribuídas sequencialmente para minimizar o tempo de inatividade.
Link da Web: https://aka.ms/PairedRegions-ptb 

![image](https://github.com/user-attachments/assets/7bcbc223-bb2c-4de7-a57f-c732fa4070cd)

**Regiões soberanas do Azure**

**Serviços Governamentais dos EUA**
Atende às necessidades de segurança e conformidade das agências federais, governos estaduais e locais dos EUA e seus provedores de soluções.

**Azure Governamental**:
Instância separada do Azure.
Fisicamente isolada de implantações que não sejam do governo dos EUA.
Acessível somente a pessoal verificado e autorizado.

**Recursos do Azure**
Os recursos do Azure são componentes como armazenamento, máquinas virtuais e redes que estão disponíveis para criar soluções de nuvem.

![image](https://github.com/user-attachments/assets/884070ac-0ea2-4df6-bcbb-58c7f2f11301)

**Grupos e Recursos**
![image](https://github.com/user-attachments/assets/7041abd9-64bb-4193-8d3a-8f8eee7a272b)

Um grupo de recursos é um contêiner que você usa para gerenciar e agregar recursos em uma única unidade. 
Os recursos podem existir em apenas um grupo de recursos.
Os recursos podem existir em diferentes regiões. 
Os recursos podem ser movidos para diferentes grupos de recursos. 
Os aplicativos podem utilizar vários grupos de recursos.

Assinaturas do Azure
![image](https://github.com/user-attachments/assets/5a8d49f4-5b3d-4c28-9c07-125ac32b7c67)

Uma assinatura do Azure fornece a você acesso autenticado e autorizado às contas do Azure.
Limite de cobrança: gere relatórios de cobrança e faturas separados para cada assinatura.
Limite do controle de acesso: gerenciar e controlar o acesso aos recursos que os usuários podem provisionar com assinaturas específicas.

**Grupos de gerenciamento**
![image](https://github.com/user-attachments/assets/75b59414-0bf8-4502-8240-2bf51e1209b4)

Os grupos de gerenciamento podem incluir várias assinaturas do Azure.
As assinaturas herdam as condições aplicadas ao grupo de gerenciamento.

**Links para Estudar**

https://learn.microsoft.com/training/modules/describe-core-architectural-components-of-azure/3-get-started-azure-accounts 
https://learn.microsoft.com/training/modules/describe-core-architectural-components-of-azure/1-introduction  
https://learn.microsoft.com/training/modules/describe-core-architectural-components-of-azure/5-describe-azure-physical-infrastructure  
https://learn.microsoft.com/training/modules/describe-core-architectural-components-of-azure/5-describe-azure-physical-infrastructure   









