# README

<br>

<b>AWS: Getting CPU Utilization of EC2 Instance: Minimum, Maximum , Average and send the metrics to Email</b>

This Custom Script I produced is out of curiosity to track certain instance if it hits certain percentage of utilization, feel free to modify/used it.

## Pre-requisites
<ol>
  <li> AWS ACCOUNT      ✅ </li>
  <li>AWS ACCESS ID     ✅ </li>
  <li>AWS SECRET KEY    ✅ </li>
  <li>SNS Topic with Subscription via Email ✅ </li>
  <li>Running EC2 Instance ✅ </li>
</ol>

## Running the the script through AWS lambda
<ol>
    <li>Zip the source file</li>
    <li>Go to your AWS Account and search lambda</li>
    <li>Create a function from scrach and Choose runtime language to python 3.7 or python 3.9</li>
    <li>After creating lambda function, Upload the zip file to the lambda</li>
    <li>Configure Environment Variables</li>
</ol>


