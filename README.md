# Projeto IoT baseado em Monitoramento ECG

### Funcionamento
O software de programação Arduino IDE foi utilizado para desenvolver o código-fonte do monitoramento de ECG. O código foi transferido para o Arduino ESP32, que realizou o monitoramento dos batimentos cardíacos usando o módulo AD8232 e eletrodos. Os dados coletados pelo Arduino foram transmitidos para a plataforma em nuvem Ubidots, que recebeu e armazenou os dados. A plataforma processa os dados em tempo real, exibindo-os por meio de gráficos e alertas em caso de anomalias detectadas.<br>

### Hardware
#### Plataforma de Desenvolvimento: Arduino IDE <br>
O Arduino IDE é uma aplicação de plataforma cruzada, escrito em funções de C e C ++. É usado para escrever e fazer upload de programas em placas compatíveis com Arduino, mas também, com a ajuda de núcleos de terceiros, outras placas de desenvolvimento de fornecedores. <br>

#### Arduino: ESP32 - WROOM32 <br>
O Arduino ESP32 é uma placa de desenvolvimento que incorpora um microcontrolador de 32 bits da família ESP32 da Espressif Systems. É uma placa versátil e de baixo custo que oferece uma ampla gama de recursos e funcionalidades, incluindo conectividade sem fio Wi-Fi e Bluetooth, interface USB, interface Ethernet, conversores analógico-digitais (ADCs) e digitais-analógicos (DACs), interfaces de comunicação serial e paralela, entre outras. <br>

#### Sensor: Módulo AD 8232 <br>
O módulo de ECG AD8232 é um módulo que captura sinais elétricos do coração do usuário e os converte em sinais elétricos processáveis pelo microcontrolador. O módulo AD8232 possui amplificador, filtro e circuitos de proteção, permitindo a captura de sinais limpos e precisos. Ele é projetado para amplificar e filtrar sinais biopotenciais fracos e para fornecer uma saída de sinal analógico pronta para uso em uma variedade de aplicações, incluindo dispositivos wearable e sistemas de monitoramento de saúde. <br>

### Documentação <br>

<a href="https://www.arduino.cc/reference/pt/">Arduino IDE</a><br>
<a href="https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/index.html">Arduino ESP32</a><br>
<a href="https://www.analog.com/media/en/technical-documentation/data-sheets/ad8232.pdf">Módulo AD 8232</a><br>
<a href="http://docs.oasis-open.org/mqtt/mqtt/v3.1.1/os/mqtt-v3.1.1-os.pdf">Protocólo MQTT</a><br>
