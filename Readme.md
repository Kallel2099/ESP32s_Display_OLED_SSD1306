# Projeto IOT com ESP32S e Display OLED SSD1306

![](https://img.shields.io/badge/Licença-MIT-greem) ![](https://img.shields.io/badge/Linguagem-C-yellow)


## Descrição
Neste projeto vamos utilizar um microcontrolador ESP32S e um display OLED SSD1306 de 128x64 0.96" para exibir uma imagem em bitmap, com código criado na Arduino IDE.

## Pré-requisitos
* Ter a [IDE](https://www.arduino.cc/en/software/) do Arduino instalada e configurada;
* 01 Microcontrolador ESP32s;
* 01 Display OLED SSD1306 128x64 0.96";
* Protoboard e jumpers;
* Cabo de dados para conexão do microcontrolador ao PC.

## Tabela de Conexões

|Pinos do ESP32S|Pinos do Display SSD1306|
| :---: | :---: |
|3.3 V (1)|VCC (2)|
|GND (38)|GND (1)|
|D22 (36)|SCL (3)|
|D21 (33)|SDA (4)|

## Imagem das Conexões

![Conexão dos componentes](ESP32s_Display_OLED.jpg)