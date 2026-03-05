# 🏗️ Princípios Arquiteturais

## Separação de Responsabilidades

Na arquitetura da plataforma Steam, a separação de responsabilidades é um princípio importante para organizar as funções do sistema em diferentes componentes. Cada parte do sistema possui uma função específica, como o gerenciamento da loja digital, a biblioteca de jogos dos usuários, os serviços de comunidade e os sistemas responsáveis pelo download e atualização dos jogos.

Essa divisão permite que cada componente do sistema seja desenvolvido e mantido de forma independente, facilitando a manutenção e evolução da plataforma ao longo do tempo. Dessa forma, mudanças em um módulo específico tendem a afetar menos os outros módulos do sistema.

## Análise de Coesão

A coesão está relacionada ao nível de organização interna de um módulo ou componente do sistema. Na Steam, os módulos tendem a apresentar boa coesão, pois cada um possui funções bem definidas. Por exemplo, o sistema responsável pela loja digital concentra atividades relacionadas à venda de jogos, enquanto o sistema de comunidade concentra funcionalidades como fóruns, avaliações e interação entre usuários.

Essa organização contribui para que cada módulo tenha responsabilidades claras, o que facilita o desenvolvimento, testes e manutenção da plataforma.

## Avaliação de Acoplamento

O acoplamento representa o nível de dependência entre diferentes partes de um sistema. Em uma arquitetura bem planejada, busca-se reduzir o acoplamento entre os componentes para evitar que mudanças em um módulo causem impactos em outros.

No caso da Steam, diferentes serviços como loja, biblioteca, comunidade e sistema de download funcionam de forma relativamente independente, embora ainda precisem se comunicar para garantir o funcionamento da plataforma. Esse equilíbrio entre comunicação e independência ajuda a manter o sistema mais flexível e escalável.
