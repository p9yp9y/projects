## Install

Install Chromium and Chromium web driver before.
```
sudo apt install chromium-browser chromium-chromedriver
```
Compile executable jar file.
```
mvn clean compile assembly:single
```
## Run
```
java -jar target/java-messenger-0.0.1-SNAPSHOT-jar-with-dependencies.jar
```
### Samples
```
-method login -email YOUR_EMAIL -password YOUR_PASSWORD

-method logout

-method startConversation -friendName "YOUR_FRIEND"

-method send -message "YOUR_MESSAGE"

-method alive  -email YOUR_EMAIL -password YOUR_PASSWORD -friendName "YOUR_FRIEND"

-method alive  -email YOUR_EMAIL -password YOUR_PASSWORD -friendName "YOUR_FRIEND" -out YOUR_OUTPUT_FILE -in YOUR_INPUT_FILE
```
