# ΕΦΑΡΜΟΦΗ ΠΟΥ ΘΑ ΒΟΗΘΗΣΕΙ ΣΤΗΝ ΙΧΝΗΛΑΤΙΣΗ ΑΝΑΛΟΓΑ ΜΕ ΤΙΣ ΠΡΟΔΙΑΓΡΑΦΕΣ ΥΓΕΟΝΟΜΙΚΗΣ ΑΡΧΗΣ
Μια πρόταση για τον περιορισμό της νόσου COVID-19. Αποτελεί μια σειρά modules για διαφορετική χρήση. Όλα είναι υπό 

**ΣΚΟΠΟΣ:** Η χρήση της από τα καταστήματα ώστε να οδηγήσει στην παρακολούθηση της χωρητικότητας των πελατών του κάθε καταστήματος ανάλογα με τα τετραγωνικά (και τις οδηγίες από την αρμόδια υγειονομική αρχή, ΕΟΔΥ-Πολιτική προστασία). Επίσης η διαδικασία θα βοηθήσει στην ιχνηλάτηση σε περίπτωση κρούσματος.

**ΣΚΕΠΤΙΚΟ:**
Μέτρηση πελατών κατά την είσοδο και την έξοδό τους.
Διατήρηση ανώνυμων στοιχείων (πχ μόνο κινητό τηλέφωνο) πελάτη για 15 ημέρες (ή όσες ορίσει η αρμόδια αρχή) με σκοπό την ειδοποίηση να προβεί σε εξέταση για τον ιό.

## ΠΕΡΙΓΡΑΦΗ

### MODULE καταστήματος:
Κάθε κατάστημα θα έχει στην είσοδο ένα qr.
* Ο πελάτης θα σκανάρει το qr κατά την είσοδο και θα του εμφανίζει ΠΡΑΣΙΝΟ αν υπάρχει χώρος για να μπει ή ΚΟΚΚΙΝΟ εάν δεν υπάρχει χώρος. Ως εφαρμογή, μπορεί να κάνει την ερώτηση ΠΟΣΑ ΑΤΟΜΑ ΘΑ ΕΙΣΕΛΟΥΝ ώστε αν είναι οικογένεια και δεν έχουν όλοι smartphone, να εισέλθουν κανονικά.
* Αφού πάρει το ΠΡΑΣΙΝΟ, το δείχνει σε υπάλληλο στην είσοδο και περνάει. ΕΑΝ είναι εμπορικό κέντρο, πρέπει να έχει ΠΡΑΣΙΝΟ τόσο στην είσοδο του εμπορικού, όσο και στου καταστήματος εντός, ώστε να μπορέσει να γίνει η ιχνηλάτηση πιο εύκολα. ΜΠΑΙΝΟΝΤΑΣ ΘΑ ΠΡΟΣΤΙΘΕΤΑΙ ΣΥΝ 1 (ή όσα δήλωσε στην εφαρμογή κατά την αρχική ερώτηση) ΣΤΑ ΑΤΟΜΑ ΜΕΣΑ ΣΤΟ ΚΑΤΑΣΤΗΜΑ.
* Με το σκανάρισμα μπαίνοντας στο κατάστημα, να του δίνεται ένα μοναδικό ID (πχ qr).
* Αν αγοράσει κάτι από το κατάστημα, κατά την πληρωμή να γίνεται η μείωση του αριθμού των ατόμων εντός του καταστήματος. 
* Αν δεν αγοράσει κάτι, μπορεί να σκανάρει το qr του βγαίνοντας ώστε να αφαιρούνται τα άτομα από αυτά που είναι στο κατάστημα.
* Σε περίπτωση που κάποιος νοσήσει, θα μπορεί να το δηλώνει στην εφαρμογή με ένα απλό κουμπί και θα ειδοποιούνται (push) ΟΛΟΙ που ήταν ή πέρασαν (ή μετά από συνεννόηση με την υγειονομική αρχή) να κάνουν το τεστ. Βέβαια θα κρατούνται τα ανώνυμα στοιχεία (τηλέφωνο) αυτών που πέρασαν από το κατάστημα για 15 ημέρες.  
**ΓΙΑ ΝΑ ΕΙΝΑΙ ΠΙΟ ΔΕΛΕΑΣΤΙΚΟ, ΜΠΟΡΕΙ ΝΑ ΥΛΟΠΟΙΗΘΕΊ ΣΕ ΣΥΝΔΥΑΣΜΟ ΜΕ ΤΟ LOYALTY CARD**  
**ΛΥΣΗ ΠΡΟΒΛΗΜΑΤΟΣ ΙΧΝΗΛΑΣΙΜΟΤΗΤΑΣ**

### MODULE μαγαζιά εστίασης:
Η λογική είναι ίδια με του γενικού module καταστημάτων. Η διαφορά προστίθεται μετά που θα μπει και θα καθίσει στο τραπέζι (το οποίο το στρώνει ο υπάλληλος μπροστά στον πελάτη). Η πρώτη κίνηση που θα κάνει θα είναι να πιάσει το μενού για να παραγγείλει. Το μενού είναι εστία μικροβίων διότι το πιάνουν όλοι οι πελάτες και επίσης δεν το καθαρίζουν οι υπάλληλοι του μαγαζιού.
* Ο πελάτης σκανάρει το qr για να μπει στο ασύρματο δίκτυο του μαγαζιού.
* Ο πελάτης σκανάρει το qr πανω στο τραπέζι του. Έτσι παίρνει τον αριθμό του τραπεζιού, συν ένα αύξοντα αριθμό (σε περίπτωση που θέλουμε να χωρίσουμε τον λογαριασμό σε ότι έφαγε ο καθένας, κάτι το οποίο το ζητάνε οι ξένοι ή ακόμα και σε περιπτώσεις καφετέρειας που ο καθένας πληρώνει ότι καφέ πήρε). Εδώ μπορεί να υπάρχει και ο αύξοντας αριθμός 0 όπου θα είναι κοινός λογαριασμός, όπου μπορεί να μπει κοινή παραγγελία (πχ ψωμιά, σαλάτες, ούζα κλπ).
* Ανοίγει ένας περιηγητής με το μενού του καταστήματος (εδώ βοηθάει πολύ όταν το κατάστημα θέλει να αλλάξει τις τιμές, το μενού, το ΦΠΑ, δεν χρειάζεται να τυπώσει νέο μενού αλλά τα προσθέτει εύκολα στην σελίδα αυτή). Στην ιστοσελίδα αυτή θα έχει πρόσβαση ΜΟΝΟ μέσα από το κατάστημα. Η λογική είναι ότι θα εμφανίζεται ως “πελάτης”, ο αριθμός του τραπεζιού και ο αύξων αριθμός. Βλέπει λοιπόν τι θέλει να παραγγείλει, και το βάζει στο καλάθι (βλέπει και κόστος). Όταν είναι έτοιμος το στέλνει στην κουζίνα. Εάν θέλουν extra παραγγελία (πχ ποτό), απλά ανοίγουν το περιηγητή και προσθέτουν στο καλάθι κοκ.
* Όταν τελειώσουν και θέλουν να πληρώσουν, πατούν το κουμπί πληρωμή, επιλέγουν μετρητά-κάρτα και ο υπάλληλος φέρνει τον αντίστοιχο λογαριασμό μαζί με το POS. * Εναλλακτικά μπορεί να δημιουργείται ένα qr το οποίο να λέει το τραπέζι+αύξον αριθμό+ποσό πληρωμής και να το σκανάρει στο ταμείο για να βγάλει το ποσό πληρωμής και αποφασίζει εκείνη τη στιγμή μετρητά-κάρτα.
* Θεωρητικά όταν πληρωθεί ένα τραπέζι, μπορεί να αφαιρεί αυτόματα από τον μετρητή ατόμων του καταστήματος, όσα άτομα πληρώνουν.
* Ίδια λογική, σε περίπτωση που κάποιος νοσήσει, να γίνεται μια push ειδοποίηση.  
**ΛΥΣΗ ΠΡΟΒΛΗΜΑΤΟΣ: ΙΧΝΗΛΑΣΙΜΟΤΗΤΑ, ΑΠΟΦΥΓΗ ΑΦΗΣ ΜΕΝΟΥ (ΜΙΚΡΟΒΙΑ), ΣΥΧΝΗ ΑΛΛΑΓΗ ΜΕΝΟΥ, ΓΡΗΓΟΡΟΤΕΡΗ ΠΑΡΑΓΓΕΛΙΑ**

### MODULE παραλίας
Η χρήση των παραπάνω ακόμα και μετά που περάσει ο ιός μπορεί λύσει το πρόβλημα του μπαίνω στο κατάστημα να δω αν υπάρχει κενό τραπεζάκι. Στην περίπτωση της παραλίας επειδή είναι ανοιχτός χώρος, φαίνονται πόσες ξαπλώστρες είναι κενές. Η λύση που θα δώσει μια ανάλογη εφαρμογή είναι η ταχύτητα εξυπηρέτησης.
* Ο πελάτης κάθεται στην ξαπλώστρα. Εάν το κατάστημα διαθέτει Internet, μπορεί να σκανάρει το qr για να μπει στο Internet. Αλλιώς σκανάρει το qr με το μενού και στέλνει την παραγγελία του στο μπαρ με το νούμερο ξαπλώστρας (επιλέγοντας και τρόπο πληρωμής).
* Ο υπάλληλος του φέρνει την παραγγελία του και πληρώνεται
* Το ίδιο, σε περίπτωση κρούσματος, θα γίνεται μια push ειδοποίηση.  
**ΛΥΣΗ ΠΡΟΒΛΗΜΑΤΟΣ: ΙΧΝΗΛΑΣΙΜΟΤΗΤΑ, ΑΠΟΦΥΓΗ ΑΦΗΣ ΜΕΝΟΥ (ΜΙΚΡΟΒΙΑ), ΣΥΧΝΗ ΑΛΛΑΓΗ ΜΕΝΟΥ, ΓΡΗΓΟΡΟΤΕΡΗ ΠΑΡΑΓΓΕΛΙΑ
ΑΠΑΡΑΙΤΗΤΗ Η ΧΡΗΣΗ-ΠΑΡΟΧΗ INTERNET ΕΙΤΕ ΑΠΟ ΤΟ ΜΑΓΑΖΙ ΕΙΤΕ ΤΑ ΔΕΔΟΜΕΝΑ ΤΟΥ ΠΕΛΑΤΗ**
  
**ΣΗΜΕΙΩΣΗ:** Επειδή κανένα κατάστημα δεν θα “θέλει” να εφαρμόσει το παραπάνω για φορολογικούς λόγους, μπορεί να υπάρχει το τυράκι του loyalty card, όπου ο πελάτης να πηγαίνει στο κατάστημα και να παίρνει πόντους και να έχει έκπτωση;

### MODULE μεταφορικού μέσου
Επειδή στα μεταφορικά μέσα των μεγάλων πόλεων γίνεται πανικός και δεν κρατώνται αποστάσεις, καλό θα ήταν να υπάρχει μέτρηση αυτών για να εισέρχονται ή όχι στο όχημα.
* Σκανάρισμα κατά την είσοδο του επιβάτη στο qr του λεωφορείου. Επίδειξη στον οδηγό για είσοδό του (το κουβούκλιο του οδηγού πρέπει να τον κλείσει στην θέση του οδηγού). Αν είναι ΚΟΚΚΙΝΟ του απαγορεύει. Αν ΠΡΑΣΙΝΟ του επιτρέπει να περάσει και προστίθεται +1 (ή όσα άτομα ορίσει ο επιβάτης, εάν είναι οικογένεια).
* Σε περίπτωση metro, ο συρμός θα έχει ένα νούμερο και τα βαγόνια ένα υπο-νούμερο. Βέβαια δεν μπορείς να ελέγξεις “αυτόματα” ποιος θα μπει και ποιος όχι στο βαγόνι. ΑΝ γίνει έλεγχος όμως και δεν συμμορφώνονται με τους αριθμούς, τότε να κόβεται πρόστιμο (στην αρχή απλό και μετά τσουχτερό).
* Κατά την κάθοδο, πρέπει να σκανάρει ξανά και να πατάει πλήκτρο ότι κατέβηκε, ώστε να απελευθερωθούν οι θέσεις και στη συνέχεια να ανέβουν οι επιβάτες από μπροστά.
* Αν νοσήσει κάποιος, πατάει το κουμπί και έρχεται ειδοποίηση push σε όποιον ταξίδεψε στο ίδιο μέσο με το κρούσμα.  
**EXTRA ΛΕΙΤΟΥΡΓΙΑ:** Αυτό μπορεί να λειτουργήσει και ως ηλεκτρονικό εισητήριο. Μάλιστα θα μπορούσε να λειτουργήσει και να γίνεται πληρωμή-χρέωση του αντίτιμου όταν κατεβαίνεις από το μεταφορικό μέσο, ώστε να σε χρεώνει κατάλληλα (δεν είναι δυνατό να χρεώνει το ίδιο τόσο για διαδρομή μιας στάσης όσο και 10 στάσεων). Μπορούν να βρεθούν δικλύδες ασφαλείας ώστε να μην σκανάρει για κάθοδο μετά από 2 στάσεις ενώ δεν θα αποβιβάζεται (ίσως πχ το qr να είναι κάτω στην στάση και όχι πάνω στο μεταφορικό μέσο).*++++++++++++++++ ΠΕΡΙΣΣΟΤΕΡΗ ΣΚΕΨΗ*   
**ΛΥΣΗ ΠΡΟΒΛΗΜΑΤΟΣ: ΙΧΝΗΛΑΣΙΜΟΤΗΤΑ, ΟΧΙ ΣΥΝΩΣΤΙΣΜΟΣ
ΑΠΑΡΑΙΤΗΤΗ ΠΡΟΥΠΟΘΕΣΗ: ΝΑ ΔΙΟΡΘΩΘΕΙ Η ΣΥΓΚΟΙΝΩΝΙΑ (ΔΡΟΜΟΛΟΓΙΑ ΚΛΠ) ΚΑΙ ΝΑ ΥΠΑΡΧΕΙ ΙΝΤΕΡΝΕΤ**

### MODULE δημόσιας υπηρεσίας-τράπεζας
Συνήθως σε δημόσιες υπηρεσίες και τράπεζες μαζεύονται στην ουρά και περιμένουν την σειρά τους. Αυτό έχει ως αποτέλεσμα να κάνουν μια ευθεία γραμμή, τις περισσότερες φορές δεν κρατάνε αποστάσεις. Η λύση που δίνει η τράπεζα-υπηρεσία είναι η έκδοση χαρτιού (νούμερο). Τις περισσότερες φορές οι πελάτες φεύγουν για άλλες δουλειές και χάνουν την σειρά τους. Ποιά λύση μπορεί να δοθεί;
* Σκανάρισμα qr. Αν είναι ΠΡΑΣΙΝΟ σημαίνει μπορεί να περάσει. Το δείχνει στον υπάλληλο που περιμένει. Μπαίνοντας προστίθεται συν ένας.
* Εάν είναι ΚΟΚΚΙΝΟ, να δείχνει πληροφορίες για ποιο νούμερο εξυπηρετείται και ένας εκτιμώμενος χρόνος αναμονής. Εάν θέλει ο πελάτης να εξυπηρετηθεί, θα πατήσει το κουμπί ότι θα περιμένει. Στα 3-5 νούμερα πριν, μπορεί να του αποστέλλεται ειδοποίηση ότι πλησιάζει το νούμερό του. Τι πετυχαίνουμε; Δεν κάθονται στην σειρά αλλά στέκονται σε ασφαλή απόσταση μεταξύ τους. Ειδοποιούνται όταν έρχεται η σειρά τους (μπορούν να συνδυάσουν και άλλες εργασίες που έχουν να διεκπεραιώσουν, ΔΕΝ χάνονται εργατοώρες σε περίπτωση εργαζομένων).
* Όταν φεύγουν από την υπηρεσία, πατάνε ξανά το qr ότι αποχωρούν. Μειώνονται τα άτομα που είναι στον χώρο και δίνεται ειδοποίηση στον επόμενο στην σειρά να περάσει.
* Εάν κάποιος νοσήσει, μπορεί να πατήσει κουμπί στην εφαρμογή ότι νόσησε, και θα έρθει ειδοποίηση push σε όποιον βρέθηκε στον ίδιο χώρο.  
**ΛΥΣΗ ΠΡΟΒΛΗΜΑΤΟΣ: ΙΧΝΗΛΑΣΙΜΟΤΗΤΑ, ΟΧΙ ΣΥΝΩΣΤΙΣΜΟΣ, ΜΜΕΙΩΣΗ ΧΑΜΕΝΩΝ ΕΡΓΑΤΟΩΡΩΝ.**
  
**EXTRA:** Αυτό μπορεί να λειτουργήσει σε επίπεδο κράτους. Όσοι είναι επαφές κρούσματος (έχουν βρεθεί δηλαδή στον ίδιο χώρο με επιβεβαιωμένο κρούσμα), θα τους έχει έρθει μια ειδοποίηση στο κινητό για να μεταβούν για τεστ (οι ΠΡΟΣ ΕΞΕΤΑΣΗ). Κάθε χρήστης της εφαρμογής θα γράφεται με τον αριθμό του κινητού του, οπότε οι αριθμοί των ΠΡΟΣ ΕΞΕΤΑΣΗ να στέλνονται στον ΕΟΔΥ. Όταν εξετάζεται ο χρήστης θα διαγράφεται ο αριθμός του από την λίστα των ΠΡΟΣ ΕΞΕΤΑΣΗ. Εάν ο χρήστης το αμελήσει ή απλά δεν θέλει να πάει, τότε όταν θα σκανάρει το qr στον χώρο που θέλει να εισέλθει, θα εμφανίζει ΚΟΚΚΙΝΟ και δεν θα του επιτρέπεται η είσοδος.

