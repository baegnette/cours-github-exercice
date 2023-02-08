node {
    stage('clone ') {
    git 'https://github.com/baegnette/cours-github-exercice.git'
    }
    stage('build') {
        sh label: '', script: 'javac Main.java'
    }
     stage('run') {
         sh label: '', script: 'java Main'   
      
    }
}
