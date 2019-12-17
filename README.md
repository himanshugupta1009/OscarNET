OscarNET: Garbage Detection and Extraction

The world is currently in the grips of a trash crisis. It is estimated that the a person produces approximately 234lb (106.2kg) of plastic waste per annually. The enormous amount of waste produced does not get discarded properly and ends up on the roadside, or in parks and wildlife areas. Our goal is to address this issue by developing an autonomous system that classifies and then removes trash from public spaces. We implemented a Mask R-CNN based model to detect garbage in images and create segments over it. We use the transfer learning approach to reduce training time by using a model trained on the famous COCO dataset. In conjunction, we use a pre-existing image depth estimator to estimate the depth and aid autonomous navigation. The current implementation sends Sparki bot to extract the garbage but this can be extended on any bot. 

Our model OscarNet, named after the garbage loving character from the show Sesame Street, was trained on the dataset that we curated.

![Team member Hunter posing with garbage for OscarNET]()
