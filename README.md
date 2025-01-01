<h1 align="center">
  <br />
  Affective VR
</h1>

The use of virtual reality (VR) for mood induction is well-documented, yet few have investigated the induction of a variety of different emotions in an ecologically valid manner in VR. This work, then, aimed to create four affective environments each designed to induce a specific emotion through as minimal changes as possible (colour, sound design, environmental objects) to allow for better use of affective VR in HCI research. 

This project discusses work carried out in my dissertation. The Unity assets used for development during this project can be found [here][1]. This research was undertaken in collaboration with another student from the University of Bath, and the development size exceeds 128GB. The environments are currently held in private repository owned by the University of Bath, and will be referenced when this repository becomes public. 

## Did I make you happy, sad, fearful, or calm? 
VR has been shown to elicit intense emotion in users. However, due to the relative novelty of the technology, developers are still unsure how to best design virtual environments (VEs) to maximize emotional engagement and intensity. Here, we look at specific design choices that can evoke four different target emotions in VR: happiness, calmness, sadness, and fear. As mentioned, a second primary goal was to achieve this with minimal variation between the VEs, ensuring usabilitity for academic research, where it is essential to minimize confounding variables. With this in mind, we designed each VE to be as similar as possible, systematically altering specific elements in each, such as lighting, to influence user emotion.

Overall, the four following virtual environments were developed. we manipulated sound design, lighting, color scheme, and environmental objects, such as flowers, and trees, within the same realistic bedroom VE. For instance, the VE designed to elicit fear was filled with bloodied handprints and stains across the room. It was also very dark, and the sound of a floor creaking could be heard in the background.

<p align="center">
  <img width="1074" alt="Screenshot 2024-10-17 at 00 52 28" src="https://github.com/user-attachments/assets/4ce7c50c-b399-4c9f-85d6-75d722017801">
</p>

After creating each VE, 20 participants experienced each VE for 1 minute 30 seconds, after which they self-reported their levels of ten different emotions by answering direct questions on QuestionPro, such as 'How excited did you feel?', rated on a scale of 0-10. Box plots and scatter plots were then used to: 
1) Compare affective ratings between each VE for the four emotions designed to be induced (e.g., comparing happiness ratings across all four VEs), shown using scatter plots.
2) Compare affective ratings within each VE for all possible emotions, shown using box plots.

In each case, a repeated-measures ANOVA was used to analyze the effect of the VE on participants' self-reported affective ratings. The plots used in this analysis are shown below. You will also note the measures of arousal and valence, where arousal refers to the intensity of the emotion felt, and valence refers to the positivity of this emotion  

<p align="center">
   <img width="1096" alt="Screenshot 2024-10-17 at 08 28 19" src="https://github.com/user-attachments/assets/09b4310c-573f-4f10-a03c-0bda34c2c257">
</p>

<p align="center">
   <img width="1551" alt="Screenshot 2024-10-17 at 08 40 53" src="https://github.com/user-attachments/assets/d6cd1fed-f2b4-4779-adfe-b360e497fa5f">
</p>

From these results, it was clear that each VE successfully elicited its target emotion at intense levels, but these emotions were not distinct within each environment. This is explored thoroughly in the provided report, where we also explore how we could further distinct emotions within each VE. Overall, though, this study provides evidence that we can elicit intense, yet specific, emotions within virtual environments without the use of traditional mood induction methods that often poorly reflect the context in which VR is actually used, such as the [autobiographical emotional memory task][2] and the [international affective picture system][3]). 

## Technologies
<p>
  <img alt="Unity3D" src="https://img.shields.io/badge/Unity3D-grey?logo=unity"<p>
  <img alt="VR" src="https://img.shields.io/badge/VR-714079"<p>
  <img alt="JASP" src="https://img.shields.io/badge/JASP-70589c"<p>
  <img alt="Prism" src="https://img.shields.io/badge/Prism-577ca4""<p>
</p>

[1]: https://assetstore.unity.com/packages/3d/environments/urban/atmospheric-house-modular-192712
[2]: https://www.amdpi.com/2414-4088/7/4/38
[3]: https://www.frontiersin.org/joaaurnals/psychology/articles/10.3389/fpsyg.2021.674179/full

