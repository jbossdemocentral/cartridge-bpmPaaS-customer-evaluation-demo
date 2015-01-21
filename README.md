Cartridge for bpmPaaS with Customer Evaluation Demo
===================================================
This cartridge provides the **_Red Hat JBoss BPM Suite_** for easy deployment to OpenShift based bpmPaaS with pre-loaded Customer
Evaluation Demo.


Install with one click in xPaaS (bpmPaaS)
-----------------------------------------
After clicking button, ensure `Gear` size is set to `medium`:

[![Click to install OpenShift](http://launch-shifter.rhcloud.com/launch/light/Install bpmPaaS.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges[]=https://raw.githubusercontent.com/jbossdemocentral/cartridge-bpmPaaS-customer-evaluation-demo/master/metadata/manifest.yml&name=customerevaluation&gear_profile=medium&initial_git_url=)

Once installed you can use the JBoss BPM Suite login: 

   * u:erics   p: bpmsuite  (admin)

   * u: alan   p: bpmsuite  (analyst)

   * u: daniel p: bpmsuite (developer)

   * u: ursla  p: bpmsuite (user)

   * u: mary   p: bpmsuite (manager)


Important Note
--------------
You need the ability to setup MEDIUM gears, which is freely available if you [upgrade your account to Bronze here](https://www.openshift.com/products/pricing). 


Manual setup on OpenShift
-------------------------
Or if you want to use the [rhc command line](https://www.openshift.com/developers/rhc-client-tools-install) type:

    rhc app create -g medium <APP NAME> https://raw.githubusercontent.com/jbossdemocentral/cartridge-bpmPaaS-customer-evaluation-demo/master/metadata/manifest.yml

For more information on the [Customer Evaluation Demo see here] (https://github.com/jbossdemocentral/bpms-customer-evaluation-demo).


Supporting Articles
-------------------
[Launching Into the Clouds With 2 New OpenShift Primer bpmPaaS Quickstarts](http://www.schabell.org/2014/10/launching-into-clouds-with-2-new-openshift-primer-bpmpaas-quickstarts.html)


Released versions
-----------------

See the tagged releases for the following versions of the product:

- v1.2 - moved to JBoss Demo Centra, added one click install button.

- v1.1 - bpmPaaS on OpenShift cartridge, JBoss BPM Suite 6.0.2 and customer evaluation demo installed.

- v1.0 - bpmPaaS on OpenShift cartridge, JBoss BPM Suite 6.0.1 and customer evaluation demo installed.

![Customer Evaluation Process](https://github.com/jbossdemocentral/bpms-customer-evaluation-demo/blob/master/docs/demo-images/process.png?raw=true)

