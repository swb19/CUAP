[//]: # (# PMBP)

[//]: # ([Wenbo Shao]&#40;https://scholar.google.com/citations?user=nJgFCn0AAAAJ&hl=zh-CN&oi=ao&#41;)
[//]: # (Wenbo Shao, Boqi Li, Wenhao Yu, Jiahui Xu, Hong Wang)

[//]: # ()
[//]: # (- School of Vehicle and Mobility, Tsinghua University )

[//]: # (- Department of Civil and Environmental Engineering, University of Michigan )

[//]: # (- School of Mechanical Engineering, Beijing Institute of Technology)

<p align="center">
<img src="src/paper_1.png" width="500" alt="curve">
</p>

# 1. Abstract
Autonomous driving systems face significant challenges in navigating complex, dynamic environments rife with uncertainty.  This study proposes a comprehensive uncertainty management framework for prediction-planning systems, which simultaneously models three key uncertainties: short-term aleatoric uncertainty (SAU), long-term aleatoric uncertainty (LAU), and epistemic uncertainty (EU). Leveraging Gaussian mixture models (GMMs) to capture SAU and LAU and deep ensemble techniques to estimate EU, the framework enables concurrent quantification of all uncertainty types. Then, a Comprehensive Uncertainty-Aware Planning (CUAP) approach is developed, integrating customized risk models and a two-stage training strategy to enhance predictive reliability. By establishing a unified foundation for decision-making, the framework addresses the limitations of traditional methods that handle uncertainties in isolation. The contributions include a thorough investigation of uncertainty estimation techniques, risk modeling, and planning strategies, validated through rigorous evaluations using the CommonRoad benchmark and perception-limited scenarios. Results demonstrate substantial improvements over current approaches, particularly in diverse traffic conditions, with the framework enhancing planning accuracy and reliability by integrating multiple uncertainties. This study offers detailed insights into applying uncertainty management from prediction to planning, highlighting its potential to significantly improve autonomous driving performance, especially in accident prevention, through comprehensive uncertainty integration.

# 2. Method Overview

Proposed unified prediction and planning framework that considers different types of uncertainties.
![img.png](src/paper_2.png)



The modeled uncertainties and their combinations, as well as various uncertainty-aware risk models.


<p align="center">

<img src="src/paper_4.png" width="800" alt="curve">

</p>

[//]: # ()
[//]: # ()
[//]: # (The process of uncertainty-aware planning.)

[//]: # ()
[//]: # (<p align="center">)

[//]: # (<img src="src/paper_5.png" width="800" alt="curve">)

[//]: # (</p>)


<!-- # 3. Experimental Results

## 3.1. Planning under Aleatoric Uncertainty

<p align="center">

<img src="src/table_2.png" width="500" alt="curve">

</p>



## 3.2. Planning with Consideration of Epistemic Uncertainty

<p align="center">

<img src="src/table_3.png" width="500" alt="curve">

</p>


## 3.3. Analysis of Comprehensive Risk Model

<p align="center">

<img src="src/table_6.png" width="500" alt="curve">

</p>



## 3.4. Testing under Limited Perception

<p align="center">

<img src="src/table_7.png" width="900" alt="curve">

</p>



## 3.5. Analysis of Typical Cases


<p align="center">

<img src="src/paper_6.png" width="900" alt="curve">

<img src="src/paper_7.png" width="900" alt="curve">

</p> -->



[//]: # (## 3.6. Citation)

[//]: # ()
[//]: # (```)

[//]: # ()
[//]: # (@article{shao2023likely,)

[//]: # ()
[//]: # (  title={When Is It Likely to Fail? Performance Monitor for Black-Box Trajectory Prediction Model},)

[//]: # ()
[//]: # (  author={Shao, Wenbo and Li, Boqi and Yu, Wenhao and Xu, Jiahui and Wang, Hong},)

[//]: # ()
[//]: # (  journal={IEEE Transactions on Automation Science and Engineering},)

[//]: # ()
[//]: # (  year={2023},)

[//]: # ()
[//]: # (  publisher={IEEE})

[//]: # ()
[//]: # (})

[//]: # ()
[//]: # (```)

# 3. Visaualization

[//]: # (## 4.1. SAU)

| <video muted controls width=380> <source src="./src/PR/USA_Lanker-2_18_T-1.mp4"  type="video/mp4"> </video> | <video muted controls width=380> <source src="./src/PR/USA_Lanker-2_22_T-1.mp4"  type="video/mp4"> </video> |

| <video muted controls width=380> <source src="./src/PR/USA_US101-26_1_T-1.mp4"  type="video/mp4"> </video> | <video muted controls width=380> <source src="./src/PR/ZAM_Tjunction-1_442_T-1.mp4"  type="video/mp4"> </video> |

| <video muted controls width=380> <source src="./src/PR/DEU_Flensburg-35_1_T-1.mp4"  type="video/mp4"> </video> | <video muted controls width=380> <source src="./src/PR/USA_Lanker-2_1_T-1.mp4"  type="video/mp4"> </video> |

| <video muted controls width=380> <source src="./src/PR/USA_Peach-4_6_T-1.mp4"  type="video/mp4"> </video> | <video muted controls width=380> <source src="./src/PR/DEU_Lohmar-58_1_T-1.mp4"  type="video/mp4"> </video> |


# 4. Contact
If you have any questions, feel free to contact Wenbo Shao ([swb19@mails.tsinghua.edu.cn](swb19@mails.tsinghua.edu.cn)).
