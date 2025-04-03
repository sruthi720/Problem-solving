This repo contain various DSA and java problems and its solutions.
Mainly started to track the DSA problem solving skill development .
Starting from  zero , an absolute beginner.


* While solving a problem make sure to follow the above steps as per the question

    For the number reversal problem
		// your code goes here
		
		// step 1-> input read
		Scanner input = new Scanner(System.in);
		int number = input.nextInt();
		
		int reminder;
		int sum=0;
		//step 2-> logic
		//step	3-> constraints
		if(100 <= number && number <= 999){
			while(number!=0){
			reminder=number%10;
			sum= sum*10+reminder;
			number=number/10;
		}
		}
		
		//step4-> output
		System.out.println(sum);
