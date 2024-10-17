# Creating Four Affective Virtual Environments in VR
This project describes the work undertaken in my dissertation, which focused on creating four affective environments each designed to induce a specific emotion. I received a mark of 80% for this work. The Unity environments developed during this project, in collaboration with another student from the University of Bath, are currently being used within the Human-Computer Interaction research group at the University of Bath. The overall development exceeded 128 GB. So, when this research becomes public and the development open-source, I will provide a link to that repository here for refernece.

## Project Overview
Virtual reality (VR) has been shown to elicit intense emotion in users. However, due to the relative novelty of the technology, developers are still unsure how to best design virtual environments (VEs) to maximize emotional engagement and intensity. This project aimed to identify specific design choices that can evoke four different target emotions in VR: happiness, calmness, sadness, and fear. A second goal was to achieve this with minimal variation between the VEs, ensuring usabilitity for academic research, where it is essential to minimize confounding variables. With this in mind, we designed each VE to be as similar as possible, systematically altering specific elements in each, such as lighting, to influence user emotion. 

## Results & Analysis
In all, the four following virtual environments were developed, where we manipulated sound design, lighting, colour scheme, and environmental objects (flowers, trees) of the same VE of a realistic bedroom. For instance, the VE designed to elicit fear was filled with bloodied handprints and stains across the room. It was also very dark in this VE, and the sound of an floor creaking could be heard in the background. 

<p align="center">
  <img width="1074" alt="Screenshot 2024-10-17 at 00 52 28" src="https://github.com/user-attachments/assets/4ce7c50c-b399-4c9f-85d6-75d722017801">
</p>

After creating each VE, 20 participants experienced each VE for 2 minutes, after which they self-reported their level of ten different emotions in each VE by answering direct questions (e.g., 'How excited did you feel?', rated on a scale of 0-10). Box plots and scatter plots where then used to 1) compare affective ratings between each VE for the four emotions designed to be induced (e.g., comparing happiness ratings across all four VEs) shown using scatter plots, and 2) compare affective ratings within each VE for each possible affective rating, shown using box-plots. In each case, a repeated-measures ANOVA was used to anaylse the effect of the VE the participant experienced on their self-reported affective ratings. The plots used in this analysis are shown below. You will also note the measures of emotional arousal and valence, where arousal here refers to the intensity of the emotion felt and valence refers to the positivity of this emotion.  

<p align="center">
   <img width="1096" alt="Screenshot 2024-10-17 at 08 28 19" src="https://github.com/user-attachments/assets/09b4310c-573f-4f10-a03c-0bda34c2c257">
</p>

<p align="center">
   <img width="1551" alt="Screenshot 2024-10-17 at 08 40 53" src="https://github.com/user-attachments/assets/d6cd1fed-f2b4-4779-adfe-b360e497fa5f">
</p>

From these results, it was clear that each VE successfully elicited its target emotion at intense levels, but these emotions were not distinct within each environment. That is, We explore reasons why in the dissertation. For instance, emotions, such as happiness and calmness, often co-occur and so it is perhaps not surprising that the Happy VE, and Calm VE elicited high levels of both calmness and happiness. We suggest future direction to developers as to how to design virtual environments to best elicit desired emotions based on these results.

## Future Work
Unmentioned above was a secondary aim of this dissertation, which was that these environments were built in mind with the intent to use them in the study of embodiment in VR. The sense of embodiment broadly refers to the feeling of owning our body, and it has been shown that we can actually feel a sense of embodiment towards external objects, including our avatars in VR. However, little is known about the interplay between emotion and embodiment, and as such this work was developed for future studies to be able to explore this relationship thoroughly in a controlled, systematic manner. 

## Technologies
