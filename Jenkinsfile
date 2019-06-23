// // Python
// pipeline {
//     agent { docker { image 'python:3.5.1' } }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'python --version'
//             }
//         }
//     }
// }

// // Java
// pipeline {
//     agent { docker { image 'maven:3.3.3' } }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'mvn --version'
//             }
//         }
//     }
// }

// // Node.js
// pipeline {
//     agent { docker { image 'node:6.3' } }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'npm --version'
//             }
//         }
//     }
// }

// Ruby
pipeline {
    agent { docker { image 'ruby' } }
    stages {
        stage('build') {
            steps {
                sh 'ruby --version'
            }
        }
    }
}