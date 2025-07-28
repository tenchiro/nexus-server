# Nexus: The Serious Game (Front-end) 

**Nexus Server** is a data-driven serious game and analytics platform developed for _**Serious Games Analytics**_ (SGA) research. It consists of a front-end (serious) game that traces users' in-game actions _in situ_ and outputs structured data into a backend database, and a back-end analytics engine that retrieves, analyzes, and visualizes that data for research and stakeholder insights. 

### 🚀Motivation 

According to Dreyfus & Dreyfus' _**Skill Acquisition Model**_, "expertise" can be operationalized as a function of repeated learning with incremental improvement, supported by metacognition processes such as reflecting on _errors made_ and strategizing on _error fix_ -- usually over a long period of time. 

In this framework:
- **Performance** is conceptualized as the “distance” between the novice's decisions and those of experts.    
- Instructional Design & Technology (IDT) can accelerate growth in the earlier phases (P1: _Novice_ → P3: _Competence_).    
- Higher phases (P4–P6: _Proficient_ to _Master_) require long-term iterative practice beyond what IDT methods typically cover.

## 📚Research Inspiration

The narrative and design of **Nexus 2.0** are inspired in part by real-world events, including the April 7, 2025 testimony of Meta whistleblowers Sarah Wynn-Williams. Nexus is designed to provoke reflection on players’ own digital behavior and ethical reasoning in social media contexts.

The gameplay tracking model is derived from Prof. C. S. Loh’s multi-year research in Serious Games Analytics and instructional modeling.

> You can experience **Nexus 2.0** here: 
> Since the game will collect users' gameplay data, you must provide consent to indicate you are aware of and agree to the gameplay data collection. *Only in-game choices are collected and used in the analytics research.* 

## 🎮 The Game: Nexus 2.0

Nexus 2.0 is the player-facing game. The game simulates a college freshman's experience navigating a new social media app, Nexus, over the course of 20 in-game weeks (first semester). 

Over the semester, players are presented with game events (Life event + Gate event) and must choose one of three social media posts in response. These choices subtly reflect different levels of ethical consideration and will directly affect the Player's Profile Analysis, which will be presented at the end of the semester. 
### Private Messaging System
**Private Messages** revealing Nexus Corp's hidden practices are delivered at **irregular intervals**, determined dynamically by in-game gates. Players’ in-game responses affect the unfolding narrative, final endings, and their Player Profiles.
### Replayability
**Replay** is a key design feature. Players are encouraged to replay with different decision patterns to uncover Nexus Corp’s secrets and observe how their ethical profile shifts.

### ✨Key Features
* - **Dynamic Gameplay:** Randomized weekly events enhance replayability and minimize testing effects.    
- **Player Profiling:** In-game choices are analyzed to build unique player performance profiles.    
- **Multiple Endings:** Players encounter different narrative conclusions based on ethical behavior scores.    
- **Persistent Sessions:** A secure **Passkey System** lets players pause and resume gameplay.    
- **Replay Tracking:** Distinct gameplay rounds are stored for repeated-measures analysis.    
- **Deep Analytics:** Nexus supports value-added insights into decision-making, learning, and player profiling.

## 🔭 Current Development

Nexus Server is developed through an iterative **"vibe coding"** process with support from Generative AI tools. The system is built to support both:
- **Player-Facing Front-End:** A serious game tailored to a given domain or training need.    
- **Researcher/Stakeholder Back-End:** An analytics engine for real-time monitoring and post-game replay/data analysis.

## 🧪 Technical Architecture

Nexus 2.0 is a complete rebuild using scalable and real-time web technologies. It replaces [[Nexus (1.0)]] -- its PHP/HTML predecessor, with modern Node.js architecture for improved flexibility and data streaming.

| Component       | Stack/Tool              |
| --------------- | ----------------------- |
| **Hosting**     | DigitalOcean Droplet    |
| **Process Mgr** | PM2                     |
| **Backend**     | Node.js                 |
| **Database**    | MongoDB Atlas           |
| **Client**      | HTML / CSS / JavaScript |
## 🤝 Contributing

Development is currently invite-only. Please reach out if you're a researcher, designer, or developer interested in serious games, behavioral analytics, or educational simulations.

## 📬 Contact

**Developer & Game Designer:** [Prof. Christian S. Loh](https://www.csloh.com)  
**GitHub:** [@tenchiro](https://github.com/tenchiro)

---
## Bibliography:

#### Books:

1. C. S. Loh, Y. Sheng, & D. Ifenthaler, \[Eds.\] (in preparation). _Serious Games Analytics in the Age of AI_. Springer
2. C. S. Loh, Y. Sheng, & D. Ifenthaler, \[Eds.\] (2015). _Serious Games Analytics: Methodologies for Performance Measurement, Assessment, and Improvement_. Springer. [https://doi.org/10.1007/978-3-319-05834-4](https://doi.org/10.1007/978-3-319-05834-4 "10.1007/978-3-319-05834-4") 

#### Publications:

1. Loh, C. S. (2021). Serious games and analytics for skill acquisition and assessment. In Silva Mangiante, E.M., & Peno, K. \[Eds.\] _Teaching and learning for adult skill acquisition:_ _Applying the Dreyfus and Dreyfus model in different fields_. Information Age Publishing. \[[PDF](https://www.csloh.com/research/wp-content/uploads/2021/04/Loh-2021_Dreyfus-preprint.pdf "PDF")\]
2. Zhou, T. & Loh, C. S. (2020). The effects of fully and partially in-game guidance on players’ declarative and procedural knowledge with a disaster preparedness serious game. _International Journal of Gaming and Computer-Mediated Simulations. 12(_4): 23-37. [https://doi.org/10.4018/IJGCMS.2020100102](https://doi.org/10.4018/IJGCMS.2020100102 "https://doi.org/10.4018/IJGCMS.2020100102")
3. Loh, C. S., Li, I-H., & Sheng, Y. (2016). Comparison of similarity measures to differentiate players’ actions and decision-making profiles in serious games analytics. _Computers in Human Behavior._ _64:_ 562-574. [https://doi.org/10.1016/j.chb.2016.07.024](https://doi.org/10.1016/j.chb.2016.07.024 "https://doi.org/10.1016/j.chb.2016.07.024 ")
4. Loh, C. S., & Sheng, Y. (2015). Measuring expert-performance for serious games analytics: From data to insights. In C. S. Loh, Y. Sheng, & D. Ifenthaler (Eds). _Serious games analytics: Methodologies for performance measurement, assessment, and improvement._ Springer. (pp.101-134) \[Chapter 5\] [https://doi.org/10.1007/978-3-319-05834-4\_5](https://doi.org/10.1007/978-3-319-05834-4_5 "10.1007/978-3-319-05834-4_5")
5. Loh, C. S., Sheng, Y., & Ifenthaler, D. (2015). Serious games analytics: Theoretical framework. In C. S. Loh, Y. Sheng, & D. Ifenthaler (Eds). _Serious games analytics: Methodologies for performance measurement, assessment, and improvement._ Springer. (pp.3-30) \[Chapter 1\] https://doi.org/10.1007/978-3-319-05834-4\_1
6. Loh, C. S., Sheng, Y., & Li, I-H. (2015). Predicting expert-novice performance as serious games analytics with objective-oriented and navigational action sequences. _Computers in Human Behavior. 49:_ 147-155. [https://doi.org/10.1016/j.chb.2015.02.053](https://doi.org/10.1016/j.chb.2015.02.053 "10.1016/j.chb.2015.02.053")
7. Byun, J. H. & Loh, C. S. (2015). Audial engagement: Effects of game sound on learner engagement in digital game-based learning environments. _Computers in Human Behavior. 46:_ 129-138. [https://doi.org/10.1016/j.chb.2014.12.052](https://doi.org/10.1016/j.chb.2014.12.052 "10.1016/j.chb.2014.12.052 ")
8. Loh, C. S., & Sheng, Y. (2015). Measuring the (dis-)similarity between expert and novice behaviors as serious games analytics. _Education and Information Technologies. 20_(1): 5-19. [https://doi.org/10.1007/s10639-013-9263-y](https://doi.org/10.1007/s10639-013-9263-y "10.1007/s10639-013-9263-y")
9. Loh, C. S., & Sheng, Y. (2014). Maximum Similarity Index (MSI): A metric to differentiate the performance of novices vs. multiple experts in serious games. _Computers in Human Behavior. 39:_ 322-330. [https://doi.org/10.1016/j.chb.2014.07.022](https://doi.org/10.1016/j.chb.2014.07.022 "DOI: 10.1016/j.chb.2014.07.022")
10. Loh, C. S. (2012). Information Trails: In-process assessment for game-based learning. In D. Ifenthaler, D. Eseryel, & X. Ge (Eds). _Assessment in game-based learning: Foundations, innovations, and perspectives_. (pp.123-144) Springer.  [https://doi.org/10.1007/978-1-4614-3546-4\_8](https://doi.org/10.1007/978-1-4614-3546-4_8 "10.1007/978-1-4614-3546-4_8") 

#### Proceedings:

1. Loh, C. S., Sheng, Y., Rajasegeran, D. D., Liu, K., Choh, A. C. L., & Ang, S. Y. (August 2023). _Serious games assessment: Analytics, measurement, and visualization of nursing competencies._ In Proceedings of the 2023 IEEE 11th International Conference on Serious Games and Applications for Health (SeGAH 2023). Athens, Greece. Aug 28-30, 2023. (Published by IEEE). \[[PDF](https://www.csloh.com/research/wp-content/uploads/2023/10/Loh_Sheng-SEGAH-2023.pdf "PDF")\]  [https://doi.org/10.1109/SeGAH57547.2023.10253804](https://doi.org/10.1109/SeGAH57547.2023.10253804 "https://doi.org/10.1109/SeGAH57547.2023.10253804")
2. Wallner, G., Kriglstein, S., Gabriel, S., Loh, C. S., Sheng, Y., Li, I. H. (2018). _Lost My Way: An educational geometry game for young children._ In Proceedings of the 13th International Conference on the Foundations of Digital Games. Malmo, Sweden. Aug 7-10, 2018. https://doi.org/10.1145/3235765.3235807
3. Loh, C. S. & I-Hung, Li. (2016). _Using players’ Gameplay Action-Decision profiles to prescribe training: Reducing training costs with Serious Games Analytics._ In Proceedings of the 3rd IEEE International Conference on Data Science and Advanced Analytics (DSAA). Montreal, Canada. Oct 17-19, 2016. \[[PDF](https://www.csloh.com/research/wp-content/uploads/2016/10/GDS-2016_Loh-Li.pdf "PDF")\]  [https://doi.org/10.13140/RG.2.2.18387.78888](https://doi.org/10.13140/RG.2.2.18387.78888 "https://doi.org/10.13140/RG.2.2.18387.78888")
4. Loh, C. S. & I-Hung, Li. (2015). _Predicting the competency improvement for Serious Games Analytics: Action-sequences, game grids, PLS-DA and JMP_. In Proceedings of the Discovery Summit 2015. San Diego, CA. \[[PDF](https://www.csloh.com/research/wp-content/uploads/2009/08/Loh_Li_Discovery_Summit_2015.pdf "PDF")\] [https://doi.org/10.13140/RG.2.1.3997.4889](https://doi.org/10.13140/RG.2.1.3997.4889 "10.13140/RG.2.1.3997.4889")
5. Loh, C. S. & Ekstrand, A. (2015). _Audialization in Serious Games Analytics: Visualizing player performance improvement by sound or music._ In Proceedings of the 3rd International Workshop on Intelligent Digital Games for Empowerment and Inclusion (IDGEI 2015), Satellite of International Conference on Intelligent User Interfaces. Atlanta, GA. \[[PDF](https://www.csloh.com/research/wp-content/uploads/2009/08/IDGEI-2015_Loh_Ekstrand_RG.pdf "PDF")\] [https://doi.org/10.13140/RG.2.1.4956.4009](https://doi.org/10.13140/RG.2.1.4956.4009 "10.13140/RG.2.1.4956.4009")
6. Loh, C. S. & Sheng, Y. (2013). _Performance metrics for serious games: Will the (real) expert please step forward?_ In Proceedings of the 18th International Conference on Computer Games: AI, Animation, Mobile, Interactive Multimedia, Educational & Serious Games (CGAMES 2013). Louisville, KY. \[[PDF](https://www.csloh.com/research/wp-content/uploads/2015/02/CGAMES-2013.pdf "PDF")\]  [https://doi.org/10.1109/CGames.2013.6632633](https://doi.org/10.1109/CGames.2013.6632633 "10.1109/CGames.2013.6632633 ")
