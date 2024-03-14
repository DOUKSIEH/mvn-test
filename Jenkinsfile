node {
    // some block
    
    stage('clone') {
        //clone le projet
        git branch: 'main', url: 'https://github.com/DOUKSIEH/jenkins-test.git'
    }
    stage('build') {
        // lancement des commandes
        sh '''javac Main.java'''
    }
    stage('run') {
        sh '''java Main'
           
    }
}
