# Load Testing FusionAuth

Load testing FusionAuth should be performed using a realistic production configuration.  The throughput goal should be to target a number of requests per second.  

## Configure FusionAuth
1. Setup an API key

2. Setup a tenant

3. Setup an application

## Running a load test
1. Register users for the application

2. Login users using the [Login API ](https://fusionauth.io/docs/apis/login)

## Cleanup

Deleting the tenant will remove the application and users.

## Load Testing Tools
A tool that can make HTTP requests will work.

1.  jmeter
https://jmeter.apache.org

2.  gatling
https://gatling.io


## Helpful Articles

1. FusionAuth [Documentation ](https://fusionauth.io/docs/operate/secure-and-monitor/monitor#load-testing)

2. Load testing scripts from an [open source project ](https://github.com/FusionAuth/fusionauth-load-tests/)

3. FusionAuth User Registration Hits 100,000,000 In [Load Test ](https://fusionauth.io/blog/got-users-100-million)

