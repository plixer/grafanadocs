Getting Started 
================

Currently I am working on having Grafana make this plugin available on their plugins repo. Once that is done I will update this documentation with the grafana-cli commands needed to install. 

For now, you can install the plug in by simply cloning it into the plugins directory. Depending on the OS you are running, there is a different path. 

**Path:** 

* Linux : '*/var/lib/grafana/plugins*' 
* Windows : '*/data/plugins*' *

When inside the directory issue the command. 


*'git clone https://github.com/plixer/scrutinizer-datasource.git'*


Once this datasource is cloned, restart your grafana server and continue on to the next step of adding the datasource to grafana. 

\*If your on a Windows system you may need to create the 'data/plugins' directory. 