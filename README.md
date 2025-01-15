package sumofarray;
public class Sumofarray {
    public static void main(String[] args) {
      int[] numbers = {5,10,15,20,25};
      int sum=0;
      for(int num : numbers){
          sum+=num;
      }
      System.out.println("sum of elements:"+sum);
    }
}

Output
sum of elements:75
