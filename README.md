# Operat-rler

            // Atama ve atama işlemi
            int x = 3;
            int y = 3;
            y = y + 2;// Y'yi iki artırıyoruz.
            y += 2;//İşlemli atama
            y /= 1;
            x *= 2;
            Console.WriteLine(x);
            Console.WriteLine(y);
            Console.ReadLine();
            
            
            
            
            //Mantıksal Operatörler
            // || , &&, !
            bool dogru = true;
            bool yanlıs = false;
            if (dogru && yanlıs)
                Console.WriteLine("Perfect");
            Console.ReadLine();
            
             if (dogru || yanlıs)
                Console.WriteLine("Perfect");
            Console.ReadLine();
            
            
             // İlişkisel Operatörler
            // < , > , <= , >= , == , !=
   
      int a = 3;
            int b = 4;
            bool sonuc = a < b;
            Console.WriteLine(sonuc);
            sonuc = a > b;
            Console.WriteLine(sonuc);
            sonuc = a >= b;
            Console.WriteLine(sonuc);
            sonuc=a <= b;
            Console.WriteLine(sonuc);
            sonuc = a == b;
            Console.WriteLine(sonuc);
            sonuc=a!b;
            Console.WriteLine(sonuc);
            
              // Aritmatik Operatörler
            // * ,/ , + , - 
            int sayi = 10;
            int sayi1 = 5;
            int sonuc1 = sayi / sayi1;
            int sonuc2 = sayi * sayi1;
            int sonuc3 = sayi + sayi1;
            int sonuc4= sayi - sayi1;
            Console.WriteLine(sonuc1);
            Console.WriteLine(sonuc2);
            Console.WriteLine(sonuc3);
            Console.WriteLine(sonuc4);
           
            Console.ReadLine();
             // mod almak
            int sonuc2 = 20 % 3;
            Console.WriteLine("sonuc2");
