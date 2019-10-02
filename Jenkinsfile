pipeline {
         agent any
         stages {
                 stage('Git step') {
                 steps {
                     echo 'this is my git step'
	             sh git --version
                 }
                 }
                 stage('Mevan') {
                 steps {
			  echo 'this is my maven step'     	 
                        sh mvn --version 
                 }
                 }
                 stage('Transfer of jar to server') {
                 steps {
	                 sh touch a.jar
                         sh cp a.jar /temp						 
                       
                 }
                 
                 }
                 
              }
}
