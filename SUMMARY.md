# Summary

* [Introduction](README.md)
* [What is MyST?](what-is-myst.md)
* [Which browsers are supported by MyST?](which-browsers-supported.md)

## Platform Configuration

* [Can I bring my SOA CS domains under the management of MyST?](platform-configuration/introspection/soacs/README.md)

* [What's required to configure a VIP with an Admin Server and perform a failover?](platform-configuration/using-adminserver-with-vip-and-failing-over.md)

* [Can I add more nodes to my environment with MyST?](platform-configuration/add-compute-nodes/README.md)

* [Can I apply patches with MyST to one server at a time?](platform-configuration/apply-rolling-patches.md)

* [Can I configure SOA MBeans with MyST Studio?](platform-configuration/can-i-configure-soa-mbeans-with-myst-studio.md)

* [Can MyST be used to configure JCA Adapters?](platform-configuration/configure-jca-adapters.md)

* [Can I configure EJB Transaction Timeout through MyST?](platform-configuration/add-compute-nodes/can-i-configure-ejb-transaction-timeout-through-myst.md)

* [How do I run SQL scripts pre and post RCU?](platform-configuration/sql-scripts-pre-and-post-rcu.md)

* [Can I integrate my custom scripts with MyST?](platform-configuration/configure-myst-custom-action.md)

* [How do I use myst-extension to configure WebLogic resources not in MyST?](platform-configuration/configure-myst-extension.md)

* [MyST is complaining about the JDK version. How can I fix this?](platform-configuration/jdk-issue.md)

* [Upgrading to v5.5.1.0+ created new RCU properties. What now?](platform-configuration/upgrading-to-v5510+-new-rcu-properties.md)

* [How do I use the MyST REST API to see and manipulate Blueprint and Model source files?](platform-configuration/rest-api.md)

* [How do I use the MyST REST API to apply common settings across Platform Blueprints?](platform-configuration/rest-api-bulk-edit-blueprints.md)

* [How do I use the MyST REST API to automate creation of resources in MyST with the help of Jenkins?](platform-configuration/creating-myst-studio-resources-using-rest-apis-with-help-of-jenkins.md)

* [I have existing WebLogic environments I built outside of MyST, how can I bring them into the control of MyST?](platform-configuration/i-have-existing-environments-i-built-outside-of-myst-how-can-i-bring-them-into-the-control-of-myst.md)

* [When trying to introspect an environment I received a notice about "Data integrity constraints". What now?](platform-configuration/i-am-receiving-data-integrity-constraints-were-violated-while-trying-to-persist-the-necessary-entities-error-when-trying-to-introspect-and-environment.md)

* [During execution I get a java.lang.NullPointerException](platform-configuration/javalangnullpointerexception/javalangnullpointerexception.md)

* [How do I perform advanced webtier customisations using MyST?](platform-configuration/webtier/advanced/README.md)

* [How to deploy SQL in 12c using SQL\*Plus?](platform-configuration/deploy-sql-12c-using-sqlplus.md)

* [Provisioning Oracle Data Integrator 12c?](platform-configuration/provisioning-oracle-data-integrator-12c.md)

* [Provisioning Oracle Order and Service Management 12c](platform-configuration/add-compute-nodes/provisioning-oracle-order-and-service-management-12c.md)

* [Provisioning Axway API Gateway](platform-configuration/axway/README.md)

* [How do I shutdown or start-up some of my servers?](platform-configuration/add-compute-nodes/how-do-i-shutdown-or-start-up-some-of-my-servers.md)

* [How do I configure SSL on my Domain?](platform-configuration/add-compute-nodes/how-do-i-configure-ssl-on-my-managed-servers.md)

* [Can I bring my oddball domains under the management of MyST?](platform-configuration/introspection/odd-domain/README.md)

* [How do I deploy artifacts as part of a provisioning?](platform-configuration/system-artifacts/README.md)

* [What can I do to troubleshoot failed MyST actions?](platform-configuration/troubleshooting-update-or-provision-failures.md)

* [How do I create OWSM Policies?](platform-configuration/OWSM-Policies.md)

* [How to create a Plain Vanilla Weblogic Domain ?](platform-configuration/Plain-Vanilla-Weblogic-Domain.md)

* [How to remove Weblogic resources from Myst ?](platform-configuration/Removing-WL-resources-in-MyST.md)

* [How to compare Platform Blueprints / Platform Models in Myst?](platform-configuration/How-to-compare-changes-between-two-versions-of-Models-Blueprints.md)

  

## Artifact Build

* [I can't get Maven to build my project. Please help!](artifact-build/maven-build-issues.md)
* [I have existing 11g automated builds using Maven. How do I update them for 12c?](artifact-build/maven-11g-to-12c.md)

## Application Deployment
* [How do I use MyST to copy files to a host?](application-deployment/how-do-i-copy-files-to-a-linux-host-using-myst.md)
* [Can I integrate my existing deploy scripts with MyST?](application-deployment/custom.md)
* [How can I test a deployment against my local development environment?](application-deployment/local/README.md)
* [Does MyST allow me to seed databases that aren't Oracle?](application-deployment/other-databases.md)
* [Can I do a bulk import of artifacts and application blueprints?](application-deployment/can-i-do-a-bulk-import-of-artifacts-and-application-blueprints.md)
* [How can I bulk migrate my properties to be available in the Artifact Property Registry?](application-deployment/how-can-i-bulk-migrate-my-properties-to-be-available-in-the-artifact-property-registry.md)
* [Can I create SOA partitions with MyST?](application-deployment/how-do-i-create-soa-partitions-with-myst.md)
* [Does MyST support configuring BPM FlexFields?](application-deployment/deploy-bpm-flexfields.md)
* [Can I skip the application deployment when reprovisioning an environment?](application-deployment/clear-cache/README.md)
* [At deploy time can I use MyST to change transport details of an OSB project?](application-deployment/osb-change-transport-details.md)
* [Deploying ESS using MyST Deployment SDK?](myst-apis-and-sdk/deploying-ess-using-deployment-sdk.md)

## MyST Management

* [MyST performance management?](myst-management/performance/README.md)
* [MyST can't connect? Should I test SSH connectivity?](myst-management/ssh-key-pair-connectivity-with-myst.md)
* [How do I setup notifications from MyST?](myst-management/notifications/README.md)
* [What do I do with the MyST license?](myst-management/myst-license.md)
* [Why does MyST Studio UI show a failure after running for a long time or a lot of logging?](myst-management/container-configuration/myst-fails-after-large-amount-of-logging.md)
* [Can I use MyST CLI with data from MyST Studio?](myst-management/myst-cli-with-myst-studio.md)
* [Uploading large files?](myst-management/uploading-large-files.md)
* [How do I solve authentication errors when MyST connects to a server?](how-do-i-solve-authentication-errors-when-myst-connects-to-a-server.md)
* [How do I setup MyST and associated components to use an Internet Proxy?](how-do-i-setup-myst-and-associated-components-to-use-an-internet-proxy.md)
* [How to improve performance of Myst?](myst-management/performance/Performance-improvement.md)
