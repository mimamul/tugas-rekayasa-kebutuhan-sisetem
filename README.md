# tugas-rekayasa-kebutuhan-sisetem
package com.company;
import java.util.Scanner;
public class Main {

    public static void main(String[] args) {
	// write your code here
        Scanner input = new Scanner(System.in);
        int pesan,pilih;
        String nama;

        System.out.print("Masukkan nama :");
        nama = input.next();

        System.out.print("PILIHAN MENU : \n1. Nasi Goreng(Rp.15.000");
        System.out.print("\n2. Mie Ayam(Rp.10.000");
        System.out.print("\n3. Bakso(Rp.13.000");
        System.out.print("\n4. Sate(Rp.14.000");
        System.out.print("\n5. Es teh manis(Rp.3.000");
        System.out.print("\n6. Es teh tawar(Rp.5.000");
        System.out.print("\n7. Pizza (Rp.25.000");
        System.out.print("\n8. Batagor(Rp.10.000");
        System.out.print("\n9. Mie Gacoan(Rp.13.000");
        System.out.print("\n10. Susu Soda(Rp.9.000\n");

        System.out.print("Masukkan Pilihan :");
        pilih = input.nextInt();
        System.out.print("Jumlah Pesan : ");
        pesan = input.nextInt();
        System.out.println("================");
        switch(pilih){
            case 1:
                System.out.println("Nama Pemesan :"+nama);
                System.out.println("Pesanan : Nasi Goreng");
                System.out.println("Harga : 15.000");
                System.out.println("Jumlah Pesan : "+pesan);
                System.out.println("Total Bayar : "+pesan*15000);
                break;
            case 2:
                System.out.println("Nama Pemesan :"+nama);
                System.out.println("Pesanan : Mie Ayam");
                System.out.println("Harga : 10.000");
                System.out.println("Jumlah Pesan : "+pesan);
                System.out.println("Total Bayar : "+pesan*10000);
                break;
            case 3:
                System.out.println("Nama Pemesan :"+nama);
                System.out.println("Pesanan : Bakso");
                System.out.println("Harga : 13.000");
                System.out.println("Jumlah Pesan : "+pesan);
                System.out.println("Total Bayar : "+pesan*13000);
                break;
            case 4:
                System.out.println("Nama Pemesan :"+nama);
                System.out.println("Pesanan : Sate");
                System.out.println("Harga : 14.000");
                System.out.println("Jumlah Pesan : "+pesan);
                System.out.println("Total Bayar : "+pesan*14000);
                break;
            case 5:
                System.out.println("Nama Pemesan :"+nama);
                System.out.println("Pesanan : Es teh manis");
                System.out.println("Harga : 3.000");
                System.out.println("Jumlah Pesan : "+pesan);
                System.out.println("Total Bayar : "+pesan*3000);
                break;
            case 6:
                System.out.println("Nama Pemesan :"+nama);
                System.out.println("Pesanan : Es teh tawar");
                System.out.println("Harga : 5.000");
                System.out.println("Jumlah Pesan : "+pesan);
                System.out.println("Total Bayar : "+pesan*5000);
                break;
            case 7:
                System.out.println("Nama Pemesan :"+nama);
                System.out.println("Pesanan : Pizza");
                System.out.println("Harga : 25.000");
                System.out.println("Jumlah Pesan : "+pesan);
                System.out.println("Total Bayar : "+pesan*25000);
                break;
            case 8:
                System.out.println("Nama Pemesan :"+nama);
                System.out.println("Pesanan : Batagor");
                System.out.println("Harga : 10.000");
                System.out.println("Jumlah Pesan : "+pesan);
                System.out.println("Total Bayar : "+pesan*10000);
                break;
            case 9:
                System.out.println("Nama Pemesan :"+nama);
                System.out.println("Pesanan : Mie Gacoan");
                System.out.println("Harga : 13.000");
                System.out.println("Jumlah Pesan : "+pesan);
                System.out.println("Total Bayar : "+pesan*13000);
                break;
            case 10:
                System.out.println("Nama Pemesan :"+nama);
                System.out.println("Pesanan : Susu soda");
                System.out.println("Harga : 9.000");
                System.out.println("Jumlah Pesan : "+pesan);
                System.out.println("Total Bayar : "+pesan*9000);
                break;
            default:
                System.out.println("Salah Pilih ! :(");
        }
    }
}
