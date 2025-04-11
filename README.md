#include <iostream>
#include <string>
using namespace std;

int main() {
    string nama, alamat, nim;
    int umur;

    // Input data dari user
    cout << "Masukkan Nama   : ";
    getline(cin, nama);

    cout << "Masukkan Umur   : ";
    cin >> umur;
    cin.ignore(); // untuk membersihkan buffer setelah input angka

    cout << "Masukkan Alamat : ";
    getline(cin, alamat);

    cout << "Masukkan NIM    : ";
    getline(cin, nim);

    // Output data
    cout << "\n=== Data Diri ===" << endl;
    cout << "Nama   : " << nama << endl;
    cout << "Umur   : " << umur << " tahun" << endl;
    cout << "Alamat : " << alamat << endl;
    cout << "NIM    : " << nim << endl;

    return 0;
}

