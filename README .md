<div align="center">
<h1> CuBe-VAE:<br> A Single-Source Pedestrian Trajectory Prediction
Framework <br> Fusing Implicit Causal Inference and Behavioral Inspiration </h1>
<h3>zwwwwwwx
</h3>


<image src="img/CuBe-VAE.png" width="500">

</div>

<div align="center"> <h3> Abstract </h3>  </div>
<div align="justify">

This paper presents CuBe-VAE, a novel pedestrian trajectory prediction approach based on Variational
Autoencoder (VAE) framework that achieves high-precision prediction by leveraging multi-level
information contained solely in single trajectory data. Unlike mainstream methods relying on social
interactions and complex scene information, we focus on single-source trajectory prediction, providing
viable solutions for information-constrained scenarios. We innovatively apply implicit causal inference through the VAE architecture to establish causal relationships from observed trajectories to future
behaviors, effectively capturing uncertainties in pedestrian decision-making processes. Meanwhile,
we incorporate two behavioral insights: local decision-making characteristics and implicit environmental awareness, enabling the model to understand subtle behavioral changes when pedestrians
encounter obstacles or make turns. The model integrates innovative designs including decompositioncompression dual-path feature extraction, VAE-based implicit causal inference framework, strain
energy-inspired trajectory evaluation mechanism, and trajectory state attention, achieving effective
extraction and fusion of multi-level trajectory information. Experimental results demonstrate that
our method significantly reduces prediction errors on multiple datasets including ETH-UCY, SDD,
and NBA SportVU. This research breaks through the limitations of traditional trajectory prediction
paradigms, proving that using only multi-level information contained in single trajectories can achieve
or even exceed the performance of models dependent on complex social and scene information.</br>


## Model Training
### Setup
**Environment**
<br>All models were trained and tested on Ubuntu 20.04 with Python 3.8 and PyTorch 2.0.1 with CUDA 11.7.

**Dataset**
<br>Preprocessed [ETH](https://data.vision.ee.ethz.ch/cvl/aem/ewap_dataset_full.tgz) and [UCY](https://graphics.cs.ucy.ac.cy/research/downloads/crowd-data) datasets are released in this repository. 
The train/test splits are the same as those found in [SocialCircle](https://github.com/cocoon2wong/SocialCircle).


<br>

### Coming Soon!

<br>

