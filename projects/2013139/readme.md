# ΙΟΝΙΟ ΠΑΝΕΠΙΣΤΗΜΙΟ


# ΤΜΗΜΑ ΠΛΗΡΟΦΟΡΙΚΗΣ


# ΜΑΘΗΜΑ 


### Κινητά και κοινωνικά μέσα
## Επιβλέπων καθηγητής: Χωριανόπουλος Κωσταντίνος
# Επιλογή Εργασίας 
**Corfu Map**
**Καπλάνης Ορέστης ΑΜ:2013139**
## Παραδοτέο 1ο
**Ζητούμενα:**
### 1o:   Είναι οι αλλαγές που έγιναν στο map init() ὀπου center είναι το κέντρο του χάρτη και zoom το επιθυμητό zoom.

          center: {lat: 39.6249838, lng: 19.922346100000027},zoom: 17
          
### 2o:   **Προσθήκη κουμπιού GeoJson Output στο sidebar μαζί με τις υπόλοιπες λειτουργίες.**
### 3ο:   **Δημιουργία info window με 5 επιλογές (Very bad,Bad,Normal,Good,Very Good) αξιολόγησης του μονοπατιού που έχει κλικάρει ο χρήστης αλλά και επιλογή για διαγραφή του μονοπατιού καθώς και επίσης προσθήκη κουμπιού στο sidebar για διαγραφή όλων των μονοπατιών**
### 4ο:   **Σχεδιασμός , Upload στον φάκελο data και load των geojson αρχείων**
### 5ο:   **Σὐστημα αξιολόγησης και καταγραφή των Properties στο geojson αρχείο**
### 6o:   **Αξιολόγηση των μονοπατιών και upload του geojson**![OPTIONS](https://github.com/userman95/cscw/blob/2013139/projects/2013139/first.png)

## Παραδοτέο 2ο
**Ζητούμενα**
### 1o:   **Προσθήκη Real-time database με το firebase και αποστολή του current geojson.**
### 2o:   **Μετατροπή της web app σε android app μέσα εργαλείου WebView από το android studio.Προυποθέτει να είναι ανοιχτό το GPS για το current location του χρήστη αν λειτουργεί σε android/i-phone.**
### 3o:   **Υπολογισμός μονοπατιού και φανέρωση στο infowindow όταν ο χρήστης κλικάρει σε οποιοδίποτε μονοπάτι**![INFOWINDOW](https://github.com/userman95/cscw/blob/2013139/projects/2013139/third.png)
### 4ο:   **Όταν ο χρήστης σχεδιάσει κάποια γραμμή έστω λίγο έξω από τον κύκλο των 100 μ.(100μ ακτίνα του κύκλου) η γραμμή αυτή διαγράφεται στο επόμενο κλικ που θα κάνει ο χρήστης σε οποιαδίποτε  γραμμή**![DELETION](https://github.com/userman95/cscw/blob/2013139/projects/2013139/fourth.png)
### 5ο:   **Προσθήκη σελίδας login ![LOGIN](https://github.com/userman95/cscw/blob/2013139/projects/2013139/second.png) και αποστολή δεδομένων στην βάση δεδομένων όπου όταν ψλικάρεται το κουμπί sumbit υπολογίζονται όλες οι αποστάσεις.Από την βάση τα στοιχεία γίνονται sort με την μέθοδο OredrByChild της Firebase στο επόμενο refresh της σελίδας και κατατάσσονται σε έναν πίνακα ονόματι leaderboard που ο χρήστης μπορεί να δει από το sidebar.**![LEADERBOARD](https://github.com/userman95/cscw/blob/2013139/projects/2013139/fifth.png)

**Link [αποθετηρίου](https://github.com/userman95/corfu-map/tree/%CE%A02013139)**

**Link [εκτελέσιμου](https://userman95.github.io./)**

**Για να ανοίξετε την εφαρμογή στο android σας απλα ανοίξτε το link της web εφαρμογής ,το GPS και επιτρέψτε στον browser να πάρει την τοποθεσία σας.Διαφορετικά ακολουθήστε αυτο το [link](https://gonative.io/share/qpeany) που ειναι αντιπροσωπευτικό [αυτού](https://github.com/userman95/corfu-map/tree/android-branch) του κώδικα**
