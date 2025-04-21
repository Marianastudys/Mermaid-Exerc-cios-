``` mermaid
flowchart TD
B{Está chovendo}
B -->|Sim| C[Leva guarda-chuva]
B -->|Não| D[Olha previsão do tempo]
D --> E{Previsão do  tempo é de chuva?}
E -->|Sim| C
E -->|Não| F[Não Leva]
```
//Crie um fluxograma para decidir se uma pessoa deve levar guarda-chuva:

Está chovendo?

Sim: Leva guarda-chuva

Não: Olha previsão do tempo

Se previsão for de chuva: Leva guarda-chuva

Senão: Não leva