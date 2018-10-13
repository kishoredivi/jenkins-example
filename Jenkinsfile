@Library('jenkins-demo-lib@master')_
node{

stage('Demo')
{
echo "Hello World"
sayHello()
}
  stage('checkout scm')
  {
    git 'https://github.com/kishoredivi/jenkins-example.git'
  }
stage('maven build')
{
  mavenBuild()
}

}
