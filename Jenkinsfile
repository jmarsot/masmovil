#!groovy
pipeline {
    agent any
   stages {     
    stage('GitHub Test') {
      steps {
        script {
                 sh'''#!/bin/bash
                    #git config --global user.email "jenkins@jenkins.com"
                    #git config --global user.name  "Jenkins"
                    #git clone https://github.com/jmarsot/masmovil
                    touch prueba.txt
                    git add prueba.txt
                    git commit -m "Prueba"
                    git push -u origin master
                '''
                } //Fin script
             } //Fin step
             } //fin stage
             } //Fin stages
  } //Fin pipeline      
     
