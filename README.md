# Planta-inteligente
RESUMO
O Projeto se propõe a produzir um artigo e um vídeo demonstrativo para o Curso de Tecnologia em Analise e Desenvolvimento de Sistemas. Para tanto, o artigo cientifico deve apresentar a descrição todo material utilizado, esquema eletrônico, o funcionamento de seu protótipo, com detalhes sobre o funcionamento e acionamento de seus sensores e atuadores e os resultados do projeto. O vídeo deve apresentar o funcionamento do projeto  com um vídeo-demonstração no YouTube de sua apresentação do funcionamento e os resultados de seu teste de funcionamento e explique o funcionamento do hardware e o código desenvolvido.





1.	Introdução

           Este projeto usa um sensor de umidade de solo para informar quando a planta precisa ser regada. A rega ocorre automaticamente atraves de uma mini bomba dagua dentro de um reservatorio de agua.


2.	Materiais e Métodos 

           Para realizar o projeto proposto serão utilizados componentes de hardware e software para o funcionamento da planta inteligente. 

		
1.	 Placa Konker
2.	Protoboard   
3.	Sensor de umidade de solo
4.	Kit jumper macho/macho – macho/fêmea
5.	Módulo relé 5V
6.	Mini Bomba de água submersível. 
7.	Materiais diversos
          Vaso com planta, cânula de silicone, pote para reservatório de água e cabos USB.
8.	Prototipagem eletrônica
              Arduino IDE. Ide (2022)
9.	Modulo de comunicação
               O MQTT Dashboard utiliza o broker HiveMQ MQTT. Podendo usar qualquer cliente ou biblioteca MQTT para publicar no broker. (HIVEMQ, 2022)

              O FRED é um serviço Node-RED hospedado na nuvem, projetado para agilizar o desenvolvimento de aplicativos IoT.






3.	Funcionamento
             Para o funcionamento da planta inteligente, será necessário fazer as conexões entre a protoboard, a placa konker, o modulo rele e o sensor de umidade utilizando os jumpers. Fazer a ligação da fonte na bomba de água e no modulo rele. Com todas as partes de hardware conectadas iniciamos a conexão com o software Arduino. Toda a escrita do código será realizada e carregamos na placa para colocar em funcionamento através do sensor de umidade que será feito o acionamento da bomba de água para irrigação da planta, assim que o solo estiver úmido a bomba é desligada automaticamente. (A BIT, 2022) 
4.	Referências

1.	KONKERLABS. Placa Konker. Disponível em: konkerlabs.com. Acesso em: 24 fev. 2022.
2.	NODEMCU. Módulo WiFi ESP8266 nodemcu. Disponível em: https://www.filipeflop.com/. Acesso em: 24 fev. 2022.
3.	AUTOR. Protoboard. Disponível em: foto propria. Acesso em: 24 fev. 2022.
4.	ELETRÔNICA, Baú da. Sensor de Umidade de solo. Disponível em: https://www.baudaeletronica.com.br/. Acesso em: 24 mar. 2022.
5.	ELETRÔNICA, Baú da. Kit Jumper. Disponível em: https://www.baudaeletronica.com.br/. Acesso em: 24 mar. 2022.
6.	ELETRÔNICA, Baú da. Módulo Relé 5V. Disponível em: https://www.baudaeletronica.com.br/. Acesso em: 24 mar. 2022.
7.	ELETRÔNICA, Baú da. Mini Bomba de água. Disponível em: https://www.baudaeletronica.com.br/. Acesso em: 24 mar. 2022.
8.	IDE, Arduino. Arduino IDE. Disponível em: https://www.arduino.cc/en/software. Acesso em: 24 mar. 2022.
9.	A BIT, Bit. Arduino - Sistema de irrigação automático. Disponível em: https://www.youtube.com. Acesso em: 24 abr. 2022.
10.	HIVEMQ. Cliente Websocket MOTT. Disponível em: http://www.hivemq.com/demos/websocket-client/. Acesso em: 28 maio 2022.
