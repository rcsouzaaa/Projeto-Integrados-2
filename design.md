 # Design

### Lista de componentes:

| Componente  |  Quantidade |
|---|---|
| Arduino Mega 2560  | 1  |
|  Node MCU v1 | 1 * | 
|  Servo Motor |  1 |
| Sensor de gás MQ2  |  1 |
|  Sensor de Temperatura DHT11 |  1 |
|  Sensor de presença e movimento PIR |  1 |
| Módulo Sensor de Umidade  |  1 |
|  Módulo Relé |  1 |
|  Sensor ultrasônico | 1  |
| Módulo Matriz de LED 8×8  |  1 |
|  Buzzer passivo |  1 |
|  Display LCD 16×2 I2C | 1  |
|  cooler | 1 *  |

> * Já possuo o componente

#### A maquete possibilita a visualização das ligações eletrônicas e de como os sensores se comunicação como um todo.

### Maquete Eletrônica:

> #### A maquete possibilita a visualização das ligações eletrônicas e de como os sensores se comunicação como um todo.
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
> - Sensor de presença e movimento PIR: Sensor para detectar movimentos na garagem e ligar a iluminacao.
> 
> - Módulo Sensor de Umidade: Será o sensor para aviasr a hora de dar aguá as plantas do jardim.
> 
> - Módulo Relé: O relé será acionado por meio de um pino de saída digital e será utilizado para controlar o cooler.
> 
> - Sensor ultrasônico: Detectar ao ter um veiculo na garagem, sua proximidade com a parede e avisar quando esta em posicao com o buzzer
> 
> - Módulo Matriz de LED 8×8: Iluminacao da garagem que será ativada pelo sensor de presenca.
> 
> - Buzzer passivo: Controlado por um pino de saída digital PWM, emitirá som ao ser atividado o sensor de gas e para a proximidade de veiculos na parede da garagem.
> 
> - Display LCD 16×2 I2C: O display LCD com módulo I2C integrado essa conexão é feita utilizando quatro pinos. Dois pinos são utilizados para alimentação e os outros dois para comunicação. O display LCD será resposável por exibir mensagens sobre o funcionamento do sistema.

### Planta base para a Maquete:


 [Voltar para pagina inicial](/README.md)
