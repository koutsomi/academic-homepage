## Διπλωματικές Εργασίες 2023-2024

1. **Μικροσυντονισμός (finetuning) γλωσσικών μοντέλων με χρήση Oντολογιών Ιστού**

	Ο συνδυασμός των γλωσσικών μοντέλων νευρωνικών δικτύων με τις οντολογίες αποτελεί υποσχόμενο βήμα στην κατεύθυνση της ορθολογικής και εξηγήσιμης τεχνητής νοημοσύνης (XAI). Οι δομημένες αναπαραστάσεις και οι λογικές εκφραστικές δυνατότητες των οντολογιών μπορούν να τροφοδοτήσουν ένα τέτοιο μοντέλο και να ενισχύσουν τις επιδόσεις του σε συγκεκριμένες εργασίες, όπως η πρόβλεψη, η δημιουργία και η ταξινόμηση κειμένων. Η προτεινόμενη διπλωματική εργασία θα μελετήσει τις προκλήσεις και τις δυνατότητες που μπορεί να έχει ένας τέτοιος συνδυασμός και θα εξετάσει το μικρό-συντονισμό ενός γλωσσικού μοντέλου εκλογής με χρήση οντολογιών για ταξινόμηση βιοϊατρικής πληροφορίας.

	*Ενδεικτικές πηγές-βιβλιογραφία:*

    - A. Medina (2023). [An experiment in fine-tuning OpenAI with D3FEND.](https://www.linkedin.com/pulse/experiment-fine-tuning-openai-d3fend-adrian-medina-vn8gf) 
    - M. Keet (2023). [ChatGPT, deep learning and the like do not make ontologies (and the rest of AI) obsolete](https://keet.wordpress.com/2023/01/31/chatgpt-deep-learning-and-the-like-do-not-make-ontologies-and-the-rest-of-ai-obsolete/)
    - J. Pan et al (2023). [Large Language Models and Knowledge Graphs: Opportunities and Challenges](https://arxiv.org/abs/2308.06374)


2. **Μικροσυντονισμός (finetuning) πολυγλωσσικών μοντέλων για ταξινόμηση βιοϊατρικής πληροφορίας με μηδενική εκμάθηση (Zero-Shot Learning)**

    Η ταξινόμηση με μηδενική εκμάθηση (zero-shot classification) βασίζεται στο γεγονός ότι μοντέλα γενικής γλώσσας που έχουν βελτιστοποιηθεί στον συμπερασμό μπορούν να χρησιμοποιηθούν για ταξινόμηση χωρίς ειδική εκπαίδευση σε σύνολα δεδομένων. Μεγάλα μοντέλα γλώσσας έχουν ικανοποιητικά αποτελέσματα με πολύ λιγότερα εξειδικευμένα δεδομένα εκπαίδευσης σε σύγκριση με μικρότερα μοντέλα.Επίσης, προκαλεί έκπληξη το γεγονός ότι πολυγλωσσικά μοντέλα ξεπερνούν αντίστοιχα μονογλωσσικά ακόμα και σε μονογλωσσικές εργασίες. Η παρούσα εργασία θα διερευνήσει κατά πόσο ο μικροσυντονισμός (finetuning) ενός προεκπαιδευμένου μοντέλου μπορεί να βοηθήσει στην απόδοση και την ακρίβεια της τεχνικής μηδενικής εκμάθησης. Για τον μικροσυντονισμό μπορούν να χρησιμοποιηθούν σώματα βιοϊατρικών κειμένων ή και οι αναπαραστάσεις των κλάσεων ταξινόμησης (για παράδειγμα, οντολογία σε λεκτική περιγραφή). Απώτερος στόχος είναι να επιτευχθεί εξοικονόμηση πόρων και ταξινόμηση σε πραγματικό χρόνο. 

    *Ενδεικτικές πηγές-βιβλιογραφία:*
    
    - Yin, W., Hay, J., & Roth, D. (2019). Benchmarking zero-shot text classification: Datasets, evaluation and entailment approach. In Proc. of the 2019 Conference on Empirical Methods in Natural Language Processing (EMNLP 2019), pp. 3914-3923.
    - Wei, J., Bosma, M., Zhao, V. Y., Guu, K., Yu, A. W., Lester, B., ... & Le, Q. V. (2021). Finetuned language models are zero-shot learners. arXiv preprint arXiv:2109.01652. 
    - Conneau, A., Khandelwal, K., Goyal, N., Chaudhary, V., Wenzek, G., Guzmán, F., Grave, E., Ott, M., Zettlemoyer, L. and Stoyanov, V. (2019). Unsupervised cross-lingual representation learning at scale. In Proc. of the 58th Annual Meeting of the Association for Computational Linguistics (ACL), pp. 8440–8451.
    - Koutsomitropoulos, D. (2021). [Validating Ontology-based Annotations of Biomedical Resources using Zero-shot Learning](/pdf/csbio2021.pdf). In Proc. of the 12th International Conference on Computational Systems-Biology and Bioinformatics (CSBio 2021). 
    - Schmid, P. (2021) [Few-shot learning in practice: GPT-Neo and the 🤗 Accelerated Inference API.](https://huggingface.co/blog/few-shot-learning-gpt-neo-and-inference-api)


3. **Μάθηση αναπαράστασης και εφαρμογή σε γραφήματα Διασυνδεδεμένων Δεδομένων**

    Η μάθηση αναπαράστασης (representation learning) έγκειται στο γεγονός ότι δίκτυα βαθιάς μάθησης μπορεί να είναι σε θέση να μαθαίνουν την κατάλληλη αναπαράσταση για κάθε μορφή δεδομένων, ώστε μετέπειτα να μπορεί αυτή να χρησιμοποιηθεί ως είσοδος σε άλλα μοντέλα μηχανικής μάθησης. Ένα σχετικό παράδειγμα αποτελούν οι διανυσματικές αναπαραστάσεις λέξεων (word embeddings). Ταυτόχρονα, αναδύονται νέα μοντέλα νευρωνικών δικτύων, όπως τα Νευρωνικά Δίκτυα Γραφημάτων (GNNs), για την επεξεργασία δεδομένων σε μορφή γραφήματος. Η εργασία αυτή θα εξετάσει τη δυνατότητα μάθησης αναπαραστάσεων για πιο περίπλοκες μορφές και συγκεκριμένα για πληροφορίες διαθέσιμες σε μορφή γραφημάτων Διασυνδεδεμένων Δεδομένων (Linked Data graphs). Απώτερος στόχος είναι η αξιοποίηση όχι μόνο της κειμενικής πληροφορίας, αλλά και της δομής, των διασυνδέσεων και των εννοιολογικών συσχετίσεων (κλάσεις, ιεραρχίες, ιδιότητες, περιορισμοί) των δεδομένων αυτών για την αποτελεσματική αναπαράστασή τους με τεχνικές βαθιάς μάθησης.
   
    *Ενδεικτικές πηγές-βιβλιογραφία:*
   
    - Ristoski, P., Rosati, J., Di Noia, T., De Leone, R. and Paulheim, H., 2019. RDF2Vec: RDF graph embeddings and their applications. *Semantic Web*, *10*(4), pp.721-752.
    - Holter, O.M., Myklebust, E.B., Chen, J. and Jimenez-Ruiz, E., [Embedding OWL Ontologies with OWL2Vec](http://ceur-ws.org/Vol-2456/paper9.pdf). 2019
    - D. Gromann, L. E. Anke, Τ. eclerck (eds.), 2019. [Special issue on Semantic Deep Learning](https://content.iospress.com/articles/semantic-web/sw190364). *Semantic Web, vol. 10*(5), pp. 815-822.
    - Bengio, Y., Courville, A. and Vincent, P., 2013. Representation learning: A review and new perspectives. *IEEE transactions on pattern analysis and machine intelligence*, *35*(8), pp.1798-1828. [(arxiv version)](https://arxiv.org/abs/1206.5538)
    - Scarselli, F., Gori, M., Tsoi, A., Hagenbuchner, M. & Monfardini, G. 2009, 'The graph neural network model', IEEE Transactions on Neural Networks, vol. 20, no. 1, pp. 61-80.


4. **Σημασιολογική αντιστοίχιση δεδομένων μεγάλου όγκου σε γράφους γνώσης με χρήση διανυσμάτων λέξεων**

    Με την εξάπλωση του Παγκόσμιου Ιστού και την αύξηση του διαθέσιμου αποθηκευτικού χώρου υπάρχουν σήμερα διαθέσιμα μεγάλα σύνολα δεδομένων σε αδόμητη ή ημιδομημένη μορφή, όπως κείμενα και συμβολοσειρές σε μορφή πίνακα ή csv. Η εργασία αυτή θα μελετήσει την δυνατότητα αντιστοίχισης των πληροφοριών αυτών σε δομημένους γράφους γνώσης (knowledge graphs) με χρήση μηχανικής μάθησης και συγκεκριμένα διανυσμάτων λέξεων (word embeddings). Το πρόβλημα αυτό παραμένει ανοιχτό στην πράξη κυρίως λόγω ελλιπών ή αμφίσημων δεδομένων. Η κατανόηση της σημασιακής δομής των δεδομένων αυτών θα βοηθήσει περαιτέρω στη διαδικασία ανάλυσής τους (data analytics).
   
    *Ενδεικτικές πηγές-βιβλιογραφία:*
   
    - Proc. of the ISWC2022 [Semantic Web Challenge](http://www.cs.ox.ac.uk/isg/challenges/sem-tab/) on Tabular Data to Knowledge Graph Matching
    - Teslya N, Savosin S. Matching Ontologies with Word2Vec-Based Neural Network. InInternational Conference on Computational Science and Its Applications 2019  (pp. 745-756). Springer.
    - Kolyvakis, P., Kalousis, A., Smith, B., & Kiritsis, D. (2018). Biomedical ontology alignment: an approach based on representation learning. *Journal of biomedical semantics*, *9*(1), 21.


5. **Χρήση τεχνικών ενσωμάτωσης στην ελληνική γλώσσα**  
	
	Είναι γενικώς παραδεκτό ότι η επεξεργασία κειμένων με χρήση τεχνικών ενσωμάτωσης φυσικής γλώσσας συνεχίζει και προκαλεί έντονα το ενδιαφέρον των επιστημόνων. Πολλές ερευνητικές ομάδες έχουν δημιουργήσει αλγορίθμους, μεθόδους αλλά και εργαλεία έχοντας ως βάση αγγλικά κείμενα, με σκοπό την βελτιστοποίηση της επικοινωνίας ανθρώπου -  υπολογιστή. Την πολυπλοκότητα του προβλήματος ενισχύουν και  τα διαφορετικά είδη γλωσσών. Στο πλαίσιο αυτό, ιδιαίτερο ενδιαφέρον παρουσιάζει η διάχυση τέτοιων τεχνικών, στην επεξεργασία ελληνικών κειμένων. Πολυγλωσσικά μοντέλα αλλά και πρόσθετες υλοποιήσεις μπορούν και ενσωματώνουν τις ιδιαιτερότητες της ελληνικής γλώσσας. Σκοπός της παρούσας διπλωματικής εργασίας είναι η συστηματική ανασκόπηση αλλά και η σχεδίαση - υλοποίηση ενός συστήματος επεξεργασίας κειμένων ελληνικής γλώσσας. Η υλοποίηση θα μπορούσε να γίνει με χρήση γλώσσας προγραμματισμού π.χ. Python.
 
	*Ενδεικτικές πηγές-βιβλιογραφία:*
	- Khurana, D., Koli, A., Khatter, K. et al. Natural language processing: state of the art, current trends and challenges. Multimed Tools Appl 82, 3713–3744 (2023). 
	- Papantoniou, K., Tzitzikas, Y.: NLP for the Greek Language: a brief survey. In: Proceedings of the 11th Hellenic Conference on Artificial Intelligence. ACM, pp. 101–109 (2020)
	- https://oneai.com/learn/multilingual-nlp

   
6. **Αξιοποίηση σύγχρονων τεχνικών για την παραγωγή βιοϊατρικού κειμένου**

    Η κατανόηση κειμένων από ένα υπολογιστικό σύστημα αποτελεί πεδίο έρευνας που έχει προσεγγίσει με ιδιαίτερο ενδιαφέρον τα τελευταία χρόνια η επιστημονική κοινότητα. Τεχνικές επεξεργασίας φυσικής γλώσσας (BERT, GPT3, κ.α.) έχουν βοηθήσει στην αξιοποίησης των δεδομένων αυτών μέσω της δημιουργίας πληθώρας εφαρμογών ανάκτηση πληροφοριών, κατηγοριοποίηση, ανάλυση συναισθήματος, κ.α. Χαρακτηριστική περίπτωση αποτελεί και η παραγωγή  κειμένου  (Text Generation) που αφορά σε μια θεματική περιοχή όπως είναι π.χ. η βιοϊατρική. Η προσπάθεια αυτή θα οδηγούσε στην άντληση στοχευμένων πληροφορίων μέσα από μια αρκετά μεγάλη βάση δεδομένων όπως είναι η PubMed, βοηθώντας έτσι σημαντικά στη γρήγορη διάθεση γνώσης. Σκοπός της παρούσας διπλωματικής εργασίας είναι η σχεδίαση αλλά και η υλοποίηση ενός συστήματος παραγωγής κειμένων ιατρικού περιεχομένου. Η υλοποίηση θα μπορούσε να γίνει με χρήση γλώσσας προγραμματισμού π.χ. Python.
    
    *Ενδεικτικές πηγές-βιβλιογραφία:*
    
    - Lewis, M., Liu, Y., Goyal, N., Ghazvininejad, M., Mohamed, A., Levy, O., Stoyanov, V., & Zettlemoyer, L. (2020). BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension. ACL.
    - Celikyilmaz, A., Clark, E., & Gao, J. (2020). Evaluation of Text Generation: A Survey. ArXiv, abs/2006.14799. 
    - https://paperswithcode.com/task/text-generation


7. **Δημιουργία Μοντέλων Μηχανικής Μάθησης για την κατηγοριοποίηση της Άνοιας και άλλων Νευροεκφυλιστικών Παθήσεων.**

    Δεδομένου ότι ο πρωταρχικός παράγοντας κινδύνου για την άνοια είναι η ηλικία, η συνεχιζόμενη αύξηση του προσδόκιμου ζωής και η γήρανση του πληθυσμού αυξάνουν επίσης την πιθανότητα να αναπτύξουν οι άνθρωποι αυτή την πάθηση.
    Ο κύριος στόχος της πρότασης είναι διττός. Πρώτον, να αναπτυχθεί μια εφαρμογή για συλλογή δεδομένων, από γνωστές (ελεύθερες) βάσεις δεδομένων. Σε πρώτη φάση θα εστιάσουμε σε δεδομένα από βιο-σήματα από μια ομάδα-στόχο, τα οποία έχουν αξιολογηθεί ως πάσχοντα από  άνοια ή είναι υποψήφια να αναπτύξουν άνοια (χρησιμοποιώντας μαγνητικές τομογραφίες και/ή εξετάσεις ΗΕΓ). Επίσης, θα εξεταστεί η χρήση δεδομένων γονιδιακής ανάλυσης και τυχόν βιοδεικτών, που σχετίζονται με τη νόσο. Χρησιμοποιώντας αυτές τις αξιολογήσεις, θα χρησιμοποιηθούν τεχνικές Μηχανικής Μάθησης (Πολυεπίπεδα Νευρωνικά Δίκτυα (MLPs), Νευρωνικά Δίκτυα Βαθιάς Μάθησης  (DNNs), κ.α.)  για να ομαδοποιήσει τους ασθενείς στους τέσσερις κύριους τύπους άνοιας ή σαν υποψήφια άτομα για να αναπτύξουν άνοια. Η εφαρμογή που θα αναπτυχθεί θα περιλαμβάνει την συλλογή και επεξεργασία δεδομένων που θα χρησιμοποιηθούν για την εκπαίδευση των μοντέλων Μηχανικής Μάθησης. Πρέπει να σημειωθεί ότι τα παραπάνω δεδομένα είναι είτε στατικά (MRI, fMRI, Βιοδείκτες), είτε δυναμικά (ΗΕΓ, HRV). Σε αυτή την έρευνα για πρώτη φορά θα κατασκευαστούν μοντέλα ΜΜ, τα οποία θα συνδυάζουν τόσο στατικά όσο και δυναμικά δεδομένα.
    Προαπαιτούμενα: Τεχνητή Νοημοσύνη, Υπολογιστική Νοημοσύνη, εμπειρία σε Python, καλή γνώση της Αγγλικής.
    

    *Ενδεικτικές πηγές-βιβλιογραφία:*
    
    - Ziad Sankaria, Hojjat Adeli, Probabilistic neural networks for diagnosis of Alzheimer’s disease using conventional and wavelet coherence, Journal of Neuroscience Methods 197 (2011) 165–170.
    - Camillo Imbimbo et al. Heart rate variability and cognitive performance in adults with cardiovascular risk, Cerebral Circulation - Cognition and Behavior 3 (2022) 100136.
    - S. Buss, et al., Objective cardiac markers in dementia: Results from the Kerala-Einstein study, Int J Cardiol. 2013 July 31; 167(2): 595–596.
    - M. Munsif, M. Ullah, B. Ahmad, M. Sajjad, and F. Alaya Cheikh, Monitoring Neurological Disorder Patients via Deep Learning based Facial Expressions Analysis, 18th Int. Conf. on Artificial Intelligence Applications and Innovations, Crete-Greece, June 17-20, 2022.
    - A. Majeed, B. Marwick, H. Yu, H. Fadavi, and M. Tavakoli, Ophthalmic Biomarkers for Alzheimer’s Disease: A Review, Frontiers in Aging Neuroscience, 574, 2021.
    - S. Dash, S. K. Shakyawar, M. Sharma, and S. Kaushik, Big data in healthcare: management, analysis and future prospects. Journal of Big Data, 6(1), 1-25, 2019.
    - J. Loucks, D. Stewart, A. Bucaille, and G. Crossan, Wearable technology in health care: getting better all the time, 2022. TMT Predictions.
    - Explainable Artificial Intelligence (XAI): Concepts, Taxonomies, Opportunities and Challenges toward Responsible AI,” ScienceDirect, June 2020.

8. **Δημιουργία Μοντέλων Μηχανικής Μάθησης για την πρόβλεψη της Άνοιας και άλλων Νευροεκφυλιστικών Παθήσεων.**

    Δεδομένου ότι ο πρωταρχικός παράγοντας κινδύνου για την άνοια είναι η ηλικία, η συνεχιζόμενη αύξηση του προσδόκιμου ζωής και η γήρανση του πληθυσμού αυξάνουν επίσης την πιθανότητα να αναπτύξουν οι άνθρωποι αυτή την πάθηση.
    Ο κύριος στόχος της πρότασης είναι διττός. Πρώτον, να αναπτυχθεί μια εφαρμογή για συλλογή δεδομένων, από γνωστές (ελεύθερες) βάσεις δεδομένων. Σε πρώτη φάση θα εστιάσουμε σε δεδομένα από βιο-σήματα από μια ομάδα-στόχο, τα οποία έχουν αξιολογηθεί ως πάσχοντα από  άνοια ή είναι υποψήφια να αναπτύξουν άνοια (χρησιμοποιώντας μαγνητικές τομογραφίες και/ή εξετάσεις ΗΕΓ1). Επίσης, θα εξεταστεί η χρήση δεδομένων γονιδιακής ανάλυσης και τυχόν βιοδεικτών, που σχετίζονται με τη νόσο. Χρησιμοποιώντας αυτές τις αξιολογήσεις, θα χρησιμοποιηθούν τεχνικές Μηχανικής Μάθησης (Πολυεπίπεδα Νευρωνικά Δίκτυα (MLPs), Νευρωνικά Δίκτυα Βαθιάς Μάθησης  (DNNs), κ.α.)  για τη δημιουργία μοντέλων, σε μία κατηγορία που θα επιλεγεί, με βάση τα διαθέσιμα δεδομένα. Δεύτερον, θα αναπτυχθεί μια ειδική εφαρμογή, που θα περιλαμβάνει την συλλογή και επεξεργασία δεδομένων που θα χρησιμοποιηθούν για την εκπαίδευση των μοντέλων Μηχανικής Μάθησης. Πρέπει να σημειωθεί ότι τα παραπάνω δεδομένα είναι είτε στατικά (MRI, fMRI, Βιοδείκτες), είτε δυναμικά (ΗΕΓ, HRV). Σε αυτή την έρευνα για πρώτη φορά θα κατασκευαστούν μοντέλα ΜΜ, τα οποία θα συνδυάζουν τόσο στατικά όσο και δυναμικά δεδομένα. 
    Προαπαιτούμενα: Τεχνητή Νοημοσύνη, Υπολογιστική Νοημοσύνη, εμπειρία σε Python, καλή γνώση της Αγγλικής.

    
    *Ενδεικτικές πηγές-βιβλιογραφία:*
    
    - Ziad Sankaria, Hojjat Adeli, Probabilistic neural networks for diagnosis of Alzheimer’s disease using conventional and wavelet coherence, Journal of Neuroscience Methods 197 (2011) 165–170.
    - Camillo Imbimbo et al. Heart rate variability and cognitive performance in adults with cardiovascular risk, Cerebral Circulation - Cognition and Behavior 3 (2022) 100136.
    - S. Buss, et al., Objective cardiac markers in dementia: Results from the Kerala-Einstein study, Int J Cardiol. 2013 July 31; 167(2): 595–596.
    - M. Munsif, M. Ullah, B. Ahmad, M. Sajjad, and F. Alaya Cheikh, Monitoring Neurological Disorder Patients via Deep Learning based Facial Expressions Analysis, 18th Int. Conf. on Artificial Intelligence Applications and Innovations, Crete-Greece, June 17-20, 2022.
    - A. Majeed, B. Marwick, H. Yu, H. Fadavi, and M. Tavakoli, Ophthalmic Biomarkers for Alzheimer’s Disease: A Review, Frontiers in Aging Neuroscience, 574, 2021.
    - S. Dash, S. K. Shakyawar, M. Sharma, and S. Kaushik, Big data in healthcare: management, analysis and future prospects. Journal of Big Data, 6(1), 1-25, 2019.
    - J. Loucks, D. Stewart, A. Bucaille, and G. Crossan, Wearable technology in health care: getting better all the time, 2022. TMT Predictions.
    - Explainable Artificial Intelligence (XAI): Concepts, Taxonomies, Opportunities and Challenges toward Responsible AI,” ScienceDirect, June 2020.

    
    
*Οι διπλωματικές εργασίες 1-6 εκπονούνται με επιβλέποντα τον κ. Κουτσομητρόπουλο (koutsomi@ceid). Οι διπλωματικές εργασίες 7-8 εκπονούνται με επιβλέποντα τον κ. Λυκοθανάση (likothan@ceid).
Απαραίτητη η καλή γνώση Αγγλικής (για τη μελέτη της βιβλιογραφίας) και επιθυμητή η εξοικείωση με έννοιες Μηχανικής Μάθησης, Νευρωνικών Δικτύων, Αναπαράστασης Γνώσης, Python, TensorFlow.*

**Αιτήσεις**  για τα παραπάνω θέματα υποβάλλονται ηλεκτρονικά κατόπιν επικοινωνίας στο koutsomi@ceid μέχρι 17/11 και περιλαμβάνουν:

- Μέχρι δύο (2) θέματα με σειρά προτίμησης.
- Αναλυτική καρτέλα βαθμολογίας, όπου θα σημειώνεται ο αριθμός μαθημάτων που απομένουν για το δίπλωμα[^1], αναμενόμενη περίοδος κτήσης αυτού και τρέχων ΜΟ βαθμολογίας.
- Σύντομο βιογραφικό σημείωμα όπου θα τεκμαίρεται η εξοικείωση με τα απαραίτητα και επιθυμητά προαπαιτούμενα (πιστοποίηση ξένης γλώσσας, παρακολούθηση σχετικού μαθήματος, σεμιναρίου, εκπόνηση εργασίας, προσωπικό ενδιαφέρον κτλ)

[^1]: *Φοιτητής που έχει διανύσει 5 έτη φοίτησης μπορεί να αναλάβει Δ. Ε. μόνον εφόσον, κατά τη στιγμή της ανάθεσης, χρωστάει αριθμό μαθημάτων ≤ 20. Φοιτητής που βρίσκεται στο 5ο έτος σπουδών, μπορεί να αναλάβει Δ.Ε. μόνον εφόσον, κατά τη στιγμή της ανάθεσης, χρωστάει έως 80 πιστωτικές μονάδες (ECTS).*
