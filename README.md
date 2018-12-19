# SLU-DATA

Spoken language understanding (SLU) task includes intent identification and slot filling. 
There are datasets for SLU in three types:

1. single-turn query
2. only tagging, without intent
3. multi-turn dialogue

dataset:
<table>
  <tr>
    <td></td>
    <td>Datasets</td>
    <td>Domain</td>
    <td>Vocab</td>
    <td>#Train</td>
    <td>#Test</td>
    <td>#Slot</td>
    <td>#Intent</td>
    <td>language</td>
    <td>paper</td>
    <td>detail</td>
  </tr>
  <tr>
    <td rowspan="2">single-turn</td>
    <td>antis</td>
    <td>1</td>
    <td>722</td>
    <td>4478</td>
    <td>893</td>
    <td>120</td>
    <td>21</td>
    <td>English</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>snips</td>
    <td>>1</td>
    <td>11241</td>
    <td>13084</td>
    <td>700</td>
    <td>72</td>
    <td>7</td>
    <td>English</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="3">only-tagging</td>
    <td>MIT rest.</td>
    <td>1</td>
    <td>4166</td>
    <td>7660</td>
    <td>1521</td>
    <td>17</td>
    <td> - </td>
    <td>English</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>MIT eng.</td>
    <td>1</td>
    <td>7481</td>
    <td>9775</td>
    <td>2443</td>
    <td>25</td>
    <td> - </td>
    <td>English</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>MIT trivia10k13.</td>
    <td>1</td>
    <td>12145</td>
    <td>7816</td>
    <td>1953</td>
    <td>25</td>
    <td> - </td>
    <td>English</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="3">multi-turn dialogue</td>
    <td>DSTC 2</td>
    <td>1</td>
    <td> - </td>
    <td>11677</td>
    <td> 9890 </td>
    <td> w/o BIO-format </td>
    <td> - </td>
    <td>English</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>incarslu</td>
    <td>1</td>
    <td>1145</td>
    <td>10571</td>
    <td> 4882 </td>
    <td> 11 (w/o BIO-format) </td>
    <td> 17 </td>
    <td>English</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>nlpcc</td>
    <td>3</td>
    <td>5443</td>
    <td>4705/21352</td>
    <td>1177/5350</td>
    <td>11</td>
    <td>11</td>
    <td>Chinese</td>
    <td></td>
    <td></td>
  </tr>
</table>
