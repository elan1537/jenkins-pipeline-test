pipeline {
   agent none # 어떤 환경에 배포할지 선정한다
   stages {
      stage("build") {
         steps {
            echo 'building the applicaiton...'
         }
      }
      stage("test") {
         steps {
            echo 'testing the applicaiton...'
         }
      }
      stage("deploy") {
         steps {
            echo 'deploying the applicaiton...'
         }
      }
   }
}