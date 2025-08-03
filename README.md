# Switch-case-arithmetic-operators
import java util.Scanner;
class Calculator
{
public static void main (String args[])
{
Scanner sc=new Scanner ("System.in");
int C;
System.out.print("Enter the operand1:");
int oper1=sc.nextInt();
System.out.print("Enter the operand2:");
int oper2=sc.nextInt();
System.out.print("Enter a operator:");
char opr=sc.next().charAt(0);
Switch(opr)
{
case'+':
  C=oper1+oper2;
  System.out.println("The addition value is"+C);
  break;
case'-':
  C=oper1-oper2;
  System.out.println("The substraction value is"+(oper1-oper2));
  break;
case'*':
 C=oper1*oper2;
 System.out.println("The multiplication value is"+(oper1*oper2));
 break;
case'/':
 C=oper1/oper2;
 System.out.println("The division value is"+C);
break;
case'%':
 C=oper1%oper2;
 System.out.println("The remainder value is"+C);
 break;
 default:
 System.out.println("The invalid operator");
 }
 }
}

 
