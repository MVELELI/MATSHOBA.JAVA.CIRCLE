/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package za.ac.wsu.driver.s220655839;

import za.ac.wsu.s220655839.Circle;

/**
 *
 * @author matsh
 */
public class CircleMain {
    public static void main(String[]args){
        // creates 3 Circle objects
        Circle cm = new Circle();
        Circle cn = new Circle();
        Circle co = new Circle();
        
        // set values to circle objects
        cm.setRadius(15);
        cm.setX(4);
        cm.setY(8);
        
        cn.setRadius(10);
        cn.setX(2);
        cn.setY(5);
        
        co.setRadius(5);
        co.setX(8);
        co.setY(4);
        
        // displays the information of these circles 
        System.out.println("\nCircle m information");
        displayInformation(cm);
        System.out.println("\nnCircle n Information");
        displayInformation(cn);
        System.out.println("\nCircle o information");
        displayInformation(co);
    }
    
    /**
     * Displays information of circle
     * @param c
     */
    public static void displayInformation(Circle c){
        System.out.println("Radius:"+c.getRadius() +", Center: (" +c.getX() +", " + c.getY() +")");
        System.out.printf("Area: %.2f",c.calculateArea());
        System.out.printf("\nCircumference: %.2f",c.calculateCircumference());
        System.out.printf("\nDiameter: %.2f",c.calculateDiameter());
        System.out.println();       
    }
    
}

