# Lab05
public class Palindrome {


    public static void main(String[] args) {    
    System.out.println(isPalindrome("aba"));
    System.out.println(isPalindrome("bhjjhb"));
    System.out.println(isPalindrome("llhhkkll"));
    System.out.println(isPalindrome("saba"));
    System.out.println(isPalindrome("1983kns1983kns"));

    }
    public static boolean isPalindrome(String word){
        
        int i = 0;
        int j = word.length()- 1;
        
        while(j > i){
            if (word.charAt(i) != word.charAt(j)){
                return false;
            }
            i = i +1;
            j = j +1;
        }
        
        return true;
        
    }
    
}
