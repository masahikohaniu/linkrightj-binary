### Welcome to LinkRightJ

The LinkRightJ is a Java implementation based on the bitcoinj library, which allows sending message to LinkRight blockchain network. The message is engraved in the non-modifiable blockchain database and the timestamp is authenticated by the LinkRight network. 

### Technologies

* Java 7 for the core modules, Java 8 for everything else
* [Maven 3+](http://maven.apache.org) - for building the project
* [Google Protocol Buffers](https://github.com/google/protobuf) - for use with serialization and hardware communications

### Getting started

Download the java jar file wallettemplate-shaded.jar and use the following command to launch the program

java -jar wallettemplate-shaded.jar

The files LinkRightMessage.db and WalletTemplateRight-main.spvchain are the latest blockchain messages downloaded from LinkRight blockchain network. 
Putting them in the same directory as the jar file wallettemplate-shaded.jar could save you some time from downloading the blockchain message from scratch. 


#### Building from the source 

If you want to compile from the source directly. pleae download the source from linkright project https://github.com/masahikohaniu/linkrightj.

To perform a full build use
```
mvn clean package
```
You can also run
```
mvn site:site
```
to generate a website with useful information like JavaDocs.

The outputs are under the `target` directory.

