# EmbarcaTech

# Sistema Embarcado para Controle de AGV com Telemetria IoT

Este repositório contém o firmware desenvolvido como Projeto Final para a capacitação em Sistemas Embarcados do Embarcatech. O projeto consiste no sistema de controle de tração e monitoramento para um Veículo Guiado Automaticamente (AGV) utilizando o microcontrolador Raspberry Pi Pico W.

## Objetivo

O objetivo principal deste projeto é implementar um sistema embarcado robusto capaz de:
1. Ler comandos de navegação analógicos via Joystick.
2. Calcular a rotação diferencial de dois motores de passo.
3. Limitar dinamicamente a potência máxima dos motores através de um potenciômetro linear.
4. Garantir a segurança da operação através de um freio de emergência acionado por Interrupção de Hardware.
5. Transmitir o status do veículo em tempo real via porta serial (UART0) estruturado no formato JSON.

## 🛠️ Dependências

Para compilar, modificar e simular este projeto, você precisará das seguintes ferramentas:

**Software:**
* **Visual Studio Code **
* **Extensão "Raspberry Pi Pico"** para VS Code .
* **Pico SDK** (C/C++) e **CMake** .
* **Wokwi Simulator** .

**Hardware Simulado / Físico (Placa BitDogLab):**
* 1x Raspberry Pi Pico W
* 2x Motores de Passo  + Drivers A4988
* 1x Módulo Joystick Analógico (Eixos X e Y)
* 1x Potenciômetro
* 1x Push-Button 
* 1x LED 
* 1x Display OLED SSD1306 

## Instruções de Instalação


