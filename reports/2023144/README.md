# Συνεργατικά Συστήματα

### ΟΝΟΜΑΤΕΠΩΝΥΜΟ: ΝΙΚΟΛΑΣ ΝΑΤΣΟΣ
### ΑΡΙΘΜΟΣ ΜΗΤΡΩΟΥ: inf2023144
### GITHUB PROFILE: [YGNT7777](https://github.com/YGNT7777)
### ORGANIZATION: [cx-dsa](https://github.com/cx-dsa) 

| Εβδομάδα* | [Όλα τα παραδοτέα βρίσκονται στην ίδια σελίδα της τελικής αναφοράς](https://epidrome.github.io/teaching/deliverables/) με τα προσωπικά στοιχεία σας (Όνομα, ΑΜ, github profile) και μαζί με αυτόν εδώ τον πίνακα περιεχομένων | Σύνδεσμος στην [εβδομαδιαία παρουσίαση προόδου στις συζητήσεις](https://github.com/courses-ionio/cscw/discussions/categories/show-and-tell) | Αυτοαξιολόγηση σύμφωνα με τα κριτήρια της αντίστοιχης άσκησης |
| --- | --- | --- | --- |
| 1 | [Δημιουργία ομάδας](https://epidrome.github.io/teaching/help/team/) + [Φορκ και δημιουργία σελίδας τελικής αναφοράς](https://epidrome.github.io/help/teaching/), [προσθήκη πίνακα περιεχομένων](https://raw.githubusercontent.com/courses-ionio/cscw/master/README.md), [συγγραφή της εισαγωγής](https://epidrome.github.io/help/teaching/), αποστολή της εισαγωγής [για σχολιασμό στην συζήτηση](https://github.com/courses-ionio/cscw/discussions/categories/show-and-tell) και καταγραφή του συνδέσμου συζήτησης δίπλα --> | [Συζήτηση 1](https://github.com/courses-ionio/cscw/discussions/213) | Ολοκληρώθηκε|
| 2 | Αίτημα ενσωμάτωσης Α (απλή προσθήκη-αλλαγή δεδομένων) | | |
| 3 | Γραμμή εντολών | [Συζήτηση 3](https://github.com/courses-ionio/cscw/discussions/214) | Ολοκληρώθηκε |
| 4 | Συμμετοχικό περιεχόμενο 1A |[Συζήτηση 4](https://github.com/courses-ionio/cscw/discussions/216) | Ολοκληρώθηκε |
| 5 | Κατασκευή του βιβλίου Α2 | | |
| 6 | Αίτημα ενσωμάτωσης Β (αποσφαλμάτωση-επεξεργασία-προσθήκη liquid) | | |
| 7 | Γραμμή εντολών | [Συζήτηση 7](https://github.com/courses-ionio/cscw/discussions/215) | Ολοκληρώθηκε|
| 8 | Συμμετοχικό περιεχόμενο 1B | | |
| 9 | Κατασκευή του βιβλίου B1 | | |
| 10 | Τελική αναφορά* | | |


# ΠΑΡΑΔΟΤΕΟ 1
Σε αυτό το μάθημα θέλω να καλλιεργήσω τις δεξιότητες μου. Συκγεκριμένα να μάθω πως να συνεργάζομαι πιο αποτελεσματικά σε ομάδες, να μπορώ να αναβαθμήσω τις γνώσεις και τις δεξιότητες που απέκτησα απο το μάθημα HCI και να μάθω πως προέκυψε ο υπολογιστής και όχι μόνο την απλή του χρήση ως εργαλείο αλλά και το πως έγινε μέσο εποικοινωνίας. Επίσης σημαντικό να αναφέρω, θα ήθελα να βελτιώσω μερικά ζητήματα που παρουσιάζει η ιστοσελίδα της σχολής με τα οποία θα ασχοληθούμε σε αυτό το μάθημα.

# ΠΑΡΑΔΟΤΕΟ 3
Για το 3ο παραδοτέο έκανα την άσκηση απο το dokey: back-up your home online

Γενικά χρειαζόταν να εγκαταστήσω το rclone, το οποίο το σύνδεσα με το ακαδημαϊκο email. Για να γίνεται αυτόματα, χρειαζόταν να εκγαταστήσω το εργαλείο [cron](https://wiki.archlinux.org/title/Cron), το οποίο, ρυθμίζοντας το config file τρέχει την εντολή που κάνει back-up τα αρχεία που έχω επιλέξει

Έχω βάλει να κάνει back-up τά αρχεία για το blog μου

Η παρακάτω εντολή αντιγράφει τον φάκελο bashyll στο cloud μου backup/bashyll

```bash
rclone copy ~/bashyll Terminal_onedrive:backup/bashyll --progress
```
Στο παρακάτω demo είναι στο config file του crontab που τρέχει την εντολή κάθε κυριακή στις 2 το πρωί

### Demo link : https://asciinema.org/a/8LmDidO8spD9sVWSZG1K7JIyq
<a href="https://asciinema.org/a/8LmDidO8spD9sVWSZG1K7JIyq" target="_blank"><img src="https://asciinema.org/a/8LmDidO8spD9sVWSZG1K7JIyq.svg" /></a>

Στην παρακάτω φωτογραφία είναι που αποθηκέυονται τα αρχεία όταν τρέχει η εντολή

![par3](https://github.com/user-attachments/assets/3f820f08-b61d-4b76-95b3-d6764f08afba)

# ΠΑΡΑΔΟΤΕΟ 4
Για το τέταρτο παραδοτέο ως διαχειριστής (founder) έκανα  deploy το σίτε του οργανισμού και πρόσθεσα δυο διαδραστικά παραδείγματα με βάση την εκφώνηση:

## Organization site link: https://cx-dsa.netlify.app/

## 1st Link : [Interactive 60% keyboard](https://cx-dsa.netlify.app/remix/interactive-keyboard/)
![keyboard](https://github.com/user-attachments/assets/4e37ad1f-1018-455d-adad-665aa3994c36)

## 2nd LInk: [Payment app](https://cx-dsa.netlify.app/remix/payment-app/)
![payment](https://github.com/user-attachments/assets/36c081e4-f6d6-4c65-9777-975cda5a6c77)

### Source:
 - https://codepen.io/sckarolos/pen/NWqGjZZ
 - https://codepen.io/32bitkid/pen/LKZzMR

# ΠΑΡΑΔΟΤΕΟ 7
Για το 7ο παροδοτέο έκανα την άσκηση απο το dokey: pair programming

Με το εργαλείο tmate επιτρέπει στον χρήστη να μοιράζεται το τερματικό του με άλλα άτομα

### Demo link : https://asciinema.org/a/m6Z4mEfr9tsp65dtjpHX2T99H
<a href="https://asciinema.org/a/m6Z4mEfr9tsp65dtjpHX2T99H" target="_blank"><img src="https://asciinema.org/a/m6Z4mEfr9tsp65dtjpHX2T99H.svg" /></a>

Στην παρακάτω εικόνα μέσω του συνδέσμου, βλέπουμε το τερματικό από το web browser

![par7](https://github.com/user-attachments/assets/e469035e-c0fc-406a-83ce-f8fe9635d918)
