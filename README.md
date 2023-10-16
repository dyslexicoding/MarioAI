# MarioAI
Using AI to beat a game

using jupitor notebook

![Mario](https://user-images.githubusercontent.com/2184469/40949613-7542733a-6834-11e8-895b-ce1cc3af9dbb.gif)

## The model 
the system was run on python 3.8 to avoid any issues with the libraries used, and also to avoid and integer overflow on the model prosses

## The game

runs version of mario that the AI/ML model learns. the game is a modified version of the original mario game, and it is called `gym-super-mario-bros`

env

[OpenAI Gym](https://github.com/openai/gym) environment for
Super Mario Bros. & Super Mario Bros. 2 (Lost Levels) on The Nintendo
Entertainment System (NES) using
[the nes-py emulator](https://github.com/Kautenja/nes-py).

main iuse ran into was gym was oporated by open-ai but discontinued and gym became gymnasium but the mario game was not ported over to the new gymnasium. 
lot more errors occuring. 

Next project i will do a one starting from more bare bones aproch I could do little to alter the rewards for the game without fully understanding the inerworkings

| Environment                     | Game | ROM           | Screenshot |
|:--------------------------------|:-----|:--------------|:-----------|
| `SuperMarioBros-v0`             | SMB  | standard      | ![][v0]    |

[v0]: https://user-images.githubusercontent.com/2184469/40948820-3d15e5c2-6830-11e8-81d4-ecfaffee0a14.png

was the enviroment used


## Citation


```tex
@misc{gym-super-mario-bros,
  author = {Christian Kauten},
  howpublished = {GitHub},
  title = {{S}uper {M}ario {B}ros for {O}pen{AI} {G}ym},
  URL = {https://github.com/Kautenja/gym-super-mario-bros},
  year = {2018},
}
```
