### Documentação do Aplicativo de Teste: Rastreamento de Encomendas

#### Descrição
Um aplicativo capaz de rastrear encomendas dos correios e armazená-las localmente para consulta do usuário.

#### Requisitos

- **Arquitetura**: Você tem liberdade para escolher a arquitetura, mas leve em conta que esse é um app simples.
  
- **Responsividade**: O projeto disponível no Figma é apenas mobile, mas você pode deixá-lo responsivo para telas maiores. Em telas maiores, a tela de cadastro de encomendas pode ser convertida em um modal, e a tela principal pode ser dividida em duas: à esquerda, a lista de encomendas, e à direita, a encomenda selecionada.
  
- **Plataformas**: O foco é o mobile, mas web e desktop são diferenciais.
  
- **Uso de Packages**: Você tem liberdade para usar quaisquer bibliotecas para gerenciamento de estado, rotas e dependências, requisições HTTP e banco de dados local.
  
- **Testes Unitários**: A criação de testes unitários, testes de widget e testes de integração são diferenciais.

#### Recursos Disponíveis

- **Design**
  - Avaliaremos a fidelidade ao projeto e sua criatividade para criação de recursos implícitos de UX.
  - Acesse o projeto no [Figma](https://www.figma.com/design/q5V0kmio5nFC0uNWhXGazn/Package-Tracking?node-id=0-1&t=PU60WiUmOvUFeC8L-1) (Senha: bel24).

- **API**
  - Disponibilizaremos uma chave para a API pública de rastreio de encomendas chamada Link & Track.
  - Consulte a [documentação da API](http://linketrack.com/api).
  - Regra importante: "Por favor, esteja ciente que nosso sistema de controle de acesso limita as consultas a uma taxa de 1 consulta por segundo. Em caso de abuso sua conta poderá ser bloqueada. Este é um serviço gratuito e visa atender a outros usuários além de você."
  - Endpoint: `https://api.linketrack.com/track/json?user=danielmarciano.ti@belenus.com.br&token=5218641b6e7d8a623b67bc22e8cf1d4e24d99599386e80296fd0d0f962b25692&codigo=PW377894918BR` (Substitua "PW377894918BR" pelo código desejado).

- **Repositório**
  - Faça um fork deste repositório.
  - Quando concluir, crie um pull request para avaliação.

#### Prazo
- **Previsão de Entrega**: 7 dias.

#### Critérios de Avaliação
- **Funcionalidade**: O aplicativo rastreia encomendas corretamente e armazena os dados localmente.
- **Responsividade**: O app se adapta bem a diferentes tamanhos de tela.
- **Qualidade do Código**: Organização, clareza e uso adequado de padrões de código.
- **Design**: Fidelidade ao projeto no Figma e criatividade nos recursos de UX.
- **Testes**: Presença e qualidade dos testes unitários, de widget e de integração.
- **Documentação**: Clareza e completude da documentação do código e do projeto.
- **Tratamento de Erros**: Não se esqueça de implementar tratamentos de erro adequados para garantir uma boa experiência ao usuário.

#### Instruções Adicionais
- Documente suas escolhas arquiteturais e de design.
- Inclua instruções claras sobre como executar o projeto localmente e realizar os testes.
