﻿BioDigital Human Content API using Java SE 8
========



Sample code using [Java Platform Standard Edition (Java SE) 8](http://www.oracle.com/technetwork/java/javase/downloads/index.html) to demonstrate making requests to the BioDigital Human Content API service.  This example provides a basic approach to:

* Requesting an access token from the BioDigital OAuth2 services
* Using an access token to make authorized requests to a Content API endpoint



## Getting Started

Below are the steps for getting this example running on your local machine for development and testing purposes.

### Prerequisites

1.  An [api / developer key and secret](https://devsupport.biodigital.com/hc/en-us/articles/234672847-Why-do-I-have-to-register-an-App-) from a verified and active BioDigital Developer account.  These will be used as your ***client id*** and ***client secret*** when making requests to the BioDigital OAuth2 services.


2. [Java SE Development Kit 8](http://www.oracle.com/technetwork/java/javase/downloads/index.html) and the following libraries (***.jar*** files should already be provided under the *libs/* directory):
	*  [Common Cli 1.3.1](https://commons.apache.org/proper/commons-cli/) - https://commons.apache.org/proper/commons-cli/
	*  [Google-Gson](https://github.com/google/gson) - https://github.com/google/gson




### Running on local machine

* Install any library prerequisites or dependencies on your local machine.


*  Download the code files to a directory.  Edit the **Client.java** file by replacing `<DEVELOER_KEY>` and `<DEVELOPER_SECRET>` with your developer key and secret credentials.


```node
	// Your API / Developer key you received when you registered your
	// application at https://developer.biodigital.com
	public static String CLIENT_ID = "<DEVELOPER_KEY>";

	// Your API / Developer secret you received when you registered your
	// application at https://developer.biodigital.com
	public static String CLIENT_SECRET = "<DEVELOPER_SECRET>";

```

*  Open a command terminal and switch to the root directory of the code files.  Run the java program by executing the Java compiler and interpreter on the **Client.java** file using the following command line parameters (see [Java Tutorials](https://docs.oracle.com/javase/tutorial/getStarted/cupojava/index.html) for more detail):
 
```
javac -verbose -classpath "libs/*;." *.java && java -classpath "libs/*;." Client
```

* Step through the command prompt instructions.    
  
  

## Official Documentation

For documentation on BioDigital Human developer APIs and services, please visit [developer.biodigital.com/documentation](https://developer.biodigital.com/documentation)

For access to BioDigital Human developer FAQs and troubleshooting topics, please visit [devsupport.biodigital.com](https://devsupport.biodigital.com)

## Author

* **BioDigital, Inc.** - developers@biodigital.com
