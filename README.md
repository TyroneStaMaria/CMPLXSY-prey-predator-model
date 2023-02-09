# Cheetah-antelope prey-predator system
We are modeling the prey-predator 
system between a cheetah and an 
antelope. Antelopes usually live in plains, 
grasslands and savannahs and we will 
choose the savannah as the environment 
of our prey-predator system.

## Behaviors

### General (prey and predator)
- Movement is random
- Every move expends 1 energy
- Reproduction expends 50% of the agent's energy
- Dies when energy reaches 0


### Antelope (Prey)
- Source of food is grass
- Gains a fixed amount of energy when eating  
- Dies when eaten by cheetah


### Cheetah (Predator)
- Source of food is antelope
- Gains 50% of the energy of the eaten prey

### Grass (Food)
- Gets eaten by antelope
- Has a random regrow time 