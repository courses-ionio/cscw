# ΙΟΝΙΟ ΠΑΝΕΠΙΣΤΗΜΙΟ, ΤΜΗΜΑ ΠΛΗΡΟΦΟΡΙΚΗΣ 

## ΜΑΘΗΜΑ
### Κινητά και Κοινωνικά Μέσα  
Επιβλέπων καθηγητής: Χωριανόπουλος Κωνσταντίνος  

## Επιλογή Εργασίας   
### Corfu Map (https://github.com/ioniodi/corfu-map)
## Στοιχεία φοιτητή  
### Γεώργιος Μαντέλλος  
### ΑΜ: Π2016149  
### Application: https://geocfu.github.io/corfu-map/  
### APK: TODO
### Repository: https://github.com/geocfu/corfu-map  

## Σύνοψη  
&nbsp;&nbsp;&nbsp;&nbsp;Το θέμα της εργασίας είναι η συνεργατική χαρτογράφηση δρόμων για πεζούς στην πόλη της Κέρκυρας. Από την εργασία αναμένεται να μάθουμε να χρησιμοποιούμε πολύ καλά την γλώσσα προγραμματισμού javascript και το API της Google για χάρτες. Με μια πρώτη ματία, η εργασία αναμένεται να είναι πολύ απαιτητική.

## Εισαγωγή  
κειμενο

## Παραδοτέα
### Παραδοτέο 1  
- [x] Όταν ανοίγει η εφαρμογή να είναι κεντραρισμένη και εστιασμένη (zoom) στην πόλη της Κέρκυρας.  
- [x]  Προστέθηκε κουμπί εναλλαγής της εμφάνισης ή μη του παραγόμενου GeoJSON string.  
- [x]  Προστέθηκε λειτουργία διαγραφής του σχήματος το οποίο θα επιλέγει ο χρήστης(δεξί κλικ στο μονοπάτι), καθώς και λειτουργία διαγραφής όσων έχουν σχεδιαστεί πάνω στο χάρτη.   
- [x]  Χρησιμοποιώντας τη γραμμή από το εργαλείο σχεδίασης της εφαρμογής (πάνω αριστερά) χαρτογραφήθηκαν οι δρόμοι όπως φαίνονται από την εικόνα δορυφόρου. Εγινε εξαγωγή του geojson αρχείου, ονομάστηκε ως εξής: 2016149.geojson και ανέβηκε στο κεντρικό αποθετήριο στον φάκελο data. Τέλος, τροποποιείθηκε ο κώδικας της εφαρμογής ώστε να "διαβάζεται" το αρχείο όταν ανοίγει η εφαρμογή και να εμφανίζονται τα μονοπάτια πάνω στο χάρτη (προστέθηκε ένα αντίγραφο του geojson αρχείου στον φάκελο data του αποθετηρίου).  
- [x]  Δημιουργήθηκε ένα σύστημα αξιολόγησης (rating system) της καταλληλότητας των δρόμων για πεζούς με 5 διαβαθμίσεις (η default επιλογή είναι "unknown"). Ανάλογα με την αξιολόγηση του χρήστη(αριστερό κλικ στο μονοπάτι), ο κάθε δρόμος να λαμβάνει αντίστοιχο χρώμα. Το καινούριο χαρακτηριστικό αξιολόγησης (property) καταγράφεται στο GeoJSON αρχείο.  
- [x]  Αξιολογήθηκαν τα μονοπάτια που γνωρίζα/θυμάμαι κατά πόσο είναι κατάλληλα/ευχάριστα για πεζούς και ανέβηκαν τα καινούρια αρχεία στο κεντρικό αποθετήριο στον φάκελο data με όνομα 2016149_review.geojson.  

### Παραδοτέο 2  
- [x] Προστέθηκε μία Βάση Δεδομένων Firebase στην οποία καταγράφονται τα σχεδιασμένα μονοπάτια και οι αξιολογήσεις.
- [x] Μετατράπηκε η εφαρμογή διαδικτύου (web app) σε εφαρμογή android. Ανέβάστε ο κώδικας της εφαρμογής σε ξεχωριστό repository και προστέθηκε υπερσύνδεσμος (σε υπηρεσία διαμοιρασμού αρχείων) για το εκτελέσιμο apk στην αναφορά.
- [x] Προστέθηκε στη νέα εφαρμογή λειτουργία εμφάνισης του μήκους του σχεδιασμένου δρόμου που επιλέγει ο χρήστης.
- [x] Τροποποιήθηκε η νέα εφαρμογή ώστε ο χρήστης να μην μπορεί να σχεδιάσει δρόμους οι οποίοι βρίσκονται πάνω από 100 μέτρα μακριά από την τρέχουσα τοποθεσία του.
- [x] Προστέθηκε η δυνατότητα αναγνώρισης (login) και καταγραφής των ενεργειών των χρηστών και εμφάνισης πίνακα κατάταξης (leaderboard) στον οποίο οι χρήστες θα κατατάσσονται ανάλογα με το συνολικό μήκος των μονοπατιών που έχουν καταγράψει.  

## Υλικό που χρησιμοποιήθηκε
&nbsp;&nbsp;&nbsp;&nbsp;Το site απο το οποίο άντλησα όλες τις πληροφορίες για το κομμάτι της χαρτογράφησης είναι το επίσημο site της Google για το documentation του API. Επιπλέον, το σιτε Stack Overflow βοήθησε αρκετά σε θέματα ανάπτυξης κώδικα.
- API Guides (https://developers.google.com/maps/documentation/javascript/tutorial)  
- API Reference (https://developers.google.com/maps/documentation/javascript/reference/3/)  
- API Samples (https://developers.google.com/maps/documentation/javascript/examples/)
- Stack Overflow (https://stackoverflow.com/questions/tagged/google-maps)  

&nbsp;&nbsp;&nbsp;&nbsp;Το site απο το οποίο άντλησα όλες τις πληροφορίες για το κομμάτι της βάσης δεδομένων firebase είναι το επίσημο site της Google για τη Firebase. Επίσης, το site Tutorialspoint με βοήθησε αρκετά στο κομμάτι πρόσβασης στη βαση δεδομένων.
- Firebase Guides (https://firebase.google.com/docs/web/setup)  
- Firebase Reference (https://firebase.google.com/docs/reference/js/)  
- Tutorialspoint (https://www.tutorialspoint.com/firebase/firebase_read_data.htm)  

### Web App
Login screen screenshot
![screenshot](https://github.com/geocfu/cscw/blob/2016149/projects/2016149/corfu_map_login_screenshot.png)  

Map screenshot  
![screenshot](https://github.com/geocfu/cscw/blob/2016149/projects/2016149/corfu_map_map.png)  

Complete Map screenshot  
![screenshot](https://github.com/geocfu/cscw/blob/2016149/projects/2016149/corfu_map_map_menu_geojsonoutput.png)  

### Android App
Login screen screenshot
![screenshot](https://github.com/geocfu/cscw/blob/2016149/projects/2016149/Screenshot_2018-05-07-22-10-40.png)  

Menu screenshot  
![screenshot](https://github.com/geocfu/cscw/blob/2016149/projects/2016149/Screenshot_2018-05-07-22-11-35.png)  

Map screenshot  
![screenshot](https://github.com/geocfu/cscw/blob/2016149/projects/2016149/Screenshot_2018-05-07-22-11-47.png)  

## Συμπεράσματα  
&nbsp;&nbsp;&nbsp;&nbsp;Σαν εργασία, μπορώ να πω με σιγουριά, πως είναι η πιο δύσκολη που έχω αντιμετωπίσει ως τώρα, εντός ακαδημαϊκού περιβάλλοντος. Αποτελεί ένα εξαιρετικό έναυσμα προκειμένου να ασχοληθεί κανείς με Javascript, Google Maps Web API, την βάση δεδομένων firebase και την δημιουργία android εφαρμογών.

## Σελίδα Τελικής Αναφοράς  
TODO

## Bonus Βαθμός  
### Peers on Map, Email: geocfupom@gmail.com
