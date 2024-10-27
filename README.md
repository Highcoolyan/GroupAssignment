#import java.util.Scanner;
#import java.io.*;

class Module{
  private String name;
  private String code;

  //constructor
  public Module(String n,String c){
    name=n;
    code=c;
  }

  //getter
  public String getName(){
    return name;
  }
  public String getCode(){
    return code;
  }

  //setter
  public void setName(){
    name=n;
  }
  public void setCode(){
    code=c;
  }

//Courses Module
  public void courseModule(){
  
  }
  public void addCourse(){

  }
  public void editCourse(){

  }
  public void deleteCourse(){

  }
  public void viewCourse(){

  }


//Student Module
  public void studentModule(module m){
  
  }
  public void addStudMark(){

  }
  public void editStudMark(){

  }
  public void delStudMark(){

  }
  public void viewStudMark(){

  }

  public void grade(){
  
  }


//Student Mark Management System Layout
  public void mainMenu(){

  }
}

public class GroupAssignment{
  public static void main(String args[])throws IOException{

    Filereader fr=new FileReader(".txt");
    Scanner sc=new Scanner(fr);

    Module modules[]=new Module[];


    sc.close();
  }
}
