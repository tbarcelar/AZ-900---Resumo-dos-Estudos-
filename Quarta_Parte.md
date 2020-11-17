# AZ 900 - Resumo dos Estudos  
<img src="https://github.com/tbarcelar/Resumo-AZ900/blob/main/cloud.jpg" width="1200" height="250">



# Inteligência Artificial (IA) 

É  uma categoria de computação que se adapta e melhora sua capacidade de tomada de decisão ao longo do tempo com base em seus sucessos e fracassos. Existem duas abordagens básicas para IA.

**A primeira**
É empregar um sistema de “aprendizado profundo” modelado na rede neural da mente humana, permitindo-lhe descobrir, aprender e crescer por meio da experiência.

**A segunda**
“aprendizado de máquina”, que é uma técnica de ciência de dados que usa dados existentes para treinar e testar um modelo e, em seguida, aplicar esse modelo a novos dados para prever comportamentos, resultados e tendências futuros.


**existem três ofertas principais da Microsoft**
**Azure Machine Learning**
Plataforma para fazer previsões. Consiste em ferramentas e serviços que permitem que se conecte aos dados para treinar e testar modelos para encontrar um que preveja com mais precisão um resultado futuro. Depois de executar experimentos para testar o modelo, pode implantar o modelo e usá-lo em tempo real por meio de um endpoint de API da web.


**Serviços Cognitivos Azure**
fornece modelos de aprendizado de máquina predefinidos que permitem que os aplicativos vejam, ouçam, falem, entendam e até mesmo comecem a raciocinar. Use os Serviços Cognitivos do Azure para resolver problemas gerais, como análise de texto para sentimento emocional ou análise de imagens para reconhecer objetos ou rostos. não precisa de conhecimento especial de machine learning ou ciência de dados para usar esses serviços. Os desenvolvedores acessam os Serviços Cognitivos do Azure por meio de APIs e podem incluir facilmente esses recursos em apenas algumas linhas de código.
- Língua serviços - Permita que seus aplicativos processem linguagem natural com scripts pré-construídos, avalie sentimentos e aprenda a reconhecer o que os usuários desejam.
- Discursoserviços - Converta fala em texto e texto em fala de som natural. Traduza de um idioma para outro e habilite a verificação e o reconhecimento do locutor.
- Visão serviços - Adicione recursos de reconhecimento e identificação ao analisar fotos, vídeos e outros conteúdos visuais.

*o Azure Machine Learning exija que você traga seus próprios dados e treine modelos sobre esses dados, os Serviços Cognitivos do Azure, na maior parte, fornecem modelos pré-treinados para que possa trazer seus dados ativos para obter previsões.*

**Serviço de bot do Azure**
 é uma plataforma para a criação de agentes virtuais que entendem e respondem a perguntas como um ser humano. O Azure Bot Service é um pouco diferente do Azure Machine Learning e dos Azure Cognitive Services por ter um caso de uso específico: a saber, a criação de um agente virtual que pode se comunicar de forma inteligente com humanos. Nos bastidores, o bot que você cria usa outros serviços do Azure, como os Serviços Cognitivos do Azure, para entender o que suas contrapartes humanas estão pedindo.


*******em resumo*********

- construindo um agente virtual que faz interface com humanos por meio de linguagem natural? Use o Bot Service
- precisa de um serviço que possa compreender o conteúdo e o significado de imagens, vídeo, áudio ou traduzir texto para um idioma diferente? Serviços Cognitivos 
- Seu aplicativo irá prever resultados futuros com base em dados históricos privados? Machine Learning quando precisar analisar dados para prever resultados futuros. 
- precisa construir um modelo usando seus próprios dados ou realizar uma tarefa diferente das listadas acima? Machine Learning para obter o máximo de flexibilidade.

Cientistas de dados ou engenheiros de IA podem usar ferramentas com as quais estão familiarizados e os dados que você fornece para desenvolver modelos de aprendizado profundo e de aprendizado de máquina ajustados para seus requisitos específicos


# Monitoramento

**Consultor Azure**
avalia seus recursos do Azure e faz recomendações para ajudá-lo a melhorar a confiabilidade, a segurança e o desempenho, alcançar a excelência operacional e reduzir custos.
Quando no portal do Azure, o painel do Consultor exibe recomendações personalizadas para todas as assinaturas, pode usar filtros para aprimorar as recomendações para assinaturas, grupos de recursos ou serviços específicos. As recomendações são divididas em cinco categorias:
- Confiabilidade - Usado para garantir e melhorar a continuidade de seus aplicativos essenciais aos negócios.
- Segurança - Usado para detectar ameaças e vulnerabilidades que podem levar a violações de segurança.
- atuação - Usado para melhorar a velocidade de seus aplicativos.
- Custo - Usado para otimizar e reduzir seus gastos gerais com o Azure.
- Excelência operacional - Usado para ajudá-lo a alcançar eficiência de processo e fluxo de trabalho, gerenciamento de recursos e práticas recomendadas de implantação.

**O Advisor** foi projetado para ajudá-lo a economizar tempo na otimização da nuvem. O serviço de recomendação inclui ações sugeridas que pode realizar imediatamente, adiar ou dispensar. é uma plataforma para coletar, analisar, visualizar e, potencialmente, realizar ações com base na métrica e dados de registro em log de todo o ambiente Azure e local.


**Azure Application Insights**
serviço para enviar informações de telemetria do código-fonte do aplicativo para o Azure,  permite que os desenvolvedores de aplicativos aproveitem a poderosa plataforma de análise de dados no Azure Monitor para fornecer insights profundos sobre as operações de um aplicativo e diagnosticar erros sem esperar que um usuário os relate.

**Azure Service Health**
visão personalizada da integridade dos serviços, regiões e recursos do Azure nos quais você confia. O site status.azure.com não fornece a imagem completa porque mostra apenas os principais problemas que afetam amplamente os clientes do Azure.


**IoT Hub**
O Hub IoT suporta comunicações do dispositivo para a nuvem e da nuvem para o dispositivo. Ele também oferece suporte a vários padrões de mensagens, como telemetria de dispositivo para nuvem, upload de arquivo de dispositivos e métodos de solicitação de resposta para controlar seus dispositivos da nuvem. Depois que o Hub IoT recebe mensagens de um dispositivo, ele pode rotear essa mensagem para outros serviços do Azure.
De uma perspectiva de nuvem para dispositivo, o IoT Hub permite "comando e controle", em outras palavras, controle remoto manual ou automatizado de dispositivos conectados para que possa instruir o dispositivo a abrir válvulas, definir temperaturas-alvo, reiniciar dispositivos presos, e assim por diante.
O monitoramento do IoT Hub ajuda a manter a integridade de sua solução rastreando eventos como criação de dispositivo, falhas de dispositivo e conexões de dispositivo.

**Azure IoT Central**
fornece um painel que permite às empresas gerenciar dispositivos IoT individualmente e em conjunto, exibir relatórios e configurar notificações de erro por meio de uma GUI. A IoT Central do Azure é uma IoT global totalmente gerenciada SaaS (software como serviço) que a torna fácil de conectar, monitorar e gerenciar seus ativos de IoT em grande escala. 
baseia-se no Hub IoT adicionando um painel que permite conectar, monitorar e gerenciar dispositivos IoT. A interface visual do usuário (IU) facilita a conexão rápida de novos dispositivos e observe enquanto eles começam a enviar mensagens de telemetria ou de erro. pode observar o desempenho geral em todos os dispositivos em conjunto e configurar alertas que enviam notificações quando um dispositivo específico precisa de manutenção. Finalmente, pode enviar atualizações de hardware para o dispositivo.

 **Azure Sphere**
fornece uma solução completa para cenários em que a segurança é crítica. 
cria uma solução de IoT altamente segura de ponta a ponta para clientes que abrange tudo, desde o hardware e sistema operacional no dispositivo até o método seguro de envio de mensagens do dispositivo para o hub de mensagens. Possui recursos de comunicação e segurança integrados para dispositivos conectados à Internet
Depois que o sistema do Azure Sphere validou a autenticidade do dispositivo e o autenticou, o dispositivo pode interagir com outros serviços do Azure IoT, enviando informações de telemetria e de erro.

**Azure Sentinel**
 é o SIEM baseado em nuvem da Microsoft. Um SIEM agrega dados de segurança de muitas fontes diferentes para fornecer recursos adicionais para detecção de ameaças e resposta a ameaças.

**Com a Central de Segurança do Azure**, 
 pode definir uma lista de aplicativos permitidos para garantir que apenas os aplicativos permitidos possam ser executados. A Central de Segurança do Azure também pode detectar e bloquear a instalação de malware em  VMs.

**O Azure Key Vault**
 permite que  armazene seus segredos em um único local central. O Key Vault também torna mais fácil registrar e renovar certificados de autoridades de certificação públicas (CAs).


***
 ## Link
  - Repository:https://docs.microsoft.com/pt-br/learn/certifications/exams/az-900
  - Dicionário: https://github.com/tbarcelar/Resumo-AZ900/blob/main/dicionario_dos_servicos.docx
  -  Teste do Resumo https://docs.google.com/forms/d/1ONzFO8K_HfiKf0wO1xFF8Rl5NvwIWqIEazTLmoQN9cs/viewform?e