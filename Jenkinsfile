#!groovy

@Library('yucjenkinslib') _

def tools = new org.devops.tools()

pipeline {
    agent any
    stages{
        stage("step 1"){
            steps{
                script{
                    tools.PrintMes("this is my lib!")
                }
            }
        }
    }
}
