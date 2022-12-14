node('master')

{

stage('ContinuousDownload_master')
         {
    git 'https://github.com/yvlokeshreddy/multibranchPipeline.git'
        }

stage('Continuousbuild_master')
         {
   sh label: '', script: 'mvn package'
        }

}
