## Διπλωματικές Εργασίες 2021-2022

1. **Μικροσυντονισμός (finetuning) πολυγλωσσικών μοντέλων για ταξινόμηση βιοϊατρικής πληροφορίας με μηδενική εκμάθηση (Zero-Shot Learning)**

    Η ταξινόμηση με μηδενική εκμάθηση (zero-shot classification) βασίζεται στο γεγονός ότι μοντέλα γενικής γλώσσας που έχουν βελτιστοποιηθεί στον συμπερασμό μπορούν να χρησιμοποιηθούν για ταξινόμηση χωρίς ειδική εκπαίδευση σε σύνολα δεδομένων. Μεγάλα μοντέλα γλώσσας έχουν ικανοποιητικά αποτελέσματα με πολύ λιγότερα εξειδικευμένα δεδομένα εκπαίδευσης σε σύγκριση με μικρότερα μοντέλα.Επίσης, προκαλεί έκπληξη το γεγονός ότι πολυγλωσσικά μοντέλα ξεπερνούν αντίστοιχα μονογλωσσικά ακόμα και σε μονογλωσσικές εργασίες. Η παρούσα εργασία θα διερευνήσει κατά πόσο ο μικροσυντονισμός (finetuning) ενός προεκπαιδευμένου μοντέλου μπορεί να βοηθήσει στην απόδοση και την ακρίβεια της τεχνικής μηδενικής εκμάθησης. Για τον μικροσυντονισμό μπορούν να χρησιμοποιηθούν σώματα βιοϊατρικών κειμένων ή και οι αναπαραστάσεις των κλάσεων ταξινόμησης (για παράδειγμα, οντολογία σε λεκτική περιγραφή). Απώτερος στόχος είναι να επιτευχθεί εξοικονόμηση πόρων και ταξινόμηση σε πραγματικό χρόνο. 


    *Ενδεικτικές πηγές-βιβλιογραφία:*
    
    - Yin, W., Hay, J., & Roth, D. (2019). Benchmarking zero-shot text classification: Datasets, evaluation and entailment approach. In Proc. of the 2019 Conference on Empirical Methods in Natural Language Processing (EMNLP 2019), pp. 3914-3923.
    - Wei, J., Bosma, M., Zhao, V. Y., Guu, K., Yu, A. W., Lester, B., ... & Le, Q. V. (2021). Finetuned language models are zero-shot learners. arXiv preprint arXiv:2109.01652. 
    - Conneau, A., Khandelwal, K., Goyal, N., Chaudhary, V., Wenzek, G., Guzmán, F., Grave, E., Ott, M., Zettlemoyer, L. and Stoyanov, V. (2019). Unsupervised cross-lingual representation learning at scale. In Proc. of the 58th Annual Meeting of the Association for Computational Linguistics (ACL), pp. 8440–8451.
    - Koutsomitropoulos, D. (2021). Validating Ontology-based Annotations of Biomedical Resources using Zero-shot Learning. In Proc. of the 12th International Conference on Computational Systems-Biology and Bioinformatics (CSBio 2021). 
    -Schmid, P. (2021) [Few-shot learning in practice: GPT-Neo and the 🤗 Accelerated Inference API.](https://huggingface.co/blog/few-shot-learning-gpt-neo-and-inference-api)

    
    
2. **Σημασιολογική αντιστοίχιση δεδομένων μεγάλου όγκου σε γράφους γνώσης με χρήση διανυσμάτων λέξεων**

    Με την εξάπλωση του Παγκόσμιου Ιστού και την αύξηση του διαθέσιμου αποθηκευτικού χώρου υπάρχουν σήμερα διαθέσιμα μεγάλα σύνολα δεδομένων σε αδόμητη ή ημιδομημένη μορφή, όπως κείμενα και συμβολοσειρές σε μορφή πίνακα ή csv. Η εργασία αυτή θα μελετήσει την δυνατότητα αντιστοίχισης των πληροφοριών αυτών σε δομημένους γράφους γνώσης (knowledge graphs) με χρήση μηχανικής μάθησης και συγκεκριμένα διανυσμάτων λέξεων (word embeddings). Το πρόβλημα αυτό παραμένει ανοιχτό στην πράξη κυρίως λόγω ελλιπών ή αμφίσημων δεδομένων. Η κατανόηση της σημασιακής δομής των δεδομένων αυτών θα βοηθήσει περαιτέρω στη διαδικασία ανάλυσής τους (data analytics).
   
    *Ενδεικτικές πηγές-βιβλιογραφία:*
   
    - Proc. of the ISWC2021 [Semantic Web Challenge](http://www.cs.ox.ac.uk/isg/challenges/sem-tab/) on Tabular Data to Knowledge Graph Matching
    - Teslya N, Savosin S. Matching Ontologies with Word2Vec-Based Neural Network. InInternational Conference on Computational Science and Its Applications 2019  (pp. 745-756). Springer.
    - Kolyvakis, P., Kalousis, A., Smith, B., & Kiritsis, D. (2018). Biomedical ontology alignment: an approach based on representation learning. *Journal of biomedical semantics*, *9*(1), 21.
    
    
3. **Συγκριτική αξιολόγηση σύγχρονων μοντέλων φυσικής γλώσσας για θεματική κατηγοριοποίηση κειμένων με αυξημένο αριθμό ετικετών**

    Τα σημερινά βαθιά μοντέλα φυσικής γλώσσας έχουν πλέον ξεπεράσει την ανθρώπινη ακρίβεια στην κατανόηση κειμένου σύμφωνα με καθιερωμένες αξιολογήσεις (benchmarks) όπως τα GLUE και SuperGLUE (https://super.gluebenchmark.com/leaderboard/). Στη διπλωματική αυτή εργασία θα πραγματοποιηθεί εφαρμογή και συγκριτική αξιολόγηση μιας σειράς σημαντικών μοντέλων και αλγορίθμων όπως τα ERNIE, T5, RoBERTa, GPT-3 κ.α. Σημαντική παράμετρος διερεύνησης αποτελεί η απόδοση των μοντέλων σε προβλήματα πολλαπλών κλάσεων πολλαπλών ετικετών (multi-class, multi-label classification) και η δυνατότητα ενσωμάτωσης αναπαράστασης γνώσης όπως αυτή αποτυπώνεται στις εννοιολογικές σχέσεις μεταξύ των ετικετών. 

    *Ενδεικτικές πηγές-βιβλιογραφία:*
   
    - Sun, Y., Wang, S., Feng, S., Ding, S., Pang, C., Shang, J., ... & Wang, H. (2021). Ernie 3.0: Large-scale knowledge enhanced pre-training for language understanding and generation. arXiv preprint arXiv:2107.02137.
    - Brown, T. B., Mann, B., Ryder, N., Subbiah, M., Kaplan, J., Dhariwal, P., ... & Amodei, D. (2020). Language models are few-shot learners. arXiv preprint arXiv:2005.14165.
    - Roberts, A. and Raffel, C. [Exploring Transfer Learning with T5: the Text-To-Text Transfer Transformer](https://ai.googleblog.com/2020/02/exploring-transfer-learning-with-t5.html)
    - Proceedings of the [9th BioASQ Workshop (BioASQ2021)](http://www.bioasq.org/workshop2021) on large-scale biomedical semantic indexing and question answering.
    - Koutsomitropoulos, D. A., & Andriopoulos, A. D. (2021). Thesaurus-based word embeddings for automated biomedical literature classification. Neural Computing and Applications, 1-14.

    
    
4. **Σύγχρονες τεχνικές για την ανάπτυξη βοηθού ανοιχτού τομέα (open-domain chatbot)**

    Τα ομιλώντα συστήματα (chatbots) με πληθώρα υλοποιήσεων συμμετέχουν ενεργά σε διάφορους τομείς της καθημερινότητας. Σημαντικό υποσύνολο, είναι αυτά που βοηθούν ικανοποιητικά σε συγκεκριμένες κατηγορίες θεμάτων, όπως παραγγελίες προϊόντων, παροχή οδηγιών μετακίνησης, ιατρικές γνωματεύσεις, κ.ά. Παρ' όλα αυτά, ιδιαίτερο ενδιαφέρουν παρουσιάζουν και όσα έχουν τη δυνατότητα γενίκευσης της συζήτησης σε διαφορετικά θέματα (Open-Domain). Σκοπός της παρούσας διπλωματικής εργασίας είναι η σχεδίαση αλλά και η υλοποίηση chatbot, όπου με τη βοήθεια τεχνικών θα μπορεί να διαχειριστεί διάλογο χρήστη-μηχανής χωρίς περιορισμό στη θεματολογία. Η ανάπτυξη θα μπορούσε να γίνει με χρήση γλώσσας προγραμματισμού πχ. Python ή οποιασδήποτε cloud πλατφόρμας πχ. Google’s DialogFlow, κλπ.
   
   *Ενδεικτικές πηγές-βιβλιογραφία:*
   
    - Adamopoulou E., Moussiades L. An Overview of Chatbot Technology. Artificial Intelligence Applications and Innovations. 2020;584:373-383. Published 2020 May 6. doi:10.1007/978-3-030-49186-4_31 
    - Roller S, Dinan E, Goyal N, Ju D, Williamson M, Liu Y, Jing Xu, Ott M, Smith EM, Boureau YL & Weston J, Recipes for Building an Open-Domain Chatbot, Proceedings of the 16th Conference of the European Chapter of the Association for Computational Linguistics: Main Volume, pp. 300-325, April 2021.
    - Adiwardana, D.D., Luong, M., So, D.R., Hall, J., Fiedel, N., Thoppilan, R., Yang, Z., Kulshreshtha, A., Nemade, G., Lu, Y., & Le, Q.V. . Towards a Human-like Open-Domain Chatbot. Published 2020, ArXiv, abs/2001.09977.


    
    
*Οι ως άνω διπλωματικές εργασίες εκπονούνται με συνεπιβλέποντα τον κ. Κουτσομητρόπουλο (koutsomi@ceid). 
Απαραίτητη η καλή γνώση Αγγλικής (για τη μελέτη της βιβλιογραφίας) και επιθυμητή η εξοικείωση με έννοιες Μηχανικής Μάθησης, Νευρωνικών Δικτύων, Αναπαράστασης Γνώσης και Τεχνολογιών Ιστού, Python, TensorFlow.*

**Αιτήσεις**  για τα παραπάνω θέματα υποβάλλονται ηλεκτρονικά κατόπιν επικοινωνίας στο παραπάνω e-mail μέχρι 22/11 και περιλαμβάνουν:

- Μέχρι δύο (2) θέματα με σειρά προτίμησης.
- Αναλυτική καρτέλα βαθμολογίας, όπου θα σημειώνεται ο αριθμός μαθημάτων που απομένουν για το δίπλωμα[^1], αναμενόμενη περίοδος κτήσης αυτού και τρέχων ΜΟ βαθμολογίας.
- Σύντομο βιογραφικό σημείωμα όπου θα τεκμαίρεται η εξοικείωση με τα απαραίτητα και επιθυμητά προαπαιτούμενα (πιστοποίηση ξένης γλώσσας, παρακολούθηση σχετικού μαθήματος, σεμιναρίου, εκπόνηση εργασίας, προσωπικό ενδιαφέρον κτλ)

[^1]: *Φοιτητής που έχει διανύσει 5 έτη φοίτησης μπορεί να αναλάβει Δ. Ε. μόνον εφόσον, κατά τη στιγμή της ανάθεσης, χρωστάει αριθμό μαθημάτων ≤ 20. Φοιτητής που βρίσκεται στο 5ο έτος σπουδών, μπορεί να αναλάβει Δ.Ε. μόνον εφόσον, κατά τη στιγμή της ανάθεσης, χρωστάει έως 80 πιστωτικές μονάδες (ECTS).*
