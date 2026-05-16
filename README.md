# PAT2.subtask3
#include <iostream>
using  namespace std;

const int NUM_EXPERIMENTS = 3;
 int NUM_READINGS = 3;

int main(){
	int i, j;
	double readingValue = 0, total = 0, average = 0;
	
	for (i =1; i<= NUM_EXPERIMENTS; i++){
		total =0;
		cout << "\nEXPERIMENT " << i <<endl;
		cout << "------------\n";
		
		for (j = 1; j <= NUM_READINGS; j++){
			cout << "Enter reading "<< j<< " value: ";
			cin >> readingValue;
			total = readingValue + total;
		} 

