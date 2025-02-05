OscarNET: Garbage Detection and Extraction

The world is currently in the grips of a trash crisis. It is estimated that the a person produces approximately 234lb (106.2kg) of plastic waste per annually. The enormous amount of waste produced does not get discarded properly and ends up on the roadside, or in parks and wildlife areas. Our goal is to address this issue by developing an autonomous system that classifies and then removes trash from public spaces. We implemented a Mask R-CNN based model to detect garbage in images and create segments over it. We use the transfer learning approach to reduce training time by using a model trained on the famous COCO dataset. In conjunction, we use a pre-existing image depth estimator to estimate the depth and aid autonomous navigation. The current implementation sends Sparki bot to extract the garbage but this can be extended on any bot. 

Our model OscarNet, named after the garbage loving character from the show Sesame Street, was trained on the dataset that we curated.

Figure 1: Detecting garbage in a park
![OscarNET at work](https://github.com/himanshugupta1009/OscarNET/blob/master/trash_can_in_park.jpg)

Figure 2: Team meber Hunter posing with garbage for OscarNET
![Team member Hunter posing with garbage for OscarNET](https://github.com/himanshugupta1009/OscarNET/blob/master/team_member_hunter_posing.png)

Figure 3: Garbage detection during our experimental setup for dispatching Sparki bot and extracting garbage
![Team member Hunter posing with garbage for OscarNET](https://github.com/himanshugupta1009/OscarNET/blob/master/packet_of_chips_on_table.jpg)

Figure 4: Detecting garbage bags on street
![Team member Hunter posing with garbage for OscarNET](https://github.com/himanshugupta1009/OscarNET/blob/master/garbage_bags_on_street.jpg)
