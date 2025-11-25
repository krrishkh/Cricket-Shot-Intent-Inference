# Cricket Shot Intent Inference 

## Objective 
  `` • To classify batsman shots into energy levels from clips using pose landmarks, while building a modular framework ``
  
  ``• To develop a system to quantify batsman’s energy, intent by analyzing body motion, aiding bowlers in strategies``


## Pre processing 

**1. Match Recording**
> Recorded 120+ hrs of cricket match and Used cvlib-based person detection algorithm to extract 2000+ relavant clips from raw video input

https://github.com/user-attachments/assets/4b013392-c31d-460b-aa27-8ee53f77055f


**2. Batsman Position Detection**

> For tracking of batsman from clip we used YOLOv11

https://github.com/user-attachments/assets/d7bbdb6c-880d-4c13-bf4c-a96f1ca274f7

https://github.com/user-attachments/assets/645fecc4-e1b6-45e0-ad39-5740c0112296


**3. Used MediaPipe Pose to extract 33 joint keypoints, forming temporal sequences**

[test_vid_9.csv](https://github.com/user-attachments/files/23746054/test_vid_9.csv)


<img width="250" height="300" alt="1" src="https://github.com/user-attachments/assets/7c85f672-938d-4916-ab28-33d56cc48454" />
<img width="250" height="300" alt="36" src="https://github.com/user-attachments/assets/ace033d0-d0c3-46ca-b8d3-29b954f255ba" />
<img width="250" height="300" alt="51" src="https://github.com/user-attachments/assets/65846c6c-cb8f-43b7-82ba-0e0eff1939d7" />


## Commentary

> Used **BeatifulSoup** and **Selenium** for extarction of commentary of a match

<img width="600" height="350" alt="image" src="https://github.com/user-attachments/assets/cab56145-a5f5-421b-bc92-8adf52b4a7d0" />

[cricket_scores149.xlsx](https://github.com/user-attachments/files/23746498/cricket_scores149.xlsx)


 ## Results 

 <img width="300" height="300" alt="Kohli_distribution_final_high" src="https://github.com/user-attachments/assets/d88408bd-6fe9-4113-924f-e02242b4792e" />
 
 <img width="300" height="300" alt="Kohli_distribution_final_low" src="https://github.com/user-attachments/assets/a97fd2f8-cec3-4e50-bf9a-d79dfcad929f" />

