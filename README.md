Guliciuc Denis Marian 3133a 
3. Modificați aplicația oferită astfel încât să realizați texturarea pe diverse
obiecte 3D (volumetrice) sau pe suprafețe non-rectangulare. Ce observați?

Observ ca textura trebuie modificata in functie de obiectul grafic folosit,pentru o calitate buna.

6.1 Utilizați pentru texturare imagini cu transparență și fără. Ce observați?
Pentru imagini cu transparență, am folosit formate precum PNG, iar pentru cele fără transparență, JPEG. Procesul implică încărcarea și aplicarea texturilor în codul nostru folosind funcționalitățile OpenTK Graphics API. OpenTK a furnizat o modalitate eficientă de gestionare a texturilor în proiectul nostru.

6.2 Ce formate de imagine pot fi aplicate în procesul de texturare în
OpenGL?

Cele mai comune sunt: Bitmap, Png,  Jpeg, Tiff

6.3 Specificați ce se întâmplă atunci când se modifică culoarea (prin
manipularea canalelor RGB) obiectului texturat.

Când modific culorile unui obiect texturat prin manipularea canalelor RGB în OpenGL, schimb nuanța și intensitatea culorii obiectului. De exemplu, ajustarea canalului roșu (R) va influența nuanța roșie, iar astfel veți obține diferite efecte vizuale, cum ar fi schimbarea culorii de bază, inversarea culorilor sau aplicarea unor filtre specifice.

6.4 
Iluminare Activată:Obiectele texturate răspund la iluminarea ambientală, direcțională și punctuală.Se evidențiază reliefurile și umbrelele, oferind o aparență mai realistă.
Iluminare Dezactivată:Obiectele texturate nu răspund la iluminare.Aspectul este uniform și lipsit de umbre, pierzând detaliile aduse de iluminare.


