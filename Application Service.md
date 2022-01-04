# Application Service
- Camada: `Application`
- **Não contém lógica de domínio**
- São classes sem estado que usam `Entities` ou a um `Value Objects`

- Transforma menssagem vindas do mundo exteriror para um formato compreensível a `Entity`,
- Invocar os métodos necessários da `Entity` e
- Interpretar a decisão tomada pela `Entity`
