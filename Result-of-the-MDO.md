# Result of the MDO
13 variables are simulated and compared in a descending order, ranking from the highest-score configuration design to least-score configuration design. The number of cases compared depends on user input. 
The 13 variables are: Total score, wingspan, no. of cargo pucks, no. of passengers ducks, no. of laps in mission 2, no. of laps in mission 3, battery capacity choice, banner length, ground mission time, mission 2 aircraft mass, mission 3 aircraft mass, aspect ratio of the wingspan, and aspect ratio of the banner.

Example as shown below:
<p align="center">
  <img src="https://github.com/Leilazehui/Multidisciplinary-Optimization-Framework-for-Aeronautics/blob/main/Example%20of%20aircraft%20configuration%20case.png" width=30%  />
<p/>
  
## Abbreviations
#### The “Bulk Group”
- Green colour corresponded to score cases where number of passengers more than 33 and number of cargoes more than 11 were chosen to be the amount of payload carried in Mission 2.
#### The “Light Group”
- Orange triangles corresponded to score cases which 3 passengers and 1 cargo was chosen to be carried on the aircraft in Mission 2.
#### "Other Top cases"
- The rest of the combinations of payloads carried in Mission 2.


## Graph Illustration of MDO
Out of the 13 variables, comparison was taken as the ratio of the total score and the aircraft mass, since the size of the aircraft determines the time taken for manufacturing, and the battery and motor selection, and banner mechanism design. 

Since bulk groups were the highest score cases, the first prototype adopted 48 Passengers and 16 cargoes. Through examination after manufacturing and testing process, the light group was selected as the final aircraft design as it took the least time to manufacture and flew faster than other design cases, while the score deviation is mild compared to the bulk group, with a difference of 0.08.

<p align="center">
  <img src="https://github.com/Leilazehui/Multidisciplinary-Optimization-Framework-for-AIAA-DBF-2026-Mission-Scoring/blob/main/top100case.png" width=45%  />
<p/>


