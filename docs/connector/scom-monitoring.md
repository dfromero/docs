# Monitoring the ADLDAP Connector with System Center Operations Manager

The Auth0 AD/LDAP connector can run as a Service on Windows based machines.

You can monitor the service status using System Center as you would do with any other service.

* Open the __Add Monitoring Wizard__ and select the __Monitoring Type: Windows Service__:

![ss-2014-12-11T22-48-51.png](https://s3.amazonaws.com/blog.auth0.com/ss-2014-12-11T22-48-51.png)

* Enter a name and description:

![ss-2014-12-11T22-49-57.png](https://s3.amazonaws.com/blog.auth0.com/ss-2014-12-11T22-49-57.png)

* Select the Server in which the AD/LDAP Connector is installed and then choose "Auth0 ADLDAP":

![ss-2014-12-11T22-50-37.png](https://s3.amazonaws.com/blog.auth0.com/ss-2014-12-11T22-50-37.png)

* Select the desired **CPU** and **Memory limits**.
