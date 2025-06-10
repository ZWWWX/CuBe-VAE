<div align="center">
<h1> CuBe-VAE:<br> A Single-Source Pedestrian Trajectory <br>Prediction
Framework <br> Fusing Implicit Causal Inference and Behavioral Inspiration </h1>
<h3>zwwwwwwx
</h3>


<image src="img/CuBe-VAE.png" width="500">

</div>

<div align="center"> <h3> Abstract </h3>  </div>
<div align="justify">

Current pedestrian trajectory prediction methods typically treat the target pedestrian, neighboring pedestrians, and obstacles as a unified system. However, we observe that trajectories inherently encode the full history of pedestrian-environment interactions, and incorporating additional input sources often introduces redundant information that degrades model performance. Moreover, existing approaches rely primarily on correlation-based learning, which fails to capture genuine causal relationships, while traditional causal-inference techniques demand explicit structural assumptions and variable interventions that are difficult to reconcile with end-to-end deep learning frameworks. To address these challenges, we propose CuBe-VAE, a single-source trajectory prediction model composed of four key innovations: (1) We introduce single-source pedestrian trajectory prediction to avoid interaction redundancy caused by excessive environmental interactions. (2) a feature extractor that integrates recurrent neural networks with wavelet transforms to capture both temporal and frequency-domain characteristics; (3) a latent causal-inference mechanism built on a Variational Auto-encoder architecture, which streamlines causal learning and effectively models behavioral stochasticity; and (4) a behavior-inspired decoder that leverages strain-energy concepts to enhance sensitivity to local trajectory variations and employs a trajectory-state attention mechanism to infer latent environmental cues from observed motion. Extensive experiments demonstrate that CuBe-VAE outperforms state-of-the-art methods, delivering more accurate trajectory predictions.</br>


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

