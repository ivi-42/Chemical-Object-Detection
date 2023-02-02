
This is a chemical_object_detection model trained to distiguish singular chemical reactions based on unique behaviours.

The chemical reactions are divided in 4 groups, that can be distiguished by:

Round shapes
Filaments
Round shapes + filament
Smoke Propagation

it tries to detect 
['oscillatingch', 'xlmetalpot', 'merall', 'unstableox']

Oscillating chemical reactions = oscillatingch

liquid metal explosive = xmetalpot

mercury and alluminium reactions = merall

unstable oxidizer = unstableox

I am using TF 2.10 as it's the latest build that supports GPU use

This is a work in progress, and I am utilizing my own machine that is not extremely powerful, when i'll have better equipment i'll update the results

This model is based out of SSD MobileNet V2 FPNLite 320x320, due to it's good compromise between speed and performance. It is a good model that I use to prototype
![tensf](https://user-images.githubusercontent.com/74068788/216372282-721d4cf3-fd27-4cb1-861e-3801b7daddf1.png)
![tensf2](https://user-images.githubusercontent.com/74068788/216372311-204af68e-6b06-465b-9d69-0f98d2b028ed.png)
![xmetalpot](https://user-images.githubusercontent.com/74068788/216372313-32f7082c-4723-41fb-b6be-2e4f9adc4c31.png)
![xmetalpot2](https://user-images.githubusercontent.com/74068788/216372315-46c3e8d9-caec-4dca-8a49-08f7946f74b8.png)
