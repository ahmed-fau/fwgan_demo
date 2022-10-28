# <center>Framewise WaveGAN: High Speed Adversarial Vocoder in Time Domain with Very Low Computational Complexity</center>

<br> 

<center> Ahmed Mustafa,&nbsp; Jean-Marc Valin,&nbsp; Jan Büthe,&nbsp; Paris Smaragdis,&nbsp; Mike Goodwin </center>

<br> 
<center><p><em>Amazon Web Services &nbsp;&nbsp;&nbsp;&nbsp;   University of Illinois at Urbana-Champaign</em></p></center> 

<br>

## Abstract:
<p>GAN vocoders are currently one of the state-of-the-art methods for building high-quality neural waveform generative models. However, most of their architectures require dozens of billion floating-point operations per second (GFLOPS) to generate speech waveforms in samplewise manner. This makes GAN vocoders still challenging to run on normal CPUs without accelerators or parallel computers. In this work, we propose a new architecture for GAN vocoders that mainly depends on recurrent and fully-connected networks to directly generate the time domain signal in framewise manner. This results in considerable reduction of the computational cost and enables very fast generation on both GPUs and low-complexity CPUs. Experimental results show that our Framewise-WaveGAN vocoder achieves significantly higher quality than auto-regressive maximumlikelihood vocoders such as LPCNet at a very low complexity of 1.2 GFLOPS. This makes GAN vocoders more practical on edge and low-power devices.</p>

<p><b>Submitted to <a href="https://2023.ieeeicassp.org/">ICASSP 2023</a></b> (Preprint will be released soon).</p>

<br> 

## Before you listen:
<ul>
  <li><p>The normal voice samples in this demo are obtained from the publicly-available datasets: the <a href="https://datashare.ed.ac.uk/handle/10283/2950">VCTK</a>, provided under <a href= "https://datashare.ed.ac.uk/bitstream/handle/10283/3443/license_text?sequence=3&isAllowed=y"> creative commons license</a> & the <a href="http://www.festvox.org/cmu_arctic/">CMU ARCTIC Database</a> </p></li>
  <li>Tea</li>
  <li>Milk</li>
</ul>



