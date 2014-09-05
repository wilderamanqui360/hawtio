### Fabric

This plugin works with [fabric8](http://fabric8.io) to allow you to provision and configure clusters of [JBoss Fuse](http://www.jboss.org/jbossfuse), [JBoss A-MQ](http://www.jboss.org/jbossamq) or Apache integration technologies like [ActiveMQ](http://activemq.apache.org/), [Camel](http://camel.apache.org/), [CXF](http://cxf.apache.org/), [Karaf](http://karaf.apache.org/) , [ServiceMix](http://servicemix.apache.org/) and introspect the running cluster.

Note that currently this plugin requires a distribution of either [fabric8](http://fabric8.io) or [JBoss Fuse](http://www.jboss.org/jbossfuse) 6.1 or later. For earlier versions of Fuse, hawtio works great for Camel, ActiveMQ, OSGi, JMX and so forth; but hawtio requires the new JMX MBean in version 6.1 of JBoss Fuse or fabric8 to enable the Fabric plugin.