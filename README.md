# Awesome Green AI 🤖🌱

*A curated list of awesome Green AI resources and tools to reduce the environmental impacts of using and deploying AI.*

In 2020, Information and Communications Technology (ICT) sector carbon footprint was estimated to be between 2.1-3.9% of total global greenhouse gas emissions. The ICT sector [continues to grow and now dominates other industries](https://www.economist.com/leaders/2017/05/06/the-worlds-most-valuable-resource-is-no-longer-oil-but-data). It is estimated that the carbon footprint will double to 6-8% by 2025. For ICT sector to remain compliant with the Paris Agreement, the industry must reduce by 45% its GHG emissions from 2020 to 2030 and reach net zero by 2050 ([Freitag et al., 2021](https://doi.org/10.1016/j.patter.2021.100340)).

AI is one of the fastest growing sectors, disrupting many other industries ([AI Market Size Report, 2022](https://www.grandviewresearch.com/industry-analysis/artificial-intelligence-ai-market)). It therefore has an important role to play in reducing carbon footprint. The impacts of ICT, and therefore AI, are not limited to GHG emissions and electricity consumption. We need to take into account all major impacts (abiotic resource depletion, primary energy consumption, water usage, etc.) using Life Cycle Assessment (LCA) ([Arushanyan et al., 2013](https://doi.org/10.1016/j.compind.2013.10.003)).

AI sobriety not only means optimizing energy consumption and reducing impacts, but also includes studies on [indirect impacts](https://en.wikipedia.org/wiki/Rebound_effect_(conservation)#Direct_and_indirect_effects) and [rebound effects](https://en.wikipedia.org/wiki/Jevons_paradox) that can negate all efforts to reduce the environmental footprint ([Willenbacher et al. 2021](https://doi.org/10.1007/978-3-030-88063-7_5)). It is therefore imperative to consider the use of AI before launching a project in order to avoid indirect impacts and rebound effects later on.

All contributions are welcome. Add links through [pull requests](https://github.com/samuelrince/awesome-green-ai/pulls) or create an [issue](https://github.com/samuelrince/awesome-green-ai/issues) to start a discussion.

## Tools

### Integrated Tools

*Tools to measure and compute environmental impacts of AI.*

* [AIPowerMeter](https://github.com/GreenAI-Uppa/AIPowerMeter) - Easily monitor energy usage of machine learning programs.
* [carbontracker](https://github.com/lfwa/carbontracker) - Track and predict the energy consumption and carbon footprint of training deep learning models.
* [CodeCarbon](https://github.com/mlco2/codecarbon) - Track emissions from Compute and recommend ways to reduce their impact on the environment.
* [experiment-impact-tracker](https://github.com/Breakend/experiment-impact-tracker) - A simple drop-in method to track energy usage, carbon emissions, and compute utilization of your system.
* [GPU Meter](https://github.com/autoai-incubator/powermeter) - Power Consumption Meter for NVIDIA GPUs.

Other honorable mentions of non-AI targeted power consumption and environmental impacts projects:

* [Boagent](https://github.com/Boavizta/boagent) - Local API and monitoring agent focussed on environmental impacts of the host.
* [PowerJoular](https://gitlab.com/joular/powerjoular) - Monitor power consumption of multiple platforms and processes.
* [Scaphandre](https://github.com/hubblo-org/scaphandre) - A metrology agent dedicated to electrical power consumption metrics.

### Calculation Tools

* [Green Algorithms](http://calculator.green-algorithms.org/) - A tool to easily estimate the carbon footprint of a project.
* [ML CO2 Impact](https://mlco2.github.io/impact/) - Compute model emissions and add the results to your paper with our generated latex template.

## Papers

* Energy and Policy Considerations for Deep Learning in NLP - [Strubell et al. (2019)](https://arxiv.org/pdf/1906.02243.pdf)
* Carbontracker: Tracking and Predicting the Carbon Footprint of Training
Deep Learning Models - [Anthony et al. (2020)](https://arxiv.org/pdf/2007.03051.pdf)
* Green AI - [Schwartz et al. (2020)](https://cacm.acm.org/magazines/2020/12/248800-green-ai/fulltext)
* Green Algorithms: Quantifying the Carbon Footprint of Computation - [Lannelongue et al. (2021)](https://onlinelibrary.wiley.com/doi/10.1002/advs.202100707)
* Aligning artificial intelligence with climate change mitigation - [Haack et al. (2021)](https://hal.archives-ouvertes.fr/hal-03368037/document)
* Unraveling the Hidden Environmental Impacts of AI Solutions for Environment Life Cycle Assessment of AI Solutions - [Ligozat et al. (2022)](https://arxiv.org/pdf/2110.11822.pdf)
* Measuring the Carbon Intensity of AI in Cloud Instances - [Dodge et al. (2022)](https://arxiv.org/pdf/2206.05229.pdf)
* Estimating the Carbon Footprint of BLOOM a 176B Parameter Language Model - [Luccioni et al. (2022)](https://arxiv.org/pdf/2211.02001.pdf)
* Bridging Fairness and Environmental Sustainability in Natural Language Processing - [Hessenthaler et al. (2022)](https://arxiv.org/pdf/2211.04256.pdf)
