# <center> Ahmed Mustafa,&nbsp; Jean-Marc Valin,&nbsp; Jan Büthe,&nbsp; Paris Smaragdis,&nbsp; Mike Goodwin </center>

<br> 
<center>Amazon Web Services &nbsp;&nbsp;&nbsp;&nbsp;   University of Illinois at Urbana-Champaign</center> 

<br>

## Abstract
GAN vocoders are currently one of the state-of-the-art methods for building high-quality neural waveform generative models. However, most of their architectures require dozens of billion floating-point operations per second (GFLOPS) to generate speech waveforms in samplewise manner. This makes GAN vocoders still challenging to run on normal CPUs without accelerators or parallel computers. In this work, we propose a new architecture for GAN vocoders that mainly depends on recurrent and fully-connected networks to directly generate the time domain signal in framewise manner. This results in considerable reduction of the computational cost and enables very fast generation on both GPUs and low-complexity CPUs. Experimental results show that our Framewise WaveGAN vocoder achieves significantly higher quality than auto-regressive maximumlikelihood vocoders such as LPCNet at a very low complexity of 1.2 GFLOPS. This makes GAN vocoders more practical on edge and low-power devices.

### Submitted to <a href="https://2023.ieeeicassp.org/">ICASSP 2023</a>
