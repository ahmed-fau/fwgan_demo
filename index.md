## <center>Ahmed Mustafa,&nbsp; Jean-Marc Valin,&nbsp; Jan Büthe,&nbsp; Paris Smaragdis,&nbsp; Mike Goodwin</center>

<br>

<center><p><b>Amazon Web Services &nbsp;&nbsp;&nbsp;&nbsp;   University of Illinois at Urbana-Champaign</b></p></center> 

<br>

### Abstract:
<p>GAN vocoders are currently one of the state-of-the-art methods for building high-quality neural waveform generative models. However, most of their architectures require dozens of billion floating-point operations per second (GFLOPS) to generate speech waveforms in samplewise manner. This makes GAN vocoders still challenging to run on normal CPUs without accelerators or parallel computers. In this work, we propose a new architecture for GAN vocoders that mainly depends on recurrent and fully-connected networks to directly generate the time domain signal in framewise manner. This results in considerable reduction of the computational cost and enables very fast generation on both GPUs and low-complexity CPUs. Experimental results show that our Framewise-WaveGAN vocoder achieves significantly higher quality than auto-regressive maximumlikelihood vocoders such as LPCNet at a very low complexity of 1.2 GFLOPS. This makes GAN vocoders more practical on edge and low-power devices.</p>

<p>Submitted to <a href="https://2023.ieeeicassp.org/">ICASSP 2023</a> (Preprint will be released soon).</p>

<br> 

### Before you listen:
<ul>
  <li>The normal voice samples in this demo are obtained from the publicly-available datasets: 
    <ul>
      <li><p>The <a href="https://datashare.ed.ac.uk/handle/10283/2950">VCTK</a>, provided under <a href= "https://datashare.ed.ac.uk/bitstream/handle/10283/3443/license_text?sequence=3&isAllowed=y"> creative commons license</a></p></li>
      <li><p>The <a href="http://www.festvox.org/cmu_arctic/">CMU ARCTIC Database</a>, &#169; Carnegie Mellon University, 2003, All Rights Reserved, <a href="./cmu_arctic_report.pdf">license</a>.</p></li></ul></li>
  <li><p>Both datasets were not used in training the vocoders in this demo.</p></li>
  <li><p>The singing voice samples in this demo are obtained from the official demo of <a href="https://arxiv.org/abs/2210.07508"> this paper</a>. We don not train the vocoders on any singing voice datasets. This is just to show the pitch consistency of the two vocoders when generating unseen expressive speech samples.</p></li>
</ul>

<br> 

### Normal Voice Samples:

<table align="center"  style="text-align: center;">
  <thead>
    <tr>
      <th style="text-align: center;">LPCNet 1.2GFLOPS</th>
      <th style="text-align: center;">Framewise WaveGAN 1.2GFLOPS (Proposed)</th>
      <th style="text-align: center;">Original</th>
    </tr>
  </thead>
  <tbody>
      <tr>
      
      <td><audio  controls="" style="width:150px;" preload="auto">
            <source src="wavs/lpcnet/v1.wav"></audio></td>
      <td><audio  controls="" style="width:150px;" preload="auto">
            <source src="wavs/fwgan/v1.wav"></audio></td>
      <td><audio  controls="" style="width:150px;" preload="auto">
            <source src="wavs/original/v1.wav"></audio></td>
    </tr>
    <tr>
    
      <td><audio  controls="" style="width:150px;" preload="auto">
            <source src="wavs/lpcnet/v7.wav"></audio></td>
      <td><audio  controls="" style="width:150px;" preload="auto">
            <source src="wavs/fwgan/v7.wav"></audio></td>
      <td><audio  controls="" style="width:150px;" preload="auto">
            <source src="wavs/original/v7.wav"></audio></td>

    </tr>
    <tr>
     
      <td><audio  controls="" style="width:150px;" preload="auto">
            <source src="wavs/GT/English-Elvis_139.wav"></audio></td>
      <td><audio  controls="" style="width:150px;" preload="auto">
            <source src="wavs/PWG/English-Elvis_139.wav"></audio></td>
      <td><audio  controls="" style="width:150px;" preload="auto">
            <source src="wavs/PG/English-Elvis_139.wav"></audio></td>

    </tr>
  </tbody>
</table>

    
<br>


