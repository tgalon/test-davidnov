# spark-auth-sample-python

This is a code sample for using the Spark authentication API.

## Creating an application on the Spark developer portal

To create an application on the Spark developer portal:

 1. Create a Spark developer account at the [Spark developer portal](https://spark.autodesk.com/developers/).
 2. Create a new application [here](https://spark.autodesk.com/developers/getStarted).
 3. In the API Keys Tab, find and note for later the following:
    a. app key
    b. app secret
 4. Set your Callback URL to http://localhost:8089/callback.

## Configuration

To configure the application:
1. Open the sample.py file.
2. Replace CONSUMER_KEY with the app key from Step 3 above.
3. Replace CONSUMER_SECRET with the app secret from Step 3 above.

## Usage

To start using this sample, browse to: [http://localhost:8089/signin](http://localhost:8089/signin)
