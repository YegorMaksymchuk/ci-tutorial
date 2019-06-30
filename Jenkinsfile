	node {
		environment {
       CI = 'true'
		}
   stage("Clone"){
       git 'https://github.com/YegorMaksymchuk/ci-tutorial.git'
   }
   stage("Install"){
       sh 'npm install'
   }
   stage("Test"){
       sh "npm test"
   }
   stage("Build"){
       sh "npm run build"
   }
	}
