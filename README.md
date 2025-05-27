# wokwi-MQTT
# Sistema de Irrigação Automatizado com ESP32 e MQTT

Este projeto simula um sistema de irrigação inteligente com ESP32 no Wokwi. Ele lê a umidade do solo usando um sensor simulado e utiliza um relé para acionar uma válvula (representada por um LED).

## Funcionalidades

- Leitura de umidade do solo com sensor DHT22 (simulado via ADC).
- Controle da válvula de irrigação via MQTT.
- Comunicação com broker MQTT público (HiveMQ).
- Simulação no ambiente Wokwi.

## Como testar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/irrigacao-mqtt-esp32.git

2. Acesse o Wokwi e importe o projeto, ou crie um novo projeto com os mesmos componentes.

3. Carregue o código codigo/main.py.

4. Utilize um cliente MQTT para enviar comandos para o tópico irrigador/comando com os valores abrir ou fechar.
