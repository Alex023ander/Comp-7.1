# Comp-7.1

public static void main(String[] args) {




	Account acct1 = new Account("Alex Tanaka", 72354);
	Account acct2 = new Account("Justin Yang", 69713);
	Account acct3 = new Account("Edward Demsey", 93757);

	      acct1.deposit(60.75);

	      double yangBalance = acct2.deposit(1000.00);
	      System.out.println("Yang balance after deposit: " +
	                          yangBalance);

	      System.out.println("Yang balance after withdrawal: " + 
	                          acct2.withdraw (430.75, 1.50));

	      acct1.addInterest();
	      acct2.addInterest();
	      acct3.addInterest();

	      System.out.println();
	      System.out.println(acct1);
	      System.out.println(acct2);
	      System.out.println(acct3);
	      
    }
}
