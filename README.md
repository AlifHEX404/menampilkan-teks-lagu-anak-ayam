# menampilkan-teks-lagu-anak-ayam


            #include <iostream>
            using namespace std;

            int main ()
            {
                int x,jumlah_anak;
                cout << " \t|================================================|" << endl ;
            cout << " \t|========= PROGRAM TEKS LAGU ANAK AYAM ==========|" << endl ;
            cout << " \t|=============== ALIF MUSTAFANAH ================|" << endl ;
            cout << " \t|================================================|\n" << endl ;

                cout<< " Masukan Jumlah Anak Ayam :";
                cin>> jumlah_anak;
                cout<< " Mari bernyanyi "<<jumlah_anak<<endl ;
                cout<< " ANAK AYAM "<<endl;
                cout<< " MULAI !!! "<<endl;
                for (x=jumlah_anak;x>0;x--)
                {
                    if (x>1)
                        cout<< " Anak Ayam Turun : "<<x<< " Mati Satu Tinggal :"<<x-1<<endl;
                    else if (x=1)
                        cout<< " Anak Ayam turun < 1 Mati Satu Tingal Induknya"<<endl;
                }
                char LG;
            cout<<"\n \n\n Apakah anda ingin mengulang program ini kembali [ Y/T ] ?";cin>>LG;
            if (LG=='Y' || LG=='y')main();
            else if (LG=='T' || LG=='t') goto x;
            x:
                cout << " \n\t" << endl ;
            cout << " \n\t|===============================================|" << endl ;
            cout << " \t|== TERIMAKASIH SUDAH MENGGUNAKAN PROGRAM INI ==|" << endl ;
            cout << " \t|============== ALIF MUSTAFANAH ================|" << endl ;
            cout << " \t|===============================================|\n" << endl;

            }
