pipeline{
        agent any
        stages{
            stage('Make Directory'){
                steps{
                    dir('/home/azureuser/') {
    touch jenkins.txt
}
                }
            }
            stage('Make Files'){
                steps{
                    sh "touch ~/jenkins-tutorial-test/file1 ~/jenkins-tutorial-test/file2"
                }
            }
        }
}
