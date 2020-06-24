# Assessment
QA AUTOMATION ASSESSMENT
	## Prerequisites
	-----------
	OS			:	Windows
	Software	: 	Full Java JDK 8 or JRE 8(Runtime)
	Execution:
	----------
	Open cmd and type=> java -jar "com.assessment-0.0.1-SNAPSHOT.jar"
	Double click on run.bat
	Data folders
	----------
	 configuration.xml => configer browser
	 users.xml => test data for user
	 
	 Test Methods
	 -----------
		Class					Methods				Actions						
		--------				--------			--------				
		UserTest				users				Add User
													Assert User
													Edit User
													Remove User
		
		DogTest					listAllBreeds									https://dog.ceo/api/breeds/list/all
								verifyBreed										https://dog.ceo/api/breeds/list/all
								listSubBreeds									https://dog.ceo/api/breed/retriever/list
								produceRandomImageOrLinkForSubBreed				https://dog.ceo/api/breed/retriever-golden/images/random
