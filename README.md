#### Setup ####

Note: Command only works for MAC or Linux, please check for Windows if you have

Read through the link for help
{
    How to install Spark and start PySpark to run Notebook
    https://blog.sicara.com/get-started-pyspark-jupyter-guide-tutorial-ae2fe84f594f
}

* Install *Python 3*
* Install *Java 8* or higher installed on your computer.
* Install *Spark* Downloaded the latest version Spark
    from http://spark.apache.org/downloads.html
    Version: spark-2.3.0-bin-hadoop2.7
* Install *Jupyter* Notebook

#### How to RUN #########
* Configure following 3 System environment variables
{
    export PYSPARK_PYTHON=python3
    export PYSPARK_DRIVER_PYTHON=jupyter
    export PYSPARK_DRIVER_PYTHON_OPTS='notebook'
}

* In the command prompt terminal
    1. Go to Spark installed location
        example: "/Users/software/spark-2.3.0-bin-hadoop2.7/bin"
    2. Run ./pyspark or python.cmd (depending on OS)

* Now you see Jupyter Home page in browser

* Now, Open the shared .ipynb files. Example: TMDbRegressionModels.ipynb
* Change "path =" to your location of the dataset i.e. "tmdb-movies-final-features-no-header.csv"

Finally, you can run through each Cell in the Jupyter


