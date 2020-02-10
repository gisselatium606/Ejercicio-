
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package hilos;

/**
 *

public class Hilos {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
    }
    
}
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package hilos;

import java.util.logging.Level;
import java.util.logging.Logger;


public class Proceso extends javax.swing.JFrame {

    /**
     * Creates new form Proceso
     */
    public Proceso() {
        initComponents();
       Hilo x=new Hilo();
       x.start();
       System.out.print("Proceso "+x.a);
    
    }
