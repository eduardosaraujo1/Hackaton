# Plataforma Integrada de Turismo da Baixada Santista Sul - Litoral Inteligente

### Problema

1. O turismo predatório é comum durante finais de semana e feriados, causando superlotação em pontos turísticos da baixada santista e prejudicando o meio ambiente local.
2. Turistas perdem a oportunidade de conhecer o potencial turístico completo da região pois existe uma taxa de R$1000,00 para cada veículo com mais de 10 pessoas que entra em cada cidade (Mongaguá, Itanhaém e Peruíbe), o que encarece os pacotes turísticos oferecidos pelas agências de turismo e reduz a competitividade e o acesso das pessoas a esses planos.

### Solução

Nossa equipe propõe o desenvolvimento de uma plataforma digital integrada que conecte turistas, agências de turismo, motoristas independentes e guias turísticos.

A plataforma oferece três funcionalidades principais através de telas intuitivas:

#### Telas do Aplicativo

1. **Atrativos (Pontos Turísticos)**

    - Listagem de todos os pontos turísticos disponíveis nas três cidades (Mongaguá, Itanhaém e Peruíbe)
    - Informações detalhadas sobre cada atrativo
    - Fotos, descrições e avaliações dos visitantes

2. **Eventos**

    - Calendário de eventos das cidades
    - Festivais, shows, eventos culturais e esportivos
    - Detalhes sobre data, local e como participar

3. **Rotas**
    - Rotas turísticas personalizadas criadas pelas agências de turismo
    - Cada rota inclui múltiplos pontos turísticos distribuídos pelas três cidades
    - Ao clicar em uma rota, o turista visualiza:
        - Horário da saída e retorno
        - Motorista designado
        - Guia turístico (se incluído)
        - Quantidade de vagas disponíveis
        - Preço total do pacote
        - Opção de pagamento integrado
    - Após realizar o pagamento, a vaga é automaticamente ocupada e confirmada

#### Fluxo de Reserva

1. O turista navega pelas rotas disponíveis
2. Seleciona uma rota de interesse
3. Visualiza todos os detalhes: horário, motorista, guia, vagas e preço
4. Realiza o pagamento diretamente na tela
5. Recebe confirmação imediata da reserva com a vaga ocupada

#### Atores da Plataforma

-   **Turistas:** exploram atrativos, eventos e rotas, fazem reservas e pagamentos
-   **Agências de Turismo:** criam e gerenciam rotas turísticas integradas
-   **Motoristas Independentes:** oferecem serviços de transporte para as rotas
-   **Guias Turísticos:** acompanham os turistas nas rotas (quando incluídos)

### Modelo de Negócio

A plataforma cobrará uma taxa fixa por reserva realizada através do aplicativo. Esse modelo de receita permitirá:

-   Redução dos custos operacionais das agências de turismo
-   Preços mais acessíveis para os turistas
-   Descentralização do transporte, eliminando a necessidade de grandes veículos que pagam taxas de R$1000,00 por cidade

### Impacto e Benefícios

**Para os Turistas:**

-   Acesso facilitado a rotas turísticas integradas nas três cidades
-   Transparência total sobre horários, guias, motoristas e disponibilidade
-   Processo de reserva e pagamento simplificado em um único aplicativo
-   Preços mais competitivos

**Para as Agências de Turismo:**

-   Plataforma de divulgação integrada
-   Redução de custos operacionais com transporte
-   Facilidade na gestão de rotas e reservas
-   Maior alcance de público

**Para a Região:**

-   Turismo mais sustentável e distribuído
-   Redução da superlotação em pontos turísticos
-   Geração de emprego para motoristas e guias locais
-   Maior visibilidade dos eventos e atrativos das três cidades

No futuro, pretendemos pressionar os governos municipais para que adotem um sistema de selos de viagem unificados, permitindo que as agências de turismo adquiram selos integrados para as três cidades a um custo reduzido. Esse modelo foi aplicado com sucesso em outras regiões, como o Parque Nacional do Iguaçu, onde a taxa de entrada é utilizada para a conservação ambiental e o desenvolvimento sustentável do turismo local.

### Validação de mercado

Para validar nossa solução, realizamos as seguintes perguntas para pessoas que já realizaram uma viagem turística:

1. Você já visitou as cidades de Mongaguá, Itanhaém ou Peruíbe?
2. Você já utilizou os serviços de uma agência de turismo para visitar essas cidades?
3. Qual seria o valor máximo que você estaria disposto a pagar por um pacote turístico completo, incluindo transporte e hospedagem?
4. Você estaria interessado em uma plataforma que ofereça pacotes turísticos integrados para essas cidades com opções de transporte flexíveis?
5. E se você pudesse economizar quase metade do custo atual dos pacotes turísticos, você consideraria utilizar essa plataforma?

### Arquitetura da solução

![Plataforma Integrada de Turismo da Baixada Santista Sul - Litoral Inteligente](./images/diagram.png)

#### Componentes do Sistema

**1. Aplicativo do Turista**

-   **Tela de Atrativos:** navegação e descoberta de pontos turísticos
-   **Tela de Eventos:** calendário e informações sobre eventos das cidades
-   **Tela de Rotas:** visualização e reserva de rotas turísticas
-   Sistema de pagamento integrado
-   Confirmação e gerenciamento de reservas

**2. Painel das Agências de Turismo**

-   Criação de rotas turísticas
-   Seleção de pontos turísticos para cada rota
-   Definição de horários
-   Associação de motoristas e guias
-   Gestão de vagas e preços
-   Acompanhamento de reservas

**3. Módulo de Motoristas**

-   Cadastro e verificação de motoristas independentes
-   Disponibilização de horários
-   Vinculação a rotas específicas
-   Gestão de capacidade de transporte

**4. Módulo de Guias Turísticos**

-   Cadastro de guias
-   Disponibilização de horários
-   Vinculação a rotas específicas

#### Fluxo Operacional

1. **Criação de Rotas:** Agências criam rotas selecionando múltiplos pontos turísticos, definindo horários, associando motoristas e guias, e estabelecendo o número de vagas
2. **Descoberta:** Turistas exploram atrativos, eventos e rotas disponíveis através do aplicativo
3. **Reserva:** Ao clicar em uma rota, o turista visualiza todos os detalhes (horário, motorista, guia, vagas disponíveis, preço)
4. **Pagamento:** Pagamento realizado diretamente na tela de detalhes da rota
5. **Confirmação:** Vaga é ocupada automaticamente após pagamento confirmado
6. **Execução:** No dia agendado, motorista e guia (se incluído) conduzem a rota conforme planejado

### Tecnologias utilizadas

-   Flutter para desenvolvimento dos aplicativos móveis.
-   SQLite para armazenamento local de dados e falsificação de login.
