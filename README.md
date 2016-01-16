# Multiple-Classes
import java.util.Scanner;
class Room
{
	float length;
	float breadth;
	void getData(float a,float b)
	{
		length=a;
		breadth=b;
	}
}
public class area {
	
	public static void main(String args[])
	{	
		float len,brd,area;
		Scanner in = new Scanner(System.in);
		System.out.println("Enter the length");
		len=in.nextFloat();
		System.out.println("Enter the breadth");
		brd=in.nextFloat();
		Room room1=new Room();
		room1.getData(len, brd);
		area=room1.length*room1.breadth;
		System.out.println("The area of the room is "+area);
	
}
	}
