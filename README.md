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
 
![image](https://github.com/user-attachments/assets/9a3adff1-9b0c-480b-a6a7-7548a2f7c45e)


A seguir, o layout também foi modelado em 3D, construindo a PCB anteriormente, para uma visualização mais precisa do posicionamento dos componentes e das trilhas.

### 📌 Etapas da Construção da PCB:
1. Conversão do esquemático atualizado para layout de PCB.
2. Posicionamento e roteamento dos componentes.
3. Geração do layout 3D.
4. Fabricação e montagem do circuito.

## PCB Constrúido
![image](https://github.com/user-attachments/assets/6b5a3065-5f44-4398-9591-0e45df2b99d0)

## Layout em 3D
![image](https://github.com/user-attachments/assets/5110a3ed-d2bc-4404-89a9-52f1de8eec1a) ![image](https://github.com/user-attachments/assets/184638af-cd8f-4754-8452-673e32880c2b)

## 🔧 Ferramentas Utilizadas

- **PROTHEUS PROFESSIONAL 8**: Desenvolvimento do esquemático, PCB e 3D.
- **Protoboard e Componentes Eletrônicos**: Montagem física do circuito.

## 📖 Como Funciona

1. A tomada fornece corrente alternada (CA) ao transformador.
2. O transformador reduz a tensão para um nível seguro.
3. A ponte retificadora converte CA em corrente contínua pulsante.
4. Capacitores filtram a tensão, reduzindo oscilações.
5. O regulador 7805 estabiliza a saída em 5V.
6. O LED acende, indicando que o circuito funciona corretamente.

## 📌 Conclusão

Este projeto demonstrou a conversão de corrente alternada em contínua de forma eficiente, sendo uma base importante para circuitos de fontes de alimentação reguladas.
