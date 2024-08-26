Pipeline{
      agent any 
             stages{
                 stages(checkout){ 
                   steps{ git 'https://github.com/siddhipande3/pipeline-1.git' 
                        }
                      }
                  stage(build){
                    steps{ sh 'mvn  install'
                        }
                      }
                   stage(deploy){
                     steps{ sh 'cp taget/pipeline-1.war/home/siddhi/Downloads/apache-tomcat-9.0.93/webapps
                        }
                      }
                   }
                  }
                           
                                 
