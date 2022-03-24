node{
     
	stage('Code checkout')
	{     
		bat 'git clone -b Dev https://github.com/SRachamf/MicroFocus.git'       
	}
    
	stage('Env setup')
	{
         bat 'C:\\Users\\Administrator\\AUTO_PIPE\\Jenkins_Env_Setup.bat'       
	}
  
	stage ('Build setup')
	{
	     bat 'C:\\Users\\Administrator\\AUTO_PIPE\\Build_Setup.bat'
	}
  
	stage('Auto_build')
	{
        bat 'C:\\Users\\Administrator\\AUTO_PIPE\\Auto_Build.bat' 
	}   
	stage('Auto_deploy')
	{
        bat 'C:\\Users\\Administrator\\AUTO_PIPE\\Auto_Deploy.bat'     
	}

	stage('Cleanup')
	{
        bat 'C:\\Users\\Administrator\\AUTO_PIPE\\Cleanup.bat'   
	}
}
