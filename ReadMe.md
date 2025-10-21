🤖 AutoBots — Robô Seguidor de Linha

Projeto acadêmico desenvolvido para a disciplina de Projeto Integrador do curso de Ciência da Computação.
O AutoBots é um robô seguidor de linha autônomo construído com Arduino Uno R3, capaz de detectar e seguir trajetórias por meio de sensores infravermelhos. O projeto integra conceitos de robótica, automação e controle, explorando o potencial da eletrônica embarcada e da programação em C/C++ para microcontroladores.

🧠 Objetivo do Projeto

O objetivo principal é desenvolver um robô móvel capaz de seguir uma linha preta sobre uma superfície branca, aplicando técnicas de controle e leitura de sensores.
O projeto também visa aprimorar habilidades em:

Programação embarcada com Arduino;

Montagem e integração de circuitos eletrônicos;

Trabalho em equipe e documentação técnica;

Desenvolvimento de um produto funcional para competições de robótica.

⚙️ Componentes Utilizados
🪛 Hardware

01 Placa Arduino Uno R3 (ATmega328P)

01 Módulo Ponte H L298N (controle dos motores)

02 Motores DC com engrenagens

02 Rodas + 01 Roda boba

01 Kit Chassi 2WD para robô

01 Sensor Ultrassônico HC-SR04

04 Módulos sensores infravermelhos (seguidor de linha)

01 Suporte para pilhas AA

01 Cabo 9V

01 Mini Protoboard

Jumpers macho/macho e macho/fêmea

🧩 Microcontrolador

Modelo: ATmega328P

Tensão de operação: 5V

Clock: 16 MHz

Memória Flash: 32 KB

SRAM: 2 KB

EEPROM: 1 KB

🧭 Funcionamento

O robô utiliza módulos sensores infravermelhos para detectar a linha no chão.
Esses sensores enviam sinais ao Arduino, que processa os dados e decide como os motores DC devem reagir — ajustando a direção para manter o robô sobre a linha.

O módulo Ponte H L298N é responsável por controlar a rotação dos motores, permitindo movimentos para frente, curvas à esquerda/direita e paradas suaves.
O sensor ultrassônico HC-SR04 complementa o sistema, detectando obstáculos à frente e evitando colisões.

🧰 Tecnologias e Ferramentas

Arduino IDE para desenvolvimento do firmware

C/C++ como linguagem de programação

GitHub para versionamento e colaboração

HTML + CSS + Bootstrap para o site do projeto e documentação

TinkerCAD (opcional) para simulação de circuitos

🧑‍💻 Equipe

Carlos Eduardo

Guilherme	

Gustavo Teixeira 	

Lucas

Victor Sardinha	

Professor Orientador	Eduardo Furlan
