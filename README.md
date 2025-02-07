# dex670-250204


## Account information
* org id : af6f1910-04c0-4e63-9204-6445022e6468
* client id : 7cdee5fff03f44b384c1144b37f71785
* client secret : 04b408d494BD401CB951f7EC735eeb56

## Connected Apps information
* Exchange Viewer
  * client id : 1d92b4f741224c2790deb685d809633a
  * client secret : 2E00B60308EF43179a542c3000693e77

* Exchange Contributor
  * client id : 92ad4921f3b945cfad8e4c595a672679
  * client secret : 9388176DaD5D41308253B76ca2c3efEE

* env var

export PROJECT_HOME=/Users/woohyeok.kim/Desktop/work/training/prints/dex670-250204
export STUDENT_FILE=/Users/woohyeok.kim/Desktop/work/training/prints/CDEV-DEX670-EN-25oct2024-Student-Files


curl -ik -X PUT -H "Content-Type: application/json" -d "{\"lastName\":\"Mule\",\"numBags\":2}" https://check-in-papi-app-as9da3.5sc6y6-2.usa-e2.cloudhub.io/api/v1/tickets/PNR123/checkin


curl -ik -X PUT -H "Content-Type: application/json" -d "{\"lastName\":\"Mule\",\"numBags\":2}" https://check-in-papi-app-as9da3.5sc6y6-2.usa-e2.cloudhub.io/api/v1/tickets/PNR123/checkin




https://check-in-papi-app-as9da3.5sc6y6-2.usa-e2.cloudhub.io/


mvn -B -f bom/pom.xml archetype:generate -DarchetypeGroupId=org.mule.extensions -DarchetypeArtifactId=mule-extensions-xml-archetype -DarchetypeVersion=1.2.0 -DgroupId=af6f1910-04c0-4e63-9204-6445022e6468 -DartifactId=resilience-mule-extension -DmuleConnectorName=resilience-mule-extension -DextensionName=resilience -Dpackage=. -DoutputDirectory=../