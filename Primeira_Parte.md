# AZ 900 - Resumo dos Estudos  
<img src="https://github.com/tbarcelar/Resumo-AZ900/blob/main/cloud.jpg" width="1200" height="250">
 
#  Como funciona Azure

**Segue alguns beneficios do uso do Azure**
> * Alta disponibilidade 
> * Escalabilidade
> * Elasticidade 
> * Distribuição geográfica 
> * Recuperação de desastre 

 ## Existe 3 modelos de serviços que são:

**IaaS (Infraestrutura como um serviço)**  
É o mais próximo de gerenciar servidores físicos, porém sem a preocupação de manter o hardware atualizado. Uma vantagem desse modelo de serviço em nuvem é a implantação rápida de novos dispositivos de computação; configurar uma nova máquina virtual é consideravelmente mais rápido do que adquirir, instalar e configurar um servidor físico.  

**PaaS (Platform-as-a-Service)**  
O provedor de nuvem gerencia as máquinas virtuais e recursos de rede, e o locatário da nuvem implanta seus aplicativos no ambiente de hospedagem gerenciada. 

**SaaS (Software-as-a-Service)**  
O provedor de nuvem gerencia as máquinas virtuais e recursos de rede, todos os aspectos do ambiente do aplicativo -  armazenamento de dados, o locatário da nuvem só precisa fornecer seus dados ao aplicativo 

## Existem três modelos de de rede em nuvem: 

**Nuvem pública**
Os recursos de nuvem (como servidores e armazenamento) pertencem a um provedor de serviço de nuvem terceirizado, são operados por ele e entregues pela Internet. O Microsoft Azure é um exemplo de nuvem pública entrega todo o hardware, software e outras infraestruturas de suporte. As implantações de nuvem pública geralmente são usadas para fornecer email baseado na Web, aplicativos de escritório online, armazenamento e ambientes de desenvolvimento e teste.

**Nuvem privada**
consiste em recursos de computação em nuvem usados exclusivamente por uma única empresa ou organização. A nuvem privada pode estar localizada fisicamente no datacenter local da sua organização ou pode ser hospedada por um provedor de serviços terceirizado. Mas em uma nuvem privada, os serviços e a infraestrutura são sempre mantidos na rede privada e o hardware e o software são dedicados unicamente à sua organização.
Dessa forma, com a nuvem privada é mais fácil para que a organização personalize seus recursos a fim de atender a requisitos de TI específicos. As nuvens privadas geralmente são usadas por órgãos governamentais, instituições financeiras e outras organizações de grande porte com operações críticas para os negócios, que buscam melhorar o controle sobre seu ambiente.


**Nuvem híbrida**
Uma nuvem híbrida é um ambiente de computação que combina uma nuvem pública e uma nuvem privada, permitindo que dados e aplicativos sejam compartilhados entre elas.

***

## Como acessar o Azure   
Através do portal do Azure, com interface gráfica facilitando a construção, gerenciamento e monitoraramento de  tudo, desde simples aplicativos da web até complexas implementações em nuvem.  O portal do Azure é atualizado continuamente e não requer tempo de inatividade para atividades de manutenção.  
**Dentro do portal tem Azure Marketplace** 
Que permite que os clientes - principalmente profissionais de TI e desenvolvedores de nuvem - encontrem, experimentem, comprem e provisionem aplicativos e serviços de centenas de provedores de serviços líderes, todos certificados para execução no Azure.

 ## Como criar uma conta do Azure  
1 - Através da Microsoft, no Site do Azure
2 - meio de um representante da Microsoft 
3 - Os parceiros do Cloud Solution Provider 

Exite conta gratuita do Azure, inclui acesso gratuito a produtos populares do Azure por 12 meses, um crédito para gastar pelos primeiros 30 dias e acesso a mais de 25 produtos que são sempre gratuitos. A conta gratuita do Azure é uma excelente maneira para novos usuários começarem e explorarem. Para se inscrever, precisa de um número de telefone, cartão de crédito e uma conta Microsoft ou GitHub. As informações do cartão de crédito são usadas apenas para verificação de identidade; não será cobrado por nenhum serviço até fazer o upgrade para uma assinatura paga.

*** 

## Despesas  

Despesas de capital (CapEx)
- Gasto inicial  em infraestrutura física, custo inicial do CapEx tem um valor que diminui com o tempo.

Despesa operacional (OpEx)
- Gastando dinheiro em serviços ou produtos, sendo cobrado por eles . Deduzir essa despesa no mesmo ano em que gasta. Não há custo inicial, pois  paga por um serviço ou produto conforme o usa.

***

## Recursos VS Assinatura

**Recursos:**
São instâncias de serviços que cria, como máquinas virtuais, armazenamento ou bancos de dados SQL.

**Grupos de recursos:**
Atuam como um contêiner lógico no qual os recursos do Azure, como aplicativos da Web, bancos de dados e contas de armazenamento, são implantados e gerenciados.

**Assinaturas:** 
Agrupa contas de usuário e os recursos que foram criados por essas contas de usuário. Para cada assinatura, existem limites ou cotas para a quantidade de recursos que  pode criar e usar. As organizações podem usar assinaturas para gerenciar custos e os recursos criados por usuários, equipes ou projetos.
Uma conta pode ter uma assinatura ou várias assinaturas que têm diferentes modelos de faturamento e às quais  aplica diferentes políticas de gerenciamento de acesso. 

## Assinatura e Faturamento

**Limite de faturamento**
Este tipo de assinatura determina como uma conta do Azure é cobrada pelo uso do Azure.  pode criar várias assinaturas para diferentes tipos de requisitos de cobrança, e o Azure irá gerar relatórios de cobrança e faturas separados para cada assinatura para que  possa organizar e gerenciar os custos.

**Limite de controle de acesso**
 O Azure aplicará políticas de gerenciamento de acesso no nível de assinatura e  pode criar assinaturas separadas para refletir diferentes estruturas organizacionais. Um exemplo é que, em uma empresa, você tem departamentos diferentes aos quais aplica políticas de assinatura distintas do Azure. Isso permite que  gerencie e controle o acesso aos recursos que os usuários fornecem com assinaturas específicas.  
 Ambientes: Ao gerenciar ambientes separados para desenvolvimento e teste, segurança ou isolar dados por motivos de conformidade. Isso é particularmente útil porque o controle de acesso ao recurso ocorre no nível da assinatura.  Todas as assinaturas em um grupo de gerenciamento herdam automaticamente as condições aplicadas ao grupo de gerenciamento. 
 Os grupos de gerenciamento fornecem gerenciamento de nível empresarial em grande escala, não importa o tipo de assinatura que possa ter. Todas as assinaturas em um único grupo de gerenciamento devem confiar no mesmo locatário do Azure Active Directory.

 
## Link
  - Repository:https://docs.microsoft.com/pt-br/learn/certifications/exams/az-900
  - Dicionário: https://github.com/tbarcelar/Resumo-AZ900/blob/main/dicionario_dos_servicos.docx
  - Próxima página: https://github.com/tbarcelar/Resumo-AZ900/blob/main/Segunda_Parte.md
  - Teste do resumo: https://docs.google.com/forms/d/e/1FAIpQLScCUm4kNuMvukI3ByoZLd4Im0_3tPjliJto8xdjIC-BBDKyyg/viewform
    

 

