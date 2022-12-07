# Comp-6.4

public static void main(String[] args) {
		//runs 100 times
	int numOfBottles = 100;

	// Loops and prints out the first 10 verses of the song
	do 
	{
		System.out.println(numOfBottles 
		+ " bottles of beer on the wall\n" 
		+ numOfBottles 
		+ " bottles of beer" 
		+ "\nIf one of those bottles should happen to fall\n" 
		+ (numOfBottles - 1 )
		+ " bottles of beer on the wall\n");
		numOfBottles -= 1;
	}
	while (numOfBottles > 90);
    }
}
