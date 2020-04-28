# Brazilian Sign Language Recognition in Healthcare Center

## Objective:

In this researcg work, we aimed to recognize the common lexical signs used by Brazilian deaf into healthcare  centers  based on Kinect v2. Our approach only uses depth images to extract robust hand-crafted features and classified based on DTW (Dynamic Time Warping) and k-NN (k Nearest Neighbor) algorithms.

## Materials and Methods

* Materials:
  
  First, we choose 107 medical signs selected from common dialogues in health-care centers.
  
  Next, signs were recorded using a Kinect v2 sensor which provides color, depth, and skeleton data. The signer perfomed each sign in a stop-motion fashiong six times. 
    
* Methods:

  Depth images have shown their ability to provide both the geometric information and new discHistogram of Oriented Point Cloud Vectorsriminative features, so we dediced to asses the feasibility of depth images to recognize isolated signs of the Brazilian Sign Language  (BSL).
  
  * Temporal segmentation of sign based on stop--motion of the body skeleton.
  * Selection of the ROI (region of interest).
  * Compute features named Histogram of Direction Cosines (or another such as [Histogram of Oriented Point Cloud Vectors](https://doi.org/10.1007/978-3-030-16053-1_55)) after the depth image is mapped to a point cloud.
  * DTW and k-NN as classifier.
  * Model assessment in a context dependent fashion.


## Dataset
As follows, we present the 107 signs both in English and Portuguese.

Signs |
--------- |
Sicken, Medical scheduling, Now, Severe, Needle, Allergy, Tomorrow, Tonsillitis, Year, Anxiety, Appendicitis, Heart attack, Well, Bronchitis, Head, Mumps, Surgery, Pill, Medical consultation, Contusion, Chronic, To heal, His, Delirium,  Insanity, Dengue, Tooth, Depression, Brain stroke, Dehydration, Diabetes, Disease, To ache, Headache, Electrocardiogram, He, Address, Nursing, Sprain, Poisoning, Stable, Stethoscope, Stomach, I, Medical exam, Fever, Fracture, Future, Flu, Bleeding, Hepatitis, Hypertension, Today, Hospital, Age, Unstable, Respiratory infection, Injection, Intoxication, To go, Laceration, Injury, Knife injury, Gun injury, Slight, Hurt, Doctor, My, Die, Very/Too, To cannot, To want not, To have not, Nausea, Name, Yesterday, Hearing people, Past, Kidney stone, Chest, To can, A few, Need, Clinic history, Psychosis, Lung, Burs, To want, X-rays, Medical prescription, Remedy, Medical risk, Bad,  Salmonella, Healthy, To feel, Your, Yes, Deaf people, To have, Dizziness, Cough, Vaccine, To come, You, Vomit |


Sinais |
--------- |
Adoecer , Agendar , Agora , Agudo , Agulha , Alergia , Amanha , Amigdalites , Ano , Ansiedade , Apendicites , Ataque_Cardiaco , Bem , Bronquite , Cabeca , Caxumba , Cirurgia , Comprimido , Consultar , Contusao , Cronico , Curar , Dele , Delirio , Demencia , Dengue , Dente , Depressao , Derrame_Cerebral , Desidratacao , Diabete , Doenca , Doer , Dor_Cabeca , Eletrocardiograma , Ele , Endereco , Enfermagem , Entorser , Envenenar , Estavel , Estetoscopio , Estomago , Eu , Exame_Medico , Febre , Fraturar , Futuro , Gripe , Hemorragia , Hepatite , Hipertensao , Hoje , Hospital , Idade , Inestavel , Infecao_Respiratoria , Injetar , Intoxicacao , Ir , Laceracao , Lesao , Lesao_Faca , Lesao_Pistola , Leve , Mal , Medico , Meu , Morir , Muito , Nao , Nao_Poder , Nao_Querer , Nao_Ter , Nausea , Nome , Ontem , Ouvinte , Passado , Pedra_Rim , Peito , Poder , Pouco , Precisar , Prontuario , Psicose , Pulmao , Queimado , Querer , Raiosx , Receita_Medica , Remedio , Risco , Ruim , Salmonela , Saudavel , Sentir , Seu , Sim , Surdo , Ter , Tontura , Tos , Vacinar , Vir , Voce , Vomito |


## How to cite:

If your are interested, please read our [paper](https://doi.org/10.1007/978-3-319-48881-3_27).

And the bibtex entry is:

@inproceedings{YauriVidalon2016,
author = {{Yauri Vidal{\'{o}}n}, Jos{\'{e}} El{\'{i}}as and {De Martino}, Jos{\'{e}} Mario},
booktitle = {ECCV 2016 Workshops},
editor = {Hua, Gang and J{\'{e}}gou, Herv{\'{e}}},
isbn = {978-3-319-48881-3},
pages = {391--402},
publisher = {Springer International Publishing},
title = {{Brazilian Sign Language Recognition Using Kinect}},
year = {2016}
}

