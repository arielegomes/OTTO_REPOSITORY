# OTTO_REPOSITORY
# 🤖 Automação e Robótica Bípede: Aplicação do Otto DIY em Canteiro de Obras
**Universidade do Estado da Bahia (UNEB)**  
**Disciplina:** **Computação Aplicada à Engenharia**
**Orientador:** **Prof. Robson Marinho**                                                                 
**Discentes:** Ariele Gomes, Luis Gustavo, Micaele Pereira e Raiane Borges
---

## 📝 1. Introdução
Este projeto apresenta o desenvolvimento, montagem e modelagem do robô bípede Otto DIY. O trabalho busca aplicar conhecimentos de programação, mecânica e sistemas de controle para solucionar problemas reais no cenário de Canteiro de Obras, explorando o potencial da robótica móvel na assistência a vistorias e automação de processos produtivos.

O projeto foi viabilizado através do suporte técnico e da infraestrutura do Laboratório InovaMech, que forneceu o ambiente necessário para a prototipagem, testes de sensores e montagem dos componentes eletrônicos.

## 📊 2. Modelagem com Redes de Petri
Conforme as diretrizes acadêmicas, a modelagem foi realizada em dois níveis de complexidade:
* **Sistema Atual:** Representação do fluxo de eventos para locomoção, desvio de obstáculos e controle via interface Bluetooth.
* **Sistema de Evolução (Canteiro de Obras):** Modelo teórico para integração de sensores de segurança (NR-33) e monitoramento de insumos.

## ⚙️ 3. Implementação e Hardware
* **Microcontrolador:** Arduino Nano (ATmega328P).
* **Atuadores:** 4 servomotores SG90 (articulados para marcha bípede).
* **Sensoriamento:** Sensor ultrassônico HC-SR04 (Mapeamento de proximidade).
* **Comunicação:** Módulo Bluetooth HC-05 (Telemetria Serial).
* **Software:** Firmware em C++ via **Arduino IDE**, com modificações documentadas sobre a biblioteca oficial.

## 📂 4. Estrutura do Repositório
* `📂 Codigo (.ino) com a **explicitação das modificações** realizadas.
* `📂 documentacao/`: Relatório técnico e apresentação em PDF (LaTeX)
* `📂 links/ : Do overleaf e Drive
* `📂  modelagem/`: Arquivos das Redes de Petri (Nível 1 e 2).
* `📂 processo-montagem/`: Arquivos (Fotos e Videos) do processo de montagem do robô


## 🚀 5. Proposta de Evolução para o Canteiro

Diferente do modelo bípede atual, a evolução foca em transformar o Otto em um *assistente de transporte e inspeção* com as seguintes características:

* *Sistema Híbrido:* Transição para rodas motorizadas (Motores DC + Driver L298N) para maior velocidade e estabilidade em superfícies de obra.
* *Função de Monitoramento:* Detecção autônoma de distância de paredes para conferência de medidas de projeto.
* *Transporte:* Implementação de uma caixa de carga para deslocamento de pequenas ferramentas e componentes leves.
---
> **Status:** Requisito avaliativo para 13/05 às 15:00.  

