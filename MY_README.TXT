ΕΡΓΑΣΙΑ_3:
ΥΛΟΠΟΙΗΣΗ ΚΑΙ ΣΧΕΔΙΑΣΗ ΒΑΣΕΩΝ ΔΕΔΟΜΕΝΩΝ 2023-2024

ΜΕΛΗ ΟΜΑΔΑΣ:
ΚΑΓΙΑΤΣΚΑ ΕΡΙΚ-1115202100043
ΚΑΛΑΜΠΟΚΗΣ ΕΥΑΓΓΕΛΟΣ-1115202100045
ΚΟΝΤΟΣ ΙΑΣΩΝ-1115202100064

ΑΛΛΑΓΕΣ ΠΟΥ ΠΡΑΓΜΑΤΟΠΟΙΗΘΗΚΑΝ:
Οι αλλαγές που έχουμε κάνει στον κώδικα του CHAT GPT καθώς ήταν αδύνατη η σωστή υλοποίηση από αυτό είναι:
Στην συνάρτηση "merge" στο αρχείο "merge.c".
Στην συνάρτηση "CHUNK_GetNextRecord" στο αρχείο "chunk.c".
Λεπτομέρειες φαίνονται στον σύνδεσμο παρακάτω.
Επιπλέον, στην συνάρτηση "main" έχει γίνει προσθήκη κατάλληλου κώδικα ώστε να γίνεται αυτόματη διαγραφή των .db αρχείων σε κάθε εκτέλεση.

ΣΥΝΔΕΣΜΟΣ ΤΟΥ CHAT GPT SESSION:
Στον παρακάτω σύνδεσμο φαίνεται ολόκληρη η επικοινωνία μας με το εργαλείο του CHAT GPT.
https://chat.openai.com/share/927d53f3-a9eb-4e38-a016-2de45e73a26d

ΔΟΚΙΜΑΣΤΙΚΕΣ ΕΚΤΕΛΕΣΕΙΣ ΚΑΙ ΠΡΟΒΛΗΜΑΤΑ
Δεν έχουν παρατηρηθεί προβλήματα σε καμία εκτέλεση.
Συγκεκριμένα οι χρόνοι εκτέλεσης,
Για RECORDS_NUM = 1.000:     real 0m0.063s, user 0m0.043s, sys 0m0.010s
Για RECORDS_NUM = 10.000:    real 0m0.784s, user 0m0.391s, sys 0m0.111s
Για RECORDS_NUM = 100.000:   real 0m5.894s, user 0m3.773s, sys 0m1.493s
Για RECORDS_NUM = 1.000.000: real 1m1.668s, user 0m40.890s, sys 0m15.844s