# AZ 900 - Resumo dos Estudos  
<img src="https://github.com/tbarcelar/Resumo-AZ900/blob/main/cloud.jpg" width="1200" height="250">
 
# Os tipos de banco de Dados que é possivel usar no Azure

**Azure Cosmos DB**
É o serviço de banco de dados de vários modelos distribuído globalmente da Microsoft. Com o clique de um botão, o Cosmos DB permite que dimensione de forma elástica e independente a taxa de transferência e o armazenamento em qualquer número de regiões do Azure em todo o mundo. Oferece suporte a dados sem esquema, o que permite criar aplicativos altamente responsivos e Always On para oferecer suporte a dados em constante mudança.  É uma ótima escolha em uma variedade de cenários porque é flexível. No nível mais baixo, o Azure Cosmos DB armazena dados no formato atom-record-sequence (ARS). Os dados são então abstraídos e projetados como uma API. Suas opções incluem SQL, MongoDB, Cassandra, Tables e Gremlin. Esse nível de flexibilidade significa que, conforme você migra os bancos de dados da sua empresa para o Azure Cosmos DB, seus desenvolvedores podem ficar com a API onde se sentirem mais confortáveis.

**Banco de Dados SQL do Azure** 
É um banco de dados relacional baseado na versão estável mais recente do mecanismo de banco de dados do Microsoft SQL Server é um banco de dados de alto desempenho, confiável, totalmente gerenciado e seguro. Pode usá-lo para construir aplicativos e sites baseados em dados na linguagem de programação de sua escolha, sem a necessidade de gerenciar a infraestrutura. É um mecanismo de banco de dados de plataforma como serviço (PaaS) totalmente gerenciado que lida com a maioria das funções de gerenciamento de banco de dados, como atualização, patch, backups e monitoramento sem envolvimento do usuário.


**Banco de Dados do Azure para MySQL**
É um serviço de banco de dados relacional na nuvem da Microsoft, o contrato de nível de serviço (SLA) de disponibilidade de 99,99% do Azure, desenvolvido por uma rede global de datacenters gerenciados pela Microsoft, ajuda a manter seu aplicativo funcionando 24 horas por dia, 7 dias por semana, pode usar a restauração point-in-time para recuperar um servidor para um estado anterior, de até 35 dias.  
Esses recursos quase não exigem administração e todos são fornecidos sem custo adicional. Eles permitem que se concentre no desenvolvimento rápido de aplicativos e acelere seu tempo de colocação no mercado, em vez de alocar tempo e recursos preciosos para gerenciar máquinas virtuais e infraestrutura. Além disso, pode migrar bancos de dados MySQL existentes com tempo de inatividade mínimo usando o Serviço de Migração de Banco de Dados do Azure. Depois de concluir a migração, pode continuar a desenvolver aplicativo com as ferramentas e a plataforma de código aberto de sua escolha para entregar com a velocidade e eficiência que seus negócios exigem, tudo sem ter que aprender novas habilidades.
 

**PostgreSQL**
 É  um serviço de banco de dados relacional na nuvem da Microsoft. O software do servidor é baseado na versão da comunidade do mecanismo de banco de dados PostgreSQL de código aberto. Sua familiaridade com ferramentas e experiência com PostgreSQL é aplicável ao usar o Banco de Dados Azure para PostgreSQL, oferece os seguintes benefícios :  *Alta disponibilidade*   *Preços simples e flexíveis*   *Aumente ou diminua conforme necessário em segundos*   *Backups automáticos ajustáveis ​​e restauração pontual por até 35 dias* 
 Segurança e conformidade de nível empresarial para proteger dados confidenciais em repouso e em movimento que cobre a criptografia de dados em disco e criptografia SSL entre a comunicação do cliente e do servidor.

## Big data e análises
 Tecnologias de cluster de código aberto foram desenvolvidas, ao longo do tempo, para tentar lidar com grandes conjuntos de dados. O Microsoft Azure oferece suporte a uma ampla variedade de tecnologias e serviços para fornecer soluções analíticas e de big data. Alguns dos tipos de big data e serviço analítico mais comuns no Azure são Azure Synapse Analytics, HDInsight, Databricks e Data Lake Analytics.

**Azure Synapse Analytics** (anteriormente Azure SQL Data Warehouse) 
 O Azure Synapse oferece a liberdade de consultar dados em seus termos, usando recursos sem servidor ou provisionados em escala. O Azure Synapse reúne esses dois mundos com uma experiência unificada para ingerir, preparar, gerenciar e fornecer dados para necessidades imediatas de BI e aprendizado de máquina. 

 **Azure HDInsight** 
  É  um serviço analítico de código aberto totalmente gerenciado para empresas. É um serviço em nuvem que torna mais fácil, rápido e econômico processar grandes quantidades de dados.  crie tipos de cluster, como Apache Spark, Apache Hadoop, Apache Kafka, Apache HBase, Tempestade Apache, Serviços de aprendizado de máquina. O HDInsight também oferece suporte a uma ampla variedade de cenários, como extração, transformação e carregamento (ETL); armazenamento de dados; aprendizado de máquina; e IoT.

**Azure Databricks** 
ajuda a desbloquear insights de todos os seus dados e construir soluções de inteligência artificial (IA). Pode configurar ambiente Apache Spark ™ em minutos, depois escalonar automaticamente e colaborar em projetos compartilhados em um espaço de trabalho interativo. Azure Databricks oferece suporte a Python, Scala, R, Java e SQL, bem como bibliotecas e estruturas de ciência de dados, incluindo TensorFlow, PyTorch e scikit-learn.

**Azure Data Lake Analytics**
É  um serviço de trabalho de análise sob demanda que simplifica o big data. Em vez de implantar, configurar e ajustar o hardware, escreve consultas para transformar seus dados e extrair percepções valiosas. O serviço de análise pode lidar com trabalhos de qualquer escala instantaneamente, definindo o dial para a quantidade de energia de que você precisa, só paga pelo seu trabalho quando ele está em execução, o que o torna mais econômico.

***

# Outros serviços do Azure

 
**As máquinas virtuais** (VMs) são emulações de software de computadores físicos. Eles incluem um processador virtual, memória, armazenamento e recursos de rede. As VMs hospedam um sistema operacional e você pode instalar e executar software como um computador físico. Ao usar um cliente de desktop remoto, você pode usar e controlar a máquina virtual como se estivesse sentado em frente a ela. 
  Fornece IaaS e pode ser usado de várias maneiras diferentes. Quando precisa de controle total sobre um sistema operacional e ambiente, as VMs do Azure são a escolha ideal. Assim como um computador físico, que pode personalizar todo o software em execução na VM. Essa capacidade é útil quando está executando um software personalizado ou configurações de hospedagem personalizadas.  

**Tem Conjuntos de escala de máquina virtual**
 São um recurso de computação do Azure que pode usar para implantar e gerenciar um conjunto de VMs idênticas. Com todas as VMs configuradas da mesma forma, os conjuntos de escala de máquina virtual são projetados para oferecer suporte à escala automática real; nenhum pré-provisionamento de VMs é necessário; e, como tal, torna mais fácil construir serviços em grande escala visando grande computação, big data e cargas de trabalho em contêiner. Portanto, conforme a demanda aumenta, mais instâncias de máquina virtual podem ser adicionadas e, conforme a demanda diminui, instâncias de máquinas virtuais podem ser removidas. O processo pode ser manual, automatizado ou uma combinação de ambos.


**Serviços de aplicativos**
 Pode construir, implantar e escalar rapidamente aplicativos da web, móveis e API de nível corporativo executados em qualquer plataforma, pode atender a requisitos rigorosos de desempenho, escalabilidade, segurança e conformidade ao usar uma plataforma totalmente gerenciada para realizar a manutenção da infraestrutura. Os serviços de aplicativos são uma oferta de plataforma como serviço (PaaS).

**Funções**
 Azure Functions são ideais quando está preocupado apenas com o código que executa serviço e não com a plataforma ou infraestrutura subjacente. Eles são comumente usados quando você precisa realizar um trabalho em resposta a um evento (geralmente por meio de uma solicitação REST), cronômetro ou mensagem de outro serviço do Azure e quando esse trabalho pode ser concluído rapidamente, em segundos ou menos.

**Recipientes e reguladores**
 Instâncias de contêiner do Azure e Serviço do Azure Governorate (AKS) são recursos de computação do Azure que pode usar para implantar e gerenciar contêineres, que são ambientes de aplicativos virtualizados leves que são projetados para serem rapidamente criados, dimensionados e interrompidos dinamicamente, pode executar várias instâncias de um aplicativo em contêiner em uma única máquina host.
 Embora as máquinas virtuais sejam uma excelente forma de reduzir custos em comparação com os investimentos necessários para hardware físico, elas ainda estão limitadas a um único sistema operacional por máquina virtual. Se você deseja executar várias instâncias de um aplicativo em uma única máquina host, os contêineres são uma excelente escolha.

 Os contêineres são um ambiente de virtualização e, assim como a execução de várias máquinas virtuais em um único host físico, pode executar vários contêineres em um único host físico ou virtual. No entanto, ao contrário das máquinas virtuais, não gerencia o sistema operacional de um contêiner. Enquanto as máquinas virtuais parecem ser uma instância de um sistema operacional ao qual você pode se conectar e gerenciar, os contêineres são leves e foram projetados para serem criados, dimensionados e interrompidos dinamicamente. Embora seja possível criar e implantar máquinas virtuais à medida que aumenta a demanda do aplicativo, os contêineres são projetados para permitir que responda às mudanças sob demanda e reinicie rapidamente em caso de falha ou interrupção do hardware. Um dos motores de contêiner mais populares é o Docker, que tem suporte do Microsoft Azure.Existem duas maneiras de gerenciar os contêineres baseados em Docker e Microsoft no Azure:Instâncias de contêiner do Azure e Serviço Azure Kubernetes.

**Instâncias de contêiner do Azure (ACI)**
 Instâncias de contêiner do Azure oferece a maneira mais rápida e simples de executar um contêiner no Azure sem ter que gerenciar nenhuma máquina virtual ou adotar qualquer serviço adicional. É uma oferta de PaaS que permite fazer upload de seus contêineres, que serão executados 

**Serviço do Azure Governorate (AKS)**
 A tarefa de automatizar, gerenciar e interagir com um grande número de contêineres é conhecida como orquestração. Serviço do Azure Governorate (AKS) é um serviço de orquestração completo para contêineres com arquiteturas distribuídas e grandes volumes de contêineres. Orquestração é a tarefa de automatizar e gerenciar um grande número de contêineres e como eles interagem.

*** 

## Tipos de serviços de aplicativos

O Serviço de Aplicativo do Azure lida com a maioria das decisões de infraestrutura, a implantação e o gerenciamento são integrados à plataforma, os pontos de extremidade podem ser protegidos, os sites podem ser escalados rapidamente para lidar com altas cargas de tráfego e a carga interna o balanceamento e o gerenciador de tráfego fornecem alta disponibilidade. 

**Aplicativos da web**
 O serviço de aplicativo inclui suporte completo para hospedar aplicativos da web usando ASP.NET, ASP.NET Core, Java, Ruby, Node.js, PHP ou Python. Você pode escolher Windows ou Linux como sistema operacional host.

**Aplicativos de API**
 Assim como hospedar um site, você pode construir APIs da Web baseadas em REST usando sua escolha de linguagem e estrutura. Você obtém suporte total do Swagger e a capacidade de empacotar e publicar sua API no Azure Marketplace. Os aplicativos produzidos podem ser consumidos de qualquer cliente baseado em HTTP (S).

**Empregos da web**
 WebJobs permite que você execute um programa (.exe, Java, PHP, Python ou Node.js) ou script (.cmd, .bat, PowerShell ou Bash) no mesmo contexto de um aplicativo da web, aplicativo de API ou dispositivo móvel aplicativo. Eles podem ser programados ou executados por um gatilho. WebJobs são frequentemente usados ​​para executar tarefas em segundo plano como parte da lógica de seu aplicativo.

**No lado do aplicativo móvel**
Há suporte de SDK para aplicativos nativos iOS e Android, Xamarin e React.


*** 

# O Azure tem duas implementações de computação sem servidor:

**Azure Functions**, que pode executar código em quase qualquer linguagem moderna.
É dimensionado automaticamente com base na demanda, portanto, são uma escolha sólida quando a demanda é variável. Usando uma abordagem baseada em VM, você incorreria em custos mesmo quando a VM estivesse ociosa. Com funções, o Azure executa seu código quando é disparado e desaloca recursos automaticamente quando a função é concluída. Neste modelo, você é cobrado apenas pelo tempo de CPU usado enquanto sua função é executada.


**Aplicativos Lógicos Azure**
 São projetados em um designer baseado na Web e podem executar a lógica acionada pelos serviços do Azure sem escrever nenhum código.
 Os Aplicativos Lógicos do Azure são semelhantes às Funções - ambos permitem que acione a lógica com base em um evento. Onde as funções executam código, os aplicativos lógicos são executados fluxos de trabalho projetado para automatizar cenários de negócios e construído a partir de blocos lógicos predefinidos. 
 Cria fluxos de trabalho do Aplicativo Lógico usando um designer visual no portal do Azure ou no Visual Studio. Os fluxos de trabalho são persistidos como um arquivo JSON com um esquema de fluxo de trabalho conhecido.

O Azure fornece mais de 200 conectores e blocos de processamento diferentes para interagir com diferentes serviços - incluindo os aplicativos empresariais mais populares, também pode criar conectores personalizados e etapas de fluxo de trabalho se o serviço com o qual precisa interagir não estiver coberto. Em seguida, usa o designer visual para vincular conectores e blocos, passando dados pelo fluxo de trabalho para fazer o processamento personalizado - geralmente sem escrever nenhum código.

**Resumo Funções vs. Aplicativos lógicos**

Funções e aplicativos lógicos podem criar orquestrações complexas, que são uma coleção de funções ou etapas que são executadas para realizar uma tarefa complexa.
Com o Azure Functions, você escreve código para concluir cada etapa.
Com os aplicativos lógicos, você usa uma GUI para definir as ações e como elas se relacionam entre si.

Pode misturar e combinar serviços ao construir uma orquestração, chamando funções de aplicativos lógicos e chamando aplicativos lógicos de funções. Aqui estão algumas diferenças comuns entre os dois.


*** 

# Fundamentos de armazenamento

**O armazenamento em disco** 
permite que os dados sejam armazenados e acessados ​​de forma persistente a partir de um disco rígido virtual conectado. Os discos podem ser gerenciados ou não gerenciados pelo Azure e, portanto, gerenciados e configurados pelo usuário. Cenários típicos para usar o armazenamento em disco são se deseja levantar e deslocar aplicativos que leem e gravam dados em discos permanentes ou se você estiver armazenando dados que não precisam ser acessados ​​de fora da máquina virtual à qual o disco está conectado.

**O armazenamento de Blob do Azure** 
é a solução de armazenamento de objeto da Microsoft para a nuvem é otimizado para armazenar grandes quantidades de dados não estruturados, como texto ou dados binários. 
O Armazenamento de Blob do Azure não é estruturado, o que significa que não há restrições aos tipos de dados que ele pode conter. Os blobs são altamente escalonáveis ​​e os aplicativos funcionam com os blobs da mesma maneira que funcionariam com arquivos em um disco, como leitura e gravação de dados. O Blob Storage pode gerenciar milhares de uploads simultâneos, grandes quantidades de dados de vídeo, arquivos de log em constante crescimento e pode ser acessado de qualquer lugar com uma conexão à Internet.

O armazenamento de Blob do Azure permite que transmita grandes arquivos de vídeo ou áudio diretamente para o navegador do usuário de qualquer lugar do mundo. O armazenamento de blob também é usado para armazenar dados para backup, recuperação de desastres e arquivamento. Ele tem a capacidade de armazenar até 8 TB de dados para máquinas virtuais. Blobs são armazenados em recipientes, que pode usar para organizar seus blobs de acordo com suas necessidades de negócios.


**Os níveis de acesso disponíveis incluem:**
- Camada de armazenamento quente: otimizado para armazenar dados que são acessados ​​com frequência. (Por exemplo: imagens para seu site.)
- Camada fria de armazenamento: otimizado para dados raramente acessados ​​e armazenados por pelo menos 30 dias. (Por exemplo: faturas para seus clientes.)
- Camada de armazenamento de arquivo: para dados raramente acessados ​​e armazenados por pelo menos 180 dias com requisitos de latência flexíveis. (Por exemplo: backups de longo prazo.)


*** 
# Link
  - Repository:https://docs.microsoft.com/pt-br/learn/certifications/exams/az-900
 -  Próxima página: O que é rede virtual do Azure
https://github.com/tbarcelar/Resumo-AZ900/blob/main/Terceira_Pagina.md