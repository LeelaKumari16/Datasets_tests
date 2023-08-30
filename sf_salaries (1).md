```python
import pandas as pd
x=pd.read_csv("C:/Users/admin/Downloads/Sf_Salaries.csv",encoding="ISO-8859-1")
x
```

    C:\Users\admin\AppData\Local\Temp\ipykernel_8196\276489859.py:2: DtypeWarning: Columns (3,4,5,6,12) have mixed types. Specify dtype option on import or set low_memory=False.
      x=pd.read_csv("C:/Users/admin/Downloads/Sf_Salaries.csv",encoding="ISO-8859-1")
    




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
      <th>Id</th>
      <th>EmployeeName</th>
      <th>JobTitle</th>
      <th>BasePay</th>
      <th>OvertimePay</th>
      <th>OtherPay</th>
      <th>Benefits</th>
      <th>TotalPay</th>
      <th>TotalPayBenefits</th>
      <th>Year</th>
      <th>Notes</th>
      <th>Agency</th>
      <th>Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>NATHANIEL FORD</td>
      <td>GENERAL MANAGER-METROPOLITAN TRANSIT AUTHORITY</td>
      <td>167411.18</td>
      <td>0.0</td>
      <td>400184.25</td>
      <td>NaN</td>
      <td>567595.43</td>
      <td>567595.43</td>
      <td>2011</td>
      <td>NaN</td>
      <td>San Francisco</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>GARY JIMENEZ</td>
      <td>CAPTAIN III (POLICE DEPARTMENT)</td>
      <td>155966.02</td>
      <td>245131.88</td>
      <td>137811.38</td>
      <td>NaN</td>
      <td>538909.28</td>
      <td>538909.28</td>
      <td>2011</td>
      <td>NaN</td>
      <td>San Francisco</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>ALBERT PARDINI</td>
      <td>CAPTAIN III (POLICE DEPARTMENT)</td>
      <td>212739.13</td>
      <td>106088.18</td>
      <td>16452.6</td>
      <td>NaN</td>
      <td>335279.91</td>
      <td>335279.91</td>
      <td>2011</td>
      <td>NaN</td>
      <td>San Francisco</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>CHRISTOPHER CHONG</td>
      <td>WIRE ROPE CABLE MAINTENANCE MECHANIC</td>
      <td>77916.0</td>
      <td>56120.71</td>
      <td>198306.9</td>
      <td>NaN</td>
      <td>332343.61</td>
      <td>332343.61</td>
      <td>2011</td>
      <td>NaN</td>
      <td>San Francisco</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>PATRICK GARDNER</td>
      <td>DEPUTY CHIEF OF DEPARTMENT,(FIRE DEPARTMENT)</td>
      <td>134401.6</td>
      <td>9737.0</td>
      <td>182234.59</td>
      <td>NaN</td>
      <td>326373.19</td>
      <td>326373.19</td>
      <td>2011</td>
      <td>NaN</td>
      <td>San Francisco</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>148649</th>
      <td>148650</td>
      <td>Roy I Tillery</td>
      <td>Custodian</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>2014</td>
      <td>NaN</td>
      <td>San Francisco</td>
      <td>PT</td>
    </tr>
    <tr>
      <th>148650</th>
      <td>148651</td>
      <td>Not provided</td>
      <td>Not provided</td>
      <td>Not Provided</td>
      <td>Not Provided</td>
      <td>Not Provided</td>
      <td>Not Provided</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>2014</td>
      <td>NaN</td>
      <td>San Francisco</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>148651</th>
      <td>148652</td>
      <td>Not provided</td>
      <td>Not provided</td>
      <td>Not Provided</td>
      <td>Not Provided</td>
      <td>Not Provided</td>
      <td>Not Provided</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>2014</td>
      <td>NaN</td>
      <td>San Francisco</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>148652</th>
      <td>148653</td>
      <td>Not provided</td>
      <td>Not provided</td>
      <td>Not Provided</td>
      <td>Not Provided</td>
      <td>Not Provided</td>
      <td>Not Provided</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>2014</td>
      <td>NaN</td>
      <td>San Francisco</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>148653</th>
      <td>148654</td>
      <td>Joe Lopez</td>
      <td>Counselor, Log Cabin Ranch</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>-618.13</td>
      <td>0.00</td>
      <td>-618.13</td>
      <td>-618.13</td>
      <td>2014</td>
      <td>NaN</td>
      <td>San Francisco</td>
      <td>PT</td>
    </tr>
  </tbody>
</table>
<p>148654 rows × 13 columns</p>
</div>




```python
x.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 148654 entries, 0 to 148653
    Data columns (total 13 columns):
     #   Column            Non-Null Count   Dtype  
    ---  ------            --------------   -----  
     0   Id                148654 non-null  int64  
     1   EmployeeName      148654 non-null  object 
     2   JobTitle          148654 non-null  object 
     3   BasePay           148049 non-null  object 
     4   OvertimePay       148654 non-null  object 
     5   OtherPay          148654 non-null  object 
     6   Benefits          112495 non-null  object 
     7   TotalPay          148654 non-null  float64
     8   TotalPayBenefits  148654 non-null  float64
     9   Year              148654 non-null  int64  
     10  Notes             0 non-null       float64
     11  Agency            148654 non-null  object 
     12  Status            38119 non-null   object 
    dtypes: float64(3), int64(2), object(8)
    memory usage: 14.7+ MB
    


```python
x.groupby("BasePay").mean()
```

    C:\Users\admin\AppData\Local\Temp\ipykernel_7460\3853933728.py:1: FutureWarning: The default value of numeric_only in DataFrameGroupBy.mean is deprecated. In a future version, numeric_only will default to False. Either specify numeric_only or select only columns which should be valid for the function.
      x.groupby("BasePay").mean()
    




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
      <th>Id</th>
      <th>TotalPay</th>
      <th>TotalPayBenefits</th>
      <th>Year</th>
      <th>Notes</th>
    </tr>
    <tr>
      <th>BasePay</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>-166.01</th>
      <td>72833.00</td>
      <td>83.01</td>
      <td>89.57</td>
      <td>2012.0</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>-121.63</th>
      <td>72866.00</td>
      <td>61.07</td>
      <td>66.51</td>
      <td>2012.0</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>-109.22</th>
      <td>72873.00</td>
      <td>54.61</td>
      <td>58.93</td>
      <td>2012.0</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>-106.6</th>
      <td>72875.00</td>
      <td>53.30</td>
      <td>57.96</td>
      <td>2012.0</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>-101.88</th>
      <td>72879.00</td>
      <td>51.20</td>
      <td>55.75</td>
      <td>2012.0</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>9991.53</th>
      <td>142974.00</td>
      <td>9991.53</td>
      <td>14008.74</td>
      <td>2014.0</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>9997.15</th>
      <td>143970.00</td>
      <td>10318.22</td>
      <td>10421.40</td>
      <td>2014.0</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>9998.60</th>
      <td>142583.00</td>
      <td>9998.60</td>
      <td>15824.17</td>
      <td>2014.0</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>9999.59</th>
      <td>144091.00</td>
      <td>9999.59</td>
      <td>9999.59</td>
      <td>2014.0</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>Not Provided</th>
      <td>148650.75</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>2014.0</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>109900 rows × 5 columns</p>
</div>




```python
x.groupby("OvertimePay").max()
```

    C:\Users\admin\AppData\Local\Temp\ipykernel_11412\1407306027.py:1: FutureWarning: Dropping invalid columns in DataFrameGroupBy.max is deprecated. In a future version, a TypeError will be raised. Before calling .max, select only columns which should be valid for the function.
      x.groupby("OvertimePay").max()
    




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
      <th>Id</th>
      <th>EmployeeName</th>
      <th>JobTitle</th>
      <th>BasePay</th>
      <th>OtherPay</th>
      <th>Benefits</th>
      <th>TotalPay</th>
      <th>TotalPayBenefits</th>
      <th>Year</th>
      <th>Notes</th>
      <th>Agency</th>
    </tr>
    <tr>
      <th>OvertimePay</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
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
      <th>-0.01</th>
      <td>90715</td>
      <td>Claudia M Sanchez</td>
      <td>Senior Eligibility Worker</td>
      <td>75033.03</td>
      <td>1540.0</td>
      <td>28864.64</td>
      <td>76573.02</td>
      <td>105437.66</td>
      <td>2013</td>
      <td>NaN</td>
      <td>San Francisco</td>
    </tr>
    <tr>
      <th>0.0</th>
      <td>131071</td>
      <td>Zuri Jones</td>
      <td>ZOO CURATOR</td>
      <td>319275.01</td>
      <td>400184.25</td>
      <td>96570.66</td>
      <td>567595.43</td>
      <td>567595.43</td>
      <td>2014</td>
      <td>NaN</td>
      <td>San Francisco</td>
    </tr>
    <tr>
      <th>0.02</th>
      <td>44426</td>
      <td>Leonid Vaynshteyn</td>
      <td>Maintenance Planner</td>
      <td>97435.01</td>
      <td>9587.68</td>
      <td>41501.43</td>
      <td>107022.71</td>
      <td>148524.14</td>
      <td>2012</td>
      <td>NaN</td>
      <td>San Francisco</td>
    </tr>
    <tr>
      <th>0.52</th>
      <td>99025</td>
      <td>Pamela J Walker</td>
      <td>Deputy Sheriff</td>
      <td>48955.57</td>
      <td>5090.12</td>
      <td>17354.01</td>
      <td>54046.21</td>
      <td>71400.22</td>
      <td>2013</td>
      <td>NaN</td>
      <td>San Francisco</td>
    </tr>
    <tr>
      <th>0.77</th>
      <td>33722</td>
      <td>JANIEN BISHOP</td>
      <td>PUBLIC SERVICE AIDE-SPECIAL PROGRAMS</td>
      <td>3940.53</td>
      <td>26.07</td>
      <td>NaN</td>
      <td>3967.37</td>
      <td>3967.37</td>
      <td>2011</td>
      <td>NaN</td>
      <td>San Francisco</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>9968.07</th>
      <td>136073</td>
      <td>Jocelyn F Romero-Toloafa</td>
      <td>Nurses Staffing Assistant</td>
      <td>42161.53</td>
      <td>952.54</td>
      <td>22502.44</td>
      <td>53082.14</td>
      <td>75584.58</td>
      <td>2014</td>
      <td>NaN</td>
      <td>San Francisco</td>
    </tr>
    <tr>
      <th>997.69</th>
      <td>146533</td>
      <td>Jonathan L Dees</td>
      <td>Junior Clerk</td>
      <td>2264.36</td>
      <td>0.00</td>
      <td>32.62</td>
      <td>3262.05</td>
      <td>3294.67</td>
      <td>2014</td>
      <td>NaN</td>
      <td>San Francisco</td>
    </tr>
    <tr>
      <th>997.76</th>
      <td>134159</td>
      <td>Charles D Kesecker</td>
      <td>Transit Fare Inspector</td>
      <td>55358.41</td>
      <td>280.41</td>
      <td>27941.98</td>
      <td>56636.58</td>
      <td>84578.56</td>
      <td>2014</td>
      <td>NaN</td>
      <td>San Francisco</td>
    </tr>
    <tr>
      <th>9971.17</th>
      <td>132726</td>
      <td>Simon Lam</td>
      <td>Assistant Cook</td>
      <td>50955.01</td>
      <td>1177.20</td>
      <td>27046.53</td>
      <td>62103.38</td>
      <td>89149.91</td>
      <td>2014</td>
      <td>NaN</td>
      <td>San Francisco</td>
    </tr>
    <tr>
      <th>Not Provided</th>
      <td>148653</td>
      <td>Not provided</td>
      <td>Not provided</td>
      <td>Not Provided</td>
      <td>Not Provided</td>
      <td>Not Provided</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>2014</td>
      <td>NaN</td>
      <td>San Francisco</td>
    </tr>
  </tbody>
</table>
<p>66555 rows × 11 columns</p>
</div>




```python
x.groupby('EmployeeName')['JobTitle'].value_counts()
```




    EmployeeName           JobTitle                 
    A BERNARD FATOOH       SHERIFF'S PROPERTY KEEPER    1
    A Bernard  Fatooh      Sheriff's Property Keeper    1
    A Bernard Fatooh       Sheriff's Property Keeper    2
    A ELIZABETH MARCHASIN  PRINCIPAL CLERK              1
    A JAMIL NIAZI          IS ENGINEER - PRINCIPAL      1
                                                       ..
    Zun Jin Zhang He       Custodian                    2
    Zuna Luu               Custodian                    1
    Zuna T Luu             Custodian                    2
    Zuri  Jones            Deputy Probation Officer     1
    Zuri Jones             Deputy Probation Officer     2
    Name: JobTitle, Length: 119698, dtype: int64




```python
y=x[x['EmployeeName']=="JOSEPH DRISCOLL"]
y
```




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
      <th>Id</th>
      <th>EmployeeName</th>
      <th>JobTitle</th>
      <th>BasePay</th>
      <th>OvertimePay</th>
      <th>OtherPay</th>
      <th>Benefits</th>
      <th>TotalPay</th>
      <th>TotalPayBenefits</th>
      <th>Year</th>
      <th>Notes</th>
      <th>Agency</th>
      <th>Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>24</th>
      <td>25</td>
      <td>JOSEPH DRISCOLL</td>
      <td>CAPTAIN, FIRE SUPPRESSION</td>
      <td>140546.86</td>
      <td>97868.77</td>
      <td>31909.28</td>
      <td>NaN</td>
      <td>270324.91</td>
      <td>270324.91</td>
      <td>2011</td>
      <td>NaN</td>
      <td>San Francisco</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>




```python
x.JobTitle.count()
```




    148654




```python
k=x[x['EmployeeName']=="JOSEPH DRISCOLL"]['TotalPayBenefits']
```




    EmployeeName
    A BERNARD FATOOH          20039.91
    A Bernard  Fatooh         29379.24
    A Bernard Fatooh          30153.03
    A ELIZABETH MARCHASIN     26282.86
    A JAMIL NIAZI             87496.21
                               ...    
    Zun Jin Zhang He          84972.76
    Zuna Luu                  79957.94
    Zuna T Luu                82151.22
    Zuri  Jones               94714.11
    Zuri Jones               122350.86
    Name: TotalPayBenefits, Length: 110811, dtype: float64




```python
x['JobTitle'].value_counts().head(5)
```




    Transit Operator                7036
    Special Nurse                   4389
    Registered Nurse                3736
    Public Svc Aide-Public Works    2518
    Police Officer 3                2421
    Name: JobTitle, dtype: int64




```python

```
