# EggBasket
//code done on eclips for practice from [Addison-Wesley] - Java.An.Introduction to Problem Solving and Programming, 6th ed.

public class EggBasket {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		int numberOfBaskets, eggsPerBasket, totalEggs; //variable declarations
		
	
		numberOfBaskets = 10; // Assignment statement
		eggsPerBasket = 6;
		
		totalEggs = numberOfBaskets * eggsPerBasket;
		
		System.out.println("If you have");
		System.out.println(eggsPerBasket + " eggs per basket and");
		System.out.println(numberOfBaskets + " baskets, then");
		System.out.println("the total number of eggs is " + totalEggs);
