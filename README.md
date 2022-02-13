# BankAccount
package JavaConcept;

public class BankAccount {
    int Accountnumber;
    int money;
    int balance;
    String Adrress;
    String password;
    
   void createAccount() {
	   System.out.println("Account Created");
   }
   void checkBalance() {
	   System.out.println("Balance Amount is..");
   }
   void transferMoney() {
	   System.out.println("Money trasfered");
   }
   void updateAddress() {
	   System.out.println("Address Updated");
   }
   void changeAddress() {
	   System.out.println("Password changed");
   }
    
    
    
}
package JavaConcept;

public class TesterBank {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		BankAccount Ba = new BankAccount();
		Ba.createAccount();
		Ba.checkBalance();
		Ba.transferMoney();
		Ba.updateAddress();
		Ba.changeAddress();

	}

}
