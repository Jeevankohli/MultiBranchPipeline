@Library('mylibrary')_

node('built-in')
{
    stage('Download_Master')
    {
        cicd.newDownload("maven.git")
    }
    stage('Build_Master')
    {
        cicd.newBuild()
    }}
}
