pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                discordSend description: '', footer: '', image: '', link: '', result: '', scmWebUrl: '', thumbnail: '', title: 'Jenkins', webhookURL: 'https://discord.com/api/webhooks/983628193930047559/y-eU27XmD2HjlZL0BwlQVCnU7ZLcJlAbgjD8wanCYfcHGxEpAL834WlS9GQPiuYd3AoG'
            }
        }
    }
}
