node('built-in') {
    
    stage('continous download') {
      git 'https://github.com/erarfat/maven-demo.git'
    }
    
    stage('continous build') {
      sh 'mvn package'
    }
    
  
}
