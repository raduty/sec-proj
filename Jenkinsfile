node { 
    stage('Build') {
        steps {
            CD > tmpFile
            SET /P myvar= < tmpFile
            DEL tmpFile
            echo 'Hello World ' %myvar%
        }
    }
    stage('Test') {
        steps {
            echo 'This is another stage'
        }
    }
    stage('Deploy') {
        steps {
            echo 'This is another stage'
        }
    }
}
echo 
