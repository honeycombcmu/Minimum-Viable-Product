# Minimum-Viable-Product

## Step for test the Minimum Viable Product
* SSH to the server ``ssh honeycomb@128.2.7.38``
* Switch to the server code folder ``cd hornet``
* Activate the virtual environment ``. venv/bin/activate``
* Start the listener ``python app.py``
* If the above step encounters an error ``Address already in use``, use ``fuser -k 32769/tcp`` to release the port
* Check the existed result by typing ``http://128.2.7.38:32769/result`` in the browser
* Run the code in real time, type ``http://128.2.7.38:32769/run`` in the browser, you should see the code is running on the server and wait for a few minutes the result will display on current page in json format.

## Memo
* [Cluster port assignment](https://github.com/bicCluster/docs/wiki/Port-Assignments)
