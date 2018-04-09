node {
    try {
		stage('Backup configuration'){
			echo 'cp src/main/resources/resources.properties conf/'
		}
		
		stage('Pull Branch'){
			echo 'Push to Repo'
		}
    }
    catch (err) {
        echo 'Error occurred'
        throw err
    }
}