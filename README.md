Faça uma montagem do TinkerCad com uma montagem de pisca-pisca com Arduino Uno de autoria própria (não pode ser exemplos existentes). Ao clicar no play do TinkerCad, o projeto deve executar sem erros uma rotina que simula um pisca-pisca de qualquer cadência. Utilize no projeto um protoboard, ligações elétricas entre LED (não o LED_BUILT_IN e sim um OFF_BOARD), resistor e uma porta do Arduino por meio de jumpers. Também crie um comentário ao lado do protoboard que mostre matematicamente o valor correto do resistor pela lei de Ohm para um corrente nominal do LED a ser definida pelo datasheet do LED OFF_BOARD

Para esta atividade, utilizei o Tinkercad para prototipar o circuito de um led em série com um resistor conectado a uma porta digital do arduino, o que possibilita, por meio do controle de estados lógicos, definir se o led está acesso ou não. A partir disso, o código demonstra um loop que onde o led fica acesso por 2s e apagado pelo mesmo tempo. Após isso, também foi adicionado um amperímetro ao circuito, a fim de medir a corrente elétrica no led. Por fim, o cálculo de dimensionamento do resistor foi feito seguindo a fórmula:

R = (Vtotal - Vled) / iled

Onde R é a resistência, Vtotal é a tensão de 5V fornecida pela Arduino, Vled é a queda de tensão no led (2V) e iled é a corrente consumida pelo led (20mA). Com isso, obteve se um valor de 150 ohms para a resistência.

Link para o projeto no Tinkercad: https://www.tinkercad.com/things/9NfHQBa89PW-ponderada-semana-1-caio-de-alcantara-santos