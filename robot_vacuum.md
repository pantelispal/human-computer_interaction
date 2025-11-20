```mermaid
flowchart TD
    A["Goal: Καθαρισμός Λεωφορείου από Ρομπότ Σκούπα<br/> Target: 5–10 mins<br/> Success Rate: 90%"] 
        --> B["1. Προετοιμασία Ρομπότ<br/> 30–45s<br/> Error Rate: 10%"]
    A --> C["2. Επιλογή Σημείων Καθαρισμού<br/> 1–2 mins<br/> User Decision Load"]
    A --> D["3. Επιλογή Τύπου Καθαρισμού<br/> 20–30s<br/> Mode Selection"]
    A --> E["4. Εκτέλεση Καθαρισμού<br/> 3–7 mins<br/> Critical Path"]
    A --> F["5. Αναγνώριση Αντικειμένων<br/> Parallel<br/> High Sensitivity"]
    A --> G["6. Αναφορές & Ειδοποιήσεις<br/> Auto<br/> Reporting"]

    %% 1. Preparation
    B --> B1["1.1 Ενεργοποίηση Ρομπότ<br/> 5s<br/> 99% Success"]
    B --> B2["1.2 Έλεγχος Μπαταρίας<br/> 5s<br/> Indicator"]
    B --> B3["1.3 Ανάπτυξη Ποδιών για Ανάβαση στο Λεωφορείο<br/> 10–15s<br/> Motion Check"]

    %% 2. Cleaning areas
    C --> C1["2.1 Επιλογή Περιοχής (θέσεις, διάδρομος, αποσκευές)<br/> 20–30s"]
    C --> C2["2.2 Προτεραιότητα Περιοχών<br/> 10s<br/> Priority Setting"]
    C --> C3["2.3 Χρονική Διάρκεια Καθαρισμού<br/> 10s<br/> Timer"]

    %% 3. Cleaning method
    D --> D1["3.1 Επιλογή Μεθόδου (αναρρόφηση, σκούπισμα, εντοπισμός)<br/> 10s"]
    D --> D2["3.2 Ένταση Καθαρισμού<br/> 10–15s<br/> Customization"]
    D --> D3["3.3 Τελική Επιβεβαίωση Ρυθμίσεων<br/> 5s<br/> Confirmation"]

    %% 4. Execution
    E --> E1["4.1 Αυτόνομη Κίνηση στο Λεωφορείο<br/> Varies<br/> Navigation"]
    E --> E2["4.2 Καθαρισμός Σημείων<br/> Varies<br/> Action"]
    E --> E3["4.3 Επιστροφή στη Βάση<br/> 10s<br/> Docking"]

    %% 5. Object Recognition
    F --> F1["5.1 Σάρωση για Αντικείμενα<br/> Continuous<br/> Sensors"]
    F --> F2["5.2 Κατηγοριοποίηση (σκουπίδι, πολύτιμο αντικείμενο)<br/> Auto<br/> AI"]
    F --> F3["5.3 Σήμανση Ευρημάτων Σημαντικότητας<br/> Auto<br/> Alert Level"]

    %% 6. Reporting
    G --> G1["6.1 Ειδοποίηση Οδηγού<br/> Auto<br/> Message"]
    G --> G2["6.2 Ειδοποίηση Εταιρείας<br/> Auto<br/> Back-end"]
    G --> G3["6.3 Ειδοποίηση Επιβατών (αν χρειάζεται)<br/> Auto<br/> Email/SMS"]

    %% Styles
    classDef critical fill:#ffcccc,stroke:#ff0000,stroke-width:2px
    classDef warning fill:#fff3cd,stroke:#ff8800,stroke-width:2px
    classDef success fill:#d4edda,stroke:#28a745,stroke-width:2px
    classDef info fill:#cce7ff,stroke:#007bff,stroke-width:2px
    '''

