``` mermaid
flowchart TD
    subgraph Modelo_OSI
        A1[Aplicação]
        A2[Apresentação]
        A3[Sessão]
        A4[Transporte]
        A5[Rede]
        A6[Enlace de Dados]
        A7[Física]
    end

    subgraph Modelo_TCP/IP
        B1[Aplicação]
        B2[Transporte]
        B3[Internet]
        B4[Acesso à Rede]
    end

    A1 --> B1
    A2 --> B1
    A3 --> B1
    A4 --> B2
    A5 --> B3
    A6 --> B4
    A7 --> B4
```