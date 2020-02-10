node {
  stage('SCM Checkout'){
    git 'https://github.com/parameshboyapati/AutomationPractice/tree/master/SeleniumCucumberBDDFramework'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
