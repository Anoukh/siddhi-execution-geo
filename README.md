Siddhi-execution-geo
======================================

The **siddhi-execution-geo extension** is an extension to <a target="_blank" href="https://wso2.github.io/siddhi">Siddhi</a> that provides geo data related functionality such as checking whether a given geo coordinate is within a predefined geo-fence, etc. Following are the functions of the Geo extension.

Find some useful links below:

* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-execution-geo">Source code</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-execution-geo/releases">Releases</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-execution-geo/issues">Issue tracker</a>

## Latest API Docs 

Latest API Docs is <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-geo/api/4.0.8">4.0.8</a>.

## How to use 

**Using the extension in <a target="_blank" href="https://github.com/wso2/product-sp">WSO2 Stream Processor</a>**

* You can use this extension in the latest <a target="_blank" href="https://github.com/wso2/product-sp/releases">WSO2 Stream Processor</a> that is a part of <a target="_blank" href="http://wso2.com/analytics?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">WSO2 Analytics</a> offering, with editor, debugger and simulation support. 

* This extension is shipped by default with WSO2 Stream Processor, if you wish to use an alternative version of this 
extension you can replace the component <a target="_blank" href="https://github.com/wso2-extensions/siddhi-execution-geo/releases">jar</a> that can be found in the `<STREAM_PROCESSOR_HOME>/lib` 
directory.

**Using the extension as a <a target="_blank" href="https://wso2.github.io/siddhi/documentation/running-as-a-java-library">java library</a>**

* This extension can be added as a maven dependency along with other Siddhi dependencies to your project.

```
     <dependency>
        <groupId>org.wso2.extension.siddhi.execution.geo</groupId>
        <artifactId>siddhi-execution-geo</artifactId>
        <version>x.x.x</version>
     </dependency>
```

## Jenkins Build Status


---

|  Branch | Build Status |
| :------ |:------------ | 
| master  | [![Build Status](https://wso2.org/jenkins/view/All%20Builds/job/siddhi/job/siddhi-execution-geo/badge/icon)](https://wso2.org/jenkins/view/All%20Builds/job/siddhi/job/siddhi-execution-geo/) |

--- 



## Features

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-geo/api/4.0.8/#geocode-stream-function">geocode</a> *(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#stream-function">(Stream Function)</a>)*<br><div style="padding-left: 1em;"><p>Geo code stream function</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-execution-geo/api/4.0.8/#reversegeocode-stream-function">reversegeocode</a> *(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#stream-function">(Stream Function)</a>)*<br><div style="padding-left: 1em;"><p>This extension transforms a latitude and longitude coordinates into precise address information. The output contains string properties streetNumber, neighborhood, route, administrativeAreaLevelTwo, administrativeAreaLevelOne, country, countryCode, postalCode and formattedAddress in order. However, these information are not available for all the geo coordinates. For example, if the latitude and longitude represent a place in a forest, only the high level information like country will be returned. For those which are not available, this extension will return "N/A" as the value.</p></div>

## How to Contribute
 
  * Please report issues at <a target="_blank" href="https://github.com/wso2-extensions/siddhi-execution-geo/issues">GitHub Issue Tracker</a>.
  
  * Send your contributions as pull requests to <a target="_blank" href="https://github.com/wso2-extensions/siddhi-execution-geo/tree/master">master branch</a>. 
 
## Contact us 

 * Post your questions with the <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">"Siddhi"</a> tag in <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">Stackoverflow</a>. 
 
 * Siddhi developers can be contacted via the mailing lists:
 
    Developers List   : [dev@wso2.org](mailto:dev@wso2.org)
    
    Architecture List : [architecture@wso2.org](mailto:architecture@wso2.org)
 
## Support 

* We are committed to ensuring support for this extension in production. Our unique approach ensures that all support leverages our open development methodology and is provided by the very same engineers who build the technology. 

* For more details and to take advantage of this unique opportunity contact us via <a target="_blank" href="http://wso2.com/support?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">http://wso2.com/support/</a>. 


