node {
    stage 'CHECKOUT'
    checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/reactjs/redux.git']]])

    stage 'BUILD'
    sh 'npm build'
}