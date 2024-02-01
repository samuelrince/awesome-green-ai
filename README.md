# Awesome Green AI 🤖🌱

*A curated list of awesome Green AI resources and tools to reduce the environmental impacts of using and deploying AI.*

<div align="center">
  <br/>
  <img src="https://user-images.githubusercontent.com/35747570/205037006-62bcbb00-ce69-4197-b9ab-bd7e30b74dc9.jpg" width="300">
  <p><i>Generated with Stable Diffusion v2</i></p>
  <br/>
</div>

In 2020, Information and Communications Technology (ICT) sector carbon footprint was estimated to be between **2.1-3.9% of total global greenhouse gas emissions**. The ICT sector [continues to grow and now dominates other industries](https://www.economist.com/leaders/2017/05/06/the-worlds-most-valuable-resource-is-no-longer-oil-but-data). It is estimated that the **carbon footprint will double to 6-8% by 2025**. For ICT sector to remain compliant with the Paris Agreement, the industry must reduce by 45% its GHG emissions from 2020 to 2030 and reach net zero by 2050 ([Freitag et al., 2021](https://doi.org/10.1016/j.patter.2021.100340)).

AI is one of the fastest growing sectors, disrupting many other industries ([AI Market Size Report, 2022](https://www.grandviewresearch.com/industry-analysis/artificial-intelligence-ai-market)). It therefore has an important role to play in reducing carbon footprint. The impacts of ICT, and therefore AI, are **not limited to GHG emissions and electricity consumption**. We need to take into account **all major impacts** (abiotic resource depletion, primary energy consumption, water usage, etc.) using Life Cycle Assessment (LCA) ([Arushanyan et al., 2013](https://doi.org/10.1016/j.compind.2013.10.003)).

**AI sobriety not only means optimizing energy consumption and reducing impacts**, but also includes studies on **[indirect impacts](https://en.wikipedia.org/wiki/Rebound_effect_(conservation)#Direct_and_indirect_effects)** and **[rebound effects](https://en.wikipedia.org/wiki/Jevons_paradox)** that can negate all efforts to reduce the environmental footprint ([Willenbacher et al. 2021](https://doi.org/10.1007/978-3-030-88063-7_5)). It is therefore imperative to consider the use of AI before launching a project in order to avoid indirect impacts and rebound effects later on.

All contributions are welcome. Add links through [pull requests](https://github.com/samuelrince/awesome-green-ai/pulls) or create an [issue](https://github.com/samuelrince/awesome-green-ai/issues) to start a discussion.

## 🛠 Tools

### Code-Based Tools

*Tools to measure and compute environmental impacts of AI.*

- [CodeCarbon](https://github.com/mlco2/codecarbon) – Track emissions from Compute and recommend ways to reduce their impact on the environment.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![Mac](https://img.shields.io/badge/Mac-black?style=flat&logo=apple) ![Win](https://img.shields.io/badge/Win-black?style=flat&logo=windows) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia) ![CLI](https://img.shields.io/badge/CLI-black?style=flat&logo=cli)
- [carbontracker](https://github.com/lfwa/carbontracker) – Track and predict the energy consumption and carbon footprint of training deep learning models.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [Eco2AI](https://github.com/sb-ai-lab/Eco2AI) – A python library which accumulates statistics about power consumption and CO2 emission during running code.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [Zeus](https://github.com/SymbioticLab/Zeus) – A framework for deep learning energy measurement and optimization.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [Tracarbon](https://github.com/fvaleye/tracarbon) – Tracks your device's energy consumption and calculates your carbon emissions using your location.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![Mac](https://img.shields.io/badge/Mac-black?style=flat&logo=apple) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [AIPowerMeter](https://github.com/GreenAI-Uppa/AIPowerMeter) – Easily monitor energy usage of machine learning programs.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)

<details>
<summary>☠️ No longer maintained:</summary>

<br>

- [carbonai](https://github.com/Capgemini-Invent-France/CarbonAI) –  Python package to monitor the power consumption of any algorithm.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![Mac](https://img.shields.io/badge/Mac-black?style=flat&logo=apple) ![Win](https://img.shields.io/badge/Win-black?style=flat&logo=windows) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [experiment-impact-tracker](https://github.com/Breakend/experiment-impact-tracker) – A simple drop-in method to track energy usage, carbon emissions, and compute utilization of your system.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [GPU Meter](https://github.com/autoai-incubator/powermeter) – Power Consumption Meter for NVIDIA GPUs.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [PyJoules](https://github.com/powerapi-ng/pyJoules) – A Python library to capture the energy consumption of code snippets.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)

</details>

### Monitoring Tools

*Tools to monitor power consumption and environmental impacts.*

- [Scaphandre](https://github.com/hubblo-org/scaphandre) – A metrology agent dedicated to electrical power consumption metrics.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![Docker](https://img.shields.io/badge/Docker-black?style=flat&logo=docker) ![k8s](https://img.shields.io/badge/k8s-black?style=flat&logo=kubernetes)
- [PowerJoular](https://github.com/joular/powerjoular) – Monitor power consumption of multiple platforms and processes.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![Raspberry](https://img.shields.io/badge/Raspberry-black?style=flat&logo=raspberrypi) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia) ![CLI](https://img.shields.io/badge/CLI-black?style=flat&logo=cli)
- [Boagent](https://github.com/Boavizta/boagent) – Local API and monitoring agent focussed on environmental impacts of the host.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux)
- [vJoule](https://github.com/davidson-consulting/vjoule) – A tool to estimate the energy consumption of your processes.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia) ![CLI](https://img.shields.io/badge/CLI-black?style=flat&logo=cli)
- [jupyter-power-usage](https://github.com/mahendrapaipuri/jupyter-power-usage) – Jupyter extension to display CPU and GPU power usage and carbon emissions.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)


### Optimization Tools

*Tools to optimize energy consumption or environmental impacts.*

- [Zeus](https://github.com/SymbioticLab/Zeus) – A framework for deep learning energy measurement and optimization.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [GEOPM](https://github.com/geopm/geopm) – A framework to enable efficient power management and performance optimizations.<br> ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia) ![k8s](https://img.shields.io/badge/k8s-black?style=flat&logo=kubernetes)


### Calculation Tools

*Tools to estimate environmental impacts of algorithms, models and compute resources.*

* [Boaviztapi](https://github.com/Boavizta/boaviztapi/) - Multi-criteria impacts of compute resources taking into account manufacturing and usage.
* [Datavizta](https://datavizta.boavizta.org/serversimpact) - Compute resources data explorer not limited to AI.
* [EcoDiag](https://ecoinfo.cnrs.fr/ecodiag-calcul/) - Compute carbon footprint of IT resources taking into account manufactuing and usage (🇫🇷 only).
* [Green Algorithms](http://calculator.green-algorithms.org/) - A tool to easily estimate the carbon footprint of a project.
* [MLCarbon](https://github.com/SotaroKaneda/MLCarbon) - End-to-end carbon footprint modeling tool.
* [ML CO2 Impact](https://mlco2.github.io/impact/) - Compute model emissions and add the results to your paper with our generated latex template.

## 📄 Papers

* Energy and Policy Considerations for Deep Learning in NLP - [Strubell et al. (2019)](https://arxiv.org/abs/1906.02243)
* Quantifying the Carbon Emissions of Machine Learning - [Lacoste et al. (2019)](https://arxiv.org/abs/1910.09700)
* Carbontracker: Tracking and Predicting the Carbon Footprint of Training Deep Learning Models - [Anthony et al. (2020)](https://arxiv.org/abs/2007.03051)
* Green AI - [Schwartz et al. (2020)](https://cacm.acm.org/magazines/2020/12/248800-green-ai/fulltext)
* Carbon Emissions and Large Neural Network Training - [Patterson, et al. (2021)](https://arxiv.org/abs/2104.10350)
* Green Algorithms: Quantifying the Carbon Footprint of Computation - [Lannelongue et al. (2021)](https://onlinelibrary.wiley.com/doi/10.1002/advs.202100707)
* Aligning artificial intelligence with climate change mitigation - [Kaack et al. (2021)](https://hal.archives-ouvertes.fr/hal-03368037/document)
* A Pratical Guide to Quantifying Carbon Emissions for Machine Learning researchers and practitioners - [Ligozat et al. (2021)](https://hal.archives-ouvertes.fr/hal-03376391/document)
* Evaluating the carbon footprint of NLP methods: a survey and analysis of existing tools - [Bannour et al.(2021)](https://aclanthology.org/2021.sustainlp-1.2.pdf)
* A Survey on Green Deep Learning - [Xu et al. (2021)](https://arxiv.org/abs/2111.05193)
* Unraveling the Hidden Environmental Impacts of AI Solutions for Environment Life Cycle Assessment of AI Solutions - [Ligozat et al. (2022)](https://arxiv.org/abs/2110.11822)
* Measuring the Carbon Intensity of AI in Cloud Instances - [Dodge et al. (2022)](https://arxiv.org/abs/2206.05229)
* Estimating the Carbon Footprint of BLOOM a 176B Parameter Language Model - [Luccioni et al. (2022)](https://arxiv.org/abs/2211.02001)
* Bridging Fairness and Environmental Sustainability in Natural Language Processing - [Hessenthaler et al. (2022)](https://arxiv.org/abs/2211.04256)
* Eco2AI: carbon emissions tracking of machine learning models as the first step towards sustainable AI - [Budennyy et al. (2022)](https://arxiv.org/abs/2208.00406)
* Environmental assessment of projects involving AI methods - [Lefèvre et al. (2022)](https://hal.science/hal-03922093v1/document)
* Sustainable AI: Environmental Implications, Challenges and Opportunities - [Wu et al. (2022)](https://arxiv.org/abs/2111.00364)
* The Carbon Footprint of Machine Learning Training Will Plateau, Then Shrink - [Patterson et al. (2022)](https://arxiv.org/abs/2204.05149)
* Towards the Systematic Reporting of the Energy and Carbon Footprints of Machine Learning - [Henderson et al. (2022)](https://arxiv.org/abs/2002.05651)
* Towards Sustainable Artificial Intelligence: An Overview of Environmental Protection Uses and Issues - [Pachot et al. (2022)](https://arxiv.org/abs/2212.11738)
* Method and evaluations of the effective gain of artificial intelligence models for reducing CO2 emissions - [Delanoë et al. (2023)](https://www.sciencedirect.com/science/article/pii/S030147972300049X)
* Counting Carbon: A Survey of Factors Influencing the Emissions of Machine Learning - [Luccioni et al. (2023)](https://arxiv.org/abs/2302.08476)
* Making AI Less "Thirsty": Uncovering and Addressing the Secret Water Footprint of AI Models - [Li et al. (2023)](https://arxiv.org/abs/2304.03271)
* Zeus: Understanding and Optimizing GPU Energy Consumption of DNN Training - [You et al. (2023)](https://www.usenix.org/conference/nsdi23/presentation/you)
* Chasing Low-Carbon Electricity for Practical and Sustainable DNN Training - [Yang et al. (2023)](https://www.climatechange.ai/papers/iclr2023/29)
* LLMCarbon: Modeling the End-To-End Carbon Footprint of Large Language Models - [Faiz et al. (2023)](https://arxiv.org/abs/2309.14393)
* Power Hungry Processing: Watts Driving the Cost of AI Deployment? - [Luccioni et al. (2023)](https://arxiv.org/abs/2311.16863)
* Perseus: Removing Energy Bloat from Large Model Training - [Chung et al. (2023)](https://arxiv.org/abs/2312.06902)
