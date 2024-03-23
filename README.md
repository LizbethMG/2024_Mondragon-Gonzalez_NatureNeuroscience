# Closed-loop recruitment of striatal interneurons prevents compulsive-like grooming behaviours.


This is a guide to the code and data for the paper **Mondragón-González, S. L., Schreiweis C, C., & Burguière E, E. (2024). Closed-loop recruitment of striatal parvalbumin interneurons prevents compulsive-like grooming behaviours. Nature Neuroscience**. [Link to Paper.](https://github.com/LizbethMG/2024_Mondragon-Gonzalez_NatureNeuroscience) Each listed repository is dedicated to a specific type of analysis or dataset. Please follow the links provided to explore the repositories in detail.

## Table of Contents
- [Repository 1: Closed-loop - TriFilterNet](#item-one)
- [Repository 2: Data Set 1](#item-two)
- [Repository 3: Analysis LFP](#item-three)
- [Repository 4: Data Set 2](#item-four)
- [Citation](#item-five)

---
<a id="item-one"></a>
## Repository 1: Closed-loop - TriFilterNet
Description: Designed to detect pre-grooming events in mice by analyzing local field potential (LFP) recordings. It uses triangular filters for feature selection, reducing data to a matrix of decorrelated coefficients. These coefficients are the input for an artificial neural network to classify behavioral states. It includes its own demo data.

- **Code**: [Link to code](https://github.com/LizbethMG/NatureNeuroscience_2024_TriFilterNet)
- **Related Data**: [Link to Related Data](https://github.com/LizbethMG/NatureNeuroscience_2024_TriFilterNet/tree/main/demo_data)

<a id="item-two"></a>
## Repository 2: Data Set 1
Description: It features the electrophysiological recordings and the associated grooming markers used in the paper to asses the closed-loop algorithm. The data is compressed and available at the [Open Science Framework](https://osf.io/).

- **Data Repository**: [Link to Data Set 1](https://osf.io/kdmjt/?view_only=7a3e37c708df4d0198d48aa1f59dbb76)
- **DOI: 10.17605/OSF.IO/KDMJT**

<a id="item-three"></a>
## Repository 3: Analysis LFP
Description: This repository contains the local field potential analysis scripts and functions.

- **Code**: [Link to code](https://github.com/LizbethMG/NatureNeuroscience_2024_LFP)
- **Related Data**: Data Set 2

<a id="item-four"></a>
## Repository 4: Data Set 2
Description: It features the electrophysiological recordings in the mice's orbitofrontal cortex around grooming events. The data is available at the [Open Science Framework](https://osf.io/).

- **Data Repository**: [Link to Data Set 2](https://osf.io/kdmjt/?view_only=7a3e37c708df4d0198d48aa1f59dbb76)
- **DOI: 10.17605/OSF.IO/KDMJT**

---
<a id="item-five"></a>
## Citation
If you use this code or data we kindly ask you to cite our paper /data. 

- Mondragon et al 2024: [TODO: DOI here](https://github.com/LizbethMG/Mondragon_NatNeuro_CL)
- Data: DOI 10.17605/OSF.IO/KDMJT

Please check out the following references for more details:

    @article{Mondragon2024,
        title = {Closed-loop recruitment of striatal interneurons prevents compulsive-like grooming behaviours},
        author = {Sirenia Lizbeth Mondragón-González and Christiane Schreiweis and Eric Burguière},
        journal = {Nature Neuroscience},
        year = {2024},
        url = { TODO }}


