# Estudo de Viabilidade
Jully Ketely Alves da Silva e Warley Leandro dos Anjos

18 de agosto de 2023

O projeto de desenvolvimento proposto pelos alunos Jully e Warley para o Trabalho de Conclusão de Curso (TCC) do curso de Bacharelado em Engenharia de Software da Pontifícia Universidade Católica de Minas Gerais (PUC Minas) tem como objetivo desenvolver um SAAS (_software as a service_) para gestão de academias. 

A HIKE é uma _startup_ sediada em São Paulo, que tem como objetivo introduzir no mercado um software de gestão para academias por assinatura, contendo uma plataforma web para os gestores da academia e um aplicativo _mobile_ para alunos e _personal trainers_.
O serviço possibilita aos alunos visualizarem sua ficha de treino, saber a lotação geral e parcial por modelos de treinos na academia, acompanhamento da evolução, realizar pagamentos e adicionar informações importantes sobre sua saúde. Por outro lado, possibilita aos gestores monitorar seus clientes, acompanhar a evolução, criar modelos de ficha de treinos e gerenciar pagamentos.

A aplicação possui as seguintes restrições: Deve estar disponível para dispositivos móveis android e IOS e suporte para os principais navegadores web (Chrome, Safari, Edge, Opera e Firefox); Comunicar com a aplicação _web_ e _mobile_ por mensageria; E fornecer informações no modo _offline_, ou seja, sem acesso a internet com a estratégia de _offline first_, utilizando o sistema de gerenciamento de banco de dados Realm visando a atualização e persistência de dados.
Não há sistemas a serem substituídos, uma vez que o sistema a ser desenvolvido será uma solução inovadora e personalizável, destinada a atender às necessidades específicas de cada academia.

Ao analisar a demanda proposta pela _startup_, os alunos Jully e Warley apresentam como projeto de solução uma aplicação completa de _front end_, _back end_, design das interfaces _web_ e _mobile_ e banco de dados. O projeto de desenvolvimento não contempla o desenvolvimento de Interface de Programação de Aplicação (API, do inglês _Application Programming Interface_), página institucional, produção de conteúdo, hospedagem _web_ e _back end_, homologação, método de pagamento na modalidade pix e disponibilização nas lojas Google Play Store e App Store.

Esse projeto se enquadra no item 3.2.1 da Resolução de TCC 1 do segundo semestre de 2023, definido como "Projetos de desenvolvimento podem ter um cliente específico, externo à universidade". A justificativa para esse enquadramento é sustentada pela profunda integração do projeto com os princípios, práticas e disciplinas da Engenharia de Software. Assim, pode-se destacar as seguintes relações:

No decorrer do processo de desenvolvimento será empregado uma abordagem ágil, um método flexível que valoriza a interação constante com os stakeholders. Integração e entregas contínuas visam garantir possíveis adaptações e alinhamento do produto às evoluções, com _feedback_ constante dos _stakeholders_. Resultando em maior agilidade, visibilidade e um produto alinhado com o escopo e estrutura do projeto.

O sistema de controle e sinalização de ocupação da academia terá a função de monitorar o fluxo de pessoas nas suas instalações e transmitir esses dados para o aplicativo utilizado pelos alunos associados à academia. Esse processo será realizado por meio de comunicação assíncrona por fila de mensagens utilizando RabbitMQ, um software de mensageria _open source_.

Por fim, o projeto de desenvolvimento apresentado demonstra uma sólida integração de diversas áreas da Engenharia de Software, refletindo a aplicação prática dos conceitos abordados nas matérias específicas.
No contexto das disciplinas do curso, este projeto está diretamente ligado às seguintes áreas: “Engenharia de Requisitos”, “Desenvolvimento de Interfaces Web”, “Banco de Dados”, “Interação Humano-Computador”, “Projeto de Software”, “Gerência de Configuração e Evolução de Software”, “Arquitetura de Software” e “Desenvolvimento de Aplicações Móveis e Distribuídas”.

A disciplina de "Engenharia de Requisitos" é fundamental para definir as funcionalidades do SAAS, abrangendo aspectos como visualização de fichas de treino, controle de lotação e pagamento. A "Arquitetura de Software" contribui na concepção das estruturas do sistema, como a plataforma _web_ para gestores e o aplicativo _mobile_ para alunos.
O conhecimento de "Desenvolvimento de Interfaces Web" é empregado na criação das interfaces amigáveis, permitindo aos usuários acessar informações e recursos de maneira intuitiva. A disciplina de "Interação Humano-Computador"  auxilia na usabilidade do aplicativo e da plataforma, visando uma experiência positiva para os usuários.
A abordagem ágil aplicada durante o desenvolvimento, com integração e entregas contínuas, alinhou-se com princípios de "Gerência de Configuração e Evolução de Software", assegurando adaptações e ajustes ao longo do processo.

Em resumo, o projeto demonstra a convergência e aplicação dos conhecimentos das disciplinas mencionadas, resultando em um sistema abrangente que contempla o desenvolvimento de software, a criação de interfaces amigáveis e a integração de elementos de Engenharia de Software de forma coesa e eficaz.
