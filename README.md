# spark_sandbox
A place to keep my apache-spark proof of concepts for integration with mesos, opendap, etc

# apache spark
you'll need to download and unpack the standalone package
export SPARK_HOME to wherever you unpacked the tarball

http://spark.apache.org/downloads.html

[bourne@skynet2]$ echo $SPARK_HOME 
/home/cgaustin/workspace/apache-spark/spark-2.0.2-bin-hadoop2.7
[bourne@skynet2 spark_sandbox]$ ls $SPARK_HOME
bin  conf  data  examples  jars  LICENSE  licenses  NOTICE  python  R  README.md  RELEASE  sbin  yarn


# create and activate the virtual environment
conda env create -f environment.yaml --name spark27

source activate spark27

ipython notebook --ip=0.0.0.0 --browser=none

