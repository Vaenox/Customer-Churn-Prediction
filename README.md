<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>
    <div class="container">
        <h1>Customer Churn Prediction</h1>
        <div class="content">
            <p>Nowadays, there’s a significant amount of customer turnover in countless sectors like finance, insurance, retail, banking, and telecommunications. This element raises the competition among sectors. Companies in a competitive atmosphere tend to find solutions to minimize the potential loss of customers. One of the most likely solutions is predicting whether customers will proactively or reactively want to terminate their active subscriptions with the company. In general terms, it refers to the intention of current users to end the service they’re receiving. This prediction process is called <strong>Customer Churn Prediction</strong>.</p>
        </div>
        <div class="content">
            <p>To implement this prediction, multiple pieces of information such as the customer's gender, contract duration, the number of months they've been with the company, and the internet service provider are analyzed using machine learning and deep learning. The telecommunications sector is at the forefront of industries that use customer churn prediction, largely due to how easy it is for customers to switch to a different operator. In this field, acquiring customers is a challenging task for operators, heavy with competition and cost. Therefore, attracting new customers takes a backseat, while their primary goal is to retain their existing customers and minimize losses. A study showed that in the fourth quarter of 2019, the total number of mobile subscribers in Turkey approached 81 million. Furthermore, when correlated with the population data from 2019, a mobile line usage rate of 98.5% can be seen.</p>
        </div>
        <div class="content">
            <p>The aim of this study is to evaluate and identify the customers the company is at risk of losing by utilizing deep learning and machine learning, and to predict the reasons behind subscription termination.</p>
        </div>
        <h2>About Data</h2>

<table style="width:100%">
  <tr>
    <th>Columns</th>
    <th>Description</th>
    <th>Values</th>
  </tr>

  <tr>
    <td>gender</td>
    <td>Whether the customer is a male or a female</td>
    <td>0:Female,1:Male</td>

  </tr>

  <tr>
    <td>SeniorCitizen</td>
    <td>Whether the customer is a senior citizen or not</td>
    <td>0:No,1:Yes</td>

  </tr>

  <tr>
    <td>Partner</td>
    <td>Whether the customer has a partner or not</td>
    <td>0:No,1:Yes</td>

  </tr>

  <tr>
    <td>Dependents</td>
    <td>Whether the customer has dependents or not</td>
    <td>0:No,1:Yes</td>

  </tr>

  <tr>
    <td>tenure</td>
    <td>Number of months the customer has stayed with the company</td>
    <td>int</td>

  </tr>

  <tr>
    <td>PhoneService</td>
    <td>Whether the customer has a phone service or not</td>
    <td>0:No,1:Yes</td>

  </tr>

  <tr>
    <td>MultipleLines</td>
    <td>Whether the customer has multiple lines or not</td>
    <td>0:No,1:Yes,2:No Phone Service</td>

  </tr>

  <tr>
    <td>InternetService</td>
    <td>Customer’s internet service provider</td>
    <td>0:DSL,1:Fiber Optic,2:No</td>

  </tr>

  <tr>
    <td>OnlineSecurity</td>
    <td>Whether the customer has online security or not</td>
    <td>0:No,1:No Internet Service,2:Yes</td>

  </tr>

  <tr>
    <td>OnlineBackup</td>
    <td>Whether the customer has online backup or not</td>
    <td>0:No,1:No Internet Service,2:Yes</td>

  </tr>

  <tr>
    <td>DeviceProtection</td>
    <td>Whether the customer has device protection or not</td>
    <td>0:No,1:No Internet Service,2:Yes</td>

  </tr>

  <tr>
    <td>TechSupport</td>
    <td>Whether the customer has tech support or not</td>
    <td>0:No,1:No Internet Service,2:Yes</td>

  </tr>

  <tr>
    <td>StreamingTV</td>
    <td>Whether the customer has streaming TV or not</td>
    <td>0:No,1:No Internet Service,2:Yes</td>

  </tr>

  <tr>
    <td>StreamingMovies</td>
    <td>Whether the customer has streaming movies or not</td>
    <td>0:No,1:No Internet Service,2:Yes</td>

  </tr>

  <tr>
    <td>Contract</td>
    <td>The contract term of the customer</td>
    <td>0:Month-to-Month,1:One Year,2:Two Year</td>

  </tr>

  <tr>
    <td>PaperlessBilling</td>
    <td>Whether the customer has paperless billing or not</td>
    <td>0:No,1:Yes</td>

  </tr>

  <tr>
    <td>PaymentMethod</td>
    <td>The customer’s payment method</td>
    <td> 0:Bank Transfer,1:Credit Card,2:Electronic Check,3:Mailed Check</td>

  </tr>

  <tr>
    <td>MonthlyCharges</td>
    <td>The amount charged to the customer monthly</td>
    <td>int</td>

  </tr>

  <tr>
    <td>TotalCharges</td>
    <td>The total amount charged to the customer</td>
    <td>int</td>

  </tr>

  <tr>
    <td>Churn</td>
    <td>Whether the customer churned or not</td>
    <td>0:No,1:Yes</td>
  </tr>
</table>
    </div>
</body>
</html>
