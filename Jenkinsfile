pipeline {
agent any 
stages {
stage('Build'){
steps {
echo 'Reunning build Automation'
sh './gradlew build --no-daemon'
archiveArtifacts artifacts: 'dist/trainSchedule.zip'
}
}
}

}
