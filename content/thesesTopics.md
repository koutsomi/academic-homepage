## Διπλωματικές Εργασίες 2024-2025


1. **Μικροσυντονισμός (finetuning) πολυγλωσσικών μοντέλων για ταξινόμηση βιοϊατρικής πληροφορίας με μηδενική εκμάθηση (Zero-Shot Learning)**

    Η ταξινόμηση με μηδενική εκμάθηση (zero-shot classification) βασίζεται στο γεγονός ότι μοντέλα γενικής γλώσσας που έχουν βελτιστοποιηθεί στον συμπερασμό μπορούν να χρησιμοποιηθούν για ταξινόμηση χωρίς ειδική εκπαίδευση σε σύνολα δεδομένων. Μεγάλα μοντέλα γλώσσας έχουν ικανοποιητικά αποτελέσματα με πολύ λιγότερα εξειδικευμένα δεδομένα εκπαίδευσης σε σύγκριση με μικρότερα μοντέλα.Επίσης, προκαλεί έκπληξη το γεγονός ότι πολυγλωσσικά μοντέλα ξεπερνούν αντίστοιχα μονογλωσσικά ακόμα και σε μονογλωσσικές εργασίες. Η παρούσα εργασία θα διερευνήσει κατά πόσο ο μικροσυντονισμός (finetuning) ενός προεκπαιδευμένου μοντέλου μπορεί να βοηθήσει στην απόδοση και την ακρίβεια της τεχνικής μηδενικής εκμάθησης. Για τον μικροσυντονισμό μπορούν να χρησιμοποιηθούν σώματα βιοϊατρικών κειμένων ή και οι αναπαραστάσεις των κλάσεων ταξινόμησης (για παράδειγμα, οντολογία σε λεκτική περιγραφή). Απώτερος στόχος είναι να επιτευχθεί εξοικονόμηση πόρων και ταξινόμηση σε πραγματικό χρόνο. 

    *Ενδεικτικές πηγές-βιβλιογραφία:*
    
    - Yin, W., Hay, J., & Roth, D. (2019). Benchmarking zero-shot text classification: Datasets, evaluation and entailment approach. In Proc. of the 2019 Conference on Empirical Methods in Natural Language Processing (EMNLP 2019), pp. 3914-3923.
    - Wei, J., Bosma, M., Zhao, V. Y., Guu, K., Yu, A. W., Lester, B., ... & Le, Q. V. (2021). Finetuned language models are zero-shot learners. arXiv preprint arXiv:2109.01652. 
    - Conneau, A., Khandelwal, K., Goyal, N., Chaudhary, V., Wenzek, G., Guzmán, F., Grave, E., Ott, M., Zettlemoyer, L. and Stoyanov, V. (2019). Unsupervised cross-lingual representation learning at scale. In Proc. of the 58th Annual Meeting of the Association for Computational Linguistics (ACL), pp. 8440–8451.
    - Koutsomitropoulos, D. (2021). [Validating Ontology-based Annotations of Biomedical Resources using Zero-shot Learning](/pdf/csbio2021.pdf). In Proc. of the 12th International Conference on Computational Systems-Biology and Bioinformatics (CSBio 2021). 
    - Schmid, P. (2021) [Few-shot learning in practice: GPT-Neo and the 🤗 Accelerated Inference API.](https://huggingface.co/blog/few-shot-learning-gpt-neo-and-inference-api)

 
2. **Σημασιολογική αντιστοίχιση δεδομένων μεγάλου όγκου σε γράφους γνώσης με χρήση διανυσμάτων λέξεων**

    Με την εξάπλωση του Παγκόσμιου Ιστού και την αύξηση του διαθέσιμου αποθηκευτικού χώρου υπάρχουν σήμερα διαθέσιμα μεγάλα σύνολα δεδομένων σε αδόμητη ή ημιδομημένη μορφή, όπως κείμενα και συμβολοσειρές σε μορφή πίνακα ή csv. Η εργασία αυτή θα μελετήσει την δυνατότητα αντιστοίχισης των πληροφοριών αυτών σε δομημένους γράφους γνώσης (knowledge graphs) με χρήση μηχανικής μάθησης και συγκεκριμένα διανυσμάτων λέξεων (word embeddings). Το πρόβλημα αυτό παραμένει ανοιχτό στην πράξη κυρίως λόγω ελλιπών ή αμφίσημων δεδομένων. Η κατανόηση της σημασιακής δομής των δεδομένων αυτών θα βοηθήσει περαιτέρω στη διαδικασία ανάλυσής τους (data analytics).
   
    *Ενδεικτικές πηγές-βιβλιογραφία:*
   
    - ISWC2024 [Semantic Web Challenge](https://sem-tab-challenge.github.io/2024/) on Tabular Data to Knowledge Graph Matching
    - Proc. of the ISWC2023 [Semantic Web Challenge](https://ceur-ws.org/Vol-3557/) on Tabular Data to Knowledge Graph Matching
    - Proc. of the ISWC2022 [Semantic Web Challenge](https://ceur-ws.org/Vol-3320/) on Tabular Data to Knowledge Graph Matching
    - Teslya N, Savosin S. Matching Ontologies with Word2Vec-Based Neural Network. InInternational Conference on Computational Science and Its Applications 2019  (pp. 745-756). Springer.
    - Kolyvakis, P., Kalousis, A., Smith, B., & Kiritsis, D. (2018). Biomedical ontology alignment: an approach based on representation learning. *Journal of biomedical semantics*, *9*(1), 21.


3. **Σχεδιασμός δικτυακών διεπαφών για μεγάλα γλωσσικά μοντέλα (LLMs) και ανάπτυξη web εφαρμογών μηδενικής εκμάθησης.**  
	
  Η επιτυχία των γλωσσικών μοντέλων βασίζεται μεταξύ άλλων στο γεγονός ότι τα μοντέλα αυτά πετυχαίνουν σε μεγάλο βαθμό μεταφορά της εκμάθησης (transfer learning) ενός γνωστικού πεδίου σε ένα άλλο, συναφές ή/και μη. Οι προτροπές που χρησιμοποιούνται σε αυτά οδηγούν στη δημιουργία αυθεντικών απαντήσεων με ουσιαστικά μηδενική εκμάθηση. Ενώ όμως πολλά από αυτά διαθέτουν APIs ή είναι διαθέσιμα σε δημόσια αποθετήρια δεν υπάρχει καθιερωμένος, άμεσος τρόπος για την εξ αποστάσεως προσπέλαση και προγραμματιστική αξιοποίησή τους, ώστε να παραχθούν συμπερασμοί (inference). Η διπλωματική αυτή εργασία θα εξετάσει:

    - Τα κυριότερα διαθέσιμα LLMs, τα APIs και τα αποθετήρια, όπως το huggingface και το AzureML.
    - Πλαίσια ανάπτυξης εφαρμογών Web βασισμένα κυρίως σε JS, όπως Next.js, node και React.
    - Την ανάπτυξη πιλοτικής web εφαρμογής μηδενικής εκμάθησης, για ένα πεδίο εφαρμογής, όπως η ταξινόμηση.
   
    *Ενδεικτικές πηγές-βιβλιογραφία:*
   
    - V. Srivastava (2023). [7 Large Language Model (LLM) APIs](https://nordicapis.com/7-large-language-model-llm-apis/)
    - K. Kerr (2023). [How to build a GPT-3 App with Nextjs, React, and GitHub Copilot](https://github.blog/developer-skills/github/how-to-build-a-gpt-3-app-with-nextjs-react-and-github-copilot/)
    - Kojima, T., Gu, S. S., Reid, M., Matsuo, Y., & Iwasawa, Y. (2022). [Large language models are zero-shot reasoners. Advances in neural information processing systems (NeurIPS 2023), 35, 22199-22213.](https://proceedings.neurips.cc/paper_files/paper/2022/file/8bb0d291acd4acf06ef112099c16f326-Paper-Conference.pdf)


4. **Μελέτη και αξιολόγηση εργαλείων υποβοήθησης προγραμματισμού για ανάπτυξη εφαρμογών Ιστού με JavaScript.**

  Η πρόοδος στα τεχνητά νευρωνικά δίκτυα και τα μεγάλα γλωσσικά μοντέλα (LLMs) έχει οδηγήσει στην ανάπτυξη στοχευμένων εργαλείων που υποβοηθούν και επιταχύνουν τον προγραμματιστή στην ανάπτυξη εφαρμογών με γλώσσες προγραμματισμού. Σκοπός της εργασίας αυτής είναι να μελετήσει και να αξιολογήσει τα διαθέσιμα, βασισμένα σε ΤΝ εργαλεία υποβοήθησης και συμπλήρωσης κώδικα, στο πρόβλημα της ανάπτυξης εφαρμογών Ιστού και ιδιαίτερα αυτών που βασίζονται σε σύγχρονα JavaScript Frameworks. Τέτοια εργαλεία ενδεικτικά περιλαμβάνουν τα Copilot, codeium, double.bot, supermaven, continue.dev κ.α. Η εργασία θα συνεισφέρει και στον προσδιορισμό ενός πλαισίου αξιολόγησης τέτοιων εργαλείων με βάση τη βιβλιογραφία και κριτήρια όπως ταχύτητα, παραγωγικότητα, ποιότητα κώδικα/bugs/errors, ασφάλεια και ψυχομετρικά στοιχεία για συγκεκριμένες ομάδες, όπως τελειόφοιτοι του τμήματος (ευκολία, κατανόηση, συνέχεια, βελτίωση).

    
    *Ενδεικτικές πηγές-βιβλιογραφία:*

    - F. Alvi (2024). [AI Coding Assistants in 2024: Choosing the Right Tool for Your Development Needs.](https://opencv.org/blog/ai-coding-assistants/)
    - N. Sesti (2024). [A framework for evaluating AI code assistants.](https://blog.continue.dev/a-framework-for-evaluating-ai-code-assistants/)
    - J. Nygard (2024). [AI-assisted code generation tools.](https://oulurepo.oulu.fi/handle/10024/50546)
    - Fajkovic, E., & Rundberg, E. (2023). [The Impact of AI-generated Code on Web Development: A Comparative Study of ChatGPT and GitHub Copilot.](https://www.diva-portal.org/smash/record.jsf?pid=diva2:1769082)


6. **Χρήση τεχνικών ενσωμάτωσης στην ελληνική γλώσσα για συστήματα διαλόγου με βάση την ομιλία**  
	
	Τεχνικές ενσωμάτωσης φυσικής γλώσσας έχουν βοηθήσει σημαντικά στην επικοινωνία ανθρώπου – μηχανής, ενώ έχουν κάνει την εμφάνισή τους συστήματα διαλόγων με βάση την ομιλία Speech-To-Speech (STS). Τα συστήματα αυτά ενσωματώνουν τεχνικές αναγνώρισης ομιλίας, μετατροπής ομιλίας σε κείμενο, μετατροπής κειμένου σε ομιλία αλλά και γλωσσικά μοντέλα Στο πλαίσιο αυτό, ιδιαίτερο ενδιαφέρον παρουσιάζει η αξιοποίηση τέτοιων τεχνικών στην ελληνική γλώσσα. Πολυγλωσσικά μοντέλα αλλά και πρόσθετες υλοποιήσεις μπορούν και ενσωματώνουν τις ιδιαιτερότητες της ελληνικής γλώσσας. Σκοπός της παρούσας διπλωματικής εργασίας είναι η συστηματική ανασκόπηση αλλά και η σχεδίαση - υλοποίηση ενός συστήματος διαλόγων (STS) στην ελληνική γλώσσα. Η υλοποίηση θα μπορούσε να γίνει με χρήση γλώσσας προγραμματισμού, π.χ. Python.
 
	*Ενδεικτικές πηγές-βιβλιογραφία:*
	- Khurana, D., Koli, A., Khatter, K. et al. Natural language processing: state of the art, current trends and challenges. Multimed Tools Appl 82, 3713–3744 (2023). 
	- Papantoniou, K., Tzitzikas, Y.: NLP for the Greek Language: a brief survey. In: Proceedings of the 11th Hellenic Conference on Artificial Intelligence. ACM, pp. 101–109 (2020)
	- https://oneai.com/learn/multilingual-nlp
	- https://huggingface.co/blog/s2s_endpoint


7. **Αξιοποίηση σύγχρονων τεχνικών για την παραγωγή βιοϊατρικού κειμένου**

    Η κατανόηση κειμένων από ένα υπολογιστικό σύστημα αποτελεί πεδίο έρευνας που έχει προσεγγίσει με ιδιαίτερο ενδιαφέρον τα τελευταία χρόνια η επιστημονική κοινότητα. Τεχνικές επεξεργασίας φυσικής γλώσσας (BERT, GPT3, κ.α.) έχουν βοηθήσει στην αξιοποίησης των δεδομένων αυτών μέσω της δημιουργίας πληθώρας εφαρμογών ανάκτηση πληροφοριών, κατηγοριοποίηση, ανάλυση συναισθήματος, κ.α. Χαρακτηριστική περίπτωση αποτελεί και η παραγωγή  κειμένου  (Text Generation) που αφορά σε μια θεματική περιοχή όπως είναι π.χ. η βιοϊατρική. Η προσπάθεια αυτή θα οδηγούσε στην άντληση στοχευμένων πληροφορίων μέσα από μια αρκετά μεγάλη βάση δεδομένων όπως είναι η PubMed, βοηθώντας έτσι σημαντικά στη γρήγορη διάθεση γνώσης. Σκοπός της παρούσας διπλωματικής εργασίας είναι η σχεδίαση αλλά και η υλοποίηση ενός συστήματος παραγωγής κειμένων ιατρικού περιεχομένου. Η υλοποίηση θα μπορούσε να γίνει με χρήση γλώσσας προγραμματισμού π.χ. Python.
    
    *Ενδεικτικές πηγές-βιβλιογραφία:*
    
    - Lewis, M., Liu, Y., Goyal, N., Ghazvininejad, M., Mohamed, A., Levy, O., Stoyanov, V., & Zettlemoyer, L. (2020). BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension. ACL.
    - Celikyilmaz, A., Clark, E., & Gao, J. (2020). Evaluation of Text Generation: A Survey. ArXiv, abs/2006.14799. 
    - https://paperswithcode.com/task/text-generation    

    
    
*Οι ως διπλωματικές εργασίες εκπονούνται με επιβλέποντα τον κ. Κουτσομητρόπουλο (koutsomi@ceid) και οι 5, 6 με συνεπιβλέποντα τον υπ. Δρ. κ. Ανδριόπουλο (andriopa@ceid). Θα δοθούν μέχρι 4 εργασίες. 
Απαραίτητη η καλή γνώση Αγγλικής (για τη μελέτη της βιβλιογραφίας) και επιθυμητή η εξοικείωση με έννοιες Μηχανικής Μάθησης, Νευρωνικών Δικτύων, Αναπαράστασης Γνώσης και Τεχνολογιών Ιστού, JS, Python, TensorFlow.*

**Αιτήσεις**  για τα παραπάνω θέματα υποβάλλονται ηλεκτρονικά κατόπιν επικοινωνίας στα παραπάνω e-mail μέχρι 20/11 και περιλαμβάνουν:

- Μέχρι δύο (2) θέματα με σειρά προτίμησης.
- Αναλυτική καρτέλα βαθμολογίας, όπου θα σημειώνεται ο αριθμός μαθημάτων που απομένουν για το δίπλωμα[^1], αναμενόμενη περίοδος κτήσης αυτού και τρέχων ΜΟ βαθμολογίας.
- Σύντομο βιογραφικό σημείωμα όπου θα τεκμαίρεται η εξοικείωση με τα απαραίτητα και επιθυμητά προαπαιτούμενα (πιστοποίηση ξένης γλώσσας, παρακολούθηση σχετικού μαθήματος, σεμιναρίου, εκπόνηση εργασίας, προσωπικό ενδιαφέρον κτλ)

[^1]: *Φοιτητής που έχει διανύσει 5 έτη φοίτησης μπορεί να αναλάβει Δ. Ε. μόνον εφόσον, κατά τη στιγμή της ανάθεσης, χρωστάει αριθμό μαθημάτων ≤ 20. Φοιτητής που βρίσκεται στο 5ο έτος σπουδών, μπορεί να αναλάβει Δ.Ε. μόνον εφόσον, κατά τη στιγμή της ανάθεσης, χρωστάει έως 80 πιστωτικές μονάδες (ECTS).*
