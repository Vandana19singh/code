# code
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n=sc.nextInt();
        int i=1;
        int FirstNo=0;
        int SecondNo=1;
        System.out.println("Series is ");
        while(i<=n){
            System.out.print(FirstNo+", ");
            int NextNo=FirstNo+SecondNo;
            FirstNo=SecondNo;
            SecondNo=NextNo;
            
            i++;
            
        }
    }
}



import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        int i = 0;
        int evenSum = 0;
        int oddSum = 0;
	  System.out.print("Enter the Number: ");
		int number = sc.nextInt();	
		for(i = 1; i <= number; i++)
		{
			if(i % 2 == 0)
			{
				evenSum = evenSum + i; 
			}
			else
			{
				oddSum = oddSum + i;
			}
		}
		System.out.println(" The Sum of Even Numbers is " + " =  " + evenSum);
		System.out.println("\n The Sum of Odd Numbers is "  + "  =  " + oddSum);
    }
}


import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in); 
        String[] arr = {"Even", "Odd"}; 
        System.out.print("Enter the number: ");
        int num = sc.nextInt();
        System.out.println(arr[num%2]);
    }
}



// To declare an array in js
const arr=[1,2,3,4,5];
console.log(arr);

// to add an element in array
arr.push(6);
console.log(arr);

// to delete an item
arr.pop();
console.log(arr);

// to add a item at particular index
arr[2]=9;
console.log(arr);

// to remove an item at a particular index
arr.splice(1,1);
console.log(arr);



function char_count(str, letter) 
{
 var letter_Count = 0;
 for (var position = 0; position < str.length; position++) 
 {
    if (str.charAt(position) == letter) 
      {
      letter_Count += 1;
      }
  }
  return letter_Count;
}

console.log(char_count('JavaScript was created by Brendan 
Eich in 1995 to give web pages a little more pep than the
 <blink> tag could provide. Today it has far more powerful 
uses and companies like Google and Facebook use JavaScript 
to build complex desktop-like web applications. With the 
launch of Node.js, It has also become one of the most 
popular languages for building server-side software. 
Today, even the web isn’t big enough to contain 
JavaScript’s versatility. I believe that you are already
 aware of these facts and this has made you land on this 
JavaScript Interview Questions article.', 'a'));
