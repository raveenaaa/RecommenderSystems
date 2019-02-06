# Dataset
Music Listening Dataset
Audioscrobbler.com
6 May 200

This data set contains profiles for around 150,000 real people. The dataset lists the artists each person listens to, and a counter indicating how many times each user played each artist.The dataset is continually growing; at the time of writing (6 May 2005). Audioscrobbler is receiving around 2 million song submissions per day

# License
This data is made available under the following Creative Commons license:http://creativecommons.org/licenses/by-nc-sa/1.0/

# Files
user_artist_data.txt
    3 columns: userid artistid playcount

artist_data.txt
    2 columns: artistid artist_name

artist_alias.txt
    2 columns: badid, goodid
    known incorrectly spelt artists and the correct artist id. 
    
# Execution
Run the following line in the terminal to open the jupyter notebook with pyspark. Make sure to open the terminal and navigate into the project directory OR right click in the project directory in the Files application and click 'Open in Terminal'.

export PYSPARK_DRIVER_PYTHON=ipython3
export PYSPARK_DRIVER_PYTHON_OPTS="notebook"
$SPARK_HOME/bin/pyspark
