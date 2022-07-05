pipeline{
    agent { label 'master' }
    stages{
        stage("git checkout")
        {
            steps{
                    //old jenkins version used git 'https://github.com/tinkusaini13/ci-cd-with-maven.git' 
                    git url: 'https://github.com/tinkusaini13/ci-cd-with-maven.git', branch: 'main'
                 }
          }
stage("maven build"){
steps{
sh "mvn clean package"
}
}
      
    }
}
