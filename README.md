MTG-
====

This is an unfinished code that will create different card objects for many different Magic-The Gathering cards, set them into a 60-card deck, and allow you to keep track of which card is where and at what time.
public class Main {

	public static void main(String[] args) {
		System.out.println("Hello and welcome to the MTG testing room, let's create a deck!");

		Card[] deck = new Card[59];
		
		


		for(int x = 0; x<60;x++){
			System.out.println("Please enter the name of the card.");
			String y = 
			System.out.println("Please enter the power");
			int a = io.readint;
			System.out.println("Enter the toughness");
			int b = io.readint;
			System.out.println("Enter the Description");
			String temp = io.readString;

			Card temporary = new Card(y,a,b,temp);
			deck[x] = temporary;
			}
		
		//I need to find out how to randomize an array of objects here so I can get the deck started.
		Stack randomdeck = new Stack();
		
		public class Card {
	String name;
	int power;
	int toughness;
	String Description;
	public Card(String name,int power,int toughness, String Description){
		this.name = name;
		this.power = power;
		this.toughness = toughness;
		this.Description = Description;
		}
}
