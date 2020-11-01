## Διπλωματικές Εργασίες 2020-2021

1. **Πρόσβαση σε μοντέλα βαθιάς μάθησης και ενσωματώσεων κειμένου μέσω υπηρεσίας Ιστού και μεταφοράς μάθησης**

    Τα σύγχρονα μοντέλα μηχανικής μάθησης έχουν αυξημένες απαιτήσεις σε υπολογιστική ισχύ και μνήμη, ενώ ιδίως τα μοντέλα γλωσσικής επεξεργασίας εκτελούνται εγγενώς και παραμένουν στη μνήμη του συστήματος. Τέτοια μοντέλα είναι κρίσιμης σημασίας σε εφαρμογές όπως η ανάλυση στάσεων και η ταξινόμηση κειμένου.  Στην εργασία αυτή θα εξεταστεί και θα υλοποιηθεί η δυνατότητα πρόσβασης σε μοντέλα επεξεργασίας φυσικής γλώσσας όπως τα ELMo, BERT κ.α. και η πρόσβαση στους συμπερασμούς που παράγουν μέσω υπηρεσίας Ιστού (web service). Ταυτόχρονα θα εξεταστεί η δυνατότητα μεταφοράς μάθησης (transfer learning) από τα προ-εκπαιδευμένα μοντέλα και αυξητικής εκπαίδευσής τους (incremental training) με έμφαση στην επίδοση και τη διαλειτουργικότητα.

    *Ενδεικτικές πηγές-βιβλιογραφία:*
    
    - Hassan, H. A. M., Sansonetti, G., Gasparetti, F., Micarelli, A., & Beel, J. (2019). [BERT, ELMo, USE and InferSent Sentence Encoders: The Panacea for Research-Paper Recommendation?.](http://ceur-ws.org/Vol-2431/paper2.pdf) In RecSys (Late-Breaking Results) (pp. 6-10)
    - [FROM Pre-trained Word Embeddings TO Pre-trained Language Models — Focus on BERT](https://towardsdatascience.com/from-pre-trained-word-embeddings-to-pre-trained-language-models-focus-on-bert-343815627598)
    - [Building a Multi-label Text Classifier using BERT and TensorFlow](https://towardsdatascience.com/building-a-multi-label-text-classifier-using-bert-and-tensorflow-f188e0ecdc5d)
    - [BlueBERT(NCBI BERT), Using BlueBERT with huggingface transformers](https://medium.com/@manasmohanty/ncbi-bluebert-ncbi-bert-using-tensorflow-weights-with-huggingface-transformers-15a7ec27fc3d)
    
    
2. **Σημασιολογική αντιστοίχιση δεδομένων μεγάλου όγκου σε γράφους γνώσης με χρήση διανυσμάτων λέξεων**

    Με την εξάπλωση του Παγκόσμιου Ιστού και την αύξηση του διαθέσιμου αποθηκευτικού χώρου υπάρχουν σήμερα διαθέσιμα μεγάλα σύνολα δεδομένων σε αδόμητη ή ημιδομημένη μορφή, όπως κείμενα και συμβολοσειρές σε μορφή πίνακα ή csv. Η εργασία αυτή θα μελετήσει την δυνατότητα αντιστοίχισης των πληροφοριών αυτών σε δομημένους γράφους γνώσης (knowledge graphs) με χρήση μηχανικής μάθησης και συγκεκριμένα διανυσμάτων λέξεων (word embeddings). Το πρόβλημα αυτό παραμένει ανοιχτό στην πράξη κυρίως λόγω ελλιπών ή αμφίσημων δεδομένων. Η κατανόηση της σημασιακής δομής των δεδομένων αυτών θα βοηθήσει περαιτέρω στη διαδικασία ανάλυσής τους (data analytics).
   
    *Ενδεικτικές πηγές-βιβλιογραφία:*
   
    - Proc. of the ISWC2020 [Semantic Web Challenge](http://www.cs.ox.ac.uk/isg/challenges/sem-tab/) on Tabular Data to Knowledge Graph Matching
    - Teslya N, Savosin S. Matching Ontologies with Word2Vec-Based Neural Network. InInternational Conference on Computational Science and Its Applications 2019  (pp. 745-756). Springer.
    - Kolyvakis, P., Kalousis, A., Smith, B., & Kiritsis, D. (2018). Biomedical ontology alignment: an approach based on representation learning. *Journal of biomedical semantics*, *9*(1), 21.
    
    
3. **Μάθηση αναπαράστασης και εφαρμογή σε γραφήματα Διασυνδεδεμένων Δεδομένων**

    Η μάθηση αναπαράστασης (representation learning) έγκειται στο γεγονός ότι δίκτυα βαθιάς μάθησης μπορεί να είναι σε θέση να μαθαίνουν την κατάλληλη αναπαράσταση για κάθε μορφή δεδομένων, ώστε μετέπειτα να μπορεί αυτή να χρησιμοποιηθεί ως είσοδος σε άλλα μοντέλα μηχανικής μάθησης. Ένα σχετικό παράδειγμα αποτελούν οι διανυσματικές αναπαραστάσεις λέξεων (word embeddings). Ταυτόχρονα, αναδύονται νέα μοντέλα νευρωνικών δικτύων, όπως τα Νευρωνικά Δίκτυα Γραφημάτων (GNNs), για την επεξεργασία δεδομένων σε μορφή γραφήματος. Η εργασία αυτή θα εξετάσει τη δυνατότητα μάθησης αναπαραστάσεων για πιο περίπλοκες μορφές και συγκεκριμένα για πληροφορίες διαθέσιμες σε μορφή γραφημάτων Διασυνδεδεμένων Δεδομένων (Linked Data graphs). Απώτερος στόχος είναι η αξιοποίηση όχι μόνο της κειμενικής πληροφορίας, αλλά και της δομής, των διασυνδέσεων και των εννοιολογικών συσχετίσεων (κλάσεις, ιεραρχίες, ιδιότητες, περιορισμοί) των δεδομένων αυτών για την αποτελεσματική αναπαράστασή τους με τεχνικές βαθιάς μάθησης.
   
    *Ενδεικτικές πηγές-βιβλιογραφία:*
   
    - Ristoski, P., Rosati, J., Di Noia, T., De Leone, R. and Paulheim, H., 2019. RDF2Vec: RDF graph embeddings and their applications. *Semantic Web*, *10*(4), pp.721-752.
    - Holter, O.M., Myklebust, E.B., Chen, J. and Jimenez-Ruiz, E., [Embedding OWL Ontologies with OWL2Vec](http://ceur-ws.org/Vol-2456/paper9.pdf). 2019
    - D. Gromann, L. E. Anke, Τ. eclerck (eds.), 2019. [Special issue on Semantic Deep Learning](https://content.iospress.com/articles/semantic-web/sw190364). *Semantic Web, vol. 10*(5), pp. 815-822.
    - Bengio, Y., Courville, A. and Vincent, P., 2013. Representation learning: A review and new perspectives. *IEEE transactions on pattern analysis and machine intelligence*, *35*(8), pp.1798-1828. [(arxiv version)](https://arxiv.org/abs/1206.5538)
    - Scarselli, F., Gori, M., Tsoi, A., Hagenbuchner, M. & Monfardini, G. 2009, 'The graph neural network model', IEEE Transactions on Neural Networks, vol. 20, no. 1, pp. 61-80.
    
    
4. **Αξιολόγηση και υλοποίηση μεθόδων εντοπισμού και αναγνώρισης αντικειμένων σε πραγματικό χρόνο με χρήση βαθέων νευρωνικών δικτύων**

    Τα συνελικτικά νευρωνικά δίκτυα (CNN) και η βελτίωση του αναδρομικού εντοπισμού περιοχών (R-CNN) αποτελούν σήμερα τις τεχνολογίες αιχμής για την αναγνώριση αντικειμένων. Αλγόριθμοι όπως oi Fast-RCNN, Faster R-CNN, Mask R-CNN, MeSH R-CNN, SSD, YoLο, χρησιμοποιούνται ευρέως για τον εντοπισμό της τοποθεσίας αντικειμένων σε εικόνες, με αφίρροπα αποτελέσματα ως αφορά την ακρίβεια, την επίδοση και την ταχύτητα απόκρισης. Η εργασία αυτή θα αξιολογήσει αλγορίθμους όπως οι παραπάνω και θα υλοποιήσει ένα σύστημα εντοπισμού και αναγνώρισης από σύνολα δεδομένων ενδιαφέροντος, **[όπως ο εντοπισμός χρήσης προστατευτικής μάσκας προσώπου σε ροές βίντεο](https://www.aicrowd.com/challenges/aicrowd-blitz-2/problems/maskd)**. 

    *Ενδεικτικές πηγές-βιβλιογραφία:*

    - Huang, Jonathan, Vivek Rathod, Chen Sun, Menglong Zhu, Anoop Korattikara, Alireza Fathi, Ian Fischer et al, 2017. Speed/accuracy trade-offs for modern convolutional object detectors. In Proceedings of the IEEE conference on computer vision and pattern recognition, pp. 7310-7311.
    - Redmon, Joseph, Santosh Divvala, Ross Girshick, and Ali Farhadi, 2016. You only look once: Unified, real-time object detection. In Proceedings of the IEEE conference on computer vision and pattern recognition, pp. 779-788.
    - Pournaras, X. and Koutsomitropoulos, D, 2020. [Deep Learning on the Web: State-of-the-art Object Detection using Web-based Client-side Frameworks](https://www.ceid.upatras.gr/webpages/koutsomi/pdf/iisa2020.pdf). In Proc. of the 11th Int. Conference on Information, Intelligence, Systems and Applications (IISA). IEEE. 
    
    
5.  **Υλοποίηση υποδομής chatbot για την αξιοποίηση βιοϊατρικής πληροφορίας**

    Διάφορες διαδικτυακές υπηρεσίες πχ PubMed, κατορθώνουν να διαχειριστούν πληθώρα ιατρικών δεδομένων με σχετική ευκολία, με τη συγκέντρωση αλλά και, σε δεύτερο χρόνο, στοχευμένη διάθεση πληροφοριών, να αποτελεί μια συνήθη διεργασία. Παρ’ όλα αυτά, ιδιαίτερο ενδιαφέρον αποτελεί η ύπαρξη ανατροφοδότησης στα διάφορα ερωτήματα που θέτει ο τελικός χρήστης. Την απαίτηση αυτή ικανοποιούν τα συστήματα συνομιλίας (chatbot), τα οποία αντικαθιστούν οποιαδήποτε ανθρώπινη παρέμβαση. Σκοπός της παρούσας διπλωματικής εργασίας, είναι η σχεδίαση αλλά και υλοποίηση ενός chatbot, όπου με τη βοήθεια τεχνικών ενσωμάτωσης λέξεων θα μπορεί να διαχειριστεί τον διάλογο χρήστη-μηχανής. Η ανάπτυξη θα μπορούσε να γίνει με χρήση γλώσσας προγραμματισμού πχ Python ή οποιαδήποτε cloud πλατφόρμας πχ Google’s DialogFlow, κλπ. 

    *Ενδεικτικές πηγές - βιβλιογραφία:*
    - Adamopoulou E, Moussiades L. An Overview of Chatbot Technology. Artificial Intelligence Applications and Innovations. 2020;584:373-383. Published 2020 May 6. doi:10.1007/978-3-030-49186-4_31
    - Mierzwa S, Souidi S, Conroy T, Abusyed M, Watarai H, Allen T. On the Potential, Feasibility, and Effectiveness of Chat Bots in Public Health Research Going Forward. Online J Public Health Inform. 2019;11(2):e4. Published 2019 Sep 19. doi:10.5210/ojphi.v11i2.9998
    - Vaidyam AN, Wisniewski H, Halamka JD, Kashavan MS, Torous JB. Chatbots and Conversational Agents in Mental Health: A Review of the Psychiatric Landscape. Can J Psychiatry. 2019 Jul;64(7):456-464. doi: 10.1177/0706743719828977. Epub 2019 Mar 21. PMID: 30897957; PMCID: PMC6610568.
    - National Library of Medicine, N.C.B.I, 2020 [online]. Available: https://pubmed.ncbi.nlm.nih.gov
    
    
6.  **Αυτόματη παραγωγή περιλήψεων από βιοϊατρικά κείμενα**

    Για τα δεδομένα κειμενικής μορφής, τα τελευταία χρόνια, έχουν αναπτυχθεί τεχνικές επεξεργασίας φυσικής γλώσσας, ικανές στο να βοηθήσουν στην κατανόηση τους από τις υπολογιστικές μηχανές. Ιδιαίτερο ενδιαφέρον παρουσιάζει επίσης και κάθε προσπάθεια εξαγωγή γνώσης μέσα από το υλικό αυτό. Μια τέτοια διαδικασία είναι και η αυτόματη παραγωγή περιλήψεων (automatic text summarization), στοιχείων δηλαδή απαλλαγμένων από κάθε είδους πλεονάζουσας πληροφορίας. Σκοπός της παρούσας διπλωματικής εργασίας είναι η αξιοποίηση τεχνικών βαθιάς μάθησης, όπως ο αλγόριθμος BERT, για την παραγωγή περιλήψεων από ιατρικά κείμενα. Η ανάπτυξη θα μπορούσε να γίνει με χρήση γλώσσας προγραμματισμού πχ Python. 

    *Ενδεικτικές πηγές - βιβλιογραφία:*
    - Devlin, J., Chang, M. W., Lee, K., Toutanova, K.: BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding, arXiv:04805v2 (2019). 
    - Kieuvongngam, Virapat & Tan, Bowen & Niu, Yiming. (2020). Automatic Text Summarization of COVID-19 Medical Research Articles using BERT and GPT-2. 
    - Chen YP, Chen YY, Lin JJ, Huang CH, Lai F. Modified Bidirectional Encoder Representations From Transformers Extractive Summarization Model for Hospital Information Systems Based on Character-Level Tokens (AlphaBERT): Development and Performance Evaluation. JMIR Med Inform. 2020;8(4):e17787. Published 2020 Apr 29. doi:10.2196/17787
    
    
7. **Σύστημα υποστήριξης διάγνωσης καρκίνου με τεχνικές βαθιάς μάθησης (deep learning)**

    Στην παραδοσιακή διάγνωση του καρκίνου, οι γιατροί εξετάζουν τη βιοψία και τις απεικονιστικές εξετάσεις για να κάνουν διαγνωστικές εκτιμήσεις, βασιζόμενοι κυρίως σε διαφοροποιήσεις της εικόνας, στη μορφολογία των κυττάρων και την κατανομή των ιστών. Συνήθως αυτές είναι υποκειμενικές και οδηγούν σε αξιόλογες διαφοροποιήσεις. Από την άλλη μεριά, τα εργαλεία υπολογιστικής διάγνωσης επιτρέπουν αντικειμενική κρίση χρησιμοποιώντας ποσοτικές μετρήσεις [1]. 
    Η διπλωματική εργασία θα εστιάσει στη χρήση αλγορίθμων βαθιάς μάθησης (Deep Learning), που αποτελούν τα βασικό και ποιο κρίσιμο στοιχείο των συστημάτων αυτόματης διάγνωσης. Η ανασκόπηση της βιβλιογραφίας δείχνει ότι έχουν χρησιμοποιηθεί τέτοιοι αλγόριθμοι, όπως Τεχνητά Νευρωνικά Δίκτυα, k- Πλησιέστεροι Γείτονες, Ασαφή Συστήματα, κλπ., στο σχεδιασμό αυτών των συστημάτων [2-9]. Η απόδοση της κατηγοριοποίησης τέτοιων αλγορίθμων είναι πολύ καλή, όταν οι παράμετροι που χρησιμοποιούν έχουν προσαρμοστεί στις βέλτιστες τιμές τους. Αφού σχεδιαστεί και υλοποιηθεί το ΝΔ, θα εκπαιδευτεί και θα επικυρωθούν τα μοντέλα που θα προκύψουν, με πρότυπα σύνολα δεδομένων. Στη συνέχεια θα χρησιμοποιηθούν δεδομένα από βάσεις δεδομένων που υπάρχουν σε Ελληνικά διαγνωστικά κέντρα ή πανεπιστημιακά εργαστήρια ή έχουν προκύψει στα πλαίσια ερευνητικών προγραμμάτων. Ενδεικτικά αναφέρουμε το έργο “Υπηρεσίες Υποβοήθησης Διάγνωσης Καρκίνου του Μαστού με Μεθόδους Ανάκτησης Εικόνας Βάσει Περιεχομένου” [10]. Θα χρησιμοποιηθούν τα ίδια δεδομένα και θα γίνει σύγκριση των αποτελεσμάτων. 
    Προαπαιτούμενα: Υπολογιστική Νοημοσύνη, Python, TensorFlow, καλή γνώση Αγγλικών.

    *Αναφορές:*

    1. C. Demir and B. Yener, “Automated Cancer Diagnosis Based on Histopathological Images: s Systematic Survey”, TECHNICAL REPORT, RENSSELAER POLYTECHNIC INSTITUTE, DEPARTMENT OF COMPUTER SCIENCE, TR-05-09.
    2.  A. Ben-Dor, L. Bruhn, N. Friedman, I. Nachman, M. Schummer, Z. Yakhini, Tissue classification with gene expression profiles, J. Comput. Biol. 7(2000) 559-583. 
    3.  T.S. Furey, N. Cristianini, N. Duffy, D.W. Bednarski, M. Schummer, D. Haussler, Support vector machine classification and validation of cancer tissue samples using microarray expression data, Bioinformatics 16(2000) 906-914. 
    4.  I. Guyon, J. Weston, S. Barnhill, V. Vapnik, Gene selection for cancer classification using support vector machines, Mach. Learn. 46(2002) 389-422. 
    5.  J. Khan, J.S. Wei, M. Ringner, L.H. Saal, M. Ladanyi, F. Westermann, F. Berthold, M. Schwab, C.R. Antonescu, C. Peterson, P.S. Meltzer, Classification and diagnostic prediction of cancers using gene expression profiling and artificial neural networks, Nat. Med. 7(2001) 673-679. 
    6.  G. Ball, S. Mian, F. Holding, R.O. Allibone, J. Lowe, S. Ali, G. Li, S. McCardle, I.O. Ellis, C. Creaser, and R.C. Rees, An integrated approach utilizing artificial neural networks and SELDI mass spectrometry for the classification of human tumours and rapid identification of potential biomarkers, Bioinformatics 18(2002) 395-404. 
    7.  M. Kallergi, Computer-aided diagnosis of mammographic microcalcification clusters, Med. Phys. 31(2004) 314-326.
    8.  B. Sahiner, H.-P. Chan, N. Petrick, D. Wei, M.A. Helvie, D.D. Adler, M.M. Goodsitt, Classification of mass and normal breast tissue: A convolution neural network classifier with spatial domain and texture images, IEEE Trans. Med. Imaging 15(1996) 598-610.
    9.  L. Shen, R.M. Rangayyan, J.E.L. Desautels, Application of shape analysis to mammographic calcifications, IEEE Trans. Med. Imaging 13(1994) 263-274. 
    10. N. Arikidis et al., “ A tow-stage for microclacification cluster segmentation in mammography by deformable models”, Medical Physics 42(10)Q 5848 – 5861, 2015.
    
    
8. **Βελτιστοποίηση συστήματος υποστήριξης διάγνωσης καρκίνου με εξελικτικές τεχνικές**

    Στην παραδοσιακή διάγνωση του καρκίνου, οι γιατροί εξετάζουν τη βιοψία και τις απεικονιστικές εξετάσεις για να κάνουν διαγνωστικές εκτιμήσεις, βασιζόμενοι κυρίως σε διαφοροποιήσεις της εικόνας, στη μορφολογία των κυττάρων και την κατανομή των ιστών. Συνήθως αυτές είναι υποκειμενικές και οδηγούν σε αξιόλογες διαφοροποιήσεις. Από την άλλη μεριά, τα εργαλεία υπολογιστικής διάγνωσης επιτρέπουν αντικειμενική κρίση χρησιμοποιώντας ποσοτικές μετρήσεις [1].Σε τέτοια συστήματα έχουν χρησιμοποιηθεί αλγόριθμοι μάθησης, που αποτελούν τα βασικό και ποιο κρίσιμο στοιχείο αυτών των συστημάτων. Η ανασκόπηση της βιβλιογραφίας δείχνει ότι έχουν χρησιμοποιηθεί τέτοιοι αλγόριθμοι, όπως Τεχνητά Νευρωνικά Δίκτυα, k- Πλησιέστεροι Γείτονες, Ασαφή Συστήματα, αλλά μηχανές διανυσμάτων υποστήριξης, στο σχεδιασμό αυτών των συστημάτων [2-9]. Η απόδοση της κατηγοριοποίησης τέτοιων αλγορίθμων είναι πολύ καλή, όταν οι παράμετροι που χρησιμοποιούν έχουν προσαρμοστεί στις βέλτιστες τιμές τους. Όμως στην πράξη, οι τιμές αυτών των παραμέτρων συνήθως καθορίζονται εμπειρικά, με τη μέθοδο δοκιμής και λάθους (trial and error). Στόχος της Δ.Ε. είναι να χρησιμοποιηθούν ευφυείς αλγόριθμοι, καθοδηγούμενοι από δεδομένα (data driven techniques) οι οποίοι βελτιστοποιούν τις παραμέτρους και ταυτόχρονα εκπαιδεύουν τα μοντέλα. Έτσι θα έχουμε σαν αποτέλεσμα ακριβή μοντέλα, τα οποία γενικεύουν και μπορούν να δίνουν ακριβέστερες διαγνώσεις. Αφού επικυρωθούν το μοντέλα που θα προκύψουν, με πρότυπα σύνολα δεδομένων, στη συνέχεια θα χρησιμοποιηθούν δεδομένα από βάσεις δεδομένων που υπάρχουν σε Ελληνικά διαγνωστικά κέντρα ή πανεπιστημιακά εργαστήρια ή έχουν προκύψει στα πλαίσια ερευνητικών προγραμμάτων. Ενδεικτικά αναφέρουμε το έργο “Υπηρεσίες Υποβοήθησης Διάγνωσης Καρκίνου του Μαστού με Μεθόδους Ανάκτησης Εικόνας Βάσει Περιεχομένου” [10]. Θα χρησιμοποιηθούν τα ίδια δεδομένα και θα γίνει σύγκριση των αποτελεσμάτων. 
    Προαπαιτούμενα: Υπολογιστική Νοημοσύνη, Python, TensorFlow, καλή γνώση Αγγλικών.

    *Αναφορές:*

    1.  C. Demir and B. Yener, “Automated Cancer Diagnosis Based on Histopathological Images: s Systematic Survey”, TECHNICAL REPORT, RENSSELAER POLYTECHNIC INSTITUTE, DEPARTMENT OF COMPUTER SCIENCE, TR-05-09.
    2.  A. Ben-Dor, L. Bruhn, N. Friedman, I. Nachman, M. Schummer, Z. Yakhini, Tissue classification with gene expression profiles, J. Comput. Biol. 7(2000) 559-583. 
    3.  T.S. Furey, N. Cristianini, N. Duffy, D.W. Bednarski, M. Schummer, D. Haussler, Support vector machine classification and validation of cancer tissue samples using microarray expression data, Bioinformatics 16(2000) 906-914. 
    4.  I. Guyon, J. Weston, S. Barnhill, V. Vapnik, Gene selection for cancer classification using support vector machines, Mach. Learn. 46(2002) 389-422. 
    5.  J. Khan, J.S. Wei, M. Ringner, L.H. Saal, M. Ladanyi, F. Westermann, F. Berthold, M. Schwab, C.R. Antonescu, C. Peterson, P.S. Meltzer, Classification and diagnostic prediction of cancers using gene expression profiling and artificial neural networks, Nat. Med. 7(2001) 673-679. 
    6.  G. Ball, S. Mian, F. Holding, R.O. Allibone, J. Lowe, S. Ali, G. Li, S. McCardle, I.O. Ellis, C. Creaser, and R.C. Rees, An integrated approach utilizing artificial neural networks and SELDI mass spectrometry for the classification of human tumours and rapid identification of potential biomarkers, Bioinformatics 18(2002) 395-404. 
    7.  M. Kallergi, Computer-aided diagnosis of mammographic microcalcification clusters, Med. Phys. 31(2004) 314-326.
    8.  B. Sahiner, H.-P. Chan, N. Petrick, D. Wei, M.A. Helvie, D.D. Adler, M.M. Goodsitt, Classification of mass and normal breast tissue: A convolution neural network classifier with spatial domain and texture images, IEEE Trans. Med. Imaging 15(1996) 598-610.
    9.  L. Shen, R.M. Rangayyan, J.E.L. Desautels, Application of shape analysis to mammographic calcifications, IEEE Trans. Med. Imaging 13(1994) 263-274. 
    10. N. Arikidis et al., “ A tow-stage for microclacification cluster segmentation in mammography by deformable models”, Medical Physics 42(10)Q 5848 – 5861, 2015.
    
    
*Οι διπλωματικές εργασίες 1-6 εκπονούνται με συνεπιβλέποντα τον κ. Κουτσομητρόπουλο (koutsomi@ceid). Θα δοθούν μέχρι 4 εργασίες. Οι διπλωματικές εργασίες 7, 8 εκπονούνται με επιβλέποντα τον κ. Λυκοθανάση (likothan@ceid).
Απαραίτητη η καλή γνώση Αγγλικής (για τη μελέτη της βιβλιογραφίας) και επιθυμητή η εξοικείωση με έννοιες Μηχανικής Μάθησης, Νευρωνικών Δικτύων, Αναπαράστασης Γνώσης και Τεχνολογιών Ιστού, Python, TensorFlow.*

**Αιτήσεις**  για τα παραπάνω θέματα υποβάλλονται ηλεκτρονικά κατόπιν επικοινωνίας στα παραπάνω e-mail μέχρι 16/11 και περιλαμβάνουν:

- Μέχρι δύο (2) θέματα με σειρά προτίμησης.
- Αναλυτική καρτέλα βαθμολογίας, όπου θα σημειώνεται ο αριθμός μαθημάτων που απομένουν για το δίπλωμα[^1], αναμενόμενη περίοδος κτήσης αυτού και τρέχων ΜΟ βαθμολογίας.
- Σύντομο βιογραφικό σημείωμα όπου θα τεκμαίρεται η εξοικείωση με τα απαραίτητα και επιθυμητά προαπαιτούμενα (πιστοποίηση ξένης γλώσσας, παρακολούθηση σχετικού μαθήματος, σεμιναρίου, εκπόνηση εργασίας, προσωπικό ενδιαφέρον κτλ)

[^1]: *Φοιτητής που έχει διανύσει 5 έτη φοίτησης μπορεί να αναλάβει Δ. Ε. μόνον εφόσον, κατά τη στιγμή της ανάθεσης, χρωστάει αριθμό μαθημάτων ≤ 20. Φοιτητής που βρίσκεται στο 5ο έτος σπουδών, μπορεί να αναλάβει Δ.Ε. μόνον εφόσον, κατά τη στιγμή της ανάθεσης, χρωστάει έως 80 πιστωτικές μονάδες (ECTS).*
