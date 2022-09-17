# Metodologia utilizada na mentoria

## Modelo de aprendizagem 70:20:10

Busca dentro da mentorial criar uma estratégia de semestral de estudo e prática onde o tempo deve, se possível, ser distribuído em:

* 70% a partir de experiências próprias e vivência profissional do cotidiano.
* 20% a partir de aprendizado informal e interações.
* 10% pelo aprendizado formal.

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
