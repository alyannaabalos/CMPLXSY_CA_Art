# Async Learning Task: Cellular Automata

## Artwork 1: Elementary Cellular Automata Rule 99

![Screen Shot 2023-01-28 at 9 16 23 PM](https://user-images.githubusercontent.com/88019519/215270326-e0840d99-e60f-48c9-8851-276c311c9562.png)

The artwork (generated in NetLogo) exhibits Rule 99 of Elementary Cellular Automata, the simplest class of 1D cellular automata. A possible current state of the left, center and right cell is taken from the configuration order 111, 110, 101,... 000, and the resulting state of the next cell in the evolution is defined by a digit from the binary representation of the integer 99 (1100011) that corresponds to the given state. The figure below illustrates the given rule:

![image](https://user-images.githubusercontent.com/88019519/215271125-a48ffd10-77ce-40c8-8159-b4998b59561c.png)

## Artwork 2: Elementary Cellular Automata Rule 150

![ca rule 150](https://user-images.githubusercontent.com/92851199/215271903-b9891b32-5267-45ae-bac6-45a6f1856d40.jpg)

The artwork (generated in NetLogo) exhibits Rule 150 of Elementary Cellular Automata. Starting with a single black cell, successive generations are given by interpreting the numbers 1, 7, 21, 107, 273, 1911, 5189, ... (OEIS A038184) in binary, namely 1, 111, 10101, 1101011, 100010001, ... (OEIS A118110). The figure below illustrates the given rule:

![rule 150](https://user-images.githubusercontent.com/92851199/215271991-4c540921-1ed4-47b9-a709-17160ad3f358.jpg)

## Artwork 3: Elementary Cellular Automata Rule 135

![image](https://user-images.githubusercontent.com/104493864/215320355-0c1a652a-f233-4a7b-bce1-0a7ff6f4907a.png)

The artwork (generated in NetLogo) exhibits Rule 130 of Elementary Cellular Automata. It begins with a singular colored cell, which then generates rows with multiple patches each dependent on its neighbors. It follows the boolean rule of ![image](https://user-images.githubusercontent.com/104493864/215320476-a2106d3a-07db-4ff5-b9a5-a002eb95d73a.png)

Its pattern can also be illustrated through:
![image](https://user-images.githubusercontent.com/104493864/215320507-9ec08300-661d-4e68-ada7-857e5ecd8adc.png)

## Artwork 4: Sunflower Model

![](https://github.com/alyannaabalos/CMPLXSY_CA_Art/blob/main/Sunflower%20Model/Sunflower%20Model.gif)

This model demonstrates how the spiral patterns found in various parts of plants, such as the seeds, petals, and branches, form naturally during the growth of the flower.

To recreate the art, set the following rules to the corresponding values:
`NUM-COLORS` = 14,
`STEP-SIZE` = 0.011,
`TURN-INCREMENT` = 0.617

# References
http://atlas.wolfram.com/01/01/135/01_01_1_135.html#01_01_2_135
* [NetLogo Models Library](https://ccl.northwestern.edu/netlogo/models/)
