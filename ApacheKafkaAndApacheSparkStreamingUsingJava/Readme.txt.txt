ApacheKafkaAndApacheSparkStreamingUsingJava

There are two Maven java Projects:

1) kafkaIntegrationWithSpark - Read data or Records from a .csv file (found in resource folder of the same project) and load it in Kafka.
   You can see this data appearing in the consumer side
2) ReadDataFromKafaUsingSpark - Read data from Kafka and print to your console

Before starting executing these code, you have should have already:

1) Kafka server running
2) Kafka Topic (demo) shoud be created.
3) kafka producer and consumer console started for testing purpose.

Once the above set up is ready, execute your kafkaIntegrationWithSpark in Intelliji or eclispe and check if the data appears in Kafaka consumer Console
Then run the project ReadDataFromKafaUsingSpark in eclipse (intelliji it throws error) .Run the 2 projects back to back, you can see data getting printed in eclipse console of spark project


https://www.youtube.com/watch?v=0j7v7sdmqh0&feature=youtu.be

Thanks to Binod Suman Academy,I used his youtube channel and git for reference 
https://www.youtube.com/watch?v=UcWi3-FODjs