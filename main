#include <iostream>
using namespace std;

int main(){
	double ilkfiyat,sonfiyat,kar,karyuzdesi;
	int hissesayisi;
	cout << "Aldığınız hisse sayısı: ";
	cin >> hissesayisi;
	cout << "Alırken fiyatı: ";
	cin >> ilkfiyat;
	cout << "Satılan fiyat: ";
	cin >> sonfiyat;
	if(ilkfiyat>sonfiyat){
        cout
        << "\n\nBaşlangıç paranız: " << (hissesayisi*ilkfiyat) << " TL"
        << "\nToplam zararınız: -" << (hissesayisi*ilkfiyat-hissesayisi*sonfiyat)
        << " TL\nZarar yüzdeniz: -" << ((hissesayisi*ilkfiyat-hissesayisi*sonfiyat)/(hissesayisi*ilkfiyat/100)) << "%"
        << "\nSon durumdaki paranız: " << (hissesayisi*sonfiyat) << " TL\n\n";
	}
	else if(sonfiyat>ilkfiyat){
        cout
        << "\n\nBaşlangıç paranız: " << (hissesayisi*ilkfiyat) << " TL"
        << "\nToplam kârınız: +" << (hissesayisi*sonfiyat-hissesayisi*ilkfiyat)
        << " TL\nKâr yüzdeniz: +" << ((hissesayisi*sonfiyat-hissesayisi*ilkfiyat)/(hissesayisi*ilkfiyat/100)) << "%"
        << "\nSon durumdaki paranız: " << (hissesayisi*sonfiyat) << " TL\n\n";
	}
	else{
	cout << "Kârınız yoktur.";
	}
}
