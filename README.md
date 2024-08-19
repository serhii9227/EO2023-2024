# Identify key factors which had impact on result of Edmonton Oilers in season 2023-2024

## Factors:
- Factor of home arena. Make analyze wins/loss at home and away
- Coach factor. On 12/11/2023 coach was changed. Compare result until and after change of coach
- Factor of key players. Make analyze how personal statistics of key players had impact on result of each game.
- Goaltender factor. Identify what goaltender was more successful.
- Defender factor. Identify best defender by +/-  statistics.

  ## Factor of home arena:
![1](https://github.com/user-attachments/assets/ba00d94a-281a-4be1-9358-1cf26237e1b2)
![3](https://github.com/user-attachments/assets/2768c334-fab1-429b-8630-8bbfb5fe1c2e)

Here percantage of home wins and home score goals is a bit more than away and percantage of home losses and home conceded goals is less respectively.

## Coach factor:
![4](https://github.com/user-attachments/assets/7fd519ce-20b6-4c63-b35a-f121994d32b7)

Percantage of wins after coach replacement is increased rapidly.

## Key players factor
Graph of  scorepoints fot all forwards:
![5](https://github.com/user-attachments/assets/9d776a2c-9c77-457e-882d-3bab46da0a4f)

From graph we can highlite 4 forwards with the highesr score statistics: McDavid, Draisaitl, Nugent-Hopkins, Hyman
Let's take a look these players separatly.

![6](https://github.com/user-attachments/assets/97d16d83-52f8-4ce1-a5e4-e56b024dc3eb)

![7](https://github.com/user-attachments/assets/aa59204d-80e6-4258-afa7-16d53de7660b)

![8](https://github.com/user-attachments/assets/eb50b5e3-d4c2-4164-8b14-ebd5db5c2636)

![9](https://github.com/user-attachments/assets/af227e4d-0e3f-4d7a-a8dd-9330ffb2f291)

And create graph statistics for these 4 players together:

![11](https://github.com/user-attachments/assets/c39c6141-0d6b-4e92-92d1-4e3f1d76302b)

We can make conclusion that if 1 of these playear score 2 or more points games with probability of 87% will be won.

## Conclusion:
- factor od home arena had not a key impact
- factor of coach replacement was important in season 2023-2024
- factor of key player. If Hyman, Nugent-Hopkins, Draisaitl or Mcdavid had a "good mood" game with 87% of probability will be successful


 ## Sources:
 - https://api-web.nhle.com/v1/score/{date}
 - https://api-web.nhle.com/v1/club-schedule-season/EDM/20232024
 - https://api-web.nhle.com/v1/roster/EDM/20232024

## DataLab:
https://www.datacamp.com/datalab/w/5657e5a9-71c2-403b-a0b4-64d20630fb67/edit

## Streamlit (ongoing):
https://da-26-06-24-eo-statistics.streamlit.app/

## Future steps:
- Continue exploration with last 2 factors
- Finish streamlit app
- Create model in order to predict upcoming season


