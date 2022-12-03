pipeline {

    agent any
   // triggers {
     // cron('*/4 * * * *')

//    } 

    stages {
    //   stage ('GIT') {
     //       steps {
      //         echo "Getting Project from Git"; 
       //        git branch:"master", url : "https://github.com/jihed2/devops-gomycode.git"; 
       //     }
        //}

       stage("Verification du version Maven") {
           steps {
                bat "mvn -version"
              
            }
        }
	
        	
    }
}