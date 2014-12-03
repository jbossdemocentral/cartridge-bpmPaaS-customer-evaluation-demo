## Cartridge for bpmPaaS with Customer Evaluation Demo

This cartridge provides the **_Red Hat JBoss BPM Suite_** for easy deployment to OpenShift based bpmPaaS with pre-loaded Customer
Evaluation Demo.

Setup Now
---------
1. Login to OpenShift Origin and go to the [OpenShift create application page](https://openshift.redhat.com/app/console/application_types).

2. In `CODE ANYTHING` field at bottom left of the page paste the following cartridge URI:

     _https://raw.githubusercontent.com/jbossdemocentral/cartridge-bpmPaaS-customer-evaluation-demo/master/metadata/manifest.yml_

3. Click on `NEXT` button and drink a warm beverage while you wait for finished cartridge installation.

Once installed you can use the JBoss BPM Suite logins: 

   * u:erics  p: bpmsuite  (admin)

   * u: mary  p: bpmsuite  (analyst)
   
   * u: alan  p: bpmsuite  (analyst)
   
   * u: bob  p: bpmsuite  (analyst)

Important Note
--------------
You need the ability to setup MEDIUM gears, which is freely available if you [upgrade your account to Bronze here] (https://www.openshift.com/products/pricing). 


Deployment
----------

Or if you want to use the [rhc command line](https://www.openshift.com/developers/rhc-client-tools-install) type:

    rhc app create -g medium <APP NAME> https://raw.githubusercontent.com/jbossdemocentral/cartridge-bpmPaaS-customer-evaluation-demo/master/metadata/manifest.yml

For more information on the [Customer Evaluation Demo see here] (https://github.com/jbossdemocentral/bpms-customer-evaluation-demo).

Supporting Articles
-------------------

[Red Hat OpenShift bpmPaaS - Customer Evaluation Demo now available in the Cloud] (TODO)


Released versions
-----------------

See the tagged releases for the following versions of the product:

- v1.1 - moved to JBoss Demo Central.

- v1.1 - bpmPaaS on OpenShift cartridge, JBoss BPM Suite 6.0.2 and customer evaluation demo installed.

- v1.0 - bpmPaaS on OpenShift cartridge, JBoss BPM Suite 6.0.1 and customer evaluation demo installed.

![Customer Evaluation Process](https://github.com/jbossdemocentral/bpms-customer-evaluation-demo/blob/master/docs/demo-images/process.png?raw=true)

