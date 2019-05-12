#!/bin/bash/env groovy
node()
{
stage('checkout')
{
checkout scm
}
stage('Build')
{
sh 'maven clean install'
}
stage('deploy')
{
sh 'ls -la $WORKSPACE/target/'
}
}
