# fileReader
import java.io.File;
import java.io.FileNotFoundException;
import java.util.ArrayList;
import java.util.Scanner;

public class FileReader
{
public static void main(String[] args) throws FileNotFoundException{
 	    String a = "";
	    File q = new File("");
	    String currentPath = q.getAbsolutePath();
	    System.out.println(currentPath);
		Scanner input = new Scanner(new File(a));
		ArrayList<String> fileInputs = new ArrayList<String>();
		while(input.hasNextLine())
		{
			String a = input.nextLine();
			fileInputs.add(a);
		}
		input.close();
	}
	String a = new String();
		for(int i = 0; i < fileInputs.s)

}
}
