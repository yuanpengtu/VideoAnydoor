
<p align="center">

  <h2 align="center">VideoAnydoor : High-fidelity Video Object Insertion with Precise Motion Control</h2>
  <p align="center">
    <a href=""><strong>Yuanpeng Tu</strong></a>
    ·
    <a href="https://scholar.google.com/citations?user=7QvWnzMAAAAJ&hl=zh-CN"><strong>Hao Luo</strong></a>
    ·
    <a href="https://xavierchen34.github.io/"><strong>Xi Chen</strong></a>
    ·
    <a href="https://sihuiji.github.io/"><strong>Sihui Ji</strong></a>
    ·
    <a href="https://scholar.google.com/citations?user=UeltiQ4AAAAJ&hl=en"><strong>Xiang Bai</strong></a>
    <br>
    <a href="https://hszhao.github.io/"><strong>Hengshuang Zhao</strong></a><sup>†</sup>
    <br>
    <br>
        <a href="https://arxiv.org/pdf/2501.01427"><img src='https://img.shields.io/badge/arXiv-VideoAnydoor-red' alt='Paper PDF'></a>
        <a href='https://videoanydoor.github.io/'><img src='https://img.shields.io/badge/Project_Page-VideoAnydoor-blue' alt='Project Page'></a>
        <!-- <a href='https://mp.weixin.qq.com/s/vDR4kPLqnCUwfPiBNKKV9A'><img src='https://badges.aleen42.com/src/wechat.svg'></a> -->
        <!-- <a href='https://huggingface.co/Shuaishuai0219/Animate-X'><img src='https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-Model-yellow'></a> -->
    <br>
    <b></a>HKU &nbsp; | &nbsp; </a> Alibaba DAMO Academy &nbsp; | &nbsp; </a> Hupan Lab &nbsp; | &nbsp; </a> HUST</b>
    <br>
  </p>
</p>

This repository is the official implementation of paper "VideoAnydoor : High-fidelity Video Object Insertion with Precise Motion Control". It can insert/replace diverse objects into the videos with precise motion alignment with the given motion trajectories, where the appearance details of the reference object can be accurately preserved as well.
  <table align="center">
    <tr>
    <td>
      <img src="/assets/teaser.png">
    </td>
    </tr>
  </table>


## &#x1F4CC; Updates
* [2025.1.1] 🔥 Our [paper](https://arxiv.org/pdf/2506.09995) is in public on arxiv.
* [2025.6.12] 🔥 We are now organizing the source code and will release it recently. Sorry for the delay.





## &#x1F304; Gallery
### Demonstration of Motion Video Alignment 
<table class="center">
<tr>
    <td width=98% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/54ebcc16-c2f7-427d-a4c5-f502b3ef66c3" muted="false"></video>
    </td>
</tr>
</table>


### More simulated videos produced by PlayerOne
<table class="center">
<tr>
    <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/ba4e51d0-4386-429f-85dd-28cd097d25fa" muted="false"></video>
    </td>
        <td width=50% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/1132e5e5-0af6-4187-ac4b-34304629046a" muted="false"></video>
    </td>
</tr>
</table>








### Comparisons with previous works

##### from left to right: Ours/Cosmos-7B/Cosmos-14B/Aether

<table class="center">
<tr>
    <td width=100% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/2cfccc9b-7dc1-43f5-8c1f-fa092edfb41c" muted="false"></video>
    </td>
</tr>
</table>
<table class="center">
<tr>
    <td width=100% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/db675e43-9ffb-4fd9-851f-fee8a9cef009" muted="false"></video>
    </td>
</tr>
</table>
<table class="center">
<tr>
    <td width=100% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/7ed03650-82be-4446-a633-cab9420d4945" muted="false"></video>
    </td>
</tr>
</table>
<table class="center">
<tr>
    <td width=100% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/2caaa386-4bea-45ad-b0c5-c58903bdec22" muted="false"></video>
    </td>
</tr>
</table>
<table class="center">
<tr>
    <td width=100% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/e1c83885-fcec-4c08-925b-2597bda57400" muted="false"></video>
    </td>
</tr>
</table>
<table class="center">
<tr>
    <td width=100% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/deb30445-6761-41a6-a5b5-3d1566328e96" muted="false"></video>
    </td>
</tr>
</table>
<table class="center">
<tr>
    <td width=100% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/a41c39fc-f62d-4f13-9e33-2af91a90821b" muted="false"></video>
    </td>
</tr>
</table>

<table class="center">
<tr>
    <td width=100% style="border: none">
        <video controls loop src="https://github.com/user-attachments/assets/ea06e798-98d3-4a51-8f42-e8cf6d94c54e" muted="false"></video>
    </td>
</tr>
</table>


## &#x1F4E7; Acknowledgement
Our implementation is based on [Wanx](https://github.com/modelscope/DiffSynth-Studio). Thanks for their remarkable contribution and released code! If we missed any open-source projects or related articles, we would like to complement the acknowledgement of this specific work immediately.

## &#x2696; License
This repository is released under the Apache-2.0 license as found in the [LICENSE](LICENSE) file.

## &#x1F4DA; Citation
If you find this codebase useful for your research, please use the following entry.
```BibTeX
@misc{tu2025videoanydoorhighfidelityvideoobject,
      title={VideoAnydoor: High-fidelity Video Object Insertion with Precise Motion Control}, 
      author={Yuanpeng Tu and Hao Luo and Xi Chen and Sihui Ji and Xiang Bai and Hengshuang Zhao},
      year={2025},
      journal={arXiv preprint arXiv:2501.01427}, 
}
        

```
