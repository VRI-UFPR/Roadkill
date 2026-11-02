# Welcome to the Jungle: a Systematic Mapping on Computer Vision Connecting Robotics and Wildlife

# Suplementary material

This supplementary material documents the search strings used in each digital library and lists the 142 primary studies of the final corpus.

## Search strategy

The search strategy used Boolean operators to combine synonyms (OR) and research facets (AND), following the guidelines of Kitchenham. The resulting strings were structured into two main thematic blocks: the first covering the problem domain, with terms related to wildlife monitoring, sighting, and roadkill, and the second encompassing the applied technologies, focusing on computational tools, artificial intelligence, and computer vision. The base string was adapted to the syntax and limits of each library.

Searches were run in March 2026, so the 2026 publications in the corpus cover only part of that year. A publication-date filter (2021 onward, inclusive) was applied afterwards.

| Library             | Fields searched                             |   Results |
| ------------------- | ------------------------------------------- | --------: |
| Scopus              | Title, abstract, keywords (`TITLE-ABS-KEY`) |     1,401 |
| IEEE Xplore         | General search, all metadata                |       706 |
| SpringerLink        | General search (metadata and full text)     |       266 |
| ScienceDirect       | Title, abstract, keywords                   |       211 |
| SBC OpenLib (SOL)   | Anywhere                                    |        32 |
| ACM Digital Library | General search, all fields                  |        29 |
| ERIC                | General search                              |         0 |
| SciELO              | General search, all indexes                 |         0 |
| **Total**           |                                             | **2,645** |

After duplicate removal in Parsifal, 2,256 studies remained. Title/abstract screening followed by full-text reading resulted in the final corpus of 142 articles.

### Scopus (advanced search)

```text
TITLE-ABS-KEY (("wildlife monitor*" OR "biodiversity track*" OR "ecological monitor*" OR "fauna monitor*" OR "wildlife surveill*" OR "wildlife roadkill*" OR "animal vehicle collision*" OR "animal-vehicle-collision*" OR "fauna road mortalit*" OR "fauna casualt*" OR "highway mortalit*" OR "roadkill*" OR "road-kill*" OR "wildlife crash*" OR "wildlife vehicle collision*" OR "wildlife-vehicle-collision*" OR "wildlife sight*" OR "animal sight*" OR "fauna record*" OR "species occurrence*" OR "wildlife observ*" OR "fauna survey*" OR "animal track*" OR "road ecolog*" OR "animal carcass*" OR "fauna carcass*" OR "wildlife detect*") AND ("mobile app*" OR "mobile application*" OR "smartphone app*" OR "web app*" OR "web platform*" OR "digital platform*" OR "computational tool*" OR "mobile tool*" OR "information system*" OR "software tool*" OR "software application*" OR "software ecosystem*" OR "artificial intelligen*" OR "machine learn*" OR "deep learn*" OR "neural network*" OR "convolutional neural network*" OR "computer vision*" OR "image recogni*" OR "object detect*" OR "automat* detect*" OR "pattern recogni*" OR "image classifi*" OR "semantic segmentat*" OR "instance segmentat*" OR "video analys*" OR "web system*"))
```

### IEEE Xplore

```text
("All Metadata":"wildlife monitor*" OR "All Metadata":"biodiversity tracking" OR "All Metadata":"ecological monitoring" OR "All Metadata":"fauna monitoring" OR "All Metadata":"wildlife surveillance" OR "All Metadata":"wildlife roadkill" OR "All Metadata":"animal vehicle collision" OR "All Metadata":"animal-vehicle-collision" OR "All Metadata":"fauna road mortality" OR "All Metadata":"fauna casualty" OR "All Metadata":"highway mortality" OR "All Metadata":"roadkill*" OR "All Metadata":"road-kill" OR "All Metadata":"wildlife crash" OR "All Metadata":"wildlife vehicle collision" OR "All Metadata":"wildlife-vehicle-collision" OR "All Metadata":"wildlife sighting" OR "All Metadata":"animal sighting" OR "All Metadata":"fauna record" OR "All Metadata":"wildlife observation" OR "All Metadata":"fauna survey" OR "All Metadata":"animal track*" OR "All Metadata":"road ecolog*" OR "All Metadata":"animal carcass" OR "All Metadata":"fauna carcass" OR "All Metadata":"wildlife detect*") AND ("All Metadata":"mobile app*" OR "All Metadata":"mobile application" OR "All Metadata":"smartphone app" OR "All Metadata":"web app" OR "All Metadata":"web platform" OR "All Metadata":"digital platform" OR "All Metadata":"computational tool" OR "All Metadata":"mobile tool" OR "All Metadata":"software tool" OR "All Metadata":"software application" OR "All Metadata":"software ecosystem" OR "All Metadata":"artificial intelligen*" OR "All Metadata":"machine learn*" OR "All Metadata":"deep learning" OR "All Metadata":"neural network" OR "All Metadata":"convolutional neural network" OR "All Metadata":"computer vision" OR "All Metadata":"image recogni*" OR "All Metadata":"object detect*" OR "All Metadata":"automated detection" OR "All Metadata":"pattern recognition" OR "All Metadata":"image classification" OR "All Metadata":"semantic segmentation" OR "All Metadata":"instance segmentation" OR "All Metadata":"video analysis" OR "All Metadata":"web system")
```

### SpringerLink

```text
("wildlife monitor*" OR "biodiversity track*" OR "ecological monitor*" OR "fauna monitor*" OR "wildlife surveill*" OR "wildlife roadkill*" OR "animal vehicle collision*" OR "animal-vehicle-collision*" OR "fauna road mortalit*" OR "fauna casualt*" OR "highway mortalit*" OR "roadkill*" OR "road-kill*" OR "wildlife crash*" OR "wildlife vehicle collision*" OR "wildlife-vehicle-collision*" OR "wildlife sight*" OR "animal sight*" OR "fauna record*" OR "species occurrence*" OR "wildlife observ*" OR "fauna survey*" OR "animal track*" OR "road ecolog*" OR "animal carcass*" OR "fauna carcass*" OR "wildlife detect*") AND ("mobile app*" OR "mobile application*" OR "smartphone app*" OR "web app*" OR "web platform*" OR "digital platform*" OR "computational tool*" OR "mobile tool*" OR "information system*" OR "software tool*" OR "software application*" OR "software ecosystem*" OR "artificial intelligen*" OR "machine learn*" OR "deep learn*" OR "neural network*" OR "convolutional neural network*" OR "computer vision*" OR "image recogni*" OR "object detect*" OR "automat* detect*" OR "pattern recogni*" OR "image classifi*" OR "semantic segmentat*" OR "instance segmentat*" OR "video analys*" OR "web system*")
```

### ScienceDirect

Reduced version of the string, due to the library's limit on the number of Boolean operators per field.

```text
("wildlife" OR "roadkill" OR "animal vehicle collision" OR "road ecology") AND ("mobile application" OR "web application" OR "machine learning" OR "computer vision")
```

### SBC OpenLib (SOL)

```text
(("wildlife" OR "fauna" OR "roadkill*" OR "animal*") AND ("monitor*" OR "collision*" OR "survey*") AND ("mobile" OR "app*" OR "platform*" OR "software" OR "intellig*" OR "learn*" OR "vision*" OR "detect*" OR "recogni*"))
```

### ACM Digital Library

Two search fields combined with `AND`, both over all fields.

Field 1:

```text
"wildlife monitor*" OR "biodiversity track*" OR "ecological monitor*" OR "fauna monitor*" OR "wildlife surveill*" OR "wildlife roadkill*" OR "animal vehicle collision*" OR "animal-vehicle-collision*" OR "fauna road mortalit*" OR "fauna casualt*" OR "highway mortalit*" OR "roadkill*" OR "road-kill*" OR "wildlife crash*" OR "wildlife vehicle collision*" OR "wildlife-vehicle-collision*" OR "wildlife sight*" OR "animal sight*" OR "fauna record*" OR "wildlife observ*" OR "fauna survey*" OR "animal track*" OR "road ecolog*" OR "animal carcass*" OR "fauna carcass*" OR "wildlife detect*"
```

Field 2:

```text
"mobile app*" OR "mobile application*" OR "smartphone app*" OR "web app*" OR "web platform*" OR "digital platform*" OR "computational tool*" OR "mobile tool*" OR "software tool*" OR "software application*" OR "software ecosystem*" OR "artificial intelligen*" OR "machine learn*" OR "deep learn*" OR "neural network*" OR "convolutional neural network*" OR "computer vision*" OR "image recogni*" OR "object detect*" OR "automat* detect*" OR "pattern recogni*" OR "image classifi*" OR "semantic segmentat*" OR "instance segmentat*" OR "video analys*" OR "web system*"
```

### ERIC

```text
("wildlife monitor*" OR "biodiversity track*" OR "ecological monitor*" OR "fauna monitor*" OR "wildlife surveill*" OR "wildlife roadkill*" OR "animal vehicle collision*" OR "animal-vehicle-collision*" OR "fauna road mortalit*" OR "fauna casualt*" OR "highway mortalit*" OR "roadkill*" OR "road-kill*" OR "wildlife crash*" OR "wildlife vehicle collision*" OR "wildlife-vehicle-collision*" OR "wildlife sight*" OR "animal sight*" OR "fauna record*" OR "species occurrence*" OR "wildlife observ*" OR "fauna survey*" OR "animal track*" OR "road ecolog*" OR "animal carcass*" OR "fauna carcass*" OR "wildlife detect*") AND ("mobile app*" OR "mobile application*" OR "smartphone app*" OR "web app*" OR "web platform*" OR "digital platform*" OR "digital plataform*" OR "computational tool*" OR "mobile tool*" OR "information system*" OR "software tool*" OR "software application*" OR "software ecosystem*" OR "artificial intelligen*" OR "machine learn*" OR "deep learn*" OR "neural network*" OR "convolutional neural network*" OR "computer vision*" OR "image recogni*" OR "object detect*" OR "automat* detect*" OR "pattern recogni*" OR "image classifi*" OR "semantic segmentat*" OR "instance segmentat*" OR "video analys*" OR "web system*" OR "software*")
```

### SciELO

Run in English and in a Portuguese translation; both returned no results.

English:

```text
("wildlife monitor" OR "wildlife monitors" OR "wildlife monitoring" OR "biodiversity track" OR "biodiversity tracks" OR "biodiversity tracking" OR "ecological monitor" OR "ecological monitors" OR "ecological monitoring" OR "fauna monitor" OR "fauna monitors" OR "fauna monitoring" OR "wildlife surveillance" OR "wildlife roadkill" OR "wildlife roadkills" OR "animal vehicle collision" OR "animal vehicle collisions" OR "animal-vehicle-collision" OR "animal-vehicle-collisions" OR "fauna road mortality" OR "fauna road mortalities" OR "fauna casualty" OR "fauna casualties" OR "highway mortality" OR "highway mortalities" OR roadkill* OR "road-kill" OR "road-kills" OR "wildlife crash" OR "wildlife crashes" OR "wildlife vehicle collision" OR "wildlife vehicle collisions" OR "wildlife-vehicle-collision" OR "wildlife-vehicle-collisions" OR "wildlife sight" OR "wildlife sights" OR "wildlife sighting" OR "wildlife sightings" OR "animal sight" OR "animal sights" OR "animal sighting" OR "animal sightings" OR "fauna record" OR "fauna records" OR "fauna recording" OR "fauna recordings" OR "wildlife observation" OR "wildlife observations" OR "wildlife observer" OR "wildlife observers" OR "fauna survey" OR "fauna surveys" OR "fauna surveying" OR "animal track" OR "animal tracks" OR "animal tracking" OR "road ecology" OR "road ecologist" OR "road ecologists" OR "animal carcass" OR "animal carcasses" OR "fauna carcass" OR "fauna carcasses" OR "wildlife detect" OR "wildlife detects" OR "wildlife detection" OR "wildlife detections" OR "wildlife detector" OR "wildlife detectors") AND ("mobile app" OR "mobile apps" OR "mobile application" OR "mobile applications" OR "smartphone app" OR "smartphone apps" OR "smartphone application" OR "smartphone applications" OR "web app" OR "web apps" OR "web application" OR "web applications" OR "web platform" OR "web platforms" OR "digital platform" OR "digital platforms" OR "computational tool" OR "computational tools" OR "mobile tool" OR "mobile tools" OR "software tool" OR "software tools" OR "software application" OR "software applications" OR "software ecosystem" OR "software ecosystems" OR "artificial intelligence" OR "machine learning" OR "deep learning" OR "neural network" OR "neural networks" OR "convolutional neural network" OR "convolutional neural networks" OR "computer vision" OR "image recognition" OR "object detection" OR "object detector" OR "object detectors" OR "automatic detection" OR "automated detection" OR "automatic detector" OR "automated detector" OR "pattern recognition" OR "image classification" OR "image classifier" OR "image classifiers" OR "semantic segmentation" OR "instance segmentation" OR "video analysis" OR "video analyses" OR "web system" OR "web systems")
```

Portuguese:

```text
("monitoramento de fauna" OR "monitoramento de animais silvestres" OR "monitoramento da vida silvestre" OR "monitoramento de biodiversidade" OR "rastreamento de biodiversidade" OR "monitoramento ecológico" OR "vigilância de fauna" OR "atropelamento de fauna" OR "atropelamento de animais" OR "atropelamentos de fauna" OR "atropelamentos de animais" OR "fauna atropelada" OR "animais atropelados" OR "colisão veículo-animal" OR "colisões veículo-animal" OR "colisão com fauna" OR "colisões com fauna" OR "mortalidade de fauna em rodovias" OR "mortalidade de animais em rodovias" OR "mortalidade rodoviária de fauna" OR "acidentes com fauna" OR "acidentes com animais silvestres" OR "avistamento de fauna" OR "avistamentos de fauna" OR "avistamento de animais" OR "observação de fauna" OR "observações de fauna" OR "registro de fauna" OR "registros de fauna" OR "levantamento de fauna" OR "levantamentos de fauna" OR "inventário de fauna" OR "inventários de fauna" OR "pegadas de animais" OR "rastros de animais" OR "rastreamento de animais" OR "ecologia de estradas" OR "ecologia rodoviária" OR "carcaça de animal" OR "carcaças de animais" OR "carcaça de fauna" OR "carcaças de fauna" OR "detecção de fauna" OR "detecção de animais" OR "detectores de fauna") AND ("aplicativo móvel" OR "aplicativos móveis" OR "aplicativo para celular" OR "aplicativo para smartphone" OR app* OR "aplicativo web" OR "aplicativos web" OR "plataforma web" OR "plataformas web" OR "plataforma digital" OR "plataformas digitais" OR "ferramenta computacional" OR "ferramentas computacionais" OR "ferramenta móvel" OR "programa de computador" OR "programas de computador" OR "inteligência artificial" OR "aprendizado de máquina" OR "aprendizagem de máquina" OR "aprendizado profundo" OR "aprendizagem profunda" OR "rede neural" OR "redes neurais" OR "rede neural convolucional" OR "redes neurais convolucionais" OR "visão computacional" OR "reconhecimento de imagem" OR "reconhecimento de imagens" OR "detecção de objetos" OR "detector de objetos" OR "detectores de objetos" OR "detecção automática" OR "detecção automatizada" OR "detector automático" OR "reconhecimento de padrões" OR "classificação de imagem" OR "classificação de imagens" OR "classificador de imagens" OR "segmentação semântica" OR "segmentação de instâncias" OR "análise de vídeo" OR "análise de vídeos" OR "sistema web" OR "sistemas web")
```

## Corpus (142 articles)

Sorted alphabetically by first author.

1. A, V., V, K., & R, P. S. (2025). Enhancing Wildlife Monitoring Through Densenet-Based Image Classification. _2025 2nd International Conference on Artificial Intelligence and Knowledge Discovery in Concurrent Engineering (ICECONF)_. https://doi.org/10.1109/ICECONF65644.2025.11379509

2. Alagarsamy, S., Rajasekar, R., Krishna, S. K. M., Chand, K. P., Nikhil, K., & Teja, K. V. P. (2023). Detection of Animals for Road Safety Using Deep Learning Method. _2023 International Conference on Computer Communication and Informatics (ICCCI)_. https://doi.org/10.1109/ICCCI56745.2023.10128493

3. Anand, A., Sathyanarayana, N., Deokar, T. D., Divya, C., & Lalitha, B. C. (2025). Comparative Study of Detection and Tracking Models for Automated Monitoring of Endangered Species. _2025 2nd International Conference on Software, Systems and Information Technology (SSITCON)_. https://doi.org/10.1109/SSITCON66133.2025.11342255

4. Anand, K., Winnie Wise, D. C. J., Pugalenthi, R., C, A., & M, V. (2025). Detection of Human and Animals for Wildlife Monitoring System Using YOLO. _2025 2nd International Conference on Computing and Data Science (ICCDS)_. https://doi.org/10.1109/ICCDS64403.2025.11209083

5. Anuar, M. H., Ismail, H., & Ahmedy, I. (2025). Animal Species Classification using Convolutional Neural Network. _Proceedings of the 2025 8th International Conference on Software Engineering and Information Management_. https://doi.org/10.1145/3725899.3725936

6. Appel, C. L., Subramanian, A., Koning, J. S., Ngosi, M., Sullivan, C. M., Levi, T., et al. (2025). Developing custom computer vision models with Njobvu‐ AI: A collaborative, user‐friendly platform for ecological research. _Ecological Applications_. https://doi.org/10.1002/eap.70096

7. Asdikian, J. P. H., Li, M., & Maier, G. (2024). Performance evaluation of YOLOv8 and YOLOv9 on custom dataset with color space augmentation for Real-time Wildlife detection at the Edge. _2024 IEEE 10th International Conference on Network Softwarization (NetSoft)_. https://doi.org/10.1109/NetSoft60951.2024.10588933

8. Asrani, D., Ramani, P., Justin, Z., Lonare, G. M., M, R., & Basha, H. A. (2025). Advanced Monitoring of Visitors and Wildlife using CNN and LSTM Techniques. _2025 International Conference on Intelligent Computing and Knowledge Extraction (ICICKE)_. https://doi.org/10.1109/ICICKE65317.2025.11136451

9. B, M., S, H., G, J. V., K, S. A., & A, S. S. (2025). Wildlife Species Identification with CNN-RNN Hybrid Deep Learning with Video Processing. _2025 IEEE 4th World Conference on Applied Intelligence and Computing (AIC)_. https://doi.org/10.1109/AIC66080.2025.11211878

10. Baek, J. W., Kim, J. I., & Kim, C. B. (2023). Deep learning-based image classification of turtles imported into Korea. _Scientific Reports_. https://doi.org/10.1038/s41598-023-49022-3

11. Ballal, D. S., Mehra, R., Mittal, S., Kumari, A., Murugan, D. S., & Satapathy, D. S. N. (2025). Utilizing Deep Learning for Automated Detection of Endangered Species in Camera Trap Data. _Natural and Engineering Sciences_. https://doi.org/10.28978/nesciences.1811113

12. Basit Mughal, A., Ullah Khan, R., Rehman, A. U., & Amine Bermak, A. (2025). Deep Learning for Dynamic Wildlife Monitoring: A Real-Time Approach. _IEEE Access_. https://doi.org/10.1109/ACCESS.2025.3600625

13. Bayyapureddi, M., Harshitha, L. S., & T, A. (2024). Enhancing Bird Species Classification with PaliGemma and Custom EfficientNet Architectures. _2024 8th International Conference on Electronics, Communication and Aerospace Technology (ICECA)_. https://doi.org/10.1109/ICECA63461.2024.10800982

14. Bhagyashree, B., Reddy, Y. M., Kumar, M. S., Murthy, V. N. L. N., Kumar, K. S., & Rout, S. K. (2024). Implementing YOLOv8 Deep Learning Framework for Bird Species Prediction. _2024 Recent Advances in Sustainable Engineering and Future Technologies (RASEFT)_. https://doi.org/10.1109/RASEFT61414.2024.00028

15. Bhargavi, I., Pratap, A. R., & Sri, A. S. (2024). An Enhanced EfficientNet-Powered Wildlife Species Classification for Biodiversity Monitoring. _2023 4th International Conference on Intelligent Technologies (CONIT)_. https://doi.org/10.1109/CONIT61985.2024.10627148

16. Brook, B. W., Buettel, J. C., Van Lunteren, P., Rajmohan, P. P., & Aandahl, R. Z. (2025). MEWC: A user-friendly AI workflow for customised wildlife-image classification. _Peer Community Journal_. https://doi.org/10.24072/pcjournal.565

17. Buslon Malarejes, J. S., Salvaleon, V. B. M. O., Mission, J. E., & Perin, M. A. D. (2025). A Comparative Study of Bird Species Classification Using K-Nearest Neighbors, Convolutional Neural Networks, and Support Vector Machines. _2025 IEEE Open Conference of Electrical, Electronic and Information Sciences (eStream)_. https://doi.org/10.1109/eStream66938.2025.11016879

18. Chamorro, D., Benítez, D., Pérez-Pérez, N., Riofrío, D., Grijalva, F., & Baldeon-Calisto, M. (2024). On the Use of YOLOv8 for Detection and Classification of Mammals Species in Wildlife Environments in the Ecuadorian Amazon. _2024 IEEE Biennial Congress of Argentina (ARGENCON)_. https://doi.org/10.1109/ARGENCON62399.2024.10735921

19. Chang, H. R., Chen, S. W., & Weng, G. J. (2025). Deep Learning for Biodiversity Monitoring: A Comparative Study on Wildlife Image Classification. _2025 IEEE International Conference on Consumer Electronics - Taiwan (ICCE-Taiwan)_. https://doi.org/10.1109/ICCE-Taiwan66881.2025.11207789

20. Chappid, J., & Sundaram, D. M. (2024). Robust Deep Learning Models For Wildlife Detection: Adapting To Varying Environmental Conditions. _2024 International Conference on Social and Sustainable Innovations in Technology and Engineering (SASI-ITE)_. https://doi.org/10.1109/SASI-ITE58663.2024.00063

21. Chauhan, S., & Lande, J. (2025). Enhancing Species Identification with Fine-Tuned ResNet50: Performance Analysis and Classification of Diverse Species. _2025 3rd International Conference on Advancement in Computation & Computer Technologies (InCACCT)_. https://doi.org/10.1109/InCACCT65424.2025.11011359

22. Chauhan, Y., Uppal, M., Gupta, D., Juneja, S., Gupta, P., & Saini, S. (2025). Fine-Tuned EfficientNetB0 Model for Accurate Bird Species Identification and Multi-Classification. _2025 7th International Conference on Signal Processing, Computing and Control (ISPCC)_. https://doi.org/10.1109/ISPCC66872.2025.11039315

23. Choiński, M., Rogowski, M., Tynecki, P., Kuijper, D. P. J., Churski, M., & Bubnicki, J. W. (2021). A First Step Towards Automated Species Recognition from Camera Trap Images of Mammals Using AI in a European Temperate Forest. _Computer Information Systems and Industrial Management_. https://doi.org/10.1007/978-3-030-84340-3_24

24. Chugh, S., Polyakov, E., Rampure, M., Basnyat, B., & Roy, N. (2025). Demo: InvisibleFence: Non-Lethal Edge-Optimized AI for Human Wildlife Coexistence and Crop Protection. _Proceedings of the 23rd Annual International Conference on Mobile Systems, Applications and Services_. https://doi.org/10.1145/3711875.3734379

25. Clarfeld, L. A., Gieder, K. D., Fuller, A., Miao, Z., Sirén, A. P. K., Webb, S. M., et al. (2025). DeepFaune New England: A Species Classification Model for Trail Camera Images in Northeastern North America. _Ecology and Evolution_. https://doi.org/10.1002/ece3.72174

26. D, R., Shanmugapriya, N., G, D. P., & K, M. (2025). Hybrid Fusion Approach for Animal Species Identification using Facial Images. _2025 3rd International Conference on Advancements in Electrical, Electronics, Communication, Computing and Automation (ICAECA)_. https://doi.org/10.1109/ICAECA63854.2025.11012250

27. Dadial, R., & Thakur, B. (2024). Advancing Wildlife Conservation through Drone- Based Multi-Classification of Species with Fused CNN-LSTM Deep Learning Model. _2024 10th International Conference on Advanced Computing and Communication Systems (ICACCS)_. https://doi.org/10.1109/ICACCS60874.2024.10717116

28. Daniel Raj, J. J., Sangeetha, C. N., Ghorai, S., Das, S., Manish, & Ahmed, S. (2023). Wild Animals Intrusion Detection for Safe Commuting in Forest Corridors using AI Techniques. _2023 3rd International Conference on Innovative Practices in Technology and Management (ICIPTM)_. https://doi.org/10.1109/ICIPTM57143.2023.10117831

29. Deng, C., Zhou, G., & Cai, Y. (2023). Wildlife Monitoring and Identification based on Faster R-CNN. _2023 International Conference on Advances in Electrical Engineering and Computer Applications (AEECA)_. https://doi.org/10.1109/AEECA59734.2023.00119

30. Dhenia, R. N. K., Sridhar, R., Sharma, J., Kanani, I. J., Banerjee, D., & Sharma, G. (2025). Using MobileNetV2 for Real-World Applications: Effective Animal Image Classification. _2025 Global Conference on Information Technology and Communication Networks (GITCON)_. https://doi.org/10.1109/GITCON65266.2025.11376889

31. Du, Z., Wu, D., Wen, Q., Xu, F., Liu, Z., Li, C., et al. (2025). An Improved Lightweight Model for Protected Wildlife Detection in Camera Trap Images. _Sensors_. https://doi.org/10.3390/s25237331

32. Fergus, P., Chalmers, C., Longmore, S., & Wich, S. (2024). Harnessing Artificial Intelligence for Wildlife Conservation. _Conservation_. https://doi.org/10.3390/conservation4040041

33. Ferrante, G. S., Vasconcelos Nakamura, L. H., Sampaio, S., Filho, G. P. R., & Meneguette, R. I. (2024). Evaluating YOLO architectures for detecting road killed endangered Brazilian animals. _Scientific Reports_. https://doi.org/10.1038/s41598-024-52054-y

34. Félix-Jiménez, A. F., Sánchez-Lee, V. S., Acuña-Cid, H. A., Ibarra-Belmonte, I., Arredondo-Morales, E., & Ahumada-Tello, E. (2025). Integration of YOLOv8 Small and MobileNet V3 Large for Efficient Bird Detection and Classification on Mobile Devices. _AI_. https://doi.org/10.3390/ai6030057

35. Gadhave, R., AnilKumar, D., Khot, R., & Gupta, D. (2024). PredatorSense-Wildlife Detection System. _2024 8th International Conference on Computing, Communication, Control and Automation (ICCUBEA)_. https://doi.org/10.1109/ICCUBEA61740.2024.10774639

36. Gadot, T., Istrate, Ș., Kim, H., Morris, D., Beery, S., Birch, T., et al. (2024). To crop or not to crop: Comparing whole‐image and cropped classification on a large dataset of camera trap images. _IET Computer Vision_. https://doi.org/10.1049/cvi2.12318

37. Gill, K. S., Gupta, R., Malhotra, S., Devliyal, S., & Sunil, G. (2024). Classification of Reptiles and Amphibians Using Transfer Learning and Deep Convolutional Neural Networks. _2024 IEEE 9th International Conference for Convergence in Technology (I2CT)_. https://doi.org/10.1109/I2CT61223.2024.10544030

38. Gogula, S., Khanna, M. R., Neelappa, N., Sundaram, A., Kumar, E. R., & Kumar R., S. (2022). Modernized Wildlife Surveillance and Behaviour Detection using a Novel Machine Learning Algorithm. _International Journal on Recent and Innovation Trends in Computing and Communication_. https://doi.org/10.17762/ijritcc.v10i2s.5911

39. Gomathi, V., Harini, I., Badmabharathi, S., Kaarthiga, K., & Dhanushkumar, M. (2024). Animal Detection and Classification to Prevent Human-Animal Conflict Using YOLOv8. _2024 13th International Conference on System Modeling & Advancement in Research Trends (SMART)_. https://doi.org/10.1109/SMART63812.2024.10882585

40. Habelalmateen, M. I., C, R. A., A N, R., Suvarnamukhi, B., & J, R. (2025). Robust Wildlife Detection Using Objectness-Aware Yolo with Attention and Pose Estimation. _2025 3rd International Conference on Data Science and Network Security (ICDSNS)_. https://doi.org/10.1109/ICDSNS65743.2025.11168762

41. Henrich, M., Fiderer, C., Klamm, A., Schneider, A., Ballmann, A., Stein, J., et al. (2026). Camera traps and deep learning enable efficient large‐scale density estimation of wildlife in temperate forest ecosystems. _Remote Sensing in Ecology and Conservation_. https://doi.org/10.1002/rse2.70030

42. Huang, X., Mirri, S., Shen, L., & Tang, S. K. (2025). Efficient Wild Animal Detection and Collection Using Quantized Models on Low-End Edge Devices. _2025 IEEE Symposium on Computers and Communications (ISCC)_. https://doi.org/10.1109/ISCC65549.2025.11325936

43. Ibrahim, M., Al-Kubaise, K., Alkapti, A., AlMusa, A., Abdelaziz, O., Al-maadeed, S., et al. (2024). Classification of Animal Species Using a Deep Neural Network-Based Feature Extraction Method. _2024 IEEE 21st International Conference on Smart Communities: Improving Quality of Life using AI, Robotics and IoT (HONET)_. https://doi.org/10.1109/HONET63146.2024.10822939

44. Jadhav, D., Patayeet, S., Salunkhe, P., Pujari, S., Sakharkar, M., & Zanje, S. (2025). BirdClassifier: An Advanced Bird Classification Model Using Deep Neural Networks. _2025 International Conference on Inventive Computation Technologies (ICICT)_. https://doi.org/10.1109/ICICT64420.2025.11004874

45. Jansi, S., Meruga, V. B., Gudala, L., Eilane, B. K., Reddy, P. V., & D.Ganesh (2025). Edge-AI Perimeter Surveillance for Autonomous Wildlife-Conflict Mitigation. _2025 5th International Conference on Evolutionary Computing and Mobile Sustainable Networks (ICECMSN)_. https://doi.org/10.1109/ICECMSN68058.2025.11383099

46. Jayanthi, M., & Kanimozhi, K. V. (2025). Automated Wildlife Monitoring for Animal Detection using CNN and Bi-GRU. _2025 6th International Conference on Electronics and Sustainable Communication Systems (ICESC)_. https://doi.org/10.1109/ICESC65114.2025.11212518

47. Jayanthi, M., & Kanimozhi, K. V. (2025). Deployment of Wildlife Monitor System based on Deep CNN in Various Ecological Zones. _2025 6th International Conference on Electronics and Sustainable Communication Systems (ICESC)_. https://doi.org/10.1109/ICESC65114.2025.11212338

48. Joseph, S., Hemalatha, S., & Tamilvannan, D. (2024). Image based Bird Species Identification using CNN. _2024 2nd International Conference on Self Sustainable Artificial Intelligence Systems (ICSSAS)_. https://doi.org/10.1109/ICSSAS64001.2024.10760418

49. Kabra, K., Xiong, A., Li, W., Luo, M., Lu, W., Yu, T., et al. (2022). Deep object detection for waterbird monitoring using aerial imagery. _2022 21st IEEE International Conference on Machine Learning and Applications (ICMLA)_. https://doi.org/10.1109/ICMLA55696.2022.00073

50. Kannan, S., P, T. K., T, J., Askar, S., Giri, P., & Hamsan, R. (2025). NGOCL: A Robust Methodology to Identify Bird Species based on Neural Gradient Optimization and Classification Logic. _2025 International Conference on Frontier Technologies and Solutions (ICFTS)_. https://doi.org/10.1109/ICFTS62006.2025.11031876

51. Kant, V., & Yamsani, N. (2025). Animal Species Classification Using Fine-Tuned ResNet152V2: A Deep Learning Approach for Biodiversity Conservation. _2025 3rd International Conference on Advancement in Computation & Computer Technologies (InCACCT)_. https://doi.org/10.1109/InCACCT65424.2025.11011471

52. Kaul, G., McDevitt, J., Johnson, J., & Eban-Rothschild, A. (2024). DAMM for the detection and tracking of multiple animals within complex social and environmental settings. _Scientific Reports_. https://doi.org/10.1038/s41598-024-72367-2

53. Kaur, A., Kukreja, V., Chattopadhyay, S., Verma, A., & Sharma, R. (2024). Empowering Wildlife Conservation with a Fused CNN-SVM Deep Learning Model for Multi-Classification Using Drone-Based Imagery. _2024 IEEE International Conference on Interdisciplinary Approaches in Technology and Management for Social Innovation (IATMSI)_. https://doi.org/10.1109/IATMSI60426.2024.10502645

54. Kaur, J., Rani, S., Sharma, A., & Dogra, A. (2024). Enhanced Bird Species Identification using ResNet-50: A Deep Learning Framework for High-Performance Classification. _2024 3rd International Conference on Automation, Computing and Renewable Systems (ICACRS)_. https://doi.org/10.1109/ICACRS62842.2024.10841723

55. Kaushik, P., & Khurana, S. (2024). Enhanced Classification of Reptiles and Amphibians Using Deep Learning: A Comparative Analysis of Model Performance. _2024 International Conference on Cybernation and Computation (CYBERCOM)_. https://doi.org/10.1109/CYBERCOM63683.2024.10803131

56. Khajuria, A., Sridhar, R., Dhenia, R. N. K., Kanani, I. J., Banerjee, D., & Anand, V. (2025). Using MobileNetV2 in the Real World: Classifying Animal Images Effectively. _2025 International Conference on Innovations and Emerging Technologies In AI & Communication Systems (IETACS)_. https://doi.org/10.1109/IETACS68750.2025.11385656

57. Kirindearachchi, Y., & Liyanage, L. (2025). Mitigating Roadkill Using Computer Vision and Machine Learning Techniques: A Case Study on Turtles in Australia. _2025 International Conference on Activity and Behavior Computing (ABC)_. https://doi.org/10.1109/ABC64332.2025.11118553

58. Kissling, W. D., Evans, J. C., Zilber, R., Breeze, T. D., Shinneman, S., Schneider, L. C., et al. (2024). Development of a cost-efficient automated wildlife camera network in a European Natura 2000 site. _Basic and Applied Ecology_. https://doi.org/10.1016/j.baae.2024.06.006

59. Kshitiz, Shreshtha, S., Dutta, B., Dosi, M., Vatsa, M., Singh, R., et al. (2024). BirdCollect: A Comprehensive Benchmark for Analyzing Dense Bird Flock Attributes. _Proceedings of the AAAI Conference on Artificial Intelligence_. https://doi.org/10.1609/aaai.v38i20.30189

60. Lan, P., Xian, Y., Shen, T., Lee, Y., & Zhao, Q. (2025). Semantic-Guided Mamba Fusion for Robust Object Detection of Tibetan Plateau Wildlife. _Electronics_. https://doi.org/10.3390/electronics14224549

61. Li, C., Pang, Y., Liu, X., Yu, Z., & Sun, M. (2026). WildMDT-YOLO: A multi-scale wildlife detection model for complex environments. _Computer Vision and Image Understanding_. https://doi.org/10.1016/j.cviu.2026.104678

62. Liu, W., & Pan, Y. (2025). A Multi-Strategy Integrated Improved YOLOV11 Algorithm and Its Application in Wildlife Object Detection. _2025 10th International Conference on Intelligent Computing and Signal Processing (ICSP)_. https://doi.org/10.1109/ICSP65755.2025.11087125

63. Liu, Y., Wu, S., & Guo, C. (2025). Research on wild animal detection algorithm based on improved YOLOv10. _Second International Conference on Image Processing, Intelligent Control, and Computer Engineering (IPICE 2025)_. https://doi.org/10.1117/12.3087245

64. Lu, X., Li, W., & Lu, X. (2024). An objectness-aware network for wildlife detection. _Multimedia Tools and Applications_. https://doi.org/10.1007/s11042-023-15246-8

65. M, A., K R, S. N., D, S., & S, R. (2025). Enhanced Wildlife Species Classification using YOLOv10-X for Sustainable Management Decisions. _2025 International Conference on Modern Sustainable Systems (CMSS)_. https://doi.org/10.1109/CMSS66566.2025.11182351

66. Ma, D., & Yang, J. (2022). YOLO-Animal: An efficient wildlife detection network based on improved YOLOv5. _2022 International Conference on Image Processing, Computer Vision and Machine Learning (ICICML)_. https://doi.org/10.1109/ICICML57342.2022.10009855

67. Ma, Z., Dong, Y., Xia, Y., Xu, D., Xu, F., & Chen, F. (2024). Wildlife Real-Time Detection in Complex Forest Scenes Based on YOLOv5s Deep Learning Network. _Remote Sensing_. https://doi.org/10.3390/rs16081350

68. Magaldi, H., Cornette, R., Tibesigwa, J. J., Katumba, R., Rugonge, H., Amarasekaran, B., et al. (2025). DeepForestVision: Automated wildlife identification for camera traps of African tropical forests. _Ecological Solutions and Evidence_. https://doi.org/10.1002/2688-8319.70167

69. Manchana, R., Gohar, A., Imad, M., & Ali, R. H. (2025). Lightweight Wildlife Image Classification Using EfficientNetV2-S with Confidence-Aware Prediction. _2025 27th International Multitopic Conference (INMIC)_. https://doi.org/10.1109/INMIC65900.2025.11348142

70. Mane, D., Bagde, S., Borhade, B., Bagul, S., & Bhanji, O. (2025). WildGuard: Realtime Wildlife Detection System using Deep Learning. _2025 IEEE Pune Section International Conference (PuneCon)_. https://doi.org/10.1109/PUNECON67554.2025.11379231

71. Mane, V., Nikude, P., Patil, T., & Tambe, P. (2024). Wildlife Classification using Convolutional Neural Networks (CNN). _2024 International Conference on Inventive Computation Technologies (ICICT)_. https://doi.org/10.1109/ICICT60155.2024.10544702

72. Matov, P. (2025). Wild Animals’ Recognition System Based on Optimized YOLO Model and Camera Traps in Bulgarian Mountains. _2025 International Conference Automatics and Informatics (ICAI)_. https://doi.org/10.1109/ICAI67591.2025.11324814

73. Matov, P., Lazarova, M., & Filipova-Petrakieva, S. (2025). Hybrid Model for Wild Animals Detection Based on Camera Traps in Bulgarian Mountains. _2025 13th International Scientific Conference on Computer Science (COMSCI)_. https://doi.org/10.1109/COMSCI67172.2025.11225219

74. More, R. P., & Khan, R. A. H. (2025). An Adaptive Deep Neuro-Fuzzy Framework for Wildlife Detection Using YOLOv3 and LGXP Features. _2025 IEEE Pune Section International Conference (PuneCon)_. https://doi.org/10.1109/PuneCon67554.2025.11379333

75. More, R. P., Chandre, P., Lokare, D., Yadav, S., Aher, S., & Ghandat, A. (2025). AI-Powered Image Processing for Wildlife Conservation: Hybrid Deep Learning Model (EDGE-WildNet) for Low-Light and Noisy Environments. _2025 IEEE 5th International Conference on ICT in Business Industry & Government (ICTBIG)_. https://doi.org/10.1109/ICTBIG68706.2025.11323650

76. Mou, C., Liang, A., Hu, C., Meng, F., Han, B., & Xu, F. (2023). Monitoring Endangered and Rare Wildlife in the Field: A Foundation Deep Learning Model Integrating Human Knowledge for Incremental Recognition with Few Data and Low Cost. _Animals_. https://doi.org/10.3390/ani13203168

77. Mughal, A. B., Arain, J. H., Shah, S. M., Haider, S. M., & Khan, R. U. (2025). Real-Time Wildlife Tracking with Fine-Tuned YOLOv11. _2025 2nd International Conference on Trends in Engineering Systems and Technologies (ICTEST)_. https://doi.org/10.1109/ICTEST64710.2025.11042292

78. Muhammad, S., Xiang, W., Mann, S., Han, K., & Nair, S. (2024). TemporalSwin-FPN Net: A Novel Pipeline for Metadata-Driven Sequence Classification in Camera Trap Imagery. _2024 International Conference on Digital Image Computing: Techniques and Applications (DICTA)_. https://doi.org/10.1109/DICTA63115.2024.00094

79. Mulero-Pázmány, M., Hurtado, S., Barba-González, C., Antequera-Gómez, M. L., Díaz-Ruiz, F., Real, R., et al. (2025). Addressing significant challenges for animal detection in camera trap images: a novel deep learning-based approach. _Scientific Reports_. https://doi.org/10.1038/s41598-025-90249-z

80. Mulero-Pérez, D., Rodriguez-Juan, J., Ramirez-Gordillo, T., Benavent-Lledo, M., Ruiz-Ponce, P., Ortiz-Perez, D., et al. (2025). A Federated Learning Architecture for Bird Species Classification in Wetlands. _Journal of Sensor and Actuator Networks_. https://doi.org/10.3390/jsan14040071

81. Najm, H., Mohsin, Z. R., & Abdulhussien, W. R. (2025). Real-Time Detection of Multiple Snake Species in Natural Environments Using YOLOv8-Nano. _Ingénierie des systèmes d information_. https://doi.org/10.18280/isi.301025

82. Nasra, P., Lande, J., Sharma, N., Kharola, A., & Badhani, R. (2026). InceptionResNetV2-Based Deep Learning Framework for Multi-Class Classification of Reptile and Amphibian Species. _2026 IEEE International Students’ Conference on Electrical, Electronics and Computer Science (SCEECS)_. https://doi.org/10.1109/SCEECS68810.2026.11429924

83. Njathi, Y., Wanjiku, L., Mugambi, L., Kabi, J. N., Kiarie, G., & Maina, C. W. (2023). Efficient Camera Trap Image Annotation Using YOLOv5. _2023 IEEE AFRICON_. https://doi.org/10.1109/AFRICON55910.2023.10293724

84. Norman, D. L., Bischoff, P. H., Wearn, O. R., Ewers, R. M., Rowcliffe, J. M., Evans, B., et al. (2023). Can CNN‐based species classification generalise across variation in habitat within a camera trap survey?. _Methods in Ecology and Evolution_. https://doi.org/10.1111/2041-210X.14031

85. P, C., S, S., S, Y. S., M, S., & P, Y. K. (2025). Image Recognition for Wildlife Conservation. _2025 International Conference on Computational, Communication and Information Technology (ICCCIT)_. https://doi.org/10.1109/ICCCIT62592.2025.10927859

86. P, S. D., An, D., & P, C. (2024). Animal Detection and Recognition in Day Light Videos Using Deep Learning. _2024 2nd International Conference on Networking, Embedded and Wireless Systems (ICNEWS)_. https://doi.org/10.1109/ICNEWS60873.2024.10730894

87. P, S. D., H P, T., N, S. S., Bhat, P. N., & Suresh, A. (2024). Animal Detection and Classification: a Similarity Measure in Realtime Videos. _2024 2nd International Conference on Networking, Embedded and Wireless Systems (ICNEWS)_. https://doi.org/10.1109/ICNEWS60873.2024.10730999

88. Paul, A., Raj, R., Gourisaria, M. K., Jha, A. V., & Bizon, N. (2026). YOLO-HARVEST: A hybrid ViT architecture with locality-enhanced attention for automated wildlife species classification. _Ecological Informatics_. https://doi.org/10.1016/j.ecoinf.2026.103605

89. Pestell, A. J. L., Rendall, A. R., Sinclair, R. D., Ritchie, E. G., Nguyen, D. T., Corva, D. M., et al. (2025). Smart camera traps and computer vision improve detections of small fauna. _Ecosphere_. https://doi.org/10.1002/ecs2.70220

90. Pishdast, H., Kalva, H., & Tye, D. (2025). AI-Enabled Smart Camera Traps for Wildlife Monitoring in African Ecosystems. _Proceedings of the 2025 International Conference on Information Technology for Social Good_. https://doi.org/10.1145/3748699.3749780

91. Polisetty, V. R. M., & Chokkalingam, S. (2024). Efficient Classification of Bird Species Using Photographic Images: A MobileViT Based Approach. _2024 3rd International Conference on Artificial Intelligence For Internet of Things (AIIoT)_. https://doi.org/10.1109/AIIoT58432.2024.10574683

92. Prabhu, S., Sreenath, M., Malavika, V., Om, H., & Swetha, S. (2023). Detection and Recognition of Animals Using Yolo Algorithm. _2023 International Conference on Distributed Computing and Electrical Circuits and Electronics (ICDCECE)_. https://doi.org/10.1109/ICDCECE57866.2023.10150649

93. R, H., M, G., Jaya, T., & Nath, S. S. (2024). Advanced FlexiNet-50 Model for Highly Accurate Multi-Class in Wildlife Monitoring Classification. _2024 5th IEEE Global Conference for Advancement in Technology (GCAT)_. https://doi.org/10.1109/GCAT62922.2024.10924002

94. Rahman, M. A., Mehari Berhe, T., Borgianni, L., Sabbir Ahmed, M., Bua, C., Adami, D., et al. (2025). A Scalable Framework for Deploying AI-Powered Wildlife Monitoring in Resource-Limited Field Environments. _IEEE Access_. https://doi.org/10.1109/ACCESS.2025.3598927

95. Rao V V R, M., N, S., G S L N V S, S., Rao Kurada, R., Ayinavilli, J. S., & K, H. M. (2025). Robust Hybrid CNN-BiGRU based Surveillance System for Wild Animal Detection and Tracking to Enhance Rural Safety and Forestry. _2025 4th International Conference on Distributed Computing and Electrical Circuits and Electronics (ICDCECE)_. https://doi.org/10.1109/ICDCECE65353.2025.11034941

96. Roca, A., Castro, G., Torre, G., Colombo, L. J., Mas, I., Pereira, J., et al. (2025). Detection of Endangered Deer Species Using UAV Imagery: A Comparative Study between Efficient Deep Learning Approaches. _2025 International Conference on Unmanned Aircraft Systems (ICUAS)_. https://doi.org/10.1109/ICUAS65942.2025.11007886

97. Roopa Devi, E. M., Sedhumadhavan, V., Sudharsan, V. K., Rakesh, M., & Surendhar, D. (2024). Wild Animal Recognition using Deep Learning Models. _2024 15th International Conference on Computing Communication and Networking Technologies (ICCCNT)_. https://doi.org/10.1109/ICCCNT61001.2024.10725145

98. Roy, A. M., Bhaduri, J., Kumar, T., & Raj, K. (2023). WilDect-YOLO: An efficient and robust computer vision-based accurate object localization model for automated endangered wildlife detection. _Ecological Informatics_. https://doi.org/10.1016/j.ecoinf.2022.101919

99. Roy, R. R., Raman, R., Amanullah, M., Kumar Pandey, V., & Ganesh, E. N. (2023). IoT Applications in Wildlife Conservation: Tracking and Protecting Endangered Species. _2023 7th International Conference on Electronics, Communication and Aerospace Technology (ICECA)_. https://doi.org/10.1109/ICECA58529.2023.10395145

100. S, D., Bruntha, P. M., G, R., R, J. S. A., & A, K. (2025). Determining the Efficacy of SENet Integrated YOLO Models For Animal Detection. _2025 5th International Conference on Expert Clouds and Applications (ICOECA)_. https://doi.org/10.1109/ICOECA66273.2025.00191

101. Saharan, A., Sharma, B., Sindhal, H., Ruksana, & Malhan, N. (2025). AI For Wildlife Monitoring. _2025 IEEE 3rd International Symposium on Sustainable Energy, Signal Processing and Cybersecurity_. https://doi.org/10.1109/iSSSC66652.2025.11389109

102. Samarin, A., Toropov, A., Mamaeva, A., Savelev, A., Kotenko, E., Nazarenko, A., et al. (2025). Automated Wildlife Detection in Protected Areas with Camera Traps and Deep Learning. _2025 IEEE Ural-Siberian Conference on Biomedical Engineering, Radioelectronics and Information Technology (USBEREIT)_. https://doi.org/10.1109/USBEREIT65494.2025.11054101

103. Sano, Y., Kitano, M., & Yamada, H. (2025). Development of an Automated Monitoring System for Japanese Wild Birds Using Deep Learning. _2025 IEEE 14th Global Conference on Consumer Electronics (GCCE)_. https://doi.org/10.1109/GCCE65946.2025.11274600

104. Santamaria, J. D., Isaza, C., & Giraldo, J. H. (2025). CATALOG: A Camera Trap Language-Guided Contrastive Learning Model. _2025 IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)_. https://doi.org/10.1109/WACV61041.2025.00124

105. Savale, V., Mahadik, S., Waghmare, M., Jadhav, P., & Wakode, N. (2024). Ecological Factors Observation and Animal Identification System. _2024 5th International Conference on Smart Electronics and Communication (ICOSEC)_. https://doi.org/10.1109/ICOSEC61587.2024.10722758

106. Shepley, A., Falzon, G., Meek, P., & Kwan, P. (2021). Automated location invariant animal detection in camera trap images using publicly available data sources. _Ecology and Evolution_. https://doi.org/10.1002/ece3.7344

107. Sravya, P., Vishwakarma, K., Sahu, A., & Panwar, A. (2025). Comparative Analysis of Vgg19 and Efficientnet-B3 for Automated Bird Species Classification Using Deep Learning. _2025 Second International Conference on Pioneering Developments in Computer Science & Digital Technologies (IC2SDT)_. https://doi.org/10.1109/IC2SDT68218.2025.11383721

108. Sree Selva Balaji, A., Arul, V., & Janagiraman, S. (2024). Snake Species Identification Using Deep Learning Technique. _2024 11th International Conference on Reliability, Infocom Technologies and Optimization (Trends and Future Directions) (ICRITO)_. https://doi.org/10.1109/ICRITO61523.2024.10522169

109. Sridhar, P., V, K., R, M., & J, M. K. (2024). Wild Animal Species Detection System using Embedded Devices. _2024 9th International Conference on Communication and Electronics Systems (ICCES)_. https://doi.org/10.1109/ICCES63552.2024.10859668

110. Srinithi, B., Pavadharani, K. N., Sriram, V., & Senthilvadivu, K. (2025). Hybrid ResNet-YOLOv5 Based Deep Learning Framework for Animal Monitoring in Ecosystem. _2025 International Conference on Advanced Computing Technologies (ICoACT)_. https://doi.org/10.1109/ICoACT63339.2025.11004731

111. Su, X., Zhang, J., Ma, Z., Dong, Y., Zi, J., Xu, N., et al. (2024). Identification of Rare Wildlife in the Field Environment Based on the Improved YOLOv5 Model. _Remote Sensing_. https://doi.org/10.3390/rs16091535

112. Sudeepa, P., Seema, P. D., Kumawat, S., Sah, M., & Choudhary, R. C. (2024). Hybrid Deep Learning Framework for Automated Classification of Wildlife Camera Trap Images. _2024 15th International Conference on Computing Communication and Networking Technologies (ICCCNT)_. https://doi.org/10.1109/ICCCNT61001.2024.10724732

113. Sulthana, U., A, M., S, V., J, R., & N, S. (2025). Advanced YOLO v11-Integrated CNN Framework for Efficient and Accurate Animal Recognition. _2025 9th International Conference on Computational System and Information Technology for Sustainable Solutions (CSITSS)_. https://doi.org/10.1109/CSITSS67709.2025.11295052

114. Sun, Z., & Zhang, Y. (2024). Wildlife detection and identification based on the improved YOLOv7. _Fourth International Conference on Computer Vision and Data Mining (ICCVDM 2023)_. https://doi.org/10.1117/12.3021527

115. Sushila Devi, S. V., & Sowmya, V. J. (2025). Automated Wildlife Identification Using CNNs and Transfer Learning Techniques. _2025 6th International Conference on Data Intelligence and Cognitive Informatics (ICDICI)_. https://doi.org/10.1109/ICDICI66477.2025.11134976

116. Teng, C. Y., Connie, T., Choo, K. Y., & Ong Goh, M. K. (2022). A Visual Approach Towards Wildlife Surveillance in Malaysia. _2022 10th International Conference on Information and Communication Technology (ICoICT)_. https://doi.org/10.1109/ICoICT55009.2022.9914861

117. Thangaraj, R., J, C. J., M, S., K, R. S., Sasikumar, S., & S, V. (2023). Automatic Detection and Classification of Wild Animal Species Using YOLO Models. _2023 3rd International Conference on Pervasive Computing and Social Networking (ICPCSN)_. https://doi.org/10.1109/ICPCSN58827.2023.00058

118. Thangaraj, R., P, J., S, L., G, D., & P, J. (2025). Bird Species Detection Using Deep Learning Techniques. _2025 3rd International Conference on Intelligent Systems, Advanced Computing and Communication (ISACC)_. https://doi.org/10.1109/ISACC65211.2025.10969422

119. Tøn, A., Ahmed, A., Imran, A. S., Ullah, M., & Azad, R. M. A. (2024). Metadata augmented deep neural networks for wild animal classification. _Ecological Informatics_. https://doi.org/10.1016/j.ecoinf.2024.102805

120. Um, J., D, M. N., Ravindranath, R. C., Devamane, S. B., G C, L., & Kamble, S. (2024). Mobile Menagerie: Evaluating and Implementing CNNs for Real-Time Animal Species Recognition on Smart Devices. _2024 International Conference on Computational Intelligence for Security, Communication and Sustainable Development (CISCSD)_. https://doi.org/10.1109/CISCSD63381.2024.00046

121. Vatsavayi, V. K., Tirumalasetty, R., Sriram, K. S., Reddy, P. S. C., & Jyothula, S. V. J. M. (2025). VANYAlytics: A YOLO-Based Model for Animal Detection and Classification with Adaptive Fapg Filtering. _2025 IEEE 17th International Conference on Computational Intelligence and Communication Networks (CICN)_. https://doi.org/10.1109/CICN67655.2025.11368115

122. Vijayendrakumar, D., & Kempegowda, B. (2025). A hybrid framework for wild animal classification using fine-tuned DenseNet121 and machine learning classifiers. _IAES International Journal of Artificial Intelligence (IJ-AI)_. https://doi.org/10.11591/ijai.v14.i3.pp2083-2095

123. Viraktamath, S. V., R, J., A, V., Bhat, A. S., & Nayak, S. (2022). Wildlife Monitoring and Surveillance. _2022 International Conference for Advancement in Technology (ICONAT)_. https://doi.org/10.1109/ICONAT53423.2022.9725874

124. Wang, F., He, P., Zhang, T., & Liang, D. (2022). Wildlife detection algorithm based on Inv-YOLOv5m. _2022 Global Reliability and Prognostics and Health Management (PHM-Yantai)_. https://doi.org/10.1109/PHM-Yantai55411.2022.9941895

125. Wang, H., Kuan, T. W., & Yu, X. (2024). Identification of first-level national protected animals based on YOLOv5 and YOLOv8 algorithms. _Proceedings of the 2024 International Conference on Intelligent Computing and its Emerging Applicaton_. https://doi.org/10.1145/3732437.3732758

126. Wang, H., Zhang, S., Zhang, C., Liu, Z., Huang, Q., Ma, X., et al. (2025). Snake-DETR: a lightweight and efficient model for fine-grained snake detection in complex natural environments. _Scientific Reports_. https://doi.org/10.1038/s41598-024-84328-w

127. Wang, K., Yang, F., Chen, Z., Chen, Y., & Zhang, Y. (2023). A Fine-Grained Bird Classification Method Based on Attention and Decoupled Knowledge Distillation. _Animals_. https://doi.org/10.3390/ani13020264

128. Wang, Z., Feng, Z., & Kobayashi, H. (2025). Smarter Animal Detection: Upgrading YOLOv8 with Scalable Attention and Loss Optimization. _2025 5th International Conference on Artificial Intelligence, Big Data and Algorithms (CAIBDA)_. https://doi.org/10.1109/CAIBDA65784.2025.11182845

129. Wei, X. (2025). Hybrid Deep Attention Network-Based Biodiversity Monitoring Using Gabor Wavelet Feature Extraction. _2025 International Conference on Communication, Computer, and Information Technology (IC3IT)_. https://doi.org/10.1109/IC3IT66137.2025.11341540

130. XiaoAn, B., LinQing, Z., XiaoMei, T., Biao, W., QingQi, Z., YuTing, J., et al. (2024). Wildlife target detection based on improved YOLOX-s network. _Scientific Reports_. https://doi.org/10.1038/s41598-024-73631-1

131. Xie, P., Zhuo, W., Wang, X., Deng, S., He, W., & Shen, L. (2026). HitBack: Transformer With Hierarchical-Semantic Cross Attention and Background Contrast for Weakly Supervised Wildlife Semantic Segmentation. _IEEE Transactions on Multimedia_. https://doi.org/10.1109/TMM.2026.3651016

132. Yan, K., Qin, J., Wang, L., Sun, H., Sun, S., & Shi, X. (2024). EA-YOLO: An Endangered Animal Detection Algorithm Incorporating Attention Mechanisms. _2024 5th International Conference on Computer Engineering and Application (ICCEA)_. https://doi.org/10.1109/ICCEA62105.2024.10603685

133. Yang, F., Hu, C., Liang, A., Wang, S., Su, Y., & Xu, F. (2024). CECS-CLIP: Fusing Domain Knowledge for Rare Wildlife Detection Model. _Animals_. https://doi.org/10.3390/ani14192909

134. Yang, W. (2024). Recognition of Local Bird Species of Yunnan Using Transfer Learning Based on ResNet. _2024 IEEE 8th International Conference on Vision, Image and Signal Processing (ICVISP)_. https://doi.org/10.1109/ICVISP64524.2024.10959396

135. Yang, W., Liu, T., Jiang, P., Qi, A., Deng, L., Liu, Z., et al. (2023). A Forest Wildlife Detection Algorithm Based on Improved YOLOv5s. _Animals_. https://doi.org/10.3390/ani13193134

136. Yang, X., Burghardt, T., & Mirmehdi, M. (2023). Dynamic Curriculum Learning for Great Ape Detection in the Wild. _International Journal of Computer Vision_. https://doi.org/10.1007/s11263-023-01748-3

137. Yuvaraju, T., Ravikiran, H. K., Jayanth, J., & Dileep, R. (2024). A Deep Multi-View Learning Approach for Wildlife Animal Detection and Identification. _2024 International Conference on Recent Advances in Science and Engineering Technology (ICRASET)_. https://doi.org/10.1109/ICRASET63057.2024.10895501

138. Zhang, Q., Ahmed, K., Khan, M. I., Wang, H., & Qu, Y. (2026). YOLO-FCE: A feature and clustering enhanced object detection model for species classification. _Pattern Recognition_. https://doi.org/10.1016/j.patcog.2025.112218

139. Zhang, T., Liu, J., Chen, Z., Chen, Y. C., Amoon, M., Kumari, S., et al. (2025). LAMNet: Fine-grained few-shot image classification with LLM-assisted multi-modal learning for urban biodiversity monitoring. _Applied Soft Computing_. https://doi.org/10.1016/j.asoc.2025.113454

140. Zheng, Z., Li, F., & Luo, X. (2026). Research on the Application of EfficientNet-B4 Model Enhanced with Attention Mechanism in Animal Image Classification. _2026 14th International Conference on Intelligent Control and Information Processing (ICICIP)_. https://doi.org/10.1109/ICICIP67436.2026.11417676

141. Zualkernan, I., Dhou, S., Judas, J., Sajun, A. R., Gomez, B. R., & Hussain, L. A. (2022). An IoT System Using Deep Learning to Classify Camera Trap Images on the Edge. _Computers_. https://doi.org/10.3390/computers11010013

142. Zurita, M. J., Riofrío, D., Pérez, N., Romo, D., Benítez, D. S., Moyano, R. F., et al. (2023). Towards Automatic Animal Classification in Wildlife Environments for Native Species Monitoring in the Amazon. _2023 IEEE Colombian Conference on Applications of Computational Intelligence (ColCACI)_. https://doi.org/10.1109/ColCACI59285.2023.10226093

