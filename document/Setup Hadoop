# hadoop Set Up
1. Prepare Server ..this case use VMWARE Generate Machine.RAM  2GB HDD 30 GB
    - RAM 2-8 GB
    - linux 64 bit
    - Hardisk speed
    - load installation file
2. Install Hadoop
    1.update& Upgrade 
        sudo apt-get update
        sudo apt-get upgrade
    2. Install ssh and java
         sudo apt-get install -y openssh-server
         ssh-keygen -t dsa -P"
         cat ~/.ssh/id_dsa.pub >> ~/.ssh/authorized_keys
         ssh localhost
         sudo apt-get install -y openjdk-8-jdk

    2. Creat Folder  and Permition 
        1.hadoop install folder
        -Create folder
            sudo mkdir /usr/local/hadoop 
            sudo chown -R user01:user01 /usr/local/hadoop
         2.log store
             sudo mkdir /var/log/hadoop
             sudo chown -R user01:user01 /var/log/hadoop
             
    2. Edit .bashrc in /usr/local/hadoop/etc/hadoop
    

            export JAVA_HOME=usr/lib/jvm/java-8-openjdk-amd64/
            export PATH=$PATH:$JAVA_HOME/bin
            export HADOOP_HOME=/usr/local/hadoop
            export PATH=$PATH:$HADOOP_HOME/bin
            export PATH=$PATH:$HADOOP_HOME/sbin


    3. Edit Hadoop Enveronment /usr/local/hadoop/etc/hadoop
        ** hadoop-env.sh
        ** yarn-env.sh
        ** core-site.xml
        ** hdfs-site.xml
        ** yarn-site.xml
        ** mapred-site.xml
    9. Format
    
    10. Test Run
         start-all.sh
         start-dfs.sh
         jps


    11. Read Result and Edit
    
    12. Use in Browse 
        http://10.1.25.138:50070/
        
    13. Speicial Commarn
    stop-all.sh
    kill -9 process_id ignoge jps_process
    rm -rf /var/hadoop_data/namenode/*
    rm -rf /var/hadoop_data/datanode/*
    rm -rf /var/log/hadoop*
    rm -rf /tpm/hadoop*
    rm -rf /tpm/Jetty*
    hdfs namenode -format
    start-all.sh

    
    
    
3. Install Topping programe
4. Input data
5. Analyze data.
