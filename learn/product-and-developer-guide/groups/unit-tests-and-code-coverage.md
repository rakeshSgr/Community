# Unit Tests and Code Coverage

Groups is integrated with JACOCO for code coverage. There is a "reports" module in the code base which helps to generate code coverage when compiled the build with maven without skipping the testcases.

Sonar with Circleci is also integrated to provide the codecoverage when a Pull Request is raised to the code base in github. Internally this uses the coverage report generated by the report module to calculate the code coverage of the github repository.

<figure><img src="../../../.gitbook/assets/Screenshot from 2023-06-22 21-25-48.png" alt=""><figcaption></figcaption></figure>
