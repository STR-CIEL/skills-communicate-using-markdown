# <h1> this is an header 
## <h2>this is an header
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

~~~ c++
		int count = 0; // Pour compter le nombre de combinaisons

		// Boucles imbriqu�es pour explorer toutes les combinaisons
		for (int n2cent = 0; n2cent <= 50; n2cent++) {  // Maximum 50 pi�ces de 2c
			for (int n5c = 0; n5c <= 20; n5c++) {  // Maximum 20 pi�ces de 5c
				for (int n10c = 0; n10c <= 10; n10c++) {  // Maximum 10 pi�ces de 10c
					if ((n2cent * 2) + (n5c * 5) + (n10c * 10) == 100) {
						cout << "1 euro = " << n2cent << " x 2c  "
							<< n5c << " x 5c  "
							<< n10c << " x 10c" << endl;
						count++;
					}
				}
			}
		}


~~~


