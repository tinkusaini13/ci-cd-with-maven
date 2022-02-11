pipeline{
    agent { label 'master' }
    stages{
        stage("git checkout")
        {
            steps{
                    git 'https://github.com/tinkusaini13/java-maven-jenkinsfile.git'
                 }
          }
stage("maven build"){
steps{
sh "mvn -f /root/project/src/main/java/ clean package"
}
}
      
    }
}
