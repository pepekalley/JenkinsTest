node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/pepekalley/JenkinsTest.git'
    }
    stage('Build') {
        sh label: 'shell', script: '''
        javac Main.java
        '''
    }
    stage('Run') {
    sh label: 'shell', script: '''
        java Main
        '''
    }
    
}
