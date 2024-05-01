# Criando um Sistema e Abstraindo um Celular com POO em C#

Este projeto é uma implementação básica de um sistema de smartphones usando a linguagem de programação C# e os conceitos de Programação Orientada a Objetos (POO). O desafio proposto consistia em criar uma abstração de um celular com POO em C#, com foco na criação de classes, herança, métodos abstratos e instanciamento de objetos.

## Conhecimentos Adquiridos:

- Abstração e Herança: Aprendi a criar uma hierarquia de classes com uma classe base (Smartphone) e classes derivadas (Iphone e Nokia), permitindo compartilhar comportamentos comuns e especializar comportamentos específicos.
- Métodos Abstratos: Entendi como usar métodos abstratos para definir um contrato na classe base (Smartphone) e implementá-lo de forma específica em suas subclasses (Iphone e Nokia), promovendo a flexibilidade e a modularidade do código.
- Construtores e Propriedades: Utilizei construtores para inicializar as propriedades das classes e garantir que os objetos fossem criados de maneira consistente, mantendo a coesão e a encapsulação do código.
- Métodos Estáticos: Explorei o uso de métodos estáticos para representar comportamentos que pertencem à classe em si e não a instâncias individuais, como os métodos Ligar e ReceberLigacao.
- Instanciação de Objetos: Pratiquei a criação de instâncias de objetos das classes Iphone e Nokia, permitindo a manipulação e execução de ações específicas de cada tipo de smartphone.
Como Executar:

Para executar este projeto, basta compilar o código-fonte em um ambiente de desenvolvimento C# compatível e executar o programa principal. As ações simuladas de ligar, receber ligação e instalar aplicativos serão exibidas no console.

## Possíveis Extensões:

Este projeto pode ser estendido de várias maneiras, adicionando novas funcionalidades aos smartphones, como enviar mensagens, navegar na internet, tirar fotos, entre outras. Além disso, é possível aprimorar a interface do usuário, permitindo interações mais dinâmicas e intuitivas.

Este desafio proporcionou uma oportunidade valiosa para aplicar e consolidar os conhecimentos adquiridos sobre POO em C#, além de estimular a criatividade e o pensamento crítico na resolução de problemas de programação.
------------------------------------------------------------

## O projeto original na DIO 👇🏽

# DIO - Trilha .NET - Programação orientada a objetos
www.dio.me

## Desafio de projeto
Para este desafio, você precisará usar seus conhecimentos adquiridos no módulo de orientação a objetos, da trilha .NET da DIO.

## Contexto
Você é responsável por modelar um sistema que trabalha com celulares. Para isso, foi solicitado que você faça uma abstração de um celular e disponibilize maneiras de diferentes marcas e modelos terem seu próprio comportamento, possibilitando um maior reuso de código e usando a orientação a objetos.

## Proposta
Você precisa criar um sistema em .NET, do tipo console, mapeando uma classe abstrata e classes específicas para dois tipos de celulares: Nokia e iPhone. 
Você deve criar as suas classes de acordo com o diagrama abaixo:

![Diagrama classes](Imagens/diagrama.png)

## Regras e validações
1. A classe **Smartphone** deve ser abstrata, não permitindo instanciar e servindo apenas como modelo.
2. A classe **Nokia** e **Iphone** devem ser classes filhas de Smartphone.
3. O método **InstalarAplicativo** deve ser sobrescrito na classe Nokia e iPhone, pois ambos possuem diferentes maneiras de instalar um aplicativo.

## Solução
O código está pela metade, e você deverá dar continuidade obedecendo as regras descritas acima, para que no final, tenhamos um programa funcional. Procure pela palavra comentada "TODO" no código, em seguida, implemente conforme as regras acima.
