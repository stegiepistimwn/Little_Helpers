# Τα εξαρτήματα, τιμές και η χρήση τους

## Εξαρτήματα - Τιμές
A/A   | Περιγραφή               | Ποσότητα  | Τιμή / Τεμ. € | Σύνολο €
------| ------------------------|-----------|---------------|----------
1     | Raspbbery Pi 5, τροφοδοσία 5v, SD card, case με Vesa τοποθέτηση (για σύνδεση πίσω από οθόνη)  |     1     |      1    |  150 €
2     | Microbit V2 | 2 | 22 | 44 €
3 	  | Arcade Machine Bundle - 2 Player - 30mm Button (για δημιουργία πληκτρολογίου για ηλικιωμένους |  1  |  1  | 50 € 
4 	  | Breadboard  |  2  |  7  | 14 € 
5 	  | Πλακέτα σύνδεσης Microbit με Breadboard  |  2  |  12  | 24 € 
6 	  | LED Διαφόρων χρομάτων 5mm  |   |   | 
7 	  | Αντιστάσεις 220Ω |   |   |   
8 	  | Διάφορα καλώδια |  |  |
9 	  | Διάφορα, χρώματα, κόλλες κλπ |  1 |  15 | 15 
10 	  | Οθόνη υπολογιστή (υπάρχει ήδη) καλώδιο hdmi | 1 |   |   
11	  | Ποντίκι, πληκτρολόγιο για τον προγραμματισμό (υπάρχει ήδη) | 1 | |
Σύνολο ||||  270 €

## Περιγραφή εξαρτημάτων

Ηλεκτρονικά εξαρτήματα και εξοπλισμός
## To microbit
Το micro:bit είναι ένας μικρός υπολογιστής που χωράει στην παλάμη μας. Με αυτόν μπορούμε να φτιάξουμε απλά προγράμματα και να τα δοκιμάσουμε στην πράξη, παίζοντας και μαθαίνοντας πώς λειτουργεί η τεχνολογία.
![microbit][def0]
Στο micro:bit μπορούμε να δίνουμε “εντολές” μέσω εισόδων, όπως κουμπιά ή ακροδέκτες (καλώδια που συνδέουμε), και αυτό να κάνει κάτι, όπως να ανάψει φώτα ή να παίξει έναν ήχο, που λέγονται έξοδοι. Έτσι, το micro:bit παίρνει πληροφορίες από το περιβάλλον ή από εμάς και μπορεί να αντιδράσει όπως θέλουμε.

Με λίγα λόγια, το micro:bit είναι το “μυαλό” σε μια κατασκευή: ακούει τι του λέμε (είσοδοι) και κάνει πράγματα που έχουμε προγραμματίσει (έξοδοι), κάνοντάς το ιδανικό για παιχνίδια, πειράματα και δημιουργικές ιδέες!


## Κουμπιά και διακόπτες.
Το δυσκολότερο κομμάτι της κατασκευής για παιδιά δημοτικού είναι να καταλάβουν την έννοια του διακόπτη σε ένα ηλεκτρονικό κύκλωμα και να "διαβάσουν" την αξία που στέλνει στο microbit.

Εδώ χρησιμοποιήσαμε την τεχνική του pull down resistor. Όταν έχουμε ένα κουμπί σε ένα ηλεκτρονικό κύκλωμα, θέλουμε να ξέρουμε πότε το πατάμε και πότε όχι. Όμως, αν δεν κάνουμε κάτι ειδικό, το κύκλωμα μπορεί να μπερδευτεί και να νομίζει πως το κουμπί πατήθηκε, ενώ δεν το έχουμε αγγίξει.

Το pulldown resistor είναι ένα μικρό κομμάτι (αντισταση) που βάζουμε για να βοηθάει. Όταν το κουμπί δεν το πατάει κανείς, αυτό το κομμάτι κρατάει το κύκλωμα ήσυχο και του δείχνει καθαρά ότι το κουμπί δεν πατήθηκε.

![pulldown][def1]

Τα κουμπιά που χρησιμοποιήσαμε προσπαθήσαμε να είναι όσο το δυνατόν πιο μεγάλα και με έντονα χρώματα οπότε και πήραμε ειδικά κουμπιά για ηλεκτρονικά παιχνίδια. 

![buttons][def2]


## Οθόνη υγρών κρυστάλλων LCD 16x2
Χρησιμεύει για να βλέπουμε εμείς τα παιδιά αν μας έστειλαν κάποιο μήνυμα οι παπούδες και οι γιαγιάδες μας. Συνδέεται εύκολα με το makecode και μπορούμε με ειδκές εντολές που έχει έτοιμες να γράψουμε με λατινικούς χαρακτήρες.
![lcd][def3]

## Αντιστάσεις
Οι αντιστάσεις είναι μικρά ηλεκτρονικά κομμάτια που βάζουμε στα κυκλώματα για να ελέγχουμε πόσο ρεύμα περνάει. Είναι σαν μικρά “εμπόδια” που βοηθούν να μην περνάει περισσότερο ρεύμα από όσο χρειάζεται και έτσι προστατεύουν τα υπόλοιπα μέρη του κυκλώματος.
![res][def4]
Χάρη στις αντιστάσεις, το κύκλωμά μας δουλεύει σωστά και με ασφάλεια, χωρίς να καίγονται τα φώτα ή τα άλλα ηλεκτρονικά εξαρτήματα.
Οι αντιστάσεις υπα΄ρχουν σε διάφορα μεγέθη και αντοχές (watt) αλλά εμείς εδώ χρειαστήκαμε μόνο αντιστάσεις για να πραγματοποιήσουμε το κύκλωμα των διακοπτών (Pull down) με αντίσταση 10 ΚOhm (θα σας πει ο δάσκαλός σας!!!)



[Αρχική Σελίδα](../README.md)


[def0]: ../photos/microbit.png
[def1]: ../photos/pullDown.png
[def2]: ../photos/buttons.jpg
[def3]: ../photos/lcd16x2.jpg
[def4]: ../photos/resistor.jpg
