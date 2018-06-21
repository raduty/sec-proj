node { 
    stage('Build') {
        checkout scm
    }
    stage('Test') {
        bat 'start cmd.exe /c mybat.bat'
    }
    stage('Deploy') {
        println('This is another stage');
    }
}
