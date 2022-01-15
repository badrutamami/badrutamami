
package pkgswitch;
import javax.swing.*;
public class SWITCH {
      public static void main(String[] args) {
       int A = 100, B = 25;
        System.out.println("Menu Pilihan :");
        System.out.println(" 1. Penjumlahan");
        System.out.println(" 2. Pengurangan");
        System.out.println(" 3. Perkalian");
        System.out.println(" 4. Pembagian");
        String data_pilihan = JOptionPane.showInputDialog ("Masukan Pilihan anda [1-4] :");
        int pilihan = Integer.parseInt(data_pilihan);
        switch (pilihan) {
            case 1: {
            int jumlah = A + B ;
            System.out.println(" Penjumlahan" + A+ " +" +B+ "=" +jumlah);
            break;
        }
            case 2: {
            int kurang = A - B ;
            System.out.println(" Pengurangan" + A + " - " + B + " = " +kurang);
            break;
        }
            case 3: {
            int kali = A * B ;
            System.out.println(" Perkalian " + A + " * " + B + " = " +kali);
            break;
    }
            case 4: {
            float bagi = A / B ;
            System.out.println(" Pembagian" + A + " : " + B + " = " +bagi);
            break;
    }
            default:
        System.out.println("Pilihan Anda Salah");
        break;
}
    }
}
