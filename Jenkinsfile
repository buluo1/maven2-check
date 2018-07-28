node {
    // Clean workspace before doing anything
    deleteDir()

    try {
        stage ('Clone') {
            echo "clone phase"
        }
        stage ('Build') {
            echo "build phase"
        }
       
        stage ('Deploy') {
            echo "deploy phase'"
        }
    } catch (err) {
        currentBuild.result = 'FAILED'
        throw err
    }
}
