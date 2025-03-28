# Portfólio - Sistemas Embarcados 🔌💡

Este repositório contém um projeto desenvolvido na disciplina de **Sistemas Embarcados** do curso de **Sistemas de Informação (5º período)**. O projeto consiste na criação de um **circuito retificador de onda completa**, projetado na plataforma **PROTHEUS PROFESSIONAL 8** e posteriormente montado em uma **protoboard** para testes práticos.

## 📜 Descrição do Projeto

O objetivo do projeto foi converter a corrente alternada (CA) proveniente de uma tomada em corrente contínua (CC) para alimentar um LED. O circuito inclui:

- **Transformador**: Reduz a tensão da rede elétrica.
- **Ponte retificadora (BR1)**: Converte CA em CC.
- **Capacitores (C1, C2, C3)**: Filtram a tensão retificada.
- **Regulador 7805 (U1)**: Estabiliza a tensão em 5V.
- **Resistor (R1) e LED (D1)**: Indicam a saída estabilizada.

![image](https://github.com/user-attachments/assets/ef43b1cb-7b3c-413c-a6bc-0227cd1480f1)
*Imagem do Circuito em formato Esquemático*


## 📷 Fotos da Montagem na Protoboard

Aqui estão as fotos das medições realizadas na prática:

1. **Medição da tensão alternada (AC) na saída do transformador:**
Nesta foto, utilizamos um multímetro para verificar a tensão de saída do transformador antes da retificação. O valor esperado era em torno de 12 volts AC, confirmando que o transformador está funcionando corretamente.

![IMG_0162 (1)](https://github.com/user-attachments/assets/a5fd5ab6-f41a-467c-b58b-60c47bb2c0aa)

3. **Medição da tensão na saída do regulador 7805 (U1):**
Nesta foto, medimos a tensão de saída do regulador de tensão. O valor esperado era de aproximadamente 5V DC, garantindo que o circuito está fornecendo uma tensão estável para alimentar o LED.

![IMG_0166 (1)](https://github.com/user-attachments/assets/86ddec29-04cb-47c9-a17c-7b94a81adc35)

## 🛠 Desenvolvimento do PCB e Layout 3D

Com base no novo esquemático, o circuito foi projetado em **PCB** utilizando o **PROTHEUS 8**. Uma alteração importante foi a remoção do transformador e da tomada, substituídos por novos componentes:

- **Componente Conn-Sil2(J1)**: Este componente foi integrado à ponte retificadora (BR1), proporcionando a conexão necessária para o processo de retificação sem o uso da tomada e transformador.
- **Componente Sil-100-02(J2)**: Conectado ao **capacitor C3**, esse componente desempenha um papel essencial no filtro da tensão retificada, melhorando a eficiência do processo de estabilização da tensão.

A seguir, o layout também foi modelado em 3D, construindo a PCB anteriormente, para uma visualização mais precisa do posicionamento dos componentes e das trilhas.

### 📌 Etapas da Construção da PCB:
1. Conversão do esquemático atualizado para layout de PCB.
2. Posicionamento e roteamento dos componentes.
3. Geração do layout 3D.
4. Fabricação e montagem do circuito.

## 🖨️ PCB
![image](https://github.com/user-attachments/assets/b237c372-57fb-4467-a83b-7fddf13672c0)


## 🖼️ Layout em 3D
![image](https://github.com/user-attachments/assets/5534b9d1-1b46-43de-a87f-bfafd8857008)
![image](https://github.com/user-attachments/assets/fb973fd2-5331-4eda-bdf0-154369dd68b2)


## 🔧 Ferramentas Utilizadas

- **PROTHEUS PROFESSIONAL 8**: Desenvolvimento do esquemático, PCB e 3D.
- **Protoboard e Componentes Eletrônicos**: Montagem física do circuito.

### 📖 Como Funciona

1. **Entrada de Corrente Alternada (CA)**: A corrente alternada (CA) é fornecida pela tomada e chega ao circuito.
2. **Transformador**: O transformador reduz a tensão da rede elétrica para um nível adequado para a retificação.
3. **Ponte Retificadora (BR1)**: A ponte retificadora converte a corrente alternada (CA) em corrente contínua pulsante.
4. **Filtragem**: Os capacitores **C1**, **C2** e **C3** filtram a tensão retificada, removendo oscilações e suavizando a corrente.
5. **Regulador de Tensão (7805)**: O regulador 7805 estabiliza a tensão de saída, mantendo-a constante em 5V DC.
6. **Saída para o LED**: O resistor (R1) e o LED (D1) indicam visualmente que a tensão foi estabilizada e o circuito está funcionando corretamente.

### 📌 Conclusão

Este projeto demonstrou a conversão de corrente alternada (CA) em corrente contínua (CC) de maneira eficiente e estável, utilizando componentes básicos de eletrônica. A integração de uma ponte retificadora, filtros capacitivos e um regulador de tensão permitiu criar uma fonte de alimentação regulada, que é essencial para alimentar circuitos sensíveis, como LEDs. Além disso, o uso de um novo esquemático, sem a necessidade de transformador e tomada, simplificou o circuito, tornando-o mais compacto e prático. Este projeto serve como uma base importante para o desenvolvimento de fontes de alimentação em sistemas embarcados.
