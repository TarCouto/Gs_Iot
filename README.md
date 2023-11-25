Monitoramento de Temperatura e Umidade IoT com ESP32

Este projeto apresenta uma solução IoT integrada para monitoramento de temperatura e umidade em tempo real, utilizando o ESP32 como microcontrolador central. Através do sensor DHT22, os dados ambientais são coletados e transmitidos via protocolo MQTT a um servidor MQTT público. Utilizamos o Node-RED como interface de gateway para processar esses dados e o Node-RED Dashboard para visualização em tempo real, criando uma interface gráfica intuitiva e acessível pelo navegador.

A solução é ideal para ambientes que requerem monitoramento climático constante, como estufas, armazéns, ou até residências inteligentes. Com a implementação de um sistema de alertas, é possível notificar os usuários sobre condições anormais, possibilitando ações rápidas e preventivas.

Monitoramento de Temperatura e Umidade IoT
Descrição
Este projeto é uma solução IoT para monitoramento de temperatura e umidade em tempo real utilizando ESP32 e sensor DHT22. Os dados coletados são enviados para um broker MQTT e processados através do Node-RED, com uma interface de dashboard para visualização.

Componentes Necessários
ESP32
Sensor DHT22
Conexão com a internet
Acesso ao broker MQTT (exemplo: test.mosquitto.org)
Node-RED instalado localmente ou em um servidor
Configuração do Hardware
Descreva como montar o circuito com o ESP32 e o DHT22, incluindo o diagrama de fiação.

Configuração do Software
ESP32
Carregue o código para o ESP32 usando a IDE do Arduino.
Assegure-se de que o ESP32 esteja conectado à mesma rede Wi-Fi que o servidor Node-RED.
Node-RED
Importe os fluxos do Node-RED fornecidos no arquivo flows.json.
Configure o nó MQTT para se conectar ao seu broker MQTT.
Ajuste os tópicos MQTT nos nós de acordo com o que está definido no código do ESP32.


https://github.com/TarCouto/Gs_iot

video: https://www.youtube.com/watch?v=AHrlINbLDmM&ab_channel=TarcisioCouto

wokwi: https://wokwi.com/projects/382291270248629249
