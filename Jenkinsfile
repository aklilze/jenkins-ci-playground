//script

node {
    stage('Build'){

        checkout scm

        git credentialsId: '2e85eb93-2796-4049-9629-847e6ba634ad', url: 'https://github.com/vegascraig11/ZIPHUB-DATA.git'
        
        echo 'Building ....'
    }
    stage('Exec Gradle'){

        //rtGradle.run rootDir: "gradle-examples/4/gradle-example/", buildFile: 'build.gradle', tasks: 'flywayMigrate', buildInfo: buildInfo

        //rtGradle.run buildFile: 'build.gradle', tasks: 'flywayMigrate', buildInfo: buildInfo

        echo 'Exec Gradle ....'


    }
    stage ('Deploy') {

        echo 'Deploying ....'
    }
}