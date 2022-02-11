pipeline{
    agent { label 'master' }
    stages{
        stage("git checkout")
        {
            steps{
                    git 'https://github.com/tinkusaini13/g2/'
                 }
          }
stage("maven build"){
steps{
sh "mvn -f /root/project/gs-maven/complete clean package"
}
}
      
    }
}
