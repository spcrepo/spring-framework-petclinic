node {
    stage('scm'){
        git 'https://github.com/spcrepo/spring-framework-petclinic.git'
    }
    stage('build'){
        sh 'mvn package'
    }
}