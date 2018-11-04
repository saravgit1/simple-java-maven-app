#!/bin/bash/env groovy

node {
stage ('git')
{
scm checkout
}
stage ('build')
{
maven clean install
}
}
