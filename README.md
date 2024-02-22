class Number
{
	public static void main(String[] args)
	{
		int number = 1;
		int n = 1;
		int space = 3;
		int secondNumber = 1;
		int secondSpace = 7;
		for (int i = 0; i < 8 ; i++ )
		{
			int count = n;
			if (i < 4)
			{
				for(int k = 0; k<space ; k++){
					System.out.print("  ");
				}
				for (int j = 1; j <= number ; j++ )
			{
				System.out.print(count+" ");
				count++;
			}
			number+=2;
			space--;
			System.out.println();
			}else
			{
				for(int k = 0; k<secondSpace ; k++){
					System.out.print("  ");
				}
				for (int j = 1; j <= secondNumber ; j++ )
			{
				System.out.print(count + " ");
				count++;
			}
			secondNumber+=2;
			secondSpace--;
			System.out.println();
			}
		}
	}
}
