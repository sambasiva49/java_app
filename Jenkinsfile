
@Library('my-shared-library') _


pipeline {

     agent any
      stages{

          stages('Git Checkout'){
               steps{
                  script{

                      gitCheckout(
                         branch: "main",
                         url: "https://github.com/sambasiva49/java_app.git"
                      )
                  }
               }



          }
      }

}