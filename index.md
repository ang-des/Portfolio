## Selected projects in Data Analysis

---

<b>Excel</b><br>
▪️ [Lariat Rental Car Company](https://github.com/ang-des/Lariat-Rental-Car) <br> 
▪️ [Home Pricing Factors](https://github.com/ang-des/home-prices-business-research/tree/main) <br>
 
<br> 

<b>SQL</b><br> 
▪️ [Product Purchases Queries](https://github.com/ang-des/SQL-1) <br> 
▪️ [Housing Prices Data](https://github.com/ang-des/SQL-2) <br> 
▪️ [Pet Salon Transactions](https://github.com/ang-des/SQL-3) <br> 
▪️ [Department of Education Data](https://github.com/ang-des/SQL-4) <br> 

<br> 

<b>Tableau</b><br>
▪️ 

<br>

<b>Python</b><br>
▪️ [Parkinson's](https://colab.research.google.com/drive/18lTk5HN1K5WvP4qbRxJwRKtg_Kf-2R1C?usp=sharing) <br>
▪️ [Penguins](https://colab.research.google.com/drive/1e3e5BRmFl2pVdOpsSO-O8MflEGFSHiOB?usp=sharing) <br>
▪️ [World University Rankings](https://colab.research.google.com/drive/1WO3QqJixv08cXFjEThK39HdO_tyPQnGn#scrollTo=LRTEiUSB7PM9) <br>

<br>

---

### Business Analysis - Revenue Growth Models
### Lariat Rent-A-Car
<p align="center">
<img width="600" src="images/Lariat.jpeg?raw=true"/>
</p>

<p>
Lariat Car Rental Company is committed to driving sustainable growth and optimizing its financial performance. With a strategic focus on profitability and cost efficiency, the company has established the following goals to align its operations:
<br>
<ul>
  <li>Revenue Maximization</li>
  <li>Cost Reduction and Efficiency</li>
  <li>Effective Asset Management</li>
  <li>Customer Experience Enhancement</li>
  <li>and Continuous Performace Monitoring</li>
</ul>
Lariat Car Rental Company aims to achieve sustainable profitability, maintain a competitive edge in the market, and deliver exceptional value to its customers while lowering business costs.
</p>

<p>
Three strategies were created to meet these goals, they are listed below:
<ol>
  <li>Increase the total number of vehicles in the Fleet</li>
  <li>Increase the number of total number of rentals in a year</li>
  <li>To sell (x) number of vehicles that bring in the lowest profit and replace them with (x) number of vehicles that bring in the highest profits.</li>
</ol>  
</p>

<br>
<p align="center">
This is a simple visual comparing the profits of each of the calculated strategies compared to the current data pulled from 2018.
<br><br>
<img height="325" width="600" src="images/graph1.png?raw=true"/>
</p>

<br><br>
<p align="center">
<img height="200" width="300" src="images/graph2.png?raw=true"/>
<img height="200" width="300" src="images/graph3.png?raw=true"/>
</p>

<br><br>
<p align="center">
This visual shows the breakdown of the profits including the Total Revenue, Total Costs, including insurance, and the Total Profits made. Strategy 1 and 2 are close together in numbers, but you can see that Strategy 1 is just above Strategy 2. And although Strategy 3 made a lower revenue, the costs were significantly lower compared to the other strategies and almost the same as the baseline data from 2018, which results in Strategy 3 having a higher profit altogether.
<br><br>
<img height="300" width="700" src="images/graph4.png?raw=true"/>
</p>
<br><br>

<p align="center">
This visual is a Scenario Summary created in Excel to show a simple table view of the numbers for each strategy compared to the baseline data in 2018.
<br><br>
<img height="225" width="700" src="images/graph5.png?raw=true"/>
</p>
<br>

<p>
All calculations were done using 25% of the current vehicle inventory or 25% of the current number of rentals to ensure a more accurate comparison.
<br><br>
The better recommendation would be Strategy 3, to remove (x) number of vehicles that bring in the lowest net revenue and replace them with an (x) number of vehicles that bring in the highest net revenue.
<br><br>
All data can be adjusted based on the needs and wants of the company in the Excel file in the "Code" section of this repository.
</p>


<!--
[![](https://img.shields.io/badge/Python-white?logo=Python)](#)
[![](https://img.shields.io/badge/PyTorch-white?logo=pytorch)](#)
[![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#)
[![](https://img.shields.io/badge/Google-white?logo=Google)](#)
[![](https://img.shields.io/badge/R-white?logo=R)](#)
[![](https://img.shields.io/badge/Apple-white?logo=Apple)](#)
[![](https://img.shields.io/badge/Anaconda-white?logo=anaconda)](#) 
[![](https://img.shields.io/badge/Geopandas-white?logo=Geopandas)](#) 
[![](https://img.shields.io/badge/Bash-white?logo=GNUbash)](#)
[![](https://img.shields.io/badge/sklearn-white?logo=scikit-learn)](#) 
[![](https://img.shields.io/badge/MongoDB-white?logo=mongodb)](#)
[![](https://img.shields.io/badge/Scrapy-white?logo=scrapy)](#)
[![](https://img.shields.io/badge/Scikit%20Optimize-white?logo=data:image/png;base64,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)](#)
[![](https://img.shields.io/badge/pandas-white?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMIAAAEDCAMAAABQ/CumAAAAeFBMVEX///8TB1QAAEb/ygDnBIgPAFLNzNYTAFnQ0NgMAFcAAETb2eP39/oUBlfV1N7/xwDmAID/9tfLydcjG17/4Yz//vbCwM3ykcL61OfoBIwyKmgAADYAAE0AAErx8PTIxdT/+un/34T85/Lyir/lAHv50eX+9fkpH2Ma8J+4AAACEklEQVR4nO3dzVIaQRSAUYNCEIGoiYmJivnP+79hFrmLVHELZ6pnmG483xqaPruh5lb32ZkkSZIkSZIkvb52z7dZU2+rT4uH2X6rx6m31afF7M1+87dTb6tPCDWEUEMINYRQQ5MS1tu0nqtMSrhKn26e1v1WmZawyn58g4DQL4QIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyECOFA6cvM5a4nYb29yjoO4WmVvM58WPQkbF8e+RqPcDlPVp4t+xLS/W0QEBCqI8yTLpsizN8n/WmJ0CEEBAQEBAQEBIT2CF+/fci6a4hw8y7rvC3CeRYCAgICAgICAgICAgICwlCEtJYIdzdp/3+kdkKHToFQ+RjJMCEcCKF7CAdC6B7CgRC6Nylh9zGtJUJ6uNCsnsOFhhkvPAHC9x+fsloi/Pp5nXTREuH++iLpMwICAgICAgICAgICAgKC/87R7/u0lggdQkBAQEBAQEB4dYQON67UTqh9KuwkDlRBQED4R8gOF5o3Rdh8yepLGO0ez6MNPO+WQ9w3NilhvBAihLIQIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyEKJt+lL0SNeADUR4TG9cGWXHew10AkPP4aRBO9ohEuOFUEMINYRQQwg1dAKEDvd41t5t2u7lL0qSJEmSJEnSyfUXeomSFq0EzbkAAAAASUVORK5CYII=)](#)
[![](https://img.shields.io/badge/NumPy-white?logo=data:image/png;base64,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)](#)
-->

<!-- [View code on Colab](https://colab.research.google.com/drive/1d_q0vUpgwmbN7imUcdsbuDwJ61OuBjvO?usp=sharing) 
-->

<!-- 
---

### Project 2

- [Project 2 Title](http://example.com/)

---
-->
