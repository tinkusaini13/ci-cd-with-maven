pipeline{
    agent { label 'master' }
    stages{
        stage("git checkout")
        {
            steps{
                    git 'https://github.com/tinkusaini13/ci-cd-with-maven.git'
                 }
          }
stage("maven build"){
steps{
sh "mvn -f /root/project/src/main/java/ clean package"
}
}
      
    }
}
