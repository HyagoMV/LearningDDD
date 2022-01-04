# Domain Services
- Camada: `Domain`
- Use-se os `Domain Services` quando colocar a  lógica de negócios dentro de uma `Entity` quebraria o encapsulamento `Entity` fazendo que `Entity` soubesse coisas que não deveria saber
-  Ex: Um certa Lógica de Negócios que manipulas diversa `Entities` distintas para alcaçar um resultado

- **Contém lógica de domínio** que não se encaxa a um `Entity` ou a um `Value Object`



- São classes sem estado que usam `Entities` ou a um `Value Objects`

- Usam as `Factories`
