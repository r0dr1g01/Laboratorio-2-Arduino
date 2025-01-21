# 🚦 Semáforo com Arduino

3 Leds com a função de um semáforo, a partir de uma placa Arduino UNO.

Este código faz um semáforo funcionar usando um Arduino e três LEDs (vermelho, amarelo e verde). Ele segue o mesmo padrão de um semáforo de rua: começa no vermelho, passa para o amarelo e depois para o verde, repetindo esse ciclo.

## 📜 Como Funciona?
1. O código inicializa e apaga todos os LEDs.
2. Ele faz um **teste**, piscando todos os LEDs três vezes.
3. O semáforo entra no ciclo normal:
   - 🔴 **Vermelho** acende por 5 segundos (carros param).
   - 🟡 **Amarelo** acende por 3 segundos (aviso de mudança).
   - 🟢 **Verde** acende por 10 segundos (carros passam).
   - O ciclo reinicia.

![image](https://github.com/user-attachments/assets/03e28a82-9871-4c5b-aa9a-74f37bc9ec5e)

## 📂 Docs  
O código-fonte pode ser acessado aqui:  
</> [Código](docs/Código)  
 


## 🔗 Simulação no Tinkercad
[Acesse aqui a simulação do semáforo no Tinkercad](https://www.tinkercad.com/things/kGEixmwBJ3y-semaforo?sharecode=YrhTA40F0SmOKw9J2PJ_9E9tMTLB_BBHsU-VEqxkv5w)

