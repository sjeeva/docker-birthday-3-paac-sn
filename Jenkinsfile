node ('docker') {
    stage "SCM Synch"
    checkout scm 

    stage "Main Src"
    git url: 'https://github.com/sjeeva/docker-birthday-3.git'
    checkout scm 

    stage "Dummy"
    sh "pwd"
    sh "ls -l"
}
