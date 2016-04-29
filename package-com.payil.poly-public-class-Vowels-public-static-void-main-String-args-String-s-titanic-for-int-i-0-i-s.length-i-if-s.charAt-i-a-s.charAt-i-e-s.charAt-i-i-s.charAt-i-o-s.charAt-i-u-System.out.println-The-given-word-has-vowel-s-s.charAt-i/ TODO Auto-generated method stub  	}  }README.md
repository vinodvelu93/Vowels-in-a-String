# Vowels-in-a-String
package com.payil.poly;

public class Vowels {

	public static void main(String[] args) {
		String s= "titanic";
		for(int i=0;i<s.length();i++){
			if((s.charAt(i)=='a') ||  (s.charAt(i)=='e') ||(s.charAt(i)=='i')||(s.charAt(i)=='o' )|| (s.charAt(i)=='u'))
					{
				System.out.println("The given word has vowel(s) :"+s.charAt(i)); 
			}
		}
		// TODO Auto-generated method stub

	}

}

Output:
The given word has vowel(s) :i
The given word has vowel(s) :a
The given word has vowel(s) :i
