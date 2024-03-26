# AVTrack
### Once our paper is accepted, our code will be open-sourced.


|           |                     |    Tracker   |  Source  | DTB70 |       | UAVDT |       | VisDrone |       | UAV123 |       | UAV123@10fps |       | WebUAV-3M | Avg.FPS |    FLOPs   |  Params  | Avg.FPS |
|:---------:|---------------------|:------------:|:--------:|:-----:|:-----:|:-----:|:-----:|:--------:|:-----:|:------:|:-----:|:------------:|:-----:|:---------:|:-------:|:----------:|:--------:|:-------:|
|           |                     |              |          | Prec. | Succ. | Prec. | Succ. |   Prec.  | Succ. |  Prec. | Succ. |     Prec.    | Succ. |   Prec.   |  Succ.  |            |          |         |
| CNN-based |                     |    TCTrack   |  CVPR 22 |  81.2 |  62.2 |  72.5 |  53.0 |   79.9   |  59.4 |  80.0  |  60.5 |     78.0     |  59.9 |    61.9   |   45.7  |    8.9G    |   10.5M  |  139.6  |
|           |                     |     UDAT     |  CVPR 22 |  80.6 |  61.8 |  80.1 |  59.2 |   81.6   |  61.9 |  76.1  |  59.0 |     77.8     |  58.5 |    64.8   |   48.7  |    23.2G   |   55.1M  |   31.3  |
|           |                     |    ABDNet    |  RAL 23  |  76.8 |  59.6 |  75.5 |  55.3 |   75.0   |  57.2 |  79.3  |  60.7 |     77.3     |  59.1 |    63.9   |   48.7  |    8.3G    |   12.3M  |  125.4  |
|           |                     |    SGDViT    |  ICRA 23 |  78.5 |  60.4 |  65.7 |  48.0 |   72.1   |  52.1 |  75.4  |  57.5 |     86.3     |  66.1 |    61.3   |   45.7  |    11.3G   |   23.3M  |  107.6  |
| ViT-based | LightWeight Tracker |      HiT     |  ICCV 23 |  64.7 |  51.3 |  53.7 |  41.1 |   64.0   |  49.9 |  73.5  |  58.4 |     74.7     |  59.1 |    49.2   |   39.7  |    1.0G    |   9.6M   |  293.4  |
|           |                     |   LiteTrack  | arXiv’23 |  82.5 |  63.9 |  81.6 |  59.3 |   79.7   |  61.4 |  84.2  |  65.9 |     83.1     |  65.0 |    69.4   |   54.1  |    7.3G    |   28.3M  |  140.9  |
|           |                     |    LightFC   |  KBS 24  |  82.8 |  64.3 |  83.4 |  60.6 |   82.7   |  62.8 |  84.2  |  65.5 |     81.3     |  63.7 |    71.2   |   54.5  |    0.95G   |   3.2M   |  143.1  |
|           |                     |     SMAT     |  WACV 24 |  81.9 |  64.0 |  80.8 |  58.7 |   82.5   |  63.4 |  81.8  |  64.6 |     80.4     |  63.5 |    68.9   |   53.9  |    3.2G    |   5.6M   |  121.4  |
|           | UAV Tracker         |  Aba-ViTrack |  ICCV 23 |  85.9 |  66.4 |  83.4 |  59.9 |   86.1   |  65.3 |  86.4  |  66.4 |     85.0     |  65.5 |    70.4   |   55.3  |    2.4G    |   7.9M   |  176.8  |
|           |                     | AVTrack-DeiT |   Ours   |  84.3 |  65.0 |  82.1 |  58.7 |   86.0   |  65.3 |  84.8  |  66.8 |     83.2     |  65.8 |    70.0   |   56.4  | 0.97M-1.9G | 6.6-7.9M |  252.7  |




<table class="tg">
<thead>
  <tr>
    <th class="tg-c3ow" colspan="2"></th>
    <th class="tg-c3ow" rowspan="2">Tracker</th>
    <th class="tg-c3ow" rowspan="2">Source</th>
    <th class="tg-c3ow" colspan="2">DTB70</th>
    <th class="tg-c3ow" colspan="2">UAVDT</th>
    <th class="tg-c3ow" colspan="2">VisDrone</th>
    <th class="tg-c3ow" colspan="2">UAV123</th>
    <th class="tg-c3ow" colspan="2"><span style="font-weight:400;font-style:normal">UAV123@10fps</span></th>
    <th class="tg-c3ow" colspan="2">WebUAV-3M</th>
    <th class="tg-c3ow" rowspan="2">FLOPs</th>
    <th class="tg-c3ow" rowspan="2">Params</th>
    <th class="tg-c3ow" rowspan="2">Avg.FPS</th>
  </tr>
  <tr>
    <th class="tg-c3ow" colspan="2" rowspan="5">CNN-based<br><br><br></th>
    <th class="tg-c3ow">Prec.</th>
    <th class="tg-c3ow">Succ.</th>
    <th class="tg-c3ow">Prec.</th>
    <th class="tg-c3ow">Succ.</th>
    <th class="tg-c3ow">Prec.</th>
    <th class="tg-c3ow">Succ.</th>
    <th class="tg-c3ow">Prec.</th>
    <th class="tg-c3ow">Succ.</th>
    <th class="tg-c3ow">Prec.</th>
    <th class="tg-c3ow">Succ.</th>
    <th class="tg-c3ow">Prec.</th>
    <th class="tg-c3ow">Succ.</th>
  </tr>
</thead>
<tbody>
  <tr>
    <th class="tg-c3ow">TCTrack</th>
    <th class="tg-c3ow">CVPR 22</th>
    <th class="tg-c3ow">81.2</th>
    <th class="tg-c3ow">62.2</th>
    <th class="tg-c3ow">72.5</th>
    <th class="tg-c3ow">53.0</th>
    <th class="tg-c3ow">79.9</th>
    <th class="tg-c3ow">59.4</th>
    <th class="tg-c3ow">80.0</th>
    <th class="tg-c3ow">60.5</th>
    <th class="tg-c3ow">78.0</th>
    <th class="tg-c3ow">59.9</th>
    <th class="tg-c3ow">61.9</th>
    <th class="tg-c3ow">45.7</th>
    <th class="tg-c3ow">8.9G</th>
    <th class="tg-c3ow">10.5M</th>
    <th class="tg-c3ow">139.6</th>
  </tr>
  <tr>
    <th class="tg-c3ow">UDAT</th>
    <th class="tg-c3ow">CVPR 22</th>
    <th class="tg-c3ow">80.6</th>
    <th class="tg-c3ow">61.8</th>
    <th class="tg-c3ow">80.1</th>
    <th class="tg-c3ow">59.2</th>
    <th class="tg-c3ow">81.6</th>
    <th class="tg-c3ow">61.9</th>
    <th class="tg-c3ow">76.1</th>
    <th class="tg-c3ow">59.0</th>
    <th class="tg-c3ow">77.8</th>
    <th class="tg-c3ow">58.5</th>
    <th class="tg-c3ow">64.8</th>
    <th class="tg-c3ow">48.7</th>
    <th class="tg-c3ow">23.2G</th>
    <th class="tg-c3ow">55.1M</th>
    <th class="tg-c3ow">31.3</th>
  </tr>
  <tr>
    <th class="tg-c3ow">ABDNet</th>
    <th class="tg-c3ow">RAL 23</th>
    <th class="tg-c3ow">76.8</th>
    <th class="tg-c3ow">59.6</th>
    <th class="tg-c3ow">75.5</th>
    <th class="tg-c3ow">55.3</th>
    <th class="tg-c3ow">75.0</th>
    <th class="tg-c3ow">57.2</th>
    <th class="tg-c3ow">79.3</th>
    <th class="tg-c3ow">60.7</th>
    <th class="tg-c3ow">77.3</th>
    <th class="tg-c3ow">59.1</th>
    <th class="tg-c3ow">63.9</th>
    <th class="tg-c3ow">48.7</th>
    <th class="tg-c3ow">8.3G</th>
    <th class="tg-c3ow">12.3M</th>
    <th class="tg-c3ow">125.4</th>
  </tr>
  <tr>
    <th class="tg-c3ow">SGDViT</th>
    <th class="tg-c3ow">ICRA 23</th>
    <th class="tg-c3ow">78.5</th>
    <th class="tg-c3ow">60.4</th>
    <th class="tg-c3ow">65.7</th>
    <th class="tg-c3ow">48.0</th>
    <th class="tg-c3ow">72.1</th>
    <th class="tg-c3ow">52.1</th>
    <th class="tg-c3ow">75.4</th>
    <th class="tg-c3ow">57.5</th>
    <th class="tg-c3ow">86.3</th>
    <th class="tg-c3ow">66.1</th>
    <th class="tg-c3ow">61.3</th>
    <th class="tg-c3ow">45.7</th>
    <th class="tg-c3ow">11.3G</th>
    <th class="tg-c3ow">23.3M</th>
    <th class="tg-c3ow">107.6</th>
  </tr>
  <tr>
    <td class="tg-c3ow" rowspan="6">ViT-based</td>
    <td class="tg-0pky" rowspan="4">LightWeight Tracker</td>
    <td class="tg-c3ow">HiT</td>
    <td class="tg-c3ow">ICCV 23</td>
    <td class="tg-c3ow">64.7</td>
    <td class="tg-c3ow">51.3</td>
    <td class="tg-c3ow">53.7</td>
    <td class="tg-c3ow">41.1</td>
    <td class="tg-c3ow">64.0</td>
    <td class="tg-c3ow">49.9</td>
    <td class="tg-c3ow">73.5</td>
    <td class="tg-c3ow">58.4</td>
    <td class="tg-c3ow">74.7</td>
    <td class="tg-c3ow">59.1</td>
    <td class="tg-c3ow">49.2</td>
    <td class="tg-c3ow">39.7</td>
    <td class="tg-c3ow">1.0G</td>
    <td class="tg-c3ow">9.6M</td>
    <td class="tg-c3ow">293.4</td>
  </tr>
  <tr>
    <td class="tg-c3ow">LiteTrack</td>
    <td class="tg-c3ow">arXiv’23</td>
    <td class="tg-c3ow">82.5</td>
    <td class="tg-c3ow">63.9</td>
    <td class="tg-c3ow">81.6</td>
    <td class="tg-c3ow">59.3</td>
    <td class="tg-c3ow">79.7</td>
    <td class="tg-c3ow">61.4</td>
    <td class="tg-c3ow">84.2</td>
    <td class="tg-c3ow">65.9</td>
    <td class="tg-c3ow">83.1</td>
    <td class="tg-c3ow">65.0</td>
    <td class="tg-c3ow">69.4</td>
    <td class="tg-c3ow">54.1</td>
    <td class="tg-c3ow">7.3G</td>
    <td class="tg-c3ow">28.3M</td>
    <td class="tg-c3ow">140.9</td>
  </tr>
  <tr>
    <td class="tg-c3ow">LightFC</td>
    <td class="tg-c3ow">KBS 24</td>
    <td class="tg-c3ow">82.8</td>
    <td class="tg-c3ow">64.3</td>
    <td class="tg-c3ow">83.4</td>
    <td class="tg-c3ow">60.6</td>
    <td class="tg-c3ow">82.7</td>
    <td class="tg-c3ow">62.8</td>
    <td class="tg-c3ow">84.2</td>
    <td class="tg-c3ow">65.5</td>
    <td class="tg-c3ow">81.3</td>
    <td class="tg-c3ow">63.7</td>
    <td class="tg-c3ow">71.2</td>
    <td class="tg-c3ow">54.5</td>
    <td class="tg-c3ow">0.95G</td>
    <td class="tg-c3ow">3.2M</td>
    <td class="tg-c3ow">143.1</td>
  </tr>
  <tr>
    <td class="tg-c3ow">SMAT</td>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">WACV 24</span></td>
    <td class="tg-c3ow">81.9</td>
    <td class="tg-c3ow">64.0</td>
    <td class="tg-c3ow">80.8</td>
    <td class="tg-c3ow">58.7</td>
    <td class="tg-c3ow">82.5</td>
    <td class="tg-c3ow">63.4</td>
    <td class="tg-c3ow">81.8</td>
    <td class="tg-c3ow">64.6</td>
    <td class="tg-c3ow">80.4</td>
    <td class="tg-c3ow">63.5</td>
    <td class="tg-c3ow">68.9</td>
    <td class="tg-c3ow">53.9</td>
    <td class="tg-c3ow">3.2G</td>
    <td class="tg-c3ow">5.6M</td>
    <td class="tg-c3ow">121.4</td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="2">UAV Tracker</td>
    <td class="tg-c3ow">Aba-ViTrack</td>
    <td class="tg-c3ow">ICCV 23</td>
    <td class="tg-c3ow">85.9</td>
    <td class="tg-c3ow">66.4</td>
    <td class="tg-c3ow">83.4</td>
    <td class="tg-c3ow">59.9</td>
    <td class="tg-c3ow">86.1</td>
    <td class="tg-c3ow">65.3</td>
    <td class="tg-c3ow">86.4</td>
    <td class="tg-c3ow">66.4</td>
    <td class="tg-c3ow">85.0</td>
    <td class="tg-c3ow">65.5</td>
    <td class="tg-c3ow">70.4</td>
    <td class="tg-c3ow">55.3</td>
    <td class="tg-c3ow">2.4G</td>
    <td class="tg-c3ow">7.9M</td>
    <td class="tg-c3ow">176.8</td>
  </tr>
  <tr>
    <td class="tg-c3ow"><span style="font-weight:400;font-style:normal">AVTrack-DeiT</span></td>
    <td class="tg-c3ow">Ours</td>
    <td class="tg-c3ow">84.3</td>
    <td class="tg-c3ow">65.0</td>
    <td class="tg-c3ow">82.1</td>
    <td class="tg-c3ow">58.7</td>
    <td class="tg-c3ow">86.0</td>
    <td class="tg-c3ow">65.3</td>
    <td class="tg-c3ow">84.8</td>
    <td class="tg-c3ow">66.8</td>
    <td class="tg-c3ow">83.2</td>
    <td class="tg-c3ow">65.8</td>
    <td class="tg-c3ow">70.0</td>
    <td class="tg-c3ow">56.4</td>
    <td class="tg-c3ow">0.97M-1.9G</td>
    <td class="tg-c3ow">6.6-7.9M</td>
    <td class="tg-c3ow">252.7</td>
  </tr>
</tbody>
</table>
