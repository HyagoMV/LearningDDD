# DDD
- O desing do sistema é guiado pelo domínio
- 

## Complexidade do Software
### Complexidade da Solução Técnica
- Exemplo: 
    - Usar ou não microserviçoes
        - Complexidade de Operação
    - Usar ou não monolitos
        - Complexidade para mander o baixo acoplamento
    - Usar ou não determinado framework
    - Usar ou não determinado linguagem
    - Qual banco de dados usar
- Escolhe-se o nível de complexidade da solução técnica

### omplexidade do Legado
- Manter o sistema legado funcionando
- Escolhe-se o nível de complexidade do legado

### Complexidade do Domínio (Obrigatória)
- Problema que se está querendo resolver
    - Exemplo: Hospital
    - Exemplo: Transportadora
- Esse nível de complexidade é imposta pela domínio

# Domínio
- O domínio é atividade comercial realizado pela empresa 
- O domínio contém o problema que ser quer resolver

## Linguagem Unipresente


## Entidades
- Geramente são substântivos que surgiram na `Linguagem Unipresente`
- Os dados de uma entidade são MUTÁVEIS ao longo do tempo
- A identificão de uma entidade é feita através de um ID, um dado IMUTÁVEL
- A comparação entre duas entidades e feita excluivamente pelo ID

## Objetos de Valor
- Geramente são substântivos que surgiram na `Linguagem Unipresente`
- Os dados de uma `objeto de valor` são IMUTÁVEIS ao longo do tempo
- A identifição de uma `objeto de valor` é feita através da(s) propriedades(es) armazenado(s)
- A comparação entre dois `objeto de valor` e feita através do(s) valores(es) armazenado(s)

## Agregados
- 