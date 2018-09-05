# Δημήτριος Λέμπερος Π2013080

## Συνεργατική χαρτογράφηση

Σκοπός της εργασίας είναι η συνεργατική χαρτογράφηση των δρόμων της πόλης της Κέρκυρας και η δημιουργία επεκτάσεων/βελτιώσεων της εφαρμογής που θα χρησιμοποιηθεί. Η εφαρμογή βασίζεται στο Google Maps Javascript API και το πρότυπο διαμόρφωσης δεδομένων GeoJSON. ( GeoJSON is an open standard format designed for representing simple geographical features, along with their non-spatial attributes. It is based on JSON, the JavaScript Object Notation ). Οι χάρτες της πόλης της Κέρκυρας σχεδιάστηκαν με στόχο να αναδείξουν κυρίως το κομμάτι της παλιάς πόλης. Μιας μεσαιωνικής πόλης που ουσιαστικά διαμόρφωσε τη ρυμοτομία της κατά την Ενετοκρατία, έτσι οι δρόμοι είναι στενοί και με περίεργα σχήματα, στην πραγματικότητα ήταν και παραμένουν πεζόδρομοι που περνούσαν ανάμεσα από τα σπίτια αφού δεν χωράνε αυτοκίνητα.

## Παραδοτέο 1

## Βήματα Σχεδίασης
-   Αρχικά όρισα τον χάρτη της εφαρμογής να είναι κεντραρισμένος και εστιασμένος στην πόλη της Κέρκυρας. Αυτο το κατάφερα βάζοντας συντεταγμένες center: {lat: 39.623675, lng: 19.923615}, και zoom: 16.
![alt text](https://github.com/dimitrile/corfu-map/blob/master/data/Screenshot_1.png)

-   Πρόσθεσα κουμπί εναλλαγής της εμφάνισης ή μη του παραγόμενου GeoJSON string. 

-   Πρόσθεσα λειτουργία διαγραφής του σχήματος το οποίο θα επιλέγει ο χρήστης, καθώς και λειτουργία διαγραφής όσων έχουν σχεδιαστεί πάνω στο χάρτη.

-   Χαρτογράφησα δρόμους με την βοήθεια της γραμμής εργαλείων. Έβγαλα το geojson αρχείο και το ανέβασα στο κεντρικό αποθετήριο στον φάκελο data. Χαρτογράφησα περίπου 50 μονοπάτια.
![alt text](https://github.com/dimitrile/corfu-map/blob/master/data/Screenshot_3.png)

-   Δημιούργησα ένα σύστημα αξιολόγησης (rating system) της καταλληλότητας των δρόμων για πεζούς με 5 διαβαθμίσεις (η default επιλογή να είναι "unknown").

    ![alt text](https://github.com/dimitrile/corfu-map/blob/master/data/Screenshot_2.png)
    ![alt text](https://github.com/dimitrile/corfu-map/blob/master/data/Screenshot_5.png)
    
-   Ανάλογα με την αξιολόγηση του χρήστη, ο κάθε δρόμος να λαμβάνει αντίστοιχο χρώμα. Το καινούριο χαρακτηριστικό αξιολόγησης (property) να καταγράφεται στο GeoJSON αρχείο.
![alt text](https://github.com/dimitrile/corfu-map/blob/master/data/Screenshot_4.png)

-   Η τελική παρουσίαση του χάρτη της πόλης της Κέρκυρας με τα βαθμολογημένα μονοπάτια είναι η ακόλουθη.
![alt text](https://github.com/dimitrile/corfu-map/blob/master/data/Screenshot_6.png)

## Σύνδεσμοι για την υλοποίηση της Εφαρμογής
- [HTML, CSS, Javascript Tutorials](https://www.w3schools.com/)
- [Google Maps Javascript API](https://developers.google.com/maps/documentation/javascript/)

