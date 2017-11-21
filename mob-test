# -*- coding: utf8 -*-
#author :-   Jabed
import requests

url_test = 'https://www.seoinc.com'

params = {
    'key': '',
    'url': url_test,
}
api_url = 'https://www.googleapis.com/pagespeedonline/v3beta1/mobileReady?url=' + url_test
response = requests.get(api_url)
data = response.json()
#print (data)
if str(data).find('"pass": true'):
    print (url_test + " is mobile friendly")
else:
    print (url_test + "is not mobile friendly")

