  pipeline {                                                                                                                                                              
      agent any                                                                                                                                                           
      stages {                                                                                                                                                            
          stage('Export Sonar Findings') {                                                                                                                                
              steps{                                                                                                                                                      
                  exportSonarQubeScan(                                                                                                                                    
                      component: "test-component",                                                                                                                        
                      project: "0006afa4456a120d1423c847a271542af0c03af6d86a10414ae7ce89b595965a",                                                                        
                      host: "https://sonarqube.saas-preprod.beescloud.com",                                                                                               
                      credentialId: "sonar-token"                                                                                                                         
                  )                                                                                                                                                       
              }                                                                                                                                                           
          }                                                                                                                                                               
      }           
  }  
