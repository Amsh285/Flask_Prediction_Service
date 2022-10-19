
ai22m043@technikum-wien.at </br>
ai22m002@technikum-wien.at

REST API build with Python and Flask </br>
For requests Postman was used </br>
to start the server start "run_server.py" </br>
lokalhost: http://127.0.0.1:5000/

    #Get
    http://127.0.0.1:5000/swe/numberprediction/rest/data/v1.0/json/en/<model>?filter=<yourfilterhere>

    form-data file:<yourfilehere>

    filters: 
        what_is_this_number // returns just the predicted Number
        what_is_this_number_probability // returns the predicted Number with probability
        what_is_this_numbers_probabilities // returns all Numbers with probabilities


    #Post
    http://127.0.0.1:5000/swe/numberprediction/rest/data/v1.0/json/en/<model>


    #Delete
    http://127.0.0.1:5000/swe/numberprediction/rest/data/v1.0/json/en/<model>
