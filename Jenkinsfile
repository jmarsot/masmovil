#!groovy
pipeline {
    agent any
   stages {     
    stage('GitHub Test') {
      steps {
        script {
                 sh'''#!/bin/bash
                    #git remote set-url origin git@github.com:jmarsot/masmovil.git
                    hub config --global hub.protocol ssh
                    hub config --global user.email "jenkins@jenkins.com"
                    hub config --global user.name  "jenkins"
                    touch prueba.txt
                    git add prueba.txt
                    git commit -m "Prueba"
                    git push -u origin HEAD:master
                '''
                } //Fin script
             } //Fin step
             } //fin stage
             } //Fin stages
  } //Fin pipeline      
     
