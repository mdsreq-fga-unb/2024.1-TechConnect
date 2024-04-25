# **Visão Geral do Produto**

## **Problema**

Uma empresa nacional especializada na entrega de soluções de software e hardware mantém um extenso cadastro de técnicos em seu banco de dados, os quais são encarregados de realizar reparos requisitados por seus clientes. Esses serviços frequentemente requerem prazos de execução curtos.

Ao abrir um chamado, a empresa precisa localizar um técnico em sua base de dados e estabelecer contato para averiguar sua disponibilidade para a execução do serviço. Atualmente, a empresa enfrenta dificuldades devido ao controle manual de análise e demanda de serviços. Todas as operações são conduzidas manualmente por meio de uma planilha Excel, o que cria ineficiências e prolonga o tempo necessário para o processo.

A comunicação com os técnicos é realizada por meio de chamadas telefônicas, que podem consumir tempo e atrasar a resolução das demandas dos clientes. A empresa precisa manter prazos de atendimento rigorosos para evitar danos à reputação e penalidades financeiras.

Além disso, a empresa enfrenta desafios significativos na organização da comunicação com os técnicos para verificar sua disponibilidade e compromisso com os serviços. A abordagem manual, que requer contatos individuais com cada técnico, resulta em consumo excessivo de tempo e recursos. 

Portanto, os desafios enfrentados pela empresa decorrem principalmente do controle manual de análise e demanda de serviços. Uma possível solução pode ser a implementação de uma ferramenta ou sistema que automatize a troca de informações entre a empresa e seus técnicos, facilitando a gestão de demandas e a alocação eficiente dos profissionais.

### _Diagrama espinha de peixe_

![Diagrama Espinha de Peixe](imagens/produto/espinhaDePeixe.jpeg)

## **Declaração de Posição do Produto**

O produto se destaca por oferecer uma solução ágil e automatizada para a comunicação e coordenação de técnicos para realizar um determinado serviço, eliminando a necessidade da maior parte dos processos manuais. 

Através de uma interface intuitiva e eficiente, o produto permite localizar rapidamente técnicos disponíveis, estabelecer contato imediato e acompanhar o progresso dos serviços em tempo real. Além disso, oferece funcionalidades de gestão de prazos e notificações para garantir a entrega pontual dos serviços, evitando consequências graves para a empresa, como atrasos nas entregas, danos à reputação e multas elevadas.

O cliente-alvo é uma empresa especializada na entrega e manutenção de soluções de software e hardware que enfrentam desafios na logística de técnicos para o atendimento de chamados abertos pelos clientes da empresa. A empresa busca uma solução tecnológica que simplifique e agilize o processo de comunicação com seus técnicos, permitindo atender às demandas de forma rápida e eficiente.

O produto se diferencia dos concorrentes pela sua abordagem abrangente e integrada para a gestão de técnicos. Enquanto muitas soluções do mercado se concentram apenas em aspectos específicos, como localização de profissionais disponíveis, o nosso produto irá oferecer uma solução completa que abrange desde a busca e contato inicial com os técnicos até o acompanhamento em tempo real do processo dos serviços.

Além disso, o produto se destaca pela sua facilidade de uso e interface intuitiva, que permite uma integração suave com os próprios processos existentes na empresa. Com funcionalidades de gestão de prazos, notificações automáticas e relatórios detalhados dos serviços para ambas as partes do processo, o produto proporciona uma experiência superior aos usuários, ajudando-os a otimizar seus processos operacionais e aprimorar a qualidade de serviço oferecido aos clientes.

![Tablea Declaração do Produto](imagens/produto/tabelaDeclaracaoProduto.jpeg)

## **Objetivos do Produto**

Com base no chamado registrado pelos clientes na Plataforma de ServiceDesk, o sistema realiza a correlação do problema identificado com a base de técnicos, buscando alocar o recurso mais próximo e com a competência necessária para o atendimento. 

Os técnicos são filtrados de acordo com suas competências, localização geográfica, preço do serviço, atividade atual e proximidade do local de serviço, sendo então plotados em um mapa para visualização fácil dos disponíveis na região do chamado. 

Uma vez selecionado o técnico, é disparada uma comunicação para que este atenda ao chamado, enquanto uma interface permite tanto ao técnico quanto à empresa acompanharem o andamento do serviço. 

O sistema tem como objetivo reduzir o tempo de resposta dos chamados, oferecendo também uma interface para a confirmação da coerência do chamado. As competências dos técnicos são constantemente atualizadas, e caso não haja contato com o técnico escolhido inicialmente, o sistema é capaz de acionar automaticamente outro técnico para o atendimento.

## **Tecnologias a Serem Utilizadas**

1. Backend:

    **Django:** Como framework principal para o desenvolvimento do backend, oferecendo uma estrutura robusta para lidar com roteamento, modelos de dados, autenticação, autorização, e muito mais.

2. Banco de Dados:

    **PostgreSQL:** Um banco de dados relacional poderoso e altamente confiável, oferecendo recursos avançados para garantir a integridade dos dados.

3. Frontend:

    **Django Templates:** Para renderizar as páginas HTML e fornecer uma experiência de usuário dinâmica, você pode usar os templates do Django.

    **JavaScript + AJAX:** Para interações mais dinâmicas na interface do usuário, você pode usar JavaScript junto com chamadas AJAX para atualizações assíncronas de conteúdo.

4.  APIs RESTful:

    **Django Rest Framework (DRF):** Uma extensão popular para o Django que simplifica o desenvolvimento de APIs RESTful, fornecendo serializadores, autenticação, autorização e outras ferramentas úteis.

5. Estilização:

    **Bootstrap:** Um framework CSS popular que fornece componentes e estilos pré-construídos para uma interface de usuário atraente e responsiva.  

6. Gerenciamento de Dependências e Implantação:

    **pipenv:** Para gerenciar as dependências do projeto de forma isolada, você pode usar o pipenv, que combina o gerenciamento de pacotes do pip com o ambiente virtual.

    **Docker:** Para criar contêineres isolados que encapsulam o aplicativo e suas dependências, facilitando a implantação e o escalonamento.