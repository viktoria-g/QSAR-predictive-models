Ovaj repozitorij sadrži skup Jupyter Notebook skripti koje zajedno čine cjeloviti workflow za obradu, standardizaciju i modeliranje podataka u svrhu razvoja QSAR (Quantitative Structure-Activity Relationship) prediktivnih modela.
Struktura repozitorija:
Priprema podataka
  1a. spajanje csv i sdf podataka.ipynb – spajanje CSV tablica s deskriptorima i SDF datoteka sa strukturnim podacima.
  1b. spajanje csv i sdf viability.ipynb – specifično spajanje podataka vezanih uz mjerenje viabilnosti.
  1c. ratio+viab.ipynb – kreiranje i analiza omjera te viabilnosti za ciljane spojeve.
Identifikacija i filtriranje autofluorescentnih molekula
  2. definiranje autofluorescentnih molekula.ipynb – definicija i obilježavanje autofluorescentnih spojeva.
  3. uklanjanje autofluorescentnih.ipynb – filtriranje i uklanjanje autofluorescentnih molekula iz dataset-a.
Standardizacija i izračun značajki
  4. svi targeti_standardizacija.ipynb – standardizacija podataka kroz sve targete.
  5. SVI TARGETI izracun desc i fp.ipynb – računanje molekularnih deskriptora i fingerprintova za sve targete.
Korekcije i završna priprema
  6. Konačne tablice.ipynb – stvaranje završnih tablica.
  6.b_zavrsna_korekcija.ipynb – provedba završnih korekcija podataka.
  6.c korekcija deskriptora.ipynb – korekcije i optimizacije vezane uz odabrane deskriptore.
Modeliranje i dodatne varijable
  7. Ubacivanje dummy varijable.ipynb – dodavanje dummy varijabli za dodatnu kontrolu i testiranje modela.

Preduvjeti:
Python 3.9+
Potrebne biblioteke: pandas, numpy, rdkit, scikit-learn, matplotlib, seaborn, mordred, imblearn

Instalacija:
pip install -r requirements.txt
