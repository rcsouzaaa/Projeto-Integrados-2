 # Design


### Maquete Eletrônica:

> #### A maquete possibilita a visualizacao das ligacoes eletronicas e de como os sensores se comunicacao como um todo.
> 
>  ![Maquete](https://user-images.githubusercontent.com/12564754/143169612-df9655b0-2026-444f-a5dc-c30d06d1c035.png)
> 
> #### Componentes e suas funcionalidades:
> 
> - Arduino Mega 2560: Controla todo o sistema e por essa razão todos os demais componentes são conectados aos seus pinos de entrada e saída.
> 
> - Node MCU v1: Controlador com wifi para interface no celular, se conecta ao Arduino Mega por Rx/Tx.
> 
> - Servo Motor: É controlado por meio de um pino de saída digital PWM e será responsável por controlar o portão da casa.
> 
> - Sensor de gás MQ2: Sensor de gás selecionado pois ele detecta GLP(gás de cozinha) e fumaça. Ele pode ser conectado a um pino de entrada digital que receberá nível lógico alto quando for detectado gás e um pino de entrada analógica que receberá a concentração de gás.
> 
> - Sensor de Temperatura DHT11: Sensor de temperatura alimentado com 5V, ele envia os dados registrados por um pino de entrada analógica.
> 
> - Sensor de presença e movimento PIR: 
> 
> - Módulo Sensor de Umidade:
> 
> - Módulo Relé: O relé será acionado por meio de um pino de saída digital e será utilizado para controlar o cooler.
> 
> - Sensor ultrasônico:
> 
> - Módulo Matriz de LED 8×8:
> 
> - Buzzer passivo: Controlado por um pino de saída digital PWM, emitirá som ao ser atividado o sensor de gas e para a proximidade de veiculos na parede da garagem.
> 
> - Display LCD 16×2 I2C: O display LCD com módulo I2C integrado essa conexão é feita utilizando quatro pinos. Dois pinos são utilizados para alimentação e os outros dois para comunicação. O display LCD será resposável por exibir mensagens sobre o funcionamento do sistema.

### Planta base para a Maquete:


 [Voltar para pagina inicial](/README.md)
