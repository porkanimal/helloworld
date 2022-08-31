node {
        stage('clone') { 
            steps {
		sh "git clone https://github.com/porkanimal/helloworld.git"
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
