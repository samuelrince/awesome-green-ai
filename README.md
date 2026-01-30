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
- [EcoCompute AI](https://github.com/hongping-zh/ecocompute-ai) – CI/CD gatekeeper that predicts AI training costs and carbon footprint before code merges. Features pre-merge cost prediction, Agent Token FinOps for LLM workflows, and GitHub Actions integration.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![Mac](https://img.shields.io/badge/Mac-black?style=flat&logo=apple) ![Win](https://img.shields.io/badge/Win-black?style=flat&logo=windows) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia) ![CLI](https://img.shields.io/badge/CLI-black?style=flat&logo=cli)
- [CodeCarbon](https://github.com/mlco2/codecarbon) – Track emissions from Compute and recommend ways to reduce their impact on the environment.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![Mac](https://img.shields.io/badge/Mac-black?style=flat&logo=apple) ![Win](https://img.shields.io/badge/Win-black?style=flat&logo=windows) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia) ![CLI](https://img.shields.io/badge/CLI-black?style=flat&logo=cli)
- [carbontracker](https://github.com/lfwa/carbontracker) – Track and predict the energy consumption and carbon footprint of training deep learning models.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [Zeus](https://github.com/SymbioticLab/Zeus) – A framework for deep learning energy measurement and optimization.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [Eco2AI](https://github.com/sb-ai-lab/Eco2AI) – A python library which accumulates statistics about power consumption and CO2 emission during running code.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [EcoLogits](https://github.com/genai-impact/ecologits) – Estimates the energy consumption and environmental footprint of LLM inference through APIs.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![Mac](https://img.shields.io/badge/Mac-black?style=flat&logo=apple) ![Win](https://img.shields.io/badge/Win-black?style=flat&logo=windows) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [Tracarbon](https://github.com/fvaleye/tracarbon) – Tracks your device's energy consumption and calculates your carbon emissions using your location.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![Mac](https://img.shields.io/badge/Mac-black?style=flat&logo=apple) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [AIPowerMeter](https://github.com/GreenAI-Uppa/AIPowerMeter) – Easily monitor energy usage of machine learning programs.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)


<details>
<summary>☠️ No longer maintained:</summary>

<br>

- [carbonai](https://github.com/Capgemini-Invent-France/CarbonAI) – Python package to monitor the power consumption of any algorithm.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![Mac](https://img.shields.io/badge/Mac-black?style=flat&logo=apple) ![Win](https://img.shields.io/badge/Win-black?style=flat&logo=windows) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [experiment-impact-tracker](https://github.com/Breakend/experiment-impact-tracker) – A simple drop-in method to track energy usage, carbon emissions, and compute utilization of your system.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [GATorch](https://github.com/GreenAITorch/GATorch) – An Energy-Aware PyTorch Extension.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [GPU Meter](https://github.com/autoai-incubator/powermeter) – Power Consumption Meter for NVIDIA GPUs.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [PyJoules](https://github.com/powerapi-ng/pyJoules) – A Python library to capture the energy consumption of code snippets.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)

</details>

### Monitoring Tools

*Tools to monitor power consumption and environmental impacts.*

- [Scaphandre](https://github.com/hubblo-org/scaphandre) – A metrology agent dedicated to electrical power consumption metrics.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![Win](https://img.shields.io/badge/Win-black?style=flat&logo=windows) ![Docker](https://img.shields.io/badge/Docker-black?style=flat&logo=docker) ![k8s](https://img.shields.io/badge/k8s-black?style=flat&logo=kubernetes)
- [CodeCarbon](https://github.com/mlco2/codecarbon) – Track emissions from Compute and recommend ways to reduce their impact on the environment.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![Mac](https://img.shields.io/badge/Mac-black?style=flat&logo=apple) ![Win](https://img.shields.io/badge/Win-black?style=flat&logo=windows) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia) ![CLI](https://img.shields.io/badge/CLI-black?style=flat&logo=cli)
- [PowerJoular](https://github.com/joular/powerjoular) – Monitor power consumption of multiple platforms and processes.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![Raspberry](https://img.shields.io/badge/Raspberry-black?style=flat&logo=raspberrypi) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia) ![CLI](https://img.shields.io/badge/CLI-black?style=flat&logo=cli)
- [ALUMET](https://github.com/alumet-dev/alumet) – A modular and efficient software measurement tool.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia) ![CLI](https://img.shields.io/badge/CLI-black?style=flat&logo=cli)
- [cardamon](https://github.com/Root-Branch/cardamon-core) – A tool for measuring the power consumption and carbon footprint of your software.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![Mac](https://img.shields.io/badge/Mac-black?style=flat&logo=apple) ![Win](https://img.shields.io/badge/Win-black?style=flat&logo=windows)
- [Boagent](https://github.com/Boavizta/boagent) – Local API and monitoring agent focussed on environmental impacts of the host.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux)
- [Powerletrics](https://github.com/green-kernel/powerletrics) – PowerLetrics is a framework designed to monitor and analyze power consumption metrics at the process level on Linux.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux)

<details>
<summary>☠️ No longer maintained:</summary>

<br>

- [vJoule](https://github.com/davidson-consulting/vjoule) – A tool to estimate the energy consumption of your processes.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia) ![CLI](https://img.shields.io/badge/CLI-black?style=flat&logo=cli)
- [jupyter-power-usage](https://github.com/mahendrapaipuri/jupyter-power-usage) – Jupyter extension to display CPU and GPU power usage and carbon emissions.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)

</details>


### Optimization Tools

*Tools to optimize energy consumption or environmental impacts.*

- [Zeus](https://github.com/SymbioticLab/Zeus) – A framework for deep learning energy measurement and optimization.<br> ![Linux](https://img.shields.io/badge/Linux-black?style=flat&logo=linux) ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia)
- [GEOPM](https://github.com/geopm/geopm) – A framework to enable efficient power management and performance optimizations.<br> ![GPU](https://img.shields.io/badge/GPU-black?style=flat&logo=nvidia) ![k8s](https://img.shields.io/badge/k8s-black?style=flat&logo=kubernetes)


### Calculation Tools

*Tools to estimate environmental impacts of algorithms, models and compute resources.*

* [Green Algorithms](http://calculator.green-algorithms.org/) - A tool to easily estimate the carbon footprint of a project.
* [ML CO2 Impact](https://mlco2.github.io/impact/) - Compute model emissions and add the results to your paper with our generated latex template.
* [EcoLogits Calculator](https://huggingface.co/spaces/genai-impact/ecologits-calculator) - Estimate energy consumption and environmental impacts of LLM inference.
* [MLCarbon](https://github.com/SotaroKaneda/MLCarbon) - End-to-end carbon footprint modeling tool.
* [Carbon footprint modeling tool](https://borisruf.github.io/carbon-footprint-modeling-tool/ai-scenarios.html) - A data model and a viewer for carbon footprint scenarios.
* [FLOPs to Footprints](https://huggingface.co/spaces/sophia-falk/flops-2-footprints) - Evaluate the resource cost of AI.
* [EcoCompute AI Calculator](https://hongping-zh.github.io/ecocompute-ai/calculator/) - LLM carbon footprint calculator with RTX 5090 benchmark data and smart quantization energy warnings.
Generic tools:

* [Boaviztapi](https://github.com/Boavizta/boaviztapi/) - Multi-criteria impacts of compute resources taking into account manufacturing and usage.
* [Datavizta](https://datavizta.boavizta.org/serversimpact) - Compute resources data explorer not limited to AI.
* [EcoDiag](https://ecoinfo.cnrs.fr/ecodiag-calcul/) - Compute carbon footprint of IT resources taking into account manufactuing and usage (🇫🇷 only).


<details>
<summary>☠️ No longer maintained:</summary>

<br>

* [AI Carbon](https://huggingface.co/spaces/sasha/AI_Carbon) - Estimate your AI model's carbon footprint.
* [GenAI Carbon Footprint](https://github.com/greenscale-ai/genai-carbon-footprint) - A tool to estimate energy use (kWh) and carbon emissions (gCO2eq) from LLM usage.

</details>


### Leaderboards

* [LLM Perf Leaderboad](https://huggingface.co/spaces/optimum/llm-perf-leaderboard) - Benchmarking LLMs on performance and energy.
* [ML.Energy Leaderboard](https://ml.energy/leaderboard/?__theme=light) - Energy consumption of GenAI models at inference.
* [AI Energy Score Leaderboard](https://huggingface.co/spaces/AIEnergyScore/2024_Leaderboard) - Energy efficiency ratings for AI models.


## 📚 Papers

* Energy and Policy Considerations for Deep Learning in NLP - [Strubell et al. (2019)](https://arxiv.org/abs/1906.02243)
* Quantifying the Carbon Emissions of Machine Learning - [Lacoste et al. (2019)](https://arxiv.org/abs/1910.09700)
* Carbontracker: Tracking and Predicting the Carbon Footprint of Training Deep Learning Models - [Anthony et al. (2020)](https://arxiv.org/abs/2007.03051)
* The carbon impact of artificial intelligence. - [Payal Dhar (2020)](https://www.researchgate.net/profile/Payal-Dhar-2/publication/343618995_The_carbon_impact_of_artificial_intelligence/links/63051d3a5eed5e4bd114250a/The-carbon-impact-of-artificial-intelligence.pdf)
* Green AI - [Schwartz et al. (2020)](https://cacm.acm.org/magazines/2020/12/248800-green-ai/fulltext)
* Towards the Systematic Reporting of the Energy and Carbon Footprints of Machine Learning - [Henderson et al. (2020)](https://www.jmlr.org/papers/v21/20-312.html)
* GPU Lifetimes on Titan Supercomputer: Survival Analysis and Reliability - [Ostrouchov et al. (2020)](https://ieeexplore.ieee.org/document/9355319)
* The Energy and Carbon Footprint of Training End-to-End Speech Recognizers - [Parcollet et al. (2021)](https://hal.science/hal-03190119v1/)
* Carbon Emissions and Large Neural Network Training - [Patterson, et al. (2021)](https://arxiv.org/abs/2104.10350)
* Green Algorithms: Quantifying the Carbon Footprint of Computation - [Lannelongue et al. (2021)](https://onlinelibrary.wiley.com/doi/10.1002/advs.202100707)
* Aligning artificial intelligence with climate change mitigation - [Kaack et al. (2021)](https://hal.archives-ouvertes.fr/hal-03368037/document)
* A Practical Guide to Quantifying Carbon Emissions for Machine Learning researchers and practitioners - [Ligozat et al. (2021)](https://hal.archives-ouvertes.fr/hal-03376391/document)
* Unraveling the Hidden Environmental Impacts of AI Solutions for Environment Life Cycle Assessment of AI Solutions - [Ligozat et al. (2022)](https://arxiv.org/abs/2110.11822)
* Measuring the Carbon Intensity of AI in Cloud Instances - [Dodge et al. (2022)](https://arxiv.org/abs/2206.05229)
* Green AI: do deep learning frameworks have different costs? - [Georgiou et al. (2022)](https://discovery.ucl.ac.uk/id/eprint/10143851/1/ml_performance_study_preprint.pdf)
* Estimating the Carbon Footprint of BLOOM a 176B Parameter Language Model - [Luccioni et al. (2022)](https://arxiv.org/abs/2211.02001)
* Bridging Fairness and Environmental Sustainability in Natural Language Processing - [Hessenthaler et al. (2022)](https://arxiv.org/abs/2211.04256)
* Eco2AI: carbon emissions tracking of machine learning models as the first step towards sustainable AI - [Budennyy et al. (2022)](https://arxiv.org/abs/2208.00406)
* Environmental assessment of projects involving AI methods - [Lefèvre et al. (2022)](https://hal.science/hal-03922093)
* Sustainable AI: Environmental Implications, Challenges and Opportunities - [Wu et al. (2022)](https://arxiv.org/abs/2111.00364)
* The Carbon Footprint of Machine Learning Training Will Plateau, Then Shrink - [Patterson et al. (2022)](https://arxiv.org/abs/2204.05149)
* Towards the Systematic Reporting of the Energy and Carbon Footprints of Machine Learning - [Henderson et al. (2022)](https://arxiv.org/abs/2002.05651)
* Towards Sustainable Artificial Intelligence: An Overview of Environmental Protection Uses and Issues - [Pachot et al. (2022)](https://arxiv.org/abs/2212.11738)
* Method and evaluations of the effective gain of artificial intelligence models for reducing CO2 emissions - [Delanoë et al. (2023)](https://www.sciencedirect.com/science/article/pii/S030147972300049X)
* Making AI Less "Thirsty": Uncovering and Addressing the Secret Water Footprint of AI Models - [Li et al. (2023)](https://arxiv.org/abs/2304.03271)
* Zeus: Understanding and Optimizing GPU Energy Consumption of DNN Training - [You et al. (2023)](https://www.usenix.org/conference/nsdi23/presentation/you)
* Trends in AI inference energy consumption: Beyond the performance-vs-parameter laws of deep learning [Desislavov et al. (2023)](https://www.sciencedirect.com/science/article/pii/S2210537923000124)
* Chasing Low-Carbon Electricity for Practical and Sustainable DNN Training - [Yang et al. (2023)](https://www.climatechange.ai/papers/iclr2023/29)
* Toward Sustainable HPC: Carbon Footprint Estimation and Environmental Implications of HPC Systems - [Li et al. (2023)](https://arxiv.org/abs/2306.13177)
* Reducing the Carbon Impact of Generative AI Inference (today and in 2035) - [Chien et al. (2023)](https://dl.acm.org/doi/10.1145/3604930.3605705)
* LLMCarbon: Modeling the End-To-End Carbon Footprint of Large Language Models - [Faiz et al. (2023)](https://arxiv.org/abs/2309.14393)
* The growing energy footprint of artificial intelligence - [De Vries (2023)](https://www.sciencedirect.com/science/article/pii/S2542435123003653)
* Exploring the Carbon Footprint of Hugging Face's ML Models: A Repository Mining Study - [Castano et al. (2023)](https://ieeexplore.ieee.org/document/10304801)
* Exploding AI Power Use: an Opportunity to Rethink Grid Planning and Management - [Lin et al. (2023)](https://arxiv.org/abs/2301.03148)
* Making AI Less "Thirsty": Uncovering and Addressing the Secret Water Footprint of AI Models - [Li et al. (2023)](https://arxiv.org/abs/2304.03271)
* Power Hungry Processing: Watts Driving the Cost of AI Deployment? - [Luccioni et al. (2023)](https://arxiv.org/abs/2311.16863)
* Perseus: Removing Energy Bloat from Large Model Training - [Chung et al. (2023)](https://arxiv.org/abs/2312.06902)
* Timeshifting strategies for carbon-efficient long-running large language model training - [Jagannadharao et al. (2023)](https://link.springer.com/article/10.1007/s11334-023-00546-x)
* From Words to Watts: Benchmarking the Energy Costs of Large Language Model Inference - [Samsi et al. (2023)](https://arxiv.org/pdf/2310.03003)
* Estimating the environmental impact of Generative-AI services using an LCA-based methodology - [Berthelot et al. (2024)](https://hal.univ-lorraine.fr/INRIA/hal-04346102v2)
* Towards Greener LLMs: Bringing Energy-Efficiency to the Forefront of LLM Inference - [Stojkovic et al. (2024)](https://arxiv.org/abs/2403.20306)
* Green AI: Exploring Carbon Footprints, Mitigation Strategies, and Trade Offs in Large Language Model Training - [Liu et al. (2024)](https://arxiv.org/abs/2404.01157)
* Engineering Carbon Emission-aware Machine Learning Pipelines - [Humsom et al. (2024)](https://dl.acm.org/doi/10.1145/3644815.3644943)
* A simplified machine learning product carbon footprint evaluation tool - [Lang et al. (2024)](https://www.sciencedirect.com/science/article/pii/S2666789424000254)
* Measuring and Improving the Energy Efficiency of Large Language Models Inference - [Argerich et al. (2024)](https://ieeexplore.ieee.org/document/10549890)
* Beyond Efficiency: Scaling AI Sustainably - [Wu et al. (2024)](https://arxiv.org/abs/2406.05303)
* The Price of Prompting: Profiling Energy Use in Large Language Models Inference - [Huson et al. (2024)](https://arxiv.org/abs/2407.16893)
* Offline Energy-Optimal LLM Serving: Workload-Based Energy Models for LLM Inference on Heterogeneous Systems - [Wilkins et al. (2024)](https://arxiv.org/abs/2407.04014)
* MLCA: a tool for Machine Learning Life Cycle Assessment - [Morand et al. (2024)](https://hal.science/hal-04643414)
* Hype, Sustainability, and the Price of the Bigger-is-Better Paradigm in AI - [Varoquaux et al. (2024)](https://arxiv.org/abs/2409.14160)
* Addition is All You Need for Energy-efficient Language Models - [Luo et al. (2024)](https://arxiv.org/abs/2410.00907)
* E-waste challenges of generative artificial intelligence - [Wang et al. (2024)](https://www.nature.com/articles/s43588-024-00712-6)
* Green My LLM: Studying the key factors affecting the energy consumption of code assistants - [Coignion et al. (2024)](https://arxiv.org/abs/2411.11892)
* LLM-Inference-Bench: Inference Benchmarking of Large Language Models on AI Accelerators - [Chitty-Venkata et al. (2024)](https://arxiv.org/abs/2411.00136)
* A Beginner's Guide to Power and Energy Measurement and Estimation for Computing and Machine Learning - [Jagannadharao et al. (2024)](https://arxiv.org/abs/2412.17830v1)
* From Efficiency Gains to Rebound Effects: The Problem of Jevons' Paradox in AI's Polarized Environmental Debate - [Luccioni et al. (2025)](https://arxiv.org/abs/2501.16548)
* Understanding the environmental impact of generative AI services - [Berthelot et al. (2025)](https://hal.science/hal-04920612)
* EcoServe: Designing Carbon-Aware AI Inference Systems - [Li et al. (2025)](https://arxiv.org/abs/2502.05043)
* Towards Sustainable NLP: Insights from Benchmarking Inference Energy in Large Language Models - [Poddar et al. (2025)](https://arxiv.org/abs/2502.05610)
* Unveiling Environmental Impacts of Large Language Model Serving: A Functional Unit View - [Wu et al. (2025)](https://arxiv.org/abs/2502.11256)
* Beyond Test-Time Compute Strategies: Advocating Energy-per-Token in LLM Inference - [Wilhelm et al. (2025)](https://dl.acm.org/doi/10.1145/3721146.3721953)
* Frugal AI: Introduction, Concepts, Development and Open Questions - [Arga et al. (2025)](https://www.researchgate.net/publication/390920260_Frugal_AI_Introduction_Concepts_Development_and_Open_Questions)
* Energy Considerations of Large Language Model Inference and Efficiency Optimizations - [Fernandez et al. (2025)](https://arxiv.org/abs/2504.17674)
* The ML.ENERGY Benchmark: Toward Automated Inference Energy Measurement and Optimization - [Chung et al. (2025)](https://arxiv.org/abs/2505.06371)
* How Hungry is AI? Benchmarking Energy, Water, and Carbon Footprint of LLM Inference - [Jegham et al. (2025)](https://arxiv.org/abs/2505.09598)
* Breaking the ICE: Exploring promises and challenges of benchmarks for Inference Carbon & Energy estimation for LLMs - [Sikand et al. (2025)](https://arxiv.org/abs/2506.08727)
* Not All Water Consumption Is Equal: A Water Stress Weighted Metric for Sustainable Computing - [Wu et al. (2025)](https://arxiv.org/abs/2506.22773)
* Measuring the environmental impact of delivering AI at Google Scale - [Elsworth et al. (2025)](https://services.google.com/fh/files/misc/measuring_the_environmental_impact_of_delivering_ai_at_google_scale.pdf)
* More than Carbon: Cradle-to-Grave environmental impacts of GenAI training on the Nvidia A100 GPU - [Falk et al. (2025)](https://arxiv.org/abs/2509.00093) [[supplemental material](https://github.com/sophia-falk/more-than-carbon)]
* Video Killed the Energy Budget: Characterizing the Latency and Power Regimes of Open Text-to-Video Models - [Delavande et al. (2025)](https://arxiv.org/abs/2509.19222)
* Ground-Truthing AI Energy Consumption: Validating CodeCarbon Against External Measurements - [Fischer (2025)](https://arxiv.org/abs/2509.22092)
* Green Prompt Engineering: Investigating the Energy Impact of Prompt Design in Software Engineering - [De Martino et al. (2025)](https://arxiv.org/abs/2509.22320)
* From FLOPs to Footprints: The Resource Cost of Artificial Intelligence - [Falk et al. (2025)](https://arxiv.org/abs/2512.04142)
* Beyond Counting Carbon: AI Environmental Assessments Struggle to Inform Net Impact Decisions - [Cook et al. (2025)](https://doi.org/10.3929/ethz-c-000789254)


### Survey Papers

* Evaluating the carbon footprint of NLP methods: a survey and analysis of existing tools - [Bannour et al.(2021)](https://aclanthology.org/2021.sustainlp-1.2.pdf)
* A Survey on Green Deep Learning - [Xu et al. (2021)](https://arxiv.org/abs/2111.05193)
* A Systematic Review of Green AI - [Verdecchia et al. (2023)](https://arxiv.org/abs/2301.11047)
* Counting Carbon: A Survey of Factors Influencing the Emissions of Machine Learning - [Luccioni et al. (2023)](https://arxiv.org/abs/2302.08476)
* How to estimate carbon footprint when training deep learning models? A guide and review - [Bouza et al. (2023)](https://iopscience.iop.org/article/10.1088/2515-7620/acf81b/meta)
* Towards Efficient Generative Large Language Model Serving: A Survey from Algorithms to Systems - [Miao et al. (2023)](https://arxiv.org/abs/2312.15234)


## 🏢 Reports

* The great challenges of generative AI (🇫🇷 only) - [Data For Good 2023](https://s3.fr-par.scw.cloud/strapi-uploads/Data_For_Good_Livre_Blanc_IA_Generative_v1_0_1_345b2a7454.pdf)
* General framework for frugal AI - [AFNOR 2024](https://www.boutique.afnor.org/en-gb/standard/afnor-spec-2314//fa208976/421140)
* Powering Up Europe: AI Datacenters and Electrification to Drive +c.40%-50% Growth in Electricity Consumption - [Goldman Sachs 2024](https://www.goldmansachs.com/insights/goldman-sachs-research/electrify-now-powering-up-europe)
* Generational Growth — AI/data centers’ global power surge and the sustainability impact - [Goldman Sachs 2024](https://www.goldmansachs.com/insights/goldman-sachs-research/gs-sustain-generational-growth-ai-data-centers-global-power)
* AI and the Environment - International Standards for AI and the Environment - [ITU 2024](https://www.itu.int/dms_pub/itu-t/opb/env/T-ENV-ENV-2024-1-PDF-E.pdf)
* Powering artificial intelligence: a study of AI’s footprint—today and tomorrow - [Deloitte 2024](https://www.deloitte.com/global/en/issues/climate/powering-ai.html)
* Artificial Intelligence and Electricity: A System Dynamics Approach - [Schneider Electric 2024](https://www.se.com/ww/en/insights/sustainability/sustainability-research-institute/artificial-intelligence-electricity-system-dynamics-approach/)
* Developing sustainable Gen AI - [Capgemini 2025](https://www.capgemini.com/gb-en/insights/research-library/sustainable-gen-ai/)
* Exploring the sustainable scaling of AI dilemma: A projective study of corporations' AI environmental impacts - [Capgemini Invent 2025](https://arxiv.org/abs/2501.14334)
* Intelligence artificielle, données, calculs : quelles infrastructures dans un monde décarboné (🇫🇷 only) - [The Shift Project 2025](https://theshiftproject.org/article/rapport-intermediaire-ia/)
* Measuring the environmental impacts of artificial intelligence compute and applications [OECD 2025](https://www.oecd.org/content/dam/oecd/en/publications/reports/2022/11/measuring-the-environmental-impacts-of-artificial-intelligence-compute-and-applications_3dddded5/7babf571-en.pdf)
