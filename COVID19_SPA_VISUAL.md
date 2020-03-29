# COVID-19 in SPAIN

Official Data Source: https://www.mscbs.gob.es/

Official Data in pdf (2020-03-03 to 2020-03-27):

Official Data in .csv (2020-03-03 to 2020-03-27):

    1) COVID19_SPA.csv the data correspond to the whole of the Spanish State. 
    2) COVID19_SPA_AC.csv the data has been classified by Autonomous Communities (Regions).

## Dataset Info

Each dataset contains 9 columns: 

* **Region**
* **Date**
* <sup>1</sup> **Total** : Total Confirmed Cases. 
* <sup>2</sup> **AI(14d)** : Accumulated Incidence in the last 14 days.
* <sup>3 </sup><sup>4</sup> **Hospitalized**
* <sup>4</sup> **ICU**
* <sup>3</sup> **Deads** 
* <sup>3</sup> **Recovered** 
* **New** : New Confirmed Cases

<sup>1</sup> The Total Confirmed Cases do not come from the sum of Hospitalized, Recovered and Dead patients, since they are not exclusive.

<sup>2</sup> AI: Accumulated incidence (cases accumulated per 100,000 inhabitants).

<sup>3</sup> Dead and Recovered patients may have been hospitalized and therefore compute in both
groups. 

<sup>4</sup> Patients who have required ICU also compute in patients who have been hospitalized.



<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th></th>
      <th>Total</th>
      <th>AI (14d)</th>
      <th>Hospitalized</th>
      <th>ICU</th>
      <th>Deads</th>
      <th>Recovered</th>
      <th>New</th>
    </tr>
    <tr>
      <th>Region</th>
      <th>Date</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th rowspan="22" valign="top">SPAIN</th>
      <th>2020-03-03</th>
      <td>150</td>
      <td>0.32</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-04</th>
      <td>198</td>
      <td>0.42</td>
      <td>NaN</td>
      <td>7.0</td>
      <td>1.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-05</th>
      <td>237</td>
      <td>0.51</td>
      <td>NaN</td>
      <td>9.0</td>
      <td>3.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-06</th>
      <td>365</td>
      <td>0.78</td>
      <td>NaN</td>
      <td>11.0</td>
      <td>5.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-09</th>
      <td>999</td>
      <td>2.14</td>
      <td>NaN</td>
      <td>68.0</td>
      <td>16.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-10</th>
      <td>1622</td>
      <td>3.48</td>
      <td>NaN</td>
      <td>100.0</td>
      <td>35.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-11</th>
      <td>2128</td>
      <td>4.55</td>
      <td>NaN</td>
      <td>142.0</td>
      <td>47.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-12</th>
      <td>2950</td>
      <td>6.29</td>
      <td>NaN</td>
      <td>190.0</td>
      <td>84.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-13</th>
      <td>4209</td>
      <td>8.99</td>
      <td>NaN</td>
      <td>272.0</td>
      <td>120.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-16</th>
      <td>9191</td>
      <td>19.30</td>
      <td>NaN</td>
      <td>432.0</td>
      <td>309.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-17</th>
      <td>11178</td>
      <td>23.45</td>
      <td>NaN</td>
      <td>563.0</td>
      <td>491.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-18</th>
      <td>13716</td>
      <td>28.75</td>
      <td>NaN</td>
      <td>774.0</td>
      <td>598.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-19</th>
      <td>17147</td>
      <td>35.96</td>
      <td>NaN</td>
      <td>939.0</td>
      <td>767.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-20</th>
      <td>19980</td>
      <td>41.71</td>
      <td>NaN</td>
      <td>1141.0</td>
      <td>1002.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-21</th>
      <td>24926</td>
      <td>52.18</td>
      <td>13282.0</td>
      <td>1612.0</td>
      <td>1326.0</td>
      <td>NaN</td>
      <td>4946.0</td>
    </tr>
    <tr>
      <th>2020-03-22</th>
      <td>28572</td>
      <td>59.64</td>
      <td>15554.0</td>
      <td>1785.0</td>
      <td>1720.0</td>
      <td>NaN</td>
      <td>3646.0</td>
    </tr>
    <tr>
      <th>2020-03-23</th>
      <td>33089</td>
      <td>68.24</td>
      <td>18374.0</td>
      <td>2355.0</td>
      <td>2182.0</td>
      <td>3355.0</td>
      <td>4517.0</td>
    </tr>
    <tr>
      <th>2020-03-24</th>
      <td>39673</td>
      <td>80.91</td>
      <td>22762.0</td>
      <td>2636.0</td>
      <td>2696.0</td>
      <td>3794.0</td>
      <td>6584.0</td>
    </tr>
    <tr>
      <th>2020-03-25</th>
      <td>47610</td>
      <td>96.56</td>
      <td>26960.0</td>
      <td>3166.0</td>
      <td>3434.0</td>
      <td>5367.0</td>
      <td>7937.0</td>
    </tr>
    <tr>
      <th>2020-03-26</th>
      <td>56188</td>
      <td>113.03</td>
      <td>31912.0</td>
      <td>3679.0</td>
      <td>4089.0</td>
      <td>7015.0</td>
      <td>8578.0</td>
    </tr>
    <tr>
      <th>2020-03-27</th>
      <td>64059</td>
      <td>127.27</td>
      <td>36293.0</td>
      <td>4165.0</td>
      <td>4858.0</td>
      <td>9357.0</td>
      <td>7871.0</td>
    </tr>
    <tr>
      <th>2020-03-28</th>
      <td>72248</td>
      <td>141.09</td>
      <td>40630.0</td>
      <td>4575.0</td>
      <td>5690.0</td>
      <td>12285.0</td>
      <td>8189.0</td>
    </tr>
  </tbody>
</table>
</div>



<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th></th>
      <th>Total</th>
      <th>AI (14d)</th>
      <th>Hospitalized</th>
      <th>ICU</th>
      <th>Deads</th>
      <th>Recovered</th>
      <th>New</th>
    </tr>
    <tr>
      <th>Region</th>
      <th>Date</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th rowspan="5" valign="top">Andalucía</th>
      <th>2020-03-03</th>
      <td>13</td>
      <td>0.15</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-04</th>
      <td>13</td>
      <td>0.15</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-05</th>
      <td>12</td>
      <td>0.14</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-06</th>
      <td>21</td>
      <td>0.25</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2020-03-09</th>
      <td>54</td>
      <td>0.64</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>...</th>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th rowspan="5" valign="top">País-Vasco</th>
      <th>2020-03-24</th>
      <td>2728</td>
      <td>114.73</td>
      <td>1425.0</td>
      <td>106.0</td>
      <td>133.0</td>
      <td>344.0</td>
      <td>307.0</td>
    </tr>
    <tr>
      <th>2020-03-25</th>
      <td>3271</td>
      <td>139.60</td>
      <td>1577.0</td>
      <td>119.0</td>
      <td>155.0</td>
      <td>466.0</td>
      <td>543.0</td>
    </tr>
    <tr>
      <th>2020-03-26</th>
      <td>3946</td>
      <td>164.99</td>
      <td>1907.0</td>
      <td>137.0</td>
      <td>180.0</td>
      <td>621.0</td>
      <td>675.0</td>
    </tr>
    <tr>
      <th>2020-03-27</th>
      <td>4601</td>
      <td>189.51</td>
      <td>2270.0</td>
      <td>154.0</td>
      <td>207.0</td>
      <td>814.0</td>
      <td>655.0</td>
    </tr>
    <tr>
      <th>2020-03-28</th>
      <td>5136</td>
      <td>209.03</td>
      <td>2612.0</td>
      <td>176.0</td>
      <td>221.0</td>
      <td>1023.0</td>
      <td>535.0</td>
    </tr>
  </tbody>
</table>
<p>418 rows × 7 columns</p>
</div>


### COVID19 in the Spanish State

Data Visualization of COVID19_SPA.csv


![png](COVID19_SPA_VISUAL_files/COVID19_SPA_VISUAL_5_0.png)



![png](COVID19_SPA_VISUAL_files/COVID19_SPA_VISUAL_6_0.png)



![png](COVID19_SPA_VISUAL_files/COVID19_SPA_VISUAL_7_0.png)



![png](COVID19_SPA_VISUAL_files/COVID19_SPA_VISUAL_8_0.png)


### Percentage growth of new cases 
* $i$, day
* $N_i$, new cases on day $i$ 
* Percentage growth of new cases, $\frac{N_{i}-N_{i-1}}{N_{i-1}}100 (\%)$

Notable changes in the percentage growth of reported new cases:
 * 2020-03-06 
    + **+228.2%** more new cases than on 2020-03-05.
 * 2020-03-07  **No Data**.
 * 2020-03-08  **No Data**.
 * 2020-03-09 
    + **+395.3%** more new cases than on 2020-03-06. 
 * 2020-03-16
    + **+295.7%** more new cases than on 2020-03-15.
    + **Lockdown measures are implemented**
    

### COVID19 in the Basque Country
Data Visualization of COVID19_SPA_AC.csv


![png](COVID19_SPA_VISUAL_files/COVID19_SPA_VISUAL_11_0.png)



![png](COVID19_SPA_VISUAL_files/COVID19_SPA_VISUAL_12_0.png)



![png](COVID19_SPA_VISUAL_files/COVID19_SPA_VISUAL_13_0.png)



![png](COVID19_SPA_VISUAL_files/COVID19_SPA_VISUAL_14_0.png)


### COVID19 compare regions 

Select regions:

['Andalucía', 'Aragón', 'Asturias', 'Baleares', 'Canarias', 'Cantabria', 'Castilla-La-Mancha', 'Castilla-y-León', 'Cataluña', 'Ceuta', 'C-Valenciana', 'Extremadura', 'Galicia', 'Madrid', 'Melilla', 'Murcia', 'Navarra', 'País-Vasco', 'La-Rioja']


![png](COVID19_SPA_VISUAL_files/COVID19_SPA_VISUAL_16_0.png)

