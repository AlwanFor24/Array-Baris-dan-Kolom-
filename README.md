# Array-Baris-dan-Kolom-
# Ujian-Akhir-Semester_Dasar-Pemograman_1227050017
<br>Mata Kuliah 		: Dasar Pemograman
<br>Nama		      	: Alwan Maulana Firdaus
<br>NIM		           	:	1227050017
<br>Jurusan		    	:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

# Deskripsi Umum
<br>Menampilkan program baris dan kolom serta pertukaran baris menjadi kolom dan kolom menjadi baris.

# Source Code
#include 
#include 
using namespace std;

void garis(){
cout<<"--------------------------------------"<<endl;
}

main(){
int row,clm,x,y,z;
cout<<"Banyaknya baris : ";
cin>>row;
cout<<"Banyaknya kolom : ";
cin>>clm;
garis();

int array[row][clm],tukar[row][clm]; 
cout<<"Masukkan Nilai"<<endl;
garis();
for (x=1; x<=row; x++){
	for(y=1; y<=clm; y++){
		cout<<" baris ke-"<<x<<" kolom ke-"<<y<<": \n";
		cin>>array[x][y];
		garis();
	}
}

cout<<" Sebelum ditukar kolom dan barisnya : \n";
garis();
for(x=1;x<=row;x++){
	for(y=1;y<=clm;y++){
		cout<<"  "<<array[x][y];
	}
	cout<<endl;
}
garis();

cout<<"Array sesudah ditukar kolom dan barisnya : \n";
garis();
for(x=1;x<=clm;x++){
	for(y=1;y<=row;y++){
		cout<<"  "<<array[y][x];
	}
	cout<<endl;
}
garis();


}

# Output
<img width="674" alt="yang soal no 1" src="https://user-images.githubusercontent.com/121307307/209391218-8207fe38-924b-4618-96a9-34ca1925e006.png">

