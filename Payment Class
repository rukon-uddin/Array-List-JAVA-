package ulab.cse;
public class Payment {
	
	public double credit;
	public double cGpa;
	
	public void set_Credit(double c) {
		credit = c;
	}
	public void set_cGpa(double cg) {
		cGpa = cg;
	}
	
	public void calculateFees() {
		credit = credit*5000;
		System.out.println("Your Fees: "+ credit);
	}
	public void offerScholarship() {
		if(cGpa>=3.8) System.out.println("You are offered Presidential Scholarship");
		else if(cGpa>=3.5 && cGpa<=3.79) System.out.println("You are offered VC Scholarship");
		else if(cGpa>=3.3 && cGpa<=3.49) System.out.println("You are offered Deans Scholarship");
		else System.out.println("You are offeref no Scholarship");
	}
	
	public void calculateFeesWithMertis()
	{
		if(cGpa>=3.8) {
			double fees = credit;
			fees = fees - (fees*0.5);
			System.out.println("After Scholarship your fees is: "+ fees);
		}else if(cGpa>=3.5 && cGpa<=3.79) {
			double fees = credit;
			fees = fees - (fees*0.3);
			System.out.println("After Scholarship your fees is: "+ fees);
		}else if(cGpa>=3.3 && cGpa<=3.49) {
			double fees = credit;
			fees = fees - (fees*0.1);
			System.out.println("After Scholarship your fees is: "+ fees);
		}else
		{
			double fees = credit;
			System.out.println("You did not resieve any scholarship, your fees: " + fees);
		}
		
	}
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
