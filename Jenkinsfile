node {
        stage('clone') { 
            steps {
		git 'https://github.com/porkanimal/helloworld.git'
            }
        }
        stage('build') { 
            steps {
                sh label:'',script: "javac Main.java"
            }
        }
        stage('Deploy') { 
            steps {
                sh label:'',script: "java Main"
            }
        }
}
