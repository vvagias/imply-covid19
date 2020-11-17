# imply-covid19
repo dedicated to covid19 related tutorials and resources for getting covid data into Imply / Druid and interacting with it. 


# run index job
from your druid directory run: 

    bin/post-index-task --file /path/to/covid.json --url http://localhost:8081

if you are not on localhost where Druid lives then replace localhost with the ip of your druid instance. 
