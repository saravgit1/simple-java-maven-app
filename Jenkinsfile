#!/bin/bash/env groovy

node {
stage ('git')
{
git clone https://github.com/Kushagra92/simple-java-maven-app.git
}
stage ('build')
{
maven clean install
}
}
