# API for Google Analytic 4 using Python  

### Steps
1. Enable API and create service account in https://console.cloud.google.com/  
2. Add service account to GA 4 property  
3. Download credential and set environment variable  
```export GOOGLE_APPLICATION_CREDENTIALS="[PATH]"```  
4. Install client library  
Mac/Linux  
```
pip install virtualenv
virtualenv <your-env>
source <your-env>/bin/activate
<your-env>/bin/pip install google-analytics-data
```
Windows  
```
pip install virtualenv
virtualenv <your-env>
<your-env>\Scripts\activate
<your-env>\Scripts\pip.exe install google-analytics-data
```
5. Set your property ID  
6. Run ```py analytics.php```