# transitive-importer
Utility for importing external data into Transitive.js

# Setup
Install componenet
```shell
npm install -g component
```
Then install the dependencies and build the project
```shell 
component install
component-build
```
Start up a server
```shell
python -m SimpleHTTPServer 8000
```

# Usage
Form the interface on 127.0.0.1:8000, click on 'Set OTP Endpoint' and enter your OTP server url pointing to the index API
```
chile-otp.elasticbeanstalk.com/otp/routers/santiago/index
```
