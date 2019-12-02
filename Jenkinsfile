node('MVN'){
    stage('GIT'){
        git 'https://github.com/wakaleo/game-of-life.git'
    }
    stage('BUILD'){
        sh 'mvn install'
    }
    stage('ARCHIVE'){
        archive 'gameoflife-web/target/*.war'
    }
}
