
@Library('my-shared-library') _


pipeline {

     agent any
      stages{

          stage('Git Checkout'){
               steps{
                  script{

                      gitCheckout(
                         branch: "main",
                         url: "https://github.com/sambasiva49/java_app.git"
                      )
                  }
               }


           stage('Unit Test maven'){
                          steps{
                            script{
                               mvnTest()

                          }
                          }
          }
      }

}