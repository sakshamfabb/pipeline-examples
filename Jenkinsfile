/*node {
	stage 'Checkout'
		checkout scm

	stage 'Build'
		bat 'nuget restore SolutionName.sln'
		bat "\"${tool 'MSBuild'}\" SolutionName.sln /p:Configuration=Release /p:Platform=\"Any CPU\" /p:ProductVersion=1.0.0.${env.BUILD_NUMBER}"

	stage 'Archive'
		archive 'ProjectName/bin/Release/**'

}
*/
        // scripted pipeline syntax
node {
    stage('Build') {
        //
        echo "build complete"
    }
    stage('Test') {
        //
        echo "test complete"
    }
    stage('Deploy') {
        //
        "echo "deploy completed
    }
}



