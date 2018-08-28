# Mysql-persistent Openshift
Configure nfs, you can use nfs.txt 
Import persistent volume in your project openshift:
oc create -f \
    https://raw.githubusercontent.com/cuccurese2010/Mysql-persistent/master/mysql-persistent.yaml
Import mysql-persistent in your project openshift:
oc create -f \
    https://raw.githubusercontent.com/cuccurese2010/Mysql-persistent/master/mysql-persistent.yaml
    
    Before you import your mysql-persistent.yaml you need to create persistent volume! 
