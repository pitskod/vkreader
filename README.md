# vkreader reads VK-pages using vk-api 

To run the jar use this command
java -jar <Path to JAR-file>/vkreader/target/vkreader-0.0.1-SNAPSHOT-jar-with-dependencies.jar <First ID> <Last ID> <Path to existing Folder>
For example this command will write information about users, who have ids from 1 to 10 (10 json files, which have names "uid=1.json","uid=2.json",...) in folder "Documents/fromVK"
java -jar vkreader/target/vkreader-0.0.1-SNAPSHOT-jar-with-dependencies.jar 1 10 /home/cloudera/Documents/fromVK
