Program Destinasi Wisata Tanah Laut

    package wisata.tanah.laut;

    public class WisataTanahLaut {
    //Atribut dan Encapsulation
    public String Kecamatan;
    
    //Constructor
    public WisataTanahLaut (String Kecamatan){
        this.Kecamatan = Kecamatan;
    }
    
    //Mutator (Setter)
    public void setKecamatan (String Kecamatan){
        this.Kecamatan = Kecamatan;
    }

    //Accessor
    public String getKecamatan () {
        return Kecamatan;
    }
    
    //Polymorphism
    public String Hasil() {
        return "Kecamatan : " +getKecamatan();
    }




    package wisata.tanah.laut;
    import java.util.Scanner;
    public class WisataAlam {
    public static void main(String[] args) {
    try{
        //IO
        Scanner masuk = new Scanner(System.in);
        int pilihan;
        System.out.println("WISATA KABUPATEN TANAH LAUT");
        
        //Object
        WisataTanahLaut Wsta = new WisataTanahLaut("Panyipatan");
        System.out.println(Wsta.Hasil());
        System.out.println("----Pilihan Destinasi Wisata----");
        System.out.println("1. Gunung\n2. Pantai\n3. Air Terjun");
        System.out.println("---Pilihan---");
        pilihan = masuk.nextInt();
        System.out.println("--------------");
        
        //Seleksi
        if(pilihan == 1) {
            System.out.println("1. Gunung Birah\n2. Bukit Sapu Angin\n3. Bukit Tamiang");
            System.out.println("\n");
            System.out.println("Pencarian Destinasi Wisata Gunung telah Berhasil");
        }
        
        else if(pilihan == 2) {
            System.out.println("1. Pantai Batakan Baru\n2. Pantai Tanjung Dewa\n3. Pantai Batakan Lama");
            System.out.println("\n");
            System.out.println("Pencarian Destinasi Wisata Pantai telah Berhasil");
        }
        
        else if(pilihan == 3) {
            System.out.println("1. Air Terjun  Giping ");
            System.out.println("\n");
            System.out.println("Pencarian Destinasi Wisata Air Terjun Berhasil");
        }
        
        //Error Handling
        System.out.println("-----------------------------------------------------");      
    } catch (Exception e) {
        System.out.println("Terdapat kesalahan");    
    } finally {
        System.out.println("Terima Kasih");
    }
     
    }

    package wisata.tanah.laut;

    //Inheritance
    public class WisataDetail extends WisataTanahLaut (

    public WisataDetail (String Kecamatan) {
        super (kecamatan);
        }
    }

Nama : Muhammad Fadil
NPM : 2310010699

  
