# mysql-persistent Volume for Openshift
Configure nfs, you can use nfs.txt
Import persistent volume in your project openshift:

oc create -f https://raw.githubusercontent.com/cuccurese2010/Mysql-persistent/master/persistent_volume.json

Import mysql-persistent in your project openshift:

oc create -f https://raw.githubusercontent.com/cuccurese2010/Mysql-persistent/master/mysql-persistent.yaml
    
    
