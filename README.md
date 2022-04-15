# Gaurav
Physics Project

#include<iostream>
#include<cmath>
#include<stdlib.h>
#include<vector>
#include<unordered_map>
using namespace std;

int main() {
	int n;
	cout << "\t\t\t\t\t\t\t----------------------------------" << endl;
	cout << "\t\t\t\t\t\t\t  Types of LASER EYE Surgery" << endl;
	cout << "\t\t\t\t\t\t\t-------------------------------------" << endl << endl;
	cout << "\t\t\t Select the problem(s) you are currently facing in your eye:" << endl << endl;
	cout << "\t\t\t\t\t\t\t  1.  Low-Myopia/Astigmatism/Low-Presbyopia" << endl;
	cout << "\t\t\t\t\t\t\t  2.  High-Presbyopia"  << endl;
	cout << "\t\t\t\t\t\t\t  3.  High-Myopia" << endl;
	cout << "\t\t\t\t\t\t\t  4.  recurrent epithelial erosion syndrome,basement membrane disorder,corneal scarring" << endl;
	cout << "\t\t\t\t\t\t\t  5.  Secondary cataract" << endl;
	cout << "\t\t\t\t\t\t\t  6.  Glaucoma" << endl;
	cout << "\t\t\t\t\t\t\t  7.  Diabetic Retinopathy" << endl;
	cout << "\t\t\t\t\t\t Select an Option from above  : ";    
	cin >> n;
	
	
	
	
	
	switch (n) {
    case 1:
        cout<<"Photo Refractive Keratectomy(PRK)/Advanced Surface Ablation(ASA)/Laser Assisted Sub-Epithelial Keratomileusis(LASEK)";
        break;
    case 2:
        cout<<"Laser Blended Vision(LBV)";
        break;
    case 3:
        cout<<"Small Incision Lenticule Extraction(SMILE)";
        break;
    case 4:
        cout<<"Photo Therapeutic Keratectomy(PTK)";
        break;
    case 5:
        cout<<"neodymium-Yttrium Aluminium Garnet(LAG)";
        break;
    case 6:
        cout<<"Selective Laser Trabeculoplasty(SLT)";
        break;
    case 7:
        cout<<"Pan Retinal Photocoagulation(PRP)";
        break;
    
        
        
    default:
        cout<<"Invalid Option";
        break;
    }
}
