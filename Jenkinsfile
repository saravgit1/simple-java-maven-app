#!/bin/bash/env groovy

node {
stage ('git')
{
sh "git clone https://github.com/Kushagra92/simple-java-maven-app.git"
}
stage ('build')
{
sh "mvn clean test verify"
}
}
