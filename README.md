![](common/ptf.header.png)

## Prerequisites

####Virualbox VM images

This workshop requires two virtualbox images to be downloaded and imported.

1. [CaNDO.v01.ova](https://drive.google.com/open?id=0B6vGR7sqCgKnSGFTVWs3SkZON2c) for *Migrate WebLogic 10.3.6 (on premise) Application to Java Cloud Service with App2Cloud tool* lab
2. [DevOpsWorkshopV3\_Final\_JavaOne.ova](https://drive.google.com/open?id=0B0MXC4qaECO6RHBWMEttdW9fOVk) for *DevOps and Cloud Native Microservices Workshop* lab

####Oracle Public Cloud PaaS  account

The workshop is intended to work with an Oracle PaaS trial account. Get the following account details ready to complete the tutorial and replace to your values when it is required:

+ Oracle Cloud account **username** and **password**
+ Oracle Cloud **identity domain**
+ **Data center/region**

IMPORTANT: Before you start to use your new Oracle Public Cloud services make sure that the replication policy has been set for your account. Otherwise you can not create storage container which is necessary for most of the services. See [Selecting a Replication Policy for Oracle Storage Cloud Service](https://docs.oracle.com/cloud/latest/storagecs_common/CSSTO/GUID-5D53C11F-3D9E-43E4-8D1D-DDBB95DEC715.htm).

####Create Database Cloud Service instance

It is recommended to provision Database Cloud Service instance in advance because it requires >20 minutes to complete. Use the [CaNDO.v01.ova](https://drive.google.com/open?id=0B6vGR7sqCgKnSGFTVWs3SkZON2c) image and follow the [instructions](preparation.md).

----

#### 1. Migrate WebLogic 10.3.6 (on premise) Application to Java Cloud Service with App2Cloud tool ####

+ [Migrate Weblogic 10.3.6 (on premise) Application to Java Cloud Service with App2Cloud tool](app-2-cloud/README.md)

#### 2. DevOps and Cloud Native Microservices Workshop

+ [Lab 100: Agile Project Management](microservices/CloudNative100.md)
+ [Lab 200: Continuous Delivery of Java Microservices](microservices/CloudNative200.md)
+ [Lab 300: Cloud Native Rapid JavaScript Development with Node.js](microservices/CloudNative300.md)
+ [Lab 400: Cloud Native Developer Cloud Service Administration](microservices/CloudNative400.md)

#### 3. Deploy complex cloud environment using Oracle Cloud Stack Manager ###
+ [FixItFast Cloud Native Application which includes multiple Oracle Application Container Cloud Services (Cache, Java, NodeJS)](stack/stack.cache.md)

#### 4. Container based application development lifecycle using Wercker and Container Cloud Service ####

+ [Build Node.js-MongoDB container packaged application using Wercker and deploy to Oracle Container Cloud Service as the Stack of services](nodejs-mongodb-stack/README.md)

---

### Contributing

Pull Requests are currently not being accepted. 

### [License](LICENSE.md)