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
			   sh 'echo "This is shubh only" > shubh2.txt'
			 }
		 }
	 }

}
