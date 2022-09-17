# Metodologia utilizada na mentoria

## Modelo de aprendizagem 70:20:10

(Documentar)

## Processo

## Entrada e Definição

```mermaid
flowchart TD

    inicio([Início]) --> avaliar
    avaliar[Avaliar proposta de mentoria] --> termos
    termos{Concorda com o termos?} -->|Não| fimTermos[Fim]
    termos -->|Sim| perfil
    perfil[Preencher perfil] --> areas
    
    areas[[Mentor propõe áreas de TI de acordo com os potenciais]] --> escolherArea
    escolherArea[Escolher uma área] --> objetivos
    
    objetivos[Definir objetivos] --> ciclo
    ciclo[Planejar ciclo] --> atividades
    atividades[Acompanhar atividades] --> oportunidades
    oportunidades[Buscar oportunidades] --> contratado
        
    contratado{Foi contratado?} --> |Não| retrospectiva
    retrospectiva(Retrospectiva) --> ciclo
    
    contratado --> |Sim| mentor
    mentor{Quer se tornar um mentor?} -->|Não| fimFeliz
    mentor -->|Sim| treinar
    
    treinar([Treinar para ser mentor])
    fimFeliz[Fim]

```
