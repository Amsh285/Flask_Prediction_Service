
ai22m043@technikum-wien.at </br>
ai22m002@technikum-wien.at

REST API build with Python and Flask
For requests Postman was used
to start the server start "run_server.py"
lokalhost: http://127.0.0.1:5000/

    #Get
    http://127.0.0.1:5000/swe/numberprediction/rest/data/v1.0/json/en/<model>?filter=<yourfilterhere>
    form-data file:<yourfilehere>

    #Post
    http://127.0.0.1:5000/swe/numberprediction/rest/data/v1.0/json/en/<model>


    #Delete
    http://127.0.0.1:5000/swe/numberprediction/rest/data/v1.0/json/en/<model>