# AWS_RestAPI_IOT
Python script for making REST API calls to AWS IoT.

Example:

```
$ python SIGv4_IOT_Shadow.py 

BEGIN REQUEST++++++++++++++++++++++++++++++++++++
Request URL = https://a2e3cvdgunjnha.iot.ap-northeast-1.amazonaws.com/things/rPi/shadow

RESPONSE++++++++++++++++++++++++++++++++++++
Response code: 200

{"state":{"reported":{"temperature":29.0232132,"humidity":54.3,"pressure":1023.2}},"metadata":{"reported":{"temperature":
{"timestamp":1529799929},"humidity":{"timestamp":1529799929},"pressure":> >>>>>{"timestamp":1529799929}}},"version":176,"timestamp":1536132588}
$
```

Based on https://docs.aws.amazon.com/general/latest/gr/sigv4-signed-request-examples.html.




