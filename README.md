Galerie Foto – HTML5 & CSS Grid
Descrierea proiectului

Acest proiect demonstrează crearea unei secțiuni de galerie foto folosind HTML5 și CSS modern. Galeria este adăugată după secțiunea #despre din interiorul elementului <main>.

Structura HTML

Secțiunea #galerie conține:

Un titlu de nivel 2 .
O grilă cu 3 imagini placeholder .
Stilizare CSS

Pentru aranjarea imaginilor este utilizat CSS Grid, cu următoarele caracteristici:

Layout cu 3 coloane pe ecrane mari.
Spațiere de 1rem între imagini.
Fără utilizarea proprietății float.
Design responsive pentru dispozitive mobile.
Responsive Design

Pentru ecrane cu lățimea mai mică de 600px, galeria se transformă într-o singură coloană folosind un media query:

css
@media (max-width: 600px) {
    #galerie .grid {
        grid-template-columns: 1fr;
    }
}

Tehnologii utilizate
HTML5
CSS3
CSS Grid
Media Queries
Instalare și utilizare
Clonează sau descarcă proiectul.
Deschide fișierul index.html într-un editor de cod.
Deschide fișierul în browser pentru a vizualiza galeria.
Obiectiv

Crearea unei galerii foto simple, moderne și responsive, utilizând tehnici actuale de dezvoltare front-end.

Autor: Proiect demonstrativ
Branch: feature/assistive-intelligence
