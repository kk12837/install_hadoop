# install_hadoop

after installation
edit yarn-env.sh

修改$HADOOP_HOME/etc/hadoop/yarn-env.sh
export YARN_RESOURCEMANAGER_OPTS="--add-modules=ALL-SYSTEM"
export YARN_NODEMANAGER_OPTS="--add-modules=ALL-SYSTEM"
