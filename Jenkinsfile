#!groovy

node {
	stage('Checkout'){

          checkout scm
       }

       stage('Compiling'){

          bat 'mvn clean install'
       }

       
}
