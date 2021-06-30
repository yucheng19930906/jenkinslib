#!groovy

@Library('yucjenkinslib') _

def tools = new org.devops.tools
pipeline {
    agent any
    stages{
        stage{
            steps{
                script{
                    tools.PrintMes("this is my lib!")
                }
            }
        }
    }
}
