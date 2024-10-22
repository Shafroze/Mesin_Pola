#include <stdio.h>

void Gambar_Pola1(int lebar, int tinggi) {
    // Loop untuk baris
    for (int i = 0; i < tinggi; i++) {
        // Loop untuk kolom
        for (int j = 0; j < lebar; j++) {
            // Menampilkan * dan spasi secara bergantian
            if ((i + j) % 2 == 0)
                printf("*");
            else
                printf(" ");
        }
        // Pindah ke baris baru setelah satu baris selesai
        printf("\n");
    }
}

void Gambar_Pola2(int lebar, int tinggi){
	  // Loop untuk baris
	  for (int k = 0; k < tinggi; k++){
		    //Loop untuk kolom
		    for (int l = 0; l < lebar; l++){
			      // Menampilkan * dan spasi secara bergantian
			      if (l % 2 == 0)
				        printf("*");
			      else 
				        printf(" ");	
		    }
		    // Pindah ke baris baru setelah satu baris selesai
        printf("\n");
	  }
}

void Gambar_Pola3(int lebar, int tinggi) {
    // Loop untuk baris
    for (int i = 0; i < tinggi; i++) {
        // Loop untuk kolom
        for (int j = 0; j < lebar; j++) {
            // Menampilkan * dan spasi secara bergantian
            if (i < 24) {
            	  if ((i + j) % 4 == 0)
                	  printf("*");
                else
               		  printf(" ");
            } else {
            	  if ((i - j) % 4 == 0)
                	  printf("*");
            	  else
               		  printf(" ");
			      }
        }
        // Pindah ke baris baru setelah satu baris selesai
        printf("\n");
    }
}

int main() {
    int lebar, tinggi, pola;

    // Meminta input dari pengguna
    printf("Masukkan lebar gambar (10-100): ");
    scanf("%d", &lebar);
    printf("Masukkan tinggi gambar (5-75): ");
    scanf("%d", &tinggi);

    // Memeriksa apakah ukuran sesuai dengan batas minimal dan maksimal
    if (lebar < 10 || lebar > 100) {
        printf("Lebar harus antara 10 hingga 100.\n");
    } else if (tinggi < 5 || tinggi > 75) {
        printf("Tinggi harus antara 5 hingga 75.\n");
    } else {
        // Jika ukuran valid, Pilih gambar pola
        printf("Pilih pola gambar 1 sampai dengan 3 ");
        scanf("%d", &pola);
        if (pola == 1){
        	printf("\n");
        	Gambar_Pola1(lebar, tinggi);
    	  }
        else if (pola == 2){
        	printf("\n");
        	Gambar_Pola2(lebar, tinggi);
        }
        else (pola == 3){
        	printf("\n");
        	Gambar_Pola3(lebar, tinggi);
        }
    }

    return 0;
}
