// pipeline {
//   agent any
    
//   tools {nodejs "node"}
    
//   stages {
        
//     stage('Cloning Git') {
//       steps {
//         git 'https://github.com/15110139/test-jenkins'
//       }
//     }
        
//     stage('Install dependencies') {
//       steps {
//         sh 'npm install'
//       }
//     }
     
//     stage('Test') {
//       steps {
//          sh 'npm start'
//       }
//     }      
//   }
// }



pipeline {
    agent {
        docker { image 'node:10-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}