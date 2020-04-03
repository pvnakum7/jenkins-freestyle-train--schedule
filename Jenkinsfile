pipeline{
  agent any
    stage {
        stage('build'){
              step{
                  echo ''Runig build Automatation'
                  sh './gradlew build --no-daemon'
                  archivesArtifacts artifacts: 'dist/trainSchedule.zip'
                  
                 }
        }
    }
}
