# @markup markdown
# @title OpenShift Origin Documentation

# OpenShift Origin

[OpenShift Online](http://www.openshift.com) is Red Hat's Platform as a Service (PaaS) offering. OpenShift is an application platform where application developers and teams can build, test, deploy, and run their applications. [OpenShift Origin](https://openshift.redhat.com/community/open-source) is a collection of open source components that are used in the OpenShift Platform as a Service.

##General Overview

* [Learning OpenShift Origin](https://openshift.redhat.com/community/wiki/learning-openshift-origin)
* [Architecture Overview](https://openshift.redhat.com/community/wiki/architecture-overview)

##OpenShift Origin Repositories

OpenShift Origin sources are arranged into 5 repositories:

* [origin-dev-tools](http://github.com/openshift/origin-dev-tools): This repository contains all the build tools necessary for building and testing a local or EC2 OpenShift Origin installation.
* [origin-server](http://github.com/openshift/origin-server):This is the main repository that contains the source code for the Broker, Node and various plugins for DNS, Communication and Authentication. It also contains some of the core cartridges used by OpenShift installations.
* [origin-community-cartridges](http://github.com/openshift/origin-community-cartridges): This repository contains additional cartridges used during the Fedora 18 installation.
* [rhc](http://github.com/openshift/rhc): This repository contains command line tools used to access an OpenShift based PaaS.
* [puppet-openshift_origin](http://github.com/openshift/puppet-openshift_origin): This repository contains puppet scripts for configuring OpenShift Origin.

##Documentation

* [Build tools](build-tools/index.html)
* Core openshift code
  + [Common code](common/index.html): Models and code used by both Broker and Node
  + [Broker and Controller](broker/index.html): Documentation for Models, Controllers and Plugin interfaces used on the Broker
      * [API docs](rest_api/index.html): Documentation for only the models and controllers involved in the REST API
      * [Internal models](broker_models/index.html): Documentation for only MongoID models
      * Plugins
          * [Communication plugin interface]()
          * [DNS plugin interface]()
          * [Authentication plugin interface]()
  + [Node](node/index.html): Documentation for Models, libraries used on the Node
* Supplimental Documentation
  + [Control Groups in OpenShift](file.cgroups.html)
  + [How nodes act on behalf of the user](file.how_nodes_act_on_behalf_of_users.html)
  + [Scaling in OpenShift](file.scaling.html)
  + [Guidelines for API documentation](file.api_documentation.html)
  + [Guidelines for supplimental documentation](file.doc_guidelines.html)

##Discussion Forums
* [OpenShift Origin Developers Google Plus group](https://plus.google.com/communities/114361859072744017486) 
* [Mailing Lists](http://lists.openshift.redhat.com/)
	+ [For Developers](http://lists.openshift.redhat.com/openshiftmm/listinfo/dev)
	+ [For Users](http://lists.openshift.redhat.com/openshiftmm/listinfo/users)
* Use [#openshift on the irc.freenode.net IRC server](http://webchat.freenode.net/?randomnick=1&channels=openshift&uio=d4) for questions about the service
* Use [#openshift-dev on the irc.freenode.net IRC server](http://webchat.freenode.net/?randomnick=1&channels=openshift-dev&uio=d4) for discussion around development of OpenShift and the open source components.

##Trademarks
These are some of the projects that are used to create Red Hat's OpenShift Platform-as-a-Service (PaaS). Red Hat and OpenShift are trademarks of Red Hat, Inc., registered in the United States and other countries. Red Hat's offering of the code for downloading, use, modification, or distribution is not a grant of a trademark license to OpenShift or any other Red Hat trademark.
