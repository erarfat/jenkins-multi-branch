node('built-in') {
    
    stage('continous download') {
      git 'https://github.com/erarfat/maven-demo.git'
    }
    
    stage('continous build') {
      sh 'mvn package'
    }
    
    stage('continous deployment') {
      sh 'scp /home/ubuntu/.jenkins/workspace/script/target/my-webapp-1.0-SNAPSHOT.war ubuntu@172.31.42.146:/var/lib/tomcat10/webapps/webapp.war'
    }
    
}
