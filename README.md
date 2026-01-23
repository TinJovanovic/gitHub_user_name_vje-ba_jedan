# gitHub_user_name_vje-ba_jedan
Osonove gita
PITANJA
1. Što je Visual Studio Code i za što se najčešće koristi?
2. Kako se zove panel u kojem vidiš sve datoteke i mape svog projekta? 
3. Kako možeš instalirati ekstenzije u VS Codeu i čemu one služe? 
4. Kako otvoriti postojeći projekt ili mapu u VS Code-u?
5. Što se sve može raditi u Exploreru?
6. Kako možeš brzo pronaći određenu datoteku u projektu?
7. Kako možeš istovremeno gledati dvije različite datoteke u editoru?
8. Kako pokrećeš automatsko formatiranje koda u VS Code-u?
9. Što je version control i zašto se koristi?
10. Kako se u VS Code-u otvara panel za Git (Source Control)? 
11. Što znače commit, push, pull?
12. Čemu služi commit poruka i kako treba izgledati?
13. Kako možeš vidjeti koje si promjene napravio u pojedinoj datoteci?
14. Kreiraš novu datoteku. Koji su koraci da se promjena pošalje na GitHub?
15. Kako se vraćaš na stariju verziju datoteke ako si pogriješio?
16. Na koji način možeš provjeriti status projekta i koje datoteke su izmijenjene?

ODGOVORI
1. Visual Studio Code (VS Code) je lagan, ali moćan uređivač izvornog koda koji se pokreće na stolnim računalima sa sustavima Windows, macOS i Linux. VS Code se primarno koristi za razvoj softvera i uređivanje koda u širokom spektru programskih jezika
2. Panel u kojem vidiš sve datoteke i mape svog projekta u Visual Studio Code-u naziva se Explorer
3. Ekstenzije se instaliraju tako što otvorite panel Ekstenzije klikom na ikonu kvadratića na lijevoj bočnoj traci (Ctrl+Shift+X), pretražite željenu ekstenziju po nazivu (npr. "Python" ili "Prettier") i kliknete na gumb "Install". One su ključne jer omogućuju prilagodbu VS Codea specifičnim potrebama projekta, dodajući podršku za isticanje sintakse, automatsko dovršavanje koda, alate za otklanjanje pogrešaka i teme sučelja.
4. Otvaranje postojećeg projekta u VS Codeu jednostavno je i nudi se kroz tri glavna pristupa: najintuitivniji način je putem izbornika File > Open Folder..., nakon čega odaberete željenu mapu projekta. Drugi način je korištenje početnog zaslona ("Welcome Screen") gdje možete kliknuti na Open Folder... ili brzo učitati nedavni projekt s popisa. Treća, učinkovita metoda za naprednije korisnike uključuje naredbenu liniju (CLI): navigirate do mape u terminalu i upišete code ., čime se projekt odmah otvara
5. To je centralno mjesto za upravljanje strukturom projekta i osnovnim operacijama nad datotekama i mapama: Pregledavanje i navigacija, Upravljanje datotekama i mapama, Pretraživanje unutar projekta, Rad s Git-om (Kontrola verzija), Organizacija radnog prostora, Korištenje "Outline" i "Timeline".
6. Možeš brzo pronaći određenu datoteku u projektu koristeći ugrađenu značajku Go to File (Idi na datoteku) ili Quick Open (Brzo otvaranje). Ovo je najefikasniji način, pogotovo u velikim projektima
7. Da biste istovremeno gledali dvije ili više datoteka, koristite značajku podijeljenog editora ("Split Editor"). Najbrži način je korištenje tipkovničkog prečaca Ctrl + \ (ili Cmd + \ na macOS-u), koji dijeli trenutni prikaz na dva. Alternativno, možete kliknuti na ikonu "Split Editor" koja se nalazi u gornjem desnom kutu panela editora (izgleda kao dva okomita pravokutnika) ili jednostavno povući datoteku iz Explorera i ispustiti je na stranu postojećeg editora dok se ne pojavi plava zona za ispuštanje
8. Automatsko formatiranje koda u VS Code-u možeš pokrenuti ručno ili automatski prilikom spremanja datoteke
9. Version control (kontrola verzija, sustav za upravljanje verzijama ili VCS) je sustav koji prati i upravlja promjenama u datotekama ili skupu datoteka (najčešće izvornom kodu) tijekom vremena
10. Panel za Git (Source Control) u VS Code-u najbrže otvarate prečacem Ctrl + Shift + G ili klikom na ikonu razgranatog stabla u lijevoj bočnoj traci (Activity Bar). Također ga možete aktivirati putem gornjeg izbornika odabirom View > Source Control, a detaljne upute o svim dostupnim alatima za upravljanje verzijama možete pronaći na službenoj dokumentaciji VS Code Source Control.
11. U Git-u, commit služi za trajno spremanje vaših promjena u lokalnu povijest projekta na računalu, stvarajući "snimku" koda uz pripadajuću poruku. Push je radnja kojom te lokalne promjene šaljete na udaljeni poslužitelj (poput GitHuba) kako bi postale dostupne drugima, dok pull radi obrnuto – on dohvaća i spaja najnovije izmjene s poslužitelja u vaš lokalni kod. Za lakše upravljanje ovim procesima unutar sučelja možete koristiti VS Code Source Control vodič koji vizualno objašnjava svaku od tih naredbi.
12. Commit poruka služi kao trajni zapis koji objašnjava zašto je određena promjena napravljena, što olakšava timsku suradnju i buduće održavanje koda. Prema standardima, poruka treba početi kratkim naslovom u imperativu (npr. fix: ispravi grešku pri prijavi), nakon kojeg slijedi prazan redak i detaljniji opis promjene ako je potreban. Kvalitetno strukturiranje prema Conventional Commits standardu pomaže u preglednosti povijesti projekta, a dodatne savjete o pisanju možete pronaći u Git dokumentaciji.
13. U VS Code-u promjene u pojedinoj datoteci možeš vidjeti klikom na nju unutar Source Control panela, što otvara Diff Editor. On ti prikazuje usporedni prikaz: lijevo je stara verzija, a desno tvoje trenutačne izmjene s označenim dodanim i obrisanim linijama. Također, u samom kodu možeš pratiti indikatore u boji na lijevom rubu editora (zeleno za novo, plavo za izmijenjeno). Za još detaljniji pregled povijesti promjena, preporučuje se korištenje GitLens ekstenzije koja omogućuje uvid u svaku izmjenu po linijama koda.
14. Da biste novu datoteku poslali na GitHub u 2026. godini, prvo je trebate dodati u pripremu klikom na ikonu + (Stage) u Source Control panelu, a zatim unijeti opisnu poruku i kliknuti Commit kako biste promjenu spremili lokalno. Nakon toga, pritisnite gumb Sync Changes ili Push da biste podatke sinkronizirali s udaljenim poslužiteljem. Ako prvi put povezujete projekt, koristite opciju Publish to GitHub koja će automatski kreirati repozitorij i odraditi slanje koda.
15. U VS Code-u se na stariju verziju najlakše vraćate pomoću kartice Timeline (nalazi se pri dnu Source Control panela ili ispod Explorer stabla), gdje možete pregledati sve prethodne snimke datoteke i desnim klikom odabrati Restore Contents.
16. Status projekta i popis izmijenjenih datoteka najlakše možete provjeriti otvaranjem Source Control panela (Ctrl + Shift + G), gdje su sve promjene grupirane u kategorije poput Changes (izmijenjene), Untracked (nove) ili Staged (pripremljene). Ako preferirate rad u terminalu, upišite naredbu git status koja će vam izlistati trenutačno stanje grane i sve datoteke koje čekaju na obradu
