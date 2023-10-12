public class Main
{
 public static void main(String[] args) {
     String str1 = "Быть или не быть, вот в чем вопрос?";
     String str2 = "Есть многое на свете друг Гораций, что и не снилось нашим мудрецам";
     int s1 = str1.length();
     int s2 = str2.length();
     if (s1<s2){
         System.out.println(str2);
     }
     else if (s2<s1){
         System.out.println(str1);
     }
 }
}
