def workspace;
node 
{
	stage("Checkout")
	{
		git 'https://github.com/yeolevinod89/website-test.git'
		workspace =pwd() 
	}
	stage("Static Code Analysis")
	{
		echo "Static Code Analysis"
	}
	stage("Build")
	{
		echo "Build time code"
	}
	stage("Test")
	{
		echo "Test time code"	
	}
	stage("Deploy")
	{
		echo "Depoly time code"	
	}
}   
