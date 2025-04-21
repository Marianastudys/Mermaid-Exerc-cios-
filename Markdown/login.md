```mermaid
flowchart TD
A[Usuário] --> |Login| B[Entra com]
A[Usuário] --> |Senha| B[Entrar]
B --> C{Os dados estão corretos?}
C -->|Sim| D[redireciona para o painel]
D --> F[Fim]
C -->|Não| E[Exibir mensagem de erro]
E --> A
```
// Crie um fluxograma que represente o processo de login em um sistema:

Usuário insere login e senha

Verifica se os dados estão corretos

Se sim, redireciona para o painel

Se não, exibe mensagem de erro e retorna para o usuário
