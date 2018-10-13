@Library('jenkins-demo-lib@master')_
node{
stages{
stage('Demo')
{
echo "Hello World"
sayHello()
}
stage('maven build')
{
  mavenBuild()
}
}
}
