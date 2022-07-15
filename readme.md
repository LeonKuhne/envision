
## WHAT
Predict next frames using previous frames

## WHY
Train on particle simulations and zooms out to predict higher order systems

## HOW (ANN)
#### Learn (AI)
- all data has same resolution
- x,y resolution is same and fixed
#### Evolve (Genetics) "survival of the fitest"
- a fixed population of AI actors compete in rounds
- each actor has an independent neural net
- unsuccessfull actors may die
- successfull actors may duplicate
- less success causes higher mutation chance
#### Adapt (Society)
- continuing to learn while predicting
- use computed average results as expected
- currently theoretical

## WHERE
#### Training
1. learn: actors train and evaluate average success scores
2. evolve: actors adapt their neural nets
#### Running
1. adapt: actors train and evaluate average success scores using other actors
2. evolve: actors adapt their neural nets

## Domain Model
#### Nouns
- Actor, Round
#### Verbs
- Learn, Adapt, Evolve (die, duplicate, mutate)
