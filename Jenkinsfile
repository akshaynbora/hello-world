pipeline {
agent any
  stages{
     stage("Build")
	   {
	    steps{
		    echo "We are in the build stage. Added the webhook. Time 10.21 again"
		    sh 'mkdir -p /tmp/akshay'
		    sh ' echo "AKshay" >> /tmp/akshay/akshay.txt'
		}
	   }
	 stage("Test")
	   {
	    steps{
		    echo "We are in the Test stage"
		}
	   }
	 stage("Deploy")
	   {
	    steps {
		    echo "We are in the Deploy stage"
		}
	   }
	  }
	 } 
