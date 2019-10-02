pipeline {
         agent any
         stages {
                 stage('Git step') {
                 steps {
                     echo 'this is my git step'
					 git --version
                 }
                 }
                 stage('Mevan') {
                 steps {
			          echo 'this is my maven step'     	 
                         mvn --version 
                 }
                 }
                 stage('Transfer of jar to server') {
                 steps {
	                     touch a.jar
                          cp a.jar /temp						 
                       
                 }
                 
                 }
                 
              }
}
