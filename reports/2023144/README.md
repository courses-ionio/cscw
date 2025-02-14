# Συνεργατικά Συστήματα

### ΟΝΟΜΑΤΕΠΩΝΥΜΟ: ΝΙΚΟΛΑΣ ΝΑΤΣΟΣ
### ΑΡΙΘΜΟΣ ΜΗΤΡΩΟΥ: inf2023144
### GITHUB PROFILE: [YGNT7777](https://github.com/YGNT7777)
### ORGANIZATION: [qwerty13276](https://github.com/qwerty13276)

| Εβδομάδα* | [Όλα τα παραδοτέα βρίσκονται στην ίδια σελίδα της τελικής αναφοράς](https://epidrome.github.io/teaching/deliverables/) με τα προσωπικά στοιχεία σας (Όνομα, ΑΜ, github profile) και μαζί με αυτόν εδώ τον πίνακα περιεχομένων | Σύνδεσμος στην [εβδομαδιαία παρουσίαση προόδου στις συζητήσεις](https://github.com/courses-ionio/cscw/discussions/categories/show-and-tell) | Αυτοαξιολόγηση σύμφωνα με τα κριτήρια της αντίστοιχης άσκησης |
| --- | --- | --- | --- |
| 1 | [Δημιουργία ομάδας](https://epidrome.github.io/teaching/help/team/) + [Φορκ και δημιουργία σελίδας τελικής αναφοράς](https://epidrome.github.io/help/teaching/), [προσθήκη πίνακα περιεχομένων](https://raw.githubusercontent.com/courses-ionio/cscw/master/README.md), [συγγραφή της εισαγωγής](https://epidrome.github.io/help/teaching/), αποστολή της εισαγωγής [για σχολιασμό στην συζήτηση](https://github.com/courses-ionio/cscw/discussions/categories/show-and-tell) και καταγραφή του συνδέσμου συζήτησης δίπλα --> | [Συζήτηση 1](https://github.com/courses-ionio/cscw/discussions/213) | Ολοκληρώθηκε|
| 2 | Αίτημα ενσωμάτωσης Α (απλή προσθήκη-αλλαγή δεδομένων) | | |
| 3 | Γραμμή εντολών | | |
| 4 | Συμμετοχικό περιεχόμενο 1A | | |
| 5 | Κατασκευή του βιβλίου Α2 | | |
| 6 | Αίτημα ενσωμάτωσης Β (αποσφαλμάτωση-επεξεργασία-προσθήκη liquid) | | |
| 7 | Γραμμή εντολών | | |
| 8 | Συμμετοχικό περιεχόμενο 1B | | |
| 9 | Κατασκευή του βιβλίου B1 | | |
| 10 | Τελική αναφορά* | | |


# ΠΑΡΑΔΟΤΕΟ 1
Σε αυτό το μάθημα θέλω να καλλιεργήσω τις δεξιότητες μου. Συκγεκριμένα να μάθω πως να συνεργάζομαι πιο αποτελεσματικά σε ομάδες, να μπορώ να αναβαθμήσω τις γνώσεις και τις δεξιότητες που απέκτησα απο το μάθημα HCI και να μάθω πως προέκυψε ο υπολογιστής και όχι μόνο την απλή του χρήση ως εργαλείο αλλά και το πως έγινε μέσο εποικοινωνίας. Επίσης σημαντικό να αναφέρω, θα ήθελα να βελτιώσω μερικά ζητήματα που παρουσιάζει η ιστοσελίδα της σχολής με τα οποία θα ασχοληθούμε σε αυτό το μάθημα.

# ΠΑΡΑΔΟΤΕΟ 3
Για το 3ο παραδοτέο έκανα την άσκηση απο το dokey: back-up your home online

Γενικά χρειαζόταν να εγκαταστήσω το rclone που το σύνδεσα με το ακαδημαϊκο email και για να γίνεται αυτόματα χρειαζόταν να εκγαταστήσω το εργαλείο [cron](https://wiki.archlinux.org/title/Cron) το οποίο ρυθμίζοντας το config file τρέχει την εντολή που κάνει backup τα αρχεία που έχω επιλέξει

Έχω βάλει να κάνει backup τά αρχεία για το blog μου

Η παρακάτω εντολή αντιγράφει τον φάκελο bashyll στο cloud μου backup/bashyll

```bash
rclone copy ~/bashyll Terminal_onedrive:backup/bashyll --progress
```
Στο παρακάτω demo είναι στο config file του crontab που τρέχει την εντολή κάθε κυριακή στις 2 το πρωί

### Demo : https://asciinema.org/a/8LmDidO8spD9sVWSZG1K7JIyq
<a href="https://asciinema.org/a/8LmDidO8spD9sVWSZG1K7JIyq" target="_blank"><img src="https://asciinema.org/a/8LmDidO8spD9sVWSZG1K7JIyq.svg" /></a>

Στην παρακάτω φωτογραφία είναι που αποθηκέυονται τα αρχεία όταν τρέχει η εντολή

![par3](https://github.com/user-attachments/assets/3f820f08-b61d-4b76-95b3-d6764f08afba)
