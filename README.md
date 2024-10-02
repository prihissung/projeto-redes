# **Simulando Topologias de Rede com o Cisco Packet Tracer**
## **Introdução**

### Este repositório demonstra como configurar cinco tipos de topologias de rede no Cisco Packet Tracer:

* **Estrela:** Uma estrutura centralizada com um dispositivo principal (switch ou roteador) conectado a todos os outros dispositivos.
* **Ponto a Ponto:** Uma conexão direta entre dois dispositivos.
* **Anel:** Uma estrutura em loop onde cada dispositivo se conecta a seus dois vizinhos.
* **Barramento:** Uma estrutura linear onde todos os dispositivos se conectam a um único canal de comunicação.
* **Árvore:** Uma estrutura hierárquica com um dispositivo principal conectado a outros dispositivos em camadas.
* **Malha:** Uma estrutura completa onde todos os dispositivos se conectam diretamente entre si.

### Conceitos Básicos

* **Topologia de Rede:** A disposição física dos elementos que compõem a rede.
* **Cisco Packet Tracer:** Software de simulação de redes que permite construir e testar redes virtuais.

### Objetivos

* Familiarizar-se com diferentes topologias de rede.
* Praticar a configuração de redes no Cisco Packet Tracer.
* Analisar o desempenho e as características de cada topologia.


## **TOPOLOGIA ESTRELA**

A topologia em estrela é uma estrutura de rede local (LAN) caracterizada pela conexão de cada dispositivo a um ponto central, como um hub ou switch. Essa organização assemelha-se a uma teia de aranha, onde os fios convergem para um único ponto central.

### [INSTRUÇÃO]
* [PASSO 1]
Por sua descrição, é bem intuitivo a sua montagem, para isso iremos precisar de 5 PC, e 1 Switch.

* [PASSO 2]
Após isso, coloque os cabos conectando de cada PC ao Switch, sendo o cabo Copper Straight Through.

Após a conexão de todos os PC com o Switch principal, os ícones ao longo do cabo ficarão verdes, caso todos estejam funcionando. 

## **TOPOLOGIA PONTO A PONTO**

A topologia ponto a ponto (P2P) é uma estrutura de rede onde cada dispositivo se conecta diretamente a outro dispositivo, sem a necessidade de um intermediário como um hub ou switch. Essa conexão direta é como uma ponte entre dois pontos, permitindo a comunicação entre eles.

### [INSTRUÇÃO]

* [PASSO 1]
Por sua descrição, é bem intuitivo a sua montagem, para isso iremos precisar de 2 PC.

* [PASSO 2]
Após isso, coloque os cabos conectando um PC ao outro PC, sendo o cabo Copper Cross Over.

Após as instruções, o sistema P2P estará pronto! Com os sinais verdes indicando o funcionamento.

## **TOPOLOGIA ANEL**

A topologia em anel conecta dispositivos em um loop fechado, onde cada dispositivo se conecta aos dois adjacentes. Essa estrutura simples, como uma roda gigante, permite que os dados circulem em uma única direção, garantindo que todos os dispositivos recebam as informações. Apesar da simplicidade, a topologia em anel apresenta desafios em termos de escalabilidade e vulnerabilidade a falhas, sendo mais utilizada em ambientes específicos como redes de automação industrial e controle de tráfego.

### [INSTRUÇÃO]

* [PASSO 1]
Infelizmente, não tem como seguir conectando os cabos de rede diretamente entre mais de 2 PC, então seguindo a base do tutorial do site GeeksForGeeks. Separando 3 PC e 3 Switch, iremos fazer a estrutura, onde os Switch estão no centro, e os PC’s rodeando, 1 PC para 1 Switch.

* [PASSO 2]
Com o cabo de Copper Cross Over, iremos conectar os Switch entre eles.

* [PASSO 3]
Com o cabo de Copper Straight Through, iremos conectar os Switch com o seu PC respectivo, apenas 1 PC por Switch.

Percebemos que nesse caso, há presença de um círculo em laranja, apenas indicando que funciona aquela conexão, mas com um certo atraso. Ademais, as conexões funcionam perfeitamente.

## **TOPOLOGIA DE BARRAMENTO**

A topologia de barramento conecta dispositivos a um único cabo central, similar a uma rua de mão única. Imagine um cabo de energia percorrendo sua casa, com diversos dispositivos conectados a ele. Essa é a ideia principal da topologia de barramento. Os dados trafegam nesse cabo em ambas as direções, acessíveis a todos os dispositivos conectados.

### [INSTRUÇÃO]

* [PASSO 1]
Como componentes, iremos usar um Switch para cada PC, nesse caso, 4 de cada, como dessa forma:

* [PASSO 2]
Conecte os Switch, um ao seu proximo, apenas. Use um cabo de Copper Cross Over.

* [PASSO 3]
E conecte cada Switch a um único PC, usando o cabo de Copper Straight Through.

## **TOPOLOGIA DE ÁRVORE**

A topologia em árvore, como o próprio nome sugere, organiza os dispositivos em uma estrutura hierárquica semelhante a uma árvore, com um dispositivo principal (raiz) no topo e vários dispositivos subordinados (ramos) conectados a ele. Essa estrutura facilita a organização e o gerenciamento da rede, dividindo-a em sub-redes menores e mais fáceis de administrar.

### [INSTRUÇÃO]

* [PASSO 1]
Seguindo o pedido de conectar 1 Switch principal (Raiz), a 3 Switch Secundários (Galhos), e cada Switch, conectando individualmente a 3 PC diferentes. Onde organizei da seguinte forma:

* [PASSO 2]
Conecte os Switches Secundários, cada um individualmente ao Switch Raiz, usando o cabo Copper Cross Over.

* [PASSO 3]
Conecte aos Switches Secundários cada um dos PC, mas apenas 1 PC a 1 Switch.

Os sinais ficam todos como triângulos verdes, indicando o funcionamento do sistema.

## **TOPOLOGIA DE MALHA**

A topologia em malha se destaca como a campeã em confiabilidade, oferecendo uma rede robusta e resiliente a falhas. Imagine uma teia de aranha, onde cada ponto está conectado a todos os outros: essa é a essência da topologia em malha. Nela, cada dispositivo se conecta diretamente a todos os demais, criando uma redundância que garante que a comunicação nunca seja interrompida.

### [INSTRUÇÃO]

* [PASSO 1]
Para a Topologia em Malha, iremos fazer o seguinte, 5 Switches no meio, em tipo “anel”, e 5 PC, 1 para cada Switch, ficando 5 PC e 5 Switch. Ficando assim:

* [PASSO 2]
Conecte 5 switches em um loop fechado, criando uma topologia em anel.

* [PASSO 3]
Conecte cada switch a um PC.

Perceba que diferente de algumas vezes, nesse têm círculos laranja, eles significam que funciona, mas com um leve atraso no ping. Mas a rede funciona corretamente.
