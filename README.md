## Installation
---------------

* Use the maven to install [mvn](https://maven.apache.org/download.cgi) to install CsvToHtml.

```bash
mvn clean install

## Usage
--------

* run below command to include header row :
	java -jar CsvToHtml.jar present

* run below command not to include header row :
	java -jar CsvToHtml.jar
	
* On running CsvToHtml.jar below message will be printed on the console :
	"Both the files converted to HTML".
  and a folder with name "html" will be created containing CsvType.html, PrnType.html files

## What's Next ?
----------------

* we can extend the application to adopt other file types like PDF to HTML etc.
* we can add test cases as per requirements
* to expose these functionalities as REST end-points to be consume by a front-end UI for better user experience.

## Assumptions
--------------

* for PRN file we can find and implement a pattern to split the lines.

## Dependencies
---------------
* Junit 5 related libraries.
* jdk 1.17