#Reddit User Generator
## Setup:
1. Chrom installieren wenn noch nicht vorhanden
2. Requirements installieren : 
	```
	pip install selenium
	pip install webdriver-manager
	```
3. In namesforreddit "password" zu dem Passwort ändern welches die neuen Accounts haben sollen.
4. In namesforreddit "email" zu der Email für die verifizierung ändern. Das Script ist nur mit Gmail getestet, kann also sein das es mit anderen Mailprogrammen nicht funktioniert. 

## How it works:
1. Sctips starten:
```
python namesforreddit.py
```
2. Das Scipt öffnet Chrom und endet auf der Registrierungsseite  von Reddit.
3. Captcha lösen und auf Registrieren klicken
4. Script mit strg+c stoppen und neustarten für den nächsten Account. Der erstellte Account ist in namesforreddit.txt zu finden und muss nur noch verifiziert werden.
