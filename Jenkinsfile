pipeline
{     
       agent 
   	{
	  node
	   {
	      label 'built-in'
		customWorkspace "/mnt/project/"
	   }	   

	}

	stages 
	 {
		stage('job')
		 {
			steps 
			 {
			   sh 'echo "This is Pravin the Teacher" > pravin.txt'
			 }
		 }
	 }

}
