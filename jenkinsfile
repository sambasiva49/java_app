pipeline {

     agent any
      stages{

          stages('Git checkout'){
               steps{
                  script{
                     git branch: 'main', url: 'https://github.com/sambasiva49/java_app.git'
                  }
               }



          }
      }

}