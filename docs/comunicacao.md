# Comunicação e Protocolos

## Wi-Fi

- Conexão à rede Wokwi-GUEST (simulada).
- Protocolo TCP/IP para acesso à Internet.

## MQTT

- Broker: HiveMQ (broker.hivemq.com)
- Tópico para comandos: `irrigador/comando`
  - Mensagens esperadas: `abrir`, `fechar`
- Tópico para status: `irrigador/status`
  - Mensagens enviadas: `Solo seco - irrigando`, `Solo úmido - válvula fechada`
