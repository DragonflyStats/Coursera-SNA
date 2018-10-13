## Gephi: Network Analytics

![alt text](https://github.com/ULStats/MA4128Assessment-2018/blob/master/Gephi_logo.jpg)

###### History
Gephi is an open-source software for network visualization and analysis written in Java on the NetBeans platform. It was initally developed by a student from the University of Technology of Compiègne in France in french. Gephi is now on version, 0.9.2 launched in September 2017. Gephi runs on Windows, Mac and Linux. Gephi Consortium was founded in 2010 as a french non-profit corporation which supports development of future releases of Gephi. 

Gephi is one of the most modern graph visualization applications available and certainly adds to the statistical analysis world. Gephi represents a friendly user interface with a sleek design and simple user controls. Gephi is available in English, French, Spanish, Japanese, Russian, Brazilian, Portuguese, Chinese, Czech and German. 

###### Application
Gephi is a Network visualization and analysis platform used when working with different types of networks e.g. online networks or offline networks. The main objective of Gephi is to provide an interactive visualization and exploration platform for all kinds of networks and complex graphs. Gephi creates a graph made up of nodes, a person, place or thing, where the edges represent the relationships between the nodes. 

Nodes can be personalized to include images and no overlapping this makes the experience better for the customer. The open source aspect of Gephi extends to the use of free plugins within the application. These help the digestion of large amounts of data, for example the Semantic Web Plugin which allows for specific Sparql, a query language, searches through large files including Dbpedia, a database of Wikipedia entries.

###### What can Gephi be used for?
* Analyse populations of posts that planning organizations post on their website. 
* Identify key stakeholders in a community or an organization. 
* Undersatnd the relationships between members of a network or an organization. 
* Visualize different communities or sub communities in a network or an organisation.

![alt text](https://github.com/ULStats/MA4128Assessment-2018/blob/master/Gephi_graph.png)

###### advantages of Gephi

* Gephi has excellent visualisation capabilities
* It works well across different platforms 
* It works well with large networks (neibourboud groups, companys)
* great help features

###### How to install Gephi
* [Gephi Homepage](https://gephi.org/)
* [Download Gephi 0.9.2 for Windows](https://github.com/gephi/gephi/releases/download/v0.9.2/gephi-0.9.2-windows.exe)
* [Download Gephi 0.9.2 for Linux](https://github.com/gephi/gephi/releases/download/v0.9.2/gephi-0.9.2-linux.tar.gz)
* [Download Gephi 0.9.2 for Mac OS X](https://github.com/gephi/gephi/releases/download/v0.9.2/gephi-0.9.2-macos.dmg)
* [Download Gephi 0.9.2 sources](https://github.com/gephi/gephi/releases/download/v0.9.2/gephi-0.9.2-sources.tar.gz)
* [Download Older Versions](https://github.com/gephi/gephi/releases)

###### Requirements

* Java JDF 7 or 8 with preferably [Oracle Java JDK](https://java.com/en/)
* [Apache Maven](http://maven.apache.org/) version 3.2.2 or later. 

###### Code for Gephi

* Fork the repository and clone
```
git clone git@github.com:username/gephi.git
```
* Run the following command or [open the project in Netbeans](https://github.com/gephi/gephi/wiki/How-to-build-Gephi)
```
mvm clean install
```
* Once built, one can test running Gephi
```
  cd modules/application
  mvn nbm:cluster-app nbm:run-platform
```

***Jonathan O'Brien* **
