# San-Francisco-Crime-Classification
<p>
As a part of the kaggle competion, San Franscisco Crime Classification is predictive analytics problem of predicting the criminal occurances in the city of San Francisco. San Franscisco released publically released their dataset on Kaggle and People have worked on this data to predict the category of crime based on the below feature<br>
</p>
  
<p>
  
 **Target:**<br>
     Category: The Type of the crime

 **Features:** <br>
     Dates:  Timestamp of the crime incident<br>
     Descript: Detail Description of the crime incident<br>
     DayOfWeek: The day of the Week<br>
     pdDistrict: Name of the Police Department District<br>
     <sup> ** </sup>Resolution: How the incident was resolved<br>
     Address: Approximate Streep address of the crime incident<br>
     X: Longitude of the location<br>
     Y: Lattitude of the location<br>
** This column is causing a data leakage as it is leaking an information from the future as it will not be available when the incident happends, so we will discraad this feature
</p> 


References:
    <ol><li><a href="https://www.kaggle.com/c/sf-crime/data">https://www.kaggle.com/c/sf-crime/data</a></li>
    <li><a href="https://arxiv.org/pdf/1607.03626.pdf">https://arxiv.org/pdf/1607.03626.pdf</a></li></ol>
