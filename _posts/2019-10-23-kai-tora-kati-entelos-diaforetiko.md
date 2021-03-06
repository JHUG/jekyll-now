---
title: Και τώρα κάτι εντελώς διαφορετικό
date: 2019-10-23T23:03:57+02:00
author: Spiros Anastasopoulos
layout: post
categories:
  - java
---
Το περασμένο Σάββατο έγινε το πρώτο meetup του JHUG για τη νέα σεζόν και ήταν διαφορετικό από τα προηγούμενα. Ας πάρουμε όμως τα πράγματα από την αρχή.

Εδώ και καιρό θέλαμε να δοκιμάσουμε κάτι διαφορετικό στα meetups και να ξεφύγουμε λιγάκι από τη δομή με τις 2 ομιλίες. Η ευκαιρία μας δόθηκε σε συνεργασία με τον [Γιώργο Ανδριανάκη](https://twitter.com/geoand86) ο οποίος πρότεινε, αλλά και προθυμοποιήθηκε να βοηθήσει, στη διοργάνωση ενός workshop σχετικό με τα [Quarkus extensions για τo spring web API](https://quarkus.io/guides/spring-web-guide). Το [Quarkus](https://quarkus.io) είναι η νέα, πολλά υποσχόμενη πρόταση της [Red Hat](https://www.redhat.com) για την ανάπτυξη εφαρμογών για microservices, cloud native και serverless εφαρμογές και φυσικά είναι σε java. Για αυτή τη νέα πλατφόρμα έχουν γίνει ομιλίες και στο [JHUG](https://vimeo.com/339715440) και στο [Voxxed Days Athens](https://www.youtube.com/watch?v=UWETnSFB0WA). Ο Γιώργος θα κάνει και μια ομιλία στο προσεχές [Devoxx](https://devoxx.be/speaker-details/?id=124451) για Quarkus και spring οπότε το JHUG ήταν ταυτόχρονα αποκλειστικότητα για τα μέλη και πρόβα generale για τον Γιώργο.

Για την διοργάνωση του workshop είχαμε για άλλη μια φορά τη βοήθεια της [Advantage FSE](http://www.afse.eu/) η οποία παραχώρησε την αίθουσα της και τα κεράσματα στους συμμετέχοντες. Η εταιρεία στέκεται πάντα πολύ κοντά στο JHUG και μας βοηθάει στις εκδηλώσεις μας. Με αυτή την ευκαιρία να ευχαριστήσουμε για άλλη μια φορά την εταιρεία και το [HR τμήμα](https://www.linkedin.com/in/peggytheodorou/) για τη προσφορά και τη συνεργασία τους.

Η εκδήλωση ξεκίνησε με το καλωσόρισμα του JHUG στους παρευρισκόμενους με την ευχή να έχουμε καλή νέα σεζόν και να ευχαριστηθούμε java. Η συμμετοχή, περίπου 30 άτομα με το laptop τους, κρίνεται πολύ ικανοποιητική για το πρώτο μας workshop.

Στη συνέχεια η Αdvantage έκανε μια παρουσίαση για το προφίλ της, τις ψηφιακές υπηρεσίες και τα προϊόντα που παρέχει στον οικονομικό τομέα και τη καλή σχέση που έχει με τα IT communities. Επιθυμία της είναι αυτή η σχέση να ισχυροποιηθεί περισσότερο και με συμμετοχή της σε προσεχείς εκδηλώσεις αλλά και ανοίγοντας [θέσεις εργασίας](http://www.afse.eu/gr/Why-Work-Here).

Μετά σειρά είχε το κύριο πιάτο, ο κώδικας. Ο Γιώργος ξεκίνησε με μια πάρα πολύ σύντομη εισαγωγή στο Quarkus και μετά μίλησε για τα spring web API extensions. Το δεύτερο κομμάτι προτίμησε να το κάνει με τη μορφή live coding. Διάλεξε μια σειρά από μικρές spring εφαρμογές και κάθε μια την έγραφε, την τέσταρε και την έτρεχε live. Οι εφαρμογές αυτές περιείχαν μεγάλη γκάμα από spring features σχετικών με web apps όπως configuration, validation, serialization, routing κτλ. Στα [παραδείγματα του Quarkus](https://github.com/quarkusio/quarkus-quickstarts) μπορείτε να βρείτε τον κώδικα για παρόμοιες εφαρμογές με αυτές που παρουσιάστηκαν.

Το live coding ήταν ένας πάρα πολύ καλός τρόπος να παρουσιαστούν αυτά τα features γιατί φάνηκαν όλα τα καθημερινά θέματα του development:

  1. τι πρέπει να γράψουμε εμείς και τι θα κάνει το framework αυτόματα
  2. τι υποστηρίζεται πλήρως, τι μερικώς και τι καθόλου
  3. πως γίνεται το debugging
  4. πως κάνουμε monitor μια εφαρμογή που τρέχει

Επιπλέον οι περισσότερες ερωτήσεις μπορούσαν να απαντηθούν και λεκτικά αλλά και live με μερικές γραμμές κώδικα όπου φαινόταν τα σημεία της ερώτησης και της απάντησης.

Το live coding τελείωσε μετά από ένα demo για deployment των [native images](https://quarkus.io/guides/building-native-image-guide) μιας Quarkus εφαρμογής σε kubernetes όπου φάνηκε πως η εφαρμογή κάνει scale ανάλογα και με το traffic πως προσαρμόζεται στα traffic bursts.

Μετά από ένα διάλειμμα για καφέ, ακολούθησε το workshop. Σε αυτό η κάθε ομάδα θα δοκίμαζε να φτιάξει μια εφαρμογή με το Quarkus με ελεύθερο θέμα. Μπορούσε είτε να κάνει ένα toy project για να δει πως δουλεύει το framework, είτε να δοκιμάσει ένα έτοιμο tutorial, είτε να δοκιμάσει να κάνει port μια υπάρχουσα spring εφαρμογή είτε να δοκιμάσει να φτιάξει μια νέα από την αρχή.

Σε όλη τη διάρκεια του coding, είχαμε ελεύθερη συζήτηση ανάμεσα στους παρευρισκόμενους. Ήταν μια χαλαρή κουβέντα από αυτές τις ωραίες που γίνονται όταν οι developers έχουν όρεξη για κώδικα και πάρλα. Μιλήσαμε για πάρα πολλά θέματα σχετικά με το Quarkus και το java οικοσύστημα αλλά και γενικότερα για διάφορα επαγγελματικά θέματα του κλάδου. Φυσικά σε όλη τη διάρκεια λύθηκαν απορίες σχετικά με τις εφαρμογές που αναπτύσσονταν εκείνη την ώρα και όλες οι ομάδες είπαν την άποψη τους για το framework και τις εντυπώσεις τους από την χρήση του.

Στο τέλος του workshop ακολούθησε pizza και networking και κληρώθηκαν δύο άδειες για το IntelliJ προσφορά της [Jetbrains](https://www.jetbrains.com). Το ραντεβού ανανεώθηκε για την επόμενη φορά με περισσότερη java.

## Join JHUG

Μπορείτε να μαθαίνετε τα νέα του JHUG, να συμμετέχετε και να ανταλλάξετε ιδέες μέσα από τα κανάλια μας:

  * [Slack](https://jhug.slack.com)
  * [Twitter](https://twitter.com/jhug)
  * [Meetup](https://www.meetup.com/Java-Hellenic-User-Group/)
  * [Blog](https://www.jhug.gr)
  * [Vimeo](https://vimeo.com/javahellenicusergroup)

Τα νέα για τα meetup και τις άλλες εκδηλώσεις δημοσιεύονται σε όλα τα κανάλια αλλά οι ενδιαφέρουσες συζητήσεις είναι στο slack. Αν δεν είσαστε εκεί, ζητήστε πρόσκληση.

## Και μετά και μετά;

Το επόμενο meetup μας θα γίνει στις [11 Νοεμβρίου](https://www.meetup.com/Java-Hellenic-User-Group/events/265867977). Έχουμε διαλέξει 2 πρακτικά θέματα και οι ομιλίες προβλέπονται πολύ ενδιαφέρουσες. Μέχρι τότε, keep coding.