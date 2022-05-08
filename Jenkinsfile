node('master')

{

stage('ContinuousDownload_master') 
   
	 {
	
    git 'https://github.com/Khadeer14/Multi_Branch.git'
    
	}

stage('Continuousbuild_master') 
   
	 {
	
   sh 'mvn package'
	}


}


