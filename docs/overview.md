# Overview of the  Project

 CSSR4Africa is a three-year research project to develop culturally sensitive social robotics for Africa. It has the following objectives.
 1. Identify the verbal and non-verbal social and cultural norms of human interaction that are prevalent in countries in Africa.
  2. Encapsulate them in the behavioural patterns of social robots so that they  can engage with African people in a manner that is consistent with their expectations of acceptable social interaction.
  3. Demonstrate these culturally-sensitive social robot behaviours in two use cases: one for giving a tour of a university laboratory, and one for assisting and giving directions to visitors at the reception of a university.
 
 In order to ensure that the project objectives can be achieved in the time available, we restrict the scope of the project to the cultures and social practices that are prevalent in Rwanda and South Africa.
    
![CSSR4Africa Scenario](/images/CSSR_Scenario3A.png)

Loosely based on work by Bruno et al. (2017), this figure illustrates the concept of a culturally competent robot. Cultural competence involves cultural awareness and cultural sensitivity, i.e.,  the ability to exhibit behaviour based on the general cultural preferences of a population using  ethnographic data stored in a cultural knowledge base (the robot's right think bubble).  Cultural competence also involves the ability to infer the cultural preferences of an individual and avoid stereotypical interaction (the robot's left think bubble), all of which allows  the robot to interact in an empathetic manner.  

CSSR4Africa focusses on cultural sensitivity. We plan to extend the work to cultural competence in a follow-on project.
 
 (The empathy symbol is courtesy of [www.empathysymbol.com](https://www.empathysymbol.com).)
 
 Reference: B. Bruno, N. Y. Chong, H. Kamide, S. Kanoria, J. Lee, Y. Lim, A. K. Pandey, C. Papadopoulos, I. Papadopoulos, F. Pecora, A. Saffioti, and A. Sgorbissa, "Paving the way for culturally competent robots: A position paper", in 26th IEEE International Symposium on Robot and Human Interactive Communication (RO-MAN), Lisbon, Portugal, 2017, pp. 553-560.
    
Papers, abstracts, posters, and presentations that describe  the project are  available on the [Publications](https://cssr4africa.github.io/publications) page.

---

## Pepper4DEC

Pepper4DEC is a spin-off project that applies the culturally sensitive social robotics research from CSSR4Africa to a real-world deployment. It develops software for an autonomous Pepper robot-led tour system at the Upanzi Digital Experience Center (DEC) at Carnegie Mellon University Africa, where the robot acts as a digital guide for visitors, replacing human-led tours with fully automated, interactive experiences across Digital Public Infrastructure booths.

The system is built on ROS2 (Humble) and uses a modular architecture covering behavior control, perception, navigation, and interaction. Key changes introduction of ROS2 Migration, conversation manager, Action based behavior controller, and SLAM-based autonomous navigation.

Pepper4DEC serves both as a practical deployment of the CSSR4Africa research outcomes and as a testbed for evaluating culturally aware human-robot interaction in an African context.