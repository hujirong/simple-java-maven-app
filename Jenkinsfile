pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                shell 'mvn -B -DskipTests clean package' 
            }
        }
    }
}

def shell(command) {
    return bat(returnStdout: true, script: "sh -x -c \"${command}\"").trim()
}
