// Lab 3 
pipeline {
    agent any
    stages {
        stage('Pipeline Stages'){
            steps {
                sh "ls"
            }
        }
        stage('second stage'){
            steps {
                sh “pwd”
            }
        }
    }
}




// // global variables
// // persistant
// // Used in groovy script

// pipeline {
//     agent any
//     //environment {// var passed to sh. creds/path}
//     /*options {
//         timestamps() //global
//         disableConcurrentBuilds() //global
//         timeout(time: 5, unit: "minutes") // global
//         retry(3) // stage

//     }*/
//     stages {
//         stage("Make a directory") {
//             options {
//                 timeout(time: 1, unit: java.util.concurrent.TimeUnit.MINUTES) // stage
//             }
//             steps {
//                 sh "mkdir ~/jenkins_test_dir" // create a directory in the home folder
//                 sh "cd ~/jenkins_test_dir" // runs seperately, so this does not change the working directory for subsequent steps
//             }

//             post {
//                 success {
//                     echo "Success: Stage 1: Directory created successfully"
//                 }
//                 failure {
//                     echo "Failure: Stage 1: Directory creation failed"
//                 }
//                 always {
//                     echo "Always: Stage 1: This will always run"
//                 }

//             }
//         }
//         stage("add file"){
//             steps {
//                 sh "touch ~/jenkins_test_dir/test_file.txt" // create a file in the directory
//             }
//         }
//     }
// }
