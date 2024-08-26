# Adding-array-in-java
Addition of 2D array in java

import java.util.Scanner;
 class AddingArray{
  public static void main( String[] args)
  {
    Scanner sc = new Scanner(System.in);
    System.out.print("Enter the no. of. rows: ");
    
    int rows = sc.nextInt();
    System.out.println(" Enter the no. of. columns: ");
    int columns = sc.nextInt();
    int matrix1[][]= new int[rows][columns];
    int matrix2[][]=new int[rows][columns];
    int result[][]= new int[rows][columns];
    System.out.print(" Enter the elements of matrix1: ");
    for(int i=0;i<rows;i++) 
      {
        for(int j=0;j<columns;j++)
          {
            matrix1[i][j]=sc.nextInt();
          }
      }
    System. out. print(" Enter the elements of matrix2: ");
    for(int i=0;i<rows;i++) 
      {
        for(int j=0;j<columns;j++)
          {
            matrix2[i][j]=sc.nextInt();
          }}
    System. out. print("Adding the elements of matrix1& matrix2: ");
    for(int i=0;i<rows;i++) {
  for(int j=0;j<columns;j++)
          {
            result[i][j]=matrix1[i][j]+ matrix2[i][j];
    }
  }
    System.out.println(" Printing the resultant result matrix as output");
    for(int i=0;i<rows;i++) 
      {
        for(int j=0;j<columns;j++)
          {
            System.out.print(result[i][j]+"");
            
          }
        System.out.println();
      }
}
 }
