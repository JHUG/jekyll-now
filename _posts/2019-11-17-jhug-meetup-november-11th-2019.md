---
id: 637
title: JHUG meetup November 11th 2019
date: 2019-11-17T20:46:28+02:00
author: Spiros Anastasopoulos
layout: post
guid: http://www.jhug.gr/?p=637
permalink: /archives/637
categories:
  - java
---
Την περασμένη Δευτέρα κάναμε τη δεύτερη μας εκδήλωση για φέτος που ήταν και το πρώτο meetup εφόσον η πρώτη εκδήλωση ένα workshop για το [quarkus](http://www.jhug.gr/archives/627).

Το meetup έγινε στην πολύ όμορφη αίθουσα του [Code.Hub](https://www.codehub.gr/) στη Λεωφόρο Αλεξάνδρας. Αυτή τη φορά είχαμε χορηγούς την [Nokia](https://www.nokia.com/networks/) και το [Code.Hub](https://www.codehub.gr/) που μας βοήθησαν με την προβολή του meetup, την αίθουσα, το networking και πρόσφεραν και τα κεράσματα σε όσους έλαβαν μέρος.

Η προσέλευση ήταν ικανοποιητική. Δυστυχώς λόγω της επίσκεψης του προέδρου της Κίνας και αναταραχών στην ΑΣΟΕΕ η κατάσταση στους δρόμους ήταν δύσκολη και υπήρχε κόσμος που δεν ρίσκαρε να κατέβει στο κέντρο. Αρκετοί από αυτούς θα σκέφτηκαν ότι δεν πειράζει, θα δουν τις ομιλίες όταν ανέβουν τα βίντεο αλλά δυστυχώς σε αυτό το meetup δεν είχαμε βίντεο λόγω υποχρεώσεων του κάμεραμαν(sic!) εκτός Αθηνών. Αυτά τα απρόοπτα δυστυχώς συμβαίνουν. Δεν είναι τα πάντα προβλέψιμα, στρωτά και εύκολα όπως όταν γράφουμε κώδικα σε java.

Ο Θωμάς καλωσόρισε τον κόσμο εκ μέρους του JHUG και για μια ακόμα φορά ζήτηση περισσότερες συμμετοχές για ομιλίες.

Ο [Δημήτρης Αϊβάτογλου](https://www.linkedin.com/in/daivatoglou/) από τη Nokia μίλησε για την εταιρεία, την πορεία της και τα απαιτητικά έργα που φέρνει σε πέρας και πως η java αποτελεί το πιο αξιόπιστο εργαλείο της.

Στη συνέχεια ο [Γιάννης Νικολακόπουλος](https://www.linkedin.com/in/inikolakopoulos/) από το Code.Hub μίλησε για τη σημασία που έχει σήμερα η γνώση προγραμματισμού, για τις υπηρεσίες που προσφέρουν και για τη στήριξη που παρέχουν στα meetups της Αθήνας και όχι μόνο.

Μετά από αυτές τις απαραίτητες αναφορές, το λόγο πήραν οι ομιλητές.

## Java Memory Management, Bedtime Stories από την Εύη Χατζιδάκη

Η Εύη, senior software engineer στη Nokia, με αυτή την ομιλία έσπασε μια άσχημη παράδοση που μας στεναχωρούσε, ότι σε κανένα meetup δεν είχε κάνει παρουσίαση γυναίκα μηχανικός.

Διάλεξε ένα θέμα με το οποίο είχε ασχοληθεί αρκετά όπως είπε, το java memory management. Το project στο οποίο συμμετέχει περιλαμβάνει ένα server από τον οποίο περνάει πολύ μεγάλη κίνηση και άρα τα memory leaks και ο χρόνος που τρέχει ο garbage collector έχουν μεγάλο αντίκτυπο στο performance του.

Η παρουσίαση της είχε πολύ υλικό, νομίζω άνετα μπορούν να βγούνε ακόμα 2-3 ομιλίες από όσα είπε για τα επόμενα meetups. Η Εύη έκανε ένα overview του πως διαχειρίζεται τη μνήμη η JVM, έδειξε σχετικά patterns και anti-patterns και παρουσίασε εργαλεία για monitoring και debugging θεμάτων σχετικών με μνήμη. Για τα περισσότερα από αυτά έδειξε και ένα live demo όπου φαινόταν καθαρά το πρόβλημα και η λύση.

Η παρουσίαση ήταν πολύ πυκνή με πολύ υλικό αλλά απλή και κατανοητή. Έβαλε σε τάξη πολλές ερωτήσεις σχετικά με τη JVM και τη μνήμη και σίγουρα έδωσε ιδέες για ομιλίες που θα εξειδικεύουν τα θέματα που έθεσε.

## Quiz, pizza and beer

Ανάμεσα στις δυο ομιλίες ο Γιώργος Καλφόπουλος βλ [Ministry Of Testing](https://www.meetup.com/Ministry-of-Testing-Athens/about/) έκανε ένα quiz με ερωτήσεις java και στους νικητές δώθηκαν δύο βιβλία και μια προσωπική άδεια intellij προσφορά της [JetBrains](https://www.jetbrains.com/)

Μετά απο αυτή την ευχάριστη νότα έγινε διάλειμμα για pizza και networking, πριν συνεχίσουμε με τη δεύτερη ομιλία.

## Faster, Cheaper, Leaner: Horizontally Scaling a CI Pipeline από τον Γιώργο Σασλή

Ο [Γιώργος](https://www.linkedin.com/in/gsaslis/) είναι software delivery engineer στη RedHat και είναι γνωστός στο Ελληνικό ΙΤ σαν ένα από τα κινητήρια γρανάζια πίσω από το IT οικοσύστημα της Κρήτης και από τη διοργάνωση των [AgileCrete](https://agilecrete.org/) και [JCrete](http://www.jcrete.org/).

Στην Αθήνα βρέθηκε ταξιδεύοντας για το DevConf της Ρουμανίας όπου και θα έκανε μια παρουσίαση με το ίδιο θέμα. Με αυτή την ευκαιρία προθυμοποιήθηκε να μας παρουσιάσει το υλικό του και τον ευχαριστούμε.

Η παρουσίαση είχε 2 μέρη.

Το πρώτο θα μπορούσε να έχει τίτλο &#8220;Όλα όσα θέλατε να μάθετε για το CI pipeline&#8221;. Πραγματικά παρουσίασε το ιστορικό της εξέλιξης του, την αναγκαιότητα του και πολλά patterns καλής χρήσης και ομοίως anti-patterns κακής. Έκανε αναφορά σε όλα τα σχεδιαστικά θέματα ενός CI pipeline όπως κόστος VMs, χρόνος εκτέλεσης, παράλληλη εκτέλεση των tests, αξιοπιστία των αποτελεσμάτων, flaky tests και πολλά άλλα.

Το δεύτερο μέρος περιείχε τη λύση που δώσανε στα παραπάνω θέματα στα projects που συμμετέχει. Παρουσίασε το CI pipeline της [3scale](https://www.3scale.net/) και έδειξε τα πλεονεκτήματα και τα μειονεκτήματα του.

Ο Γιώργος ανέβασε τις διαφάνειες του [εδώ](https://speakerdeck.com/gsaslis/faster-cheaper-leaner-horizontally-scaling-a-ci-pipeline-1ac8963b-22ed-4149-9047-7a7d192312d3) ενώ τα projects της 3scale είναι open source και βρίσκεται [εδώ](https://github.com/3scale/porta)

## Το επόμενο;

Το ραντεβού ανανεώθηκε για την επόμενη φορά με περισσότερη java. Επειδή όμως το meetup.com έχει ένα θέμα με τα RSVP αν θέλετε κοιτάζεται και τα υπόλοιπα κανάλια για να μην χάσετε την ημέρα.

## Join JHUG

Μπορείτε να μαθαίνετε τα νέα του JHUG, να συμμετέχετε και να ανταλλάξετε ιδέες μέσα από τα κανάλια μας:  
&#8211; [Slack](https://jhug.slack.com)  
&#8211; [Twitter](https://twitter.com/jhug)  
&#8211; [Meetup](https://www.meetup.com/Java-Hellenic-User-Group)  
&#8211; [Blog](https://www.jhug.gr)  
&#8211; [Vimeo](https://vimeo.org/javahellenicusergroup)

Τα νέα για τα meetup και τις άλλες εκδηλώσεις δημοσιεύονται σε όλα τα κανάλια αλλά οι ενδιαφέρουσες συζητήσεις είναι στο slack. Αν δεν είσαστε εκεί, ζητήστε πρόσκληση.