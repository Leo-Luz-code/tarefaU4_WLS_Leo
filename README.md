## Projeto: Interrupções e Controle de LEDs no RP2040

Assista à demonstração do projeto aqui: https://www.youtube.com/watch?v=A0cId_PjqpM

Olá! Meu nome é Leonardo Rodrigues Luz, sou aluno do EmbarcaTech e neste projeto, desenvolvi uma aplicação para o microcontrolador RP2040, utilizando a placa de desenvolvimento BitDogLab. O objetivo principal foi consolidar o entendimento sobre interrupções, controle de LEDs, tratamento de "bouncing" de botões e manipulação de LEDs endereçáveis WS2812.

## Objetivos do Projeto

Compreender o funcionamento e aplicação de interrupções em microcontroladores.

Corrigir o fenômeno do bouncing em botões usando debouncing via software.

Controlar LEDs comuns e LEDs endereçáveis WS2812.

Utilizar resistores de pull-up internos nos botões de acionamento.
Desenvolver um projeto funcional que combine hardware e software.

## Componentes Utilizados

Matriz 5x5 de LEDs WS2812 (conectada à GPIO 7).

LED RGB (pinos conectados às GPIOs 11, 12 e 13).

Botão A (conectado à GPIO 5).

Botão B (conectado à GPIO 6).

## Funcionalidades

LED Vermelho Piscando: O LED vermelho do LED RGB deve piscar continuamente 5 vezes por segundo.

Botão A: Incrementa o número exibido na matriz de LEDs cada vez que for pressionado.

Botão B: Decrementa o número exibido na matriz de LEDs cada vez que for pressionado.

Exibição de Números: Os LEDs WS2812 são usados para criar efeitos visuais representando números de 0 a 9 em formato fixo ou criativo.

## Requisitos Técnicos

Uso de interrupções: Toda funcionalidade dos botões é implementada usando interrupções (IRQ).

Debouncing: O tratamento do "bouncing" dos botões foi implementado via software.

Controle de LEDs: Demonstra o uso de LEDs comuns e LEDs WS2812.

Organização do código: O código está bem estruturado e comentado para facilitar o entendimento.
