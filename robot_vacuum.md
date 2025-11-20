```mermaid
flowchart TD
    A["Goal: Καθαρισμός Λεωφορείου από Ρομπότ Σκούπα<br/> Target: 5–10 mins<br/> Success Rate: 90%"]:::info
    
    A --> B["1. Προετοιμασία Ρομπότ<br/> 30–45s<br/> Error Rate: 10%"]:::warning
    A --> C["2. Επιλογή Σημείων Καθαρισμού<br/> 1–2 mins<br/> User Decision Load"]:::warning
    A --> D["3. Επιλογή Τύπου Καθαρισμού<br/> 20–30s<br/> Mode Selection"]:::warning
    A --> E["4. Εκτέλεση Καθαρισμού<br/> 3–7 mins<br/> Critical Path"]:::critical
    A --> F["5. Αναγνώριση Αντικειμένων<br/> Parallel<br/> High Sensitivity"]:::critical
    A --> G["6. Αναφορές & Ειδοποιήσεις<br/> Auto<br/> Reporting"]:::info

    %% 1. Preparation
    B --> B1["1.1 Ενεργοποίηση Ρομπότ<br/> 5s<br/> 99% Success"]:::success
    B --> B2["1.2 Έλεγχος Μπαταρίας<br/> 5s<br/> Indicator"]:::info
    B --> B3["1.3 Ανάπτυξη Ποδιών για Ανάβαση στο Λεωφορείο<br/> 10–15s<br/> Motion Check"]:::warning

    %% 2. Cleaning areas
    C --> C1["2.1 Επιλογή Περιοχής<br/> 20–30s"]:::warning
    C --> C2["2.2 Προτεραιότητα Περιοχών<br/> 10s<br/> Priority Setting"]:::warning
    C --> C3["2.3 Χρονική Διάρκεια Καθαρισμού<br/> 10s<br/> Timer"]:::info

    %% 3. Cleaning method
    D --> D1["3.1 Επιλογή Μεθόδου<br/> 10s"]:::warning
    D --> D2["3.2 Ένταση Καθαρισμού<br/> 10–15s"]:::warning
    D --> D3["3.3 Τελική Επιβεβαίωση Ρυθμίσεων<br/> 5s"]:::success

    %% 4. Execution
    E --> E1["4.1 Αυτόνομη Κίνηση στο Λεωφορείο<br/> Varies"]:::critical
    E --> E2["4.2 Καθαρισμός Σημείων<br/> Varies"]:::critical
    E --> E3["4.3 Επιστροφή στη Βάση<br/> 10s<br/> Docking"]:::success

    %% 5. Object Recognition
    F --> F1["5.1 Σάρωση για Αντικείμενα<br/> Continuous"]:::critical
    F --> F2["5.2 Κατηγοριοποίηση<br/> Auto"]:::critical
    F --> F3["5.3 Σήμανση Ευρημάτων<br/> Auto"]:::warning

    %% 6. Reporting
    G --> G1["6.1 Ειδοποίηση Οδηγού<br/> Auto"]:::info
    G --> G2["6.2 Ειδοποίηση Εταιρείας<br/> Auto"]:::info
    G --> G3["6.3 Ειδοποίηση Επιβατών<br/> Auto"]:::info

    %% Styles
    classDef critical fill:#ffcccc,stroke:#ff0000,stroke-width:2px
    classDef warning fill:#fff3cd,stroke:#ff8800,stroke-width:2px
    classDef success fill:#d4edda,stroke:#28a745,stroke-width:2px
    classDef info fill:#cce7ff,stroke:#007bff,stroke-width:2px

    '''

