# What 's Crowd People? 
Crowd people, also known as crowds, are a common subject of interest in computer vision research. They are a complex and dynamic visual phenomenon, and understanding their behavior and movements is important for a variety of applications, such as crowd management, surveillance, and security.

Computer vision techniques can be used to automatically detect, track, and analyze crowd people in real-time, providing valuable information to decision-makers and stakeholders. For example, crowd density and movement patterns can be analyzed to optimize crowd flow and prevent overcrowding in public spaces and events. Crowd behavior can also be monitored to detect potentially dangerous situations, such as stampedes or fights, and alert authorities.

In addition to real-time applications, computer vision can also be used to analyze crowd behavior in video recordings, providing insights into crowd dynamics and social interactions. This can be useful for understanding the behavior of crowds in different scenarios, such as protests, concerts, or sports events.

Overall, understanding crowd behavior is important for a wide range of applications, and computer vision plays a crucial role in enabling automated analysis and decision-making in these scenarios.

## What I did in this project?
u can find the dataset which is called frames and label 
- I used YOLO V7 in this project
- I used Mall Dataset (u can find it in kaggle )
- applying yolo in this dataset to make object detection then i filter that to detect Person only , then i put them in Dataframe to be able to compare between the pred and orginal count in images
- ![download (1)](https://github.com/omarahmed19992/YOLO4Crowd-People/assets/60344203/a58fcdfc-20d5-4c57-beb5-415d0d4f358f)
  <br/><br/><br/><br/>
- ![download (2)](https://github.com/omarahmed19992/YOLO4Crowd-People/assets/60344203/deee7882-67d6-49b2-ba50-8ea36ad468f5)
  <br/><br/>
-  mean absolute error is equal 6.0035
-  U also can do the same process in video
-  U can use superVision with YOLO to work with only class / object or count the number of this object in the area 
