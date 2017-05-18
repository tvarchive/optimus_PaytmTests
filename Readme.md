# Mobile App testing using Optimus

Optimus Template is the native framework for Optimus, designed to help you
to get started with your tests in the swiftest time possible. Read more about Optimus on our [wiki](https://github.com/testvagrant/optimusTemplate/wiki).

### How to run this test
1.Clone the repository.
2.Select ```build.gradle``` file from the project and open it as a project.
3.There are two options for running your tests -

a.Go to your IntelliJ terminal and type the following -
  ```gradle clean build runFragmentation -DtestFeed="paytm" -Dtags=@paytm-mobile-recharge
  ```
  Here you can choose to replace the tags which you will find in the feature
  files which you will find under src/test/resources

b.The other option is to go to Run->Edit Configurations from your menu and
  click on it.Then click on Defaults->Cucumber java.You will see a configuration
  tab on the top right side.Under that you will find VM options.There you have
  to write the following :
  ```-DtestFeed=paytm -DrunMode=Fragmentation
  ```
  After doing this, go to any of the feature files and right click on any
  scenario and select Run option.


  
