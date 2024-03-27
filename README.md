# AVTrack
### Once our paper is accepted, our code will be open-sourced.


---

AVTrack contributes to the field of UAV tracking in several key ways. 
*  Innovative Techniques: We introduce novel approaches, such as the activation module and view-invariant representation via mutual information maximization, which enhance the adaptability and efficiency of the tracking system and can can be integrated easily in existing systems. In contrast to the variable token number approach of Aba-ViTrack, which enhances efficiency in an unstructured manner, our DEEM employs a structured approach, resulting in greater effectiveness. These innovations contribute to advancing the state-of-the-art in UAV tracking technology. 
*   Enhanced Speed: Our method achieves a higher speed than Aba-ViTrack. This advantage becomes more pronounced, specifically,  **81.2 FPS vs. 42.1 FPS**  <u>下划线</u>   when evaluated on the NVIDIA Jetson AGX Xavier 32GB. This increased speed is vital for real-time UAV tracking applications, especially for platforms with limited computational resources and low power consumption requirements. 
*   Balanced Performance: Despite prioritizing speed, AVTrack achieves SOTA performance on multiple UAV tracking benchmarks. AVTrack can serve as a strong baseline for further research.

<table class="tg">
<thead>
  <tr>
    <th class="tg-baqh" colspan="3" rowspan="2">Tracker<br><br><br><br>  </th>
    <th class="tg-baqh" rowspan="2">Source</th>
    <th class="tg-baqh" colspan="2">DTB70</th>
    <th class="tg-baqh" colspan="2">UAVDT</th>
    <th class="tg-baqh" colspan="2">VisDrone</th>
    <th class="tg-baqh" colspan="2">UAV123</th>
    <th class="tg-baqh" colspan="2"><span style="font-style:normal">UAV123@10fps</span></th>
    <th class="tg-baqh" colspan="2">WebUAV-3M</th>
    <th class="tg-baqh" rowspan="2">FLOPs</th>
    <th class="tg-baqh" rowspan="2">Params</th>
    <th class="tg-baqh" rowspan="2">Avg.FPS</th>
  </tr>
  <tr>
    <th class="tg-baqh">Prec.</th>
    <th class="tg-baqh">Succ.</th>
    <th class="tg-baqh">Prec.</th>
    <th class="tg-baqh">Succ.</th>
    <th class="tg-baqh">Prec.</th>
    <th class="tg-baqh">Succ.</th>
    <th class="tg-baqh">Prec.</th>
    <th class="tg-baqh">Succ.</th>
    <th class="tg-baqh">Prec.</th>
    <th class="tg-baqh">Succ.</th>
    <th class="tg-baqh">Prec.</th>
    <th class="tg-baqh">Succ.</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-baqh" colspan="2" rowspan="4">CNN-based</td>
    <td class="tg-baqh">TCTrack</td>
    <td class="tg-baqh">CVPR 22</td>
    <td class="tg-baqh">81.2</td>
    <td class="tg-baqh">62.2</td>
    <td class="tg-baqh">72.5</td>
    <td class="tg-baqh">53.0</td>
    <td class="tg-baqh">79.9</td>
    <td class="tg-baqh">59.4</td>
    <td class="tg-baqh">80.0</td>
    <td class="tg-baqh">60.5</td>
    <td class="tg-baqh">78.0</td>
    <td class="tg-baqh">59.9</td>
    <td class="tg-baqh">61.9</td>
    <td class="tg-baqh">45.7</td>
    <td class="tg-baqh">8.9G</td>
    <td class="tg-baqh">10.5M</td>
    <td class="tg-baqh">139.6</td>
  </tr>
  <tr>
    <td class="tg-baqh">UDAT</td>
    <td class="tg-baqh">CVPR 22</td>
    <td class="tg-baqh">80.6</td>
    <td class="tg-baqh">61.8</td>
    <td class="tg-baqh">80.1</td>
    <td class="tg-baqh">59.2</td>
    <td class="tg-baqh">81.6</td>
    <td class="tg-baqh">61.9</td>
    <td class="tg-baqh">76.1</td>
    <td class="tg-baqh">59.0</td>
    <td class="tg-baqh">77.8</td>
    <td class="tg-baqh">58.5</td>
    <td class="tg-baqh">64.8</td>
    <td class="tg-baqh">48.7</td>
    <td class="tg-baqh">23.2G</td>
    <td class="tg-baqh">55.1M</td>
    <td class="tg-baqh">31.3</td>
  </tr>
  <tr>
    <td class="tg-baqh">ABDNet</td>
    <td class="tg-baqh">RAL 23</td>
    <td class="tg-baqh">76.8</td>
    <td class="tg-baqh">59.6</td>
    <td class="tg-baqh">75.5</td>
    <td class="tg-baqh">55.3</td>
    <td class="tg-baqh">75.0</td>
    <td class="tg-baqh">57.2</td>
    <td class="tg-baqh">79.3</td>
    <td class="tg-baqh">60.7</td>
    <td class="tg-baqh">77.3</td>
    <td class="tg-baqh">59.1</td>
    <td class="tg-baqh">63.9</td>
    <td class="tg-baqh">48.7</td>
    <td class="tg-baqh">8.3G</td>
    <td class="tg-baqh">12.3M</td>
    <td class="tg-baqh">125.4</td>
  </tr>
  <tr>
    <td class="tg-baqh">SGDViT</td>
    <td class="tg-baqh">ICRA 23</td>
    <td class="tg-baqh">78.5</td>
    <td class="tg-baqh">60.4</td>
    <td class="tg-baqh">65.7</td>
    <td class="tg-baqh">48.0</td>
    <td class="tg-baqh">72.1</td>
    <td class="tg-baqh">52.1</td>
    <td class="tg-baqh">75.4</td>
    <td class="tg-baqh">57.5</td>
    <td class="tg-baqh">86.3</td>
    <td class="tg-baqh">66.1</td>
    <td class="tg-baqh">61.3</td>
    <td class="tg-baqh">45.7</td>
    <td class="tg-baqh">11.3G</td>
    <td class="tg-baqh">23.3M</td>
    <td class="tg-baqh">107.6</td>
  </tr>
  <tr>
    <td class="tg-baqh" rowspan="6">ViT-based</td>
    <td class="tg-baqh" rowspan="4">LightWeight Tracker</td>
    <td class="tg-baqh">HiT</td>
    <td class="tg-baqh">ICCV 23</td>
    <td class="tg-baqh">64.7</td>
    <td class="tg-baqh">51.3</td>
    <td class="tg-baqh">53.7</td>
    <td class="tg-baqh">41.1</td>
    <td class="tg-baqh">64.0</td>
    <td class="tg-baqh">49.9</td>
    <td class="tg-baqh">73.5</td>
    <td class="tg-baqh">58.4</td>
    <td class="tg-baqh">74.7</td>
    <td class="tg-baqh">59.1</td>
    <td class="tg-baqh">49.2</td>
    <td class="tg-baqh">39.7</td>
    <td class="tg-baqh">1.0G</td>
    <td class="tg-baqh">9.6M</td>
    <td class="tg-mxrt">293.4</td>
  </tr>
  <tr>
    <td class="tg-baqh">LiteTrack</td>
    <td class="tg-baqh">arXiv’23</td>
    <td class="tg-baqh">82.5</td>
    <td class="tg-baqh">63.9</td>
    <td class="tg-baqh">81.6</td>
    <td class="tg-baqh">59.3</td>
    <td class="tg-baqh">79.7</td>
    <td class="tg-baqh">61.4</td>
    <td class="tg-baqh">84.2</td>
    <td class="tg-baqh">65.9</td>
    <td class="tg-baqh">83.1</td>
    <td class="tg-baqh">65.0</td>
    <td class="tg-baqh">69.4</td>
    <td class="tg-baqh">54.1</td>
    <td class="tg-baqh">7.3G</td>
    <td class="tg-baqh">28.3M</td>
    <td class="tg-baqh">140.9</td>
  </tr>
  <tr>
    <td class="tg-baqh">LightFC</td>
    <td class="tg-baqh">KBS 24</td>
    <td class="tg-baqh">82.8</td>
    <td class="tg-baqh">64.3</td>
    <td class="tg-baqh">83.4</td>
    <td class="tg-baqh">60.6</td>
    <td class="tg-baqh">82.7</td>
    <td class="tg-baqh">62.8</td>
    <td class="tg-baqh">84.2</td>
    <td class="tg-baqh">65.5</td>
    <td class="tg-baqh">81.3</td>
    <td class="tg-baqh">63.7</td>
    <td class="tg-baqh">71.2</td>
    <td class="tg-baqh">54.5</td>
    <td class="tg-baqh">0.95G</td>
    <td class="tg-baqh">3.2M</td>
    <td class="tg-baqh">143.1</td>
  </tr>
  <tr>
    <td class="tg-baqh">SMAT</td>
    <td class="tg-baqh"><span style="font-style:normal">WACV 24</span></td>
    <td class="tg-baqh">81.9</td>
    <td class="tg-baqh">64.0</td>
    <td class="tg-baqh">80.8</td>
    <td class="tg-baqh">58.7</td>
    <td class="tg-baqh">82.5</td>
    <td class="tg-baqh">63.4</td>
    <td class="tg-baqh">81.8</td>
    <td class="tg-baqh">64.6</td>
    <td class="tg-baqh">80.4</td>
    <td class="tg-baqh">63.5</td>
    <td class="tg-baqh">68.9</td>
    <td class="tg-baqh">53.9</td>
    <td class="tg-baqh">3.2G</td>
    <td class="tg-baqh">5.6M</td>
    <td class="tg-baqh">121.4</td>
  </tr>
  <tr>
    <td class="tg-baqh" rowspan="2">UAV Tracker</td>
    <td class="tg-baqh">Aba-ViTrack</td>
    <td class="tg-baqh">ICCV 23</td>
    <td class="tg-baqh">85.9</td>
    <td class="tg-baqh">66.4</td>
    <td class="tg-baqh">83.4</td>
    <td class="tg-baqh">59.9</td>
    <td class="tg-baqh">86.1</td>
    <td class="tg-baqh">65.3</td>
    <td class="tg-baqh">86.4</td>
    <td class="tg-baqh">66.4</td>
    <td class="tg-baqh">85.0</td>
    <td class="tg-baqh">65.5</td>
    <td class="tg-baqh">70.4</td>
    <td class="tg-baqh">55.3</td>
    <td class="tg-baqh">2.4G</td>
    <td class="tg-baqh">7.9M</td>
    <td class="tg-vkwr">176.8</td>
  </tr>
  <tr>
    <td class="tg-baqh"><span style="font-style:normal">AVTrack-DeiT</span></td>
    <td class="tg-baqh">Ours</td>
    <td class="tg-baqh">84.3</td>
    <td class="tg-baqh">65.0</td>
    <td class="tg-baqh">82.1</td>
    <td class="tg-baqh">58.7</td>
    <td class="tg-baqh">86.0</td>
    <td class="tg-baqh">65.3</td>
    <td class="tg-baqh">84.8</td>
    <td class="tg-baqh">66.8</td>
    <td class="tg-baqh">83.2</td>
    <td class="tg-baqh">65.8</td>
    <td class="tg-baqh">70.0</td>
    <td class="tg-baqh">56.4</td>
    <td class="tg-baqh">0.97M-1.9G</td>
    <td class="tg-baqh">6.6-7.9M</td>
    <td class="tg-6ho8">252.7</td>
  </tr>
</tbody>
</table>
