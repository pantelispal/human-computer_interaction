flowchart TD
    A["Goal: Παραγγελία Καφέ<br/> Target: 3–5 mins<br/> Success Rate: 95%"]:::success
        --> B["1. Αναγνώριση Χρήστη & Πρόσβαση<br/> 10–20s<br/> User Friction Point"]:::info
    A --> C["2. Επιλογή Καφετέριας (Geo-Aware)<br/> 5–10s<br/> Feasibility Check"]:::success
    A --> D["3. Επιλογή Προϊόντων<br/> 1–2 mins<br/> Customization"]:::warning
    A --> E["4. Επιβεβαίωση Παραγγελίας<br/> 15–20s<br/> Location Check"]
    A --> F["5. Πληρωμή με Κάρτα<br/> 15–25s<br/> Critical Path"]:::critical
    A --> G["6. Ειδοποίηση Παράδοσης<br/> Auto<br/> Satisfaction Point"]
    
    %% 1. Αναγνώριση
    B --> B1["1.1 Επιλογή: Login / Guest<br/> 5s"]
    B --> B2["1.2 Εισαγωγή Credentials / Επαφής<br/> 10-15s<br/> Error Handling"]:::warning
    
    %% 2. Επιλογή Καφετέριας
    C --> C1["2.1 Έλεγχος Geo-Awareness<br/> 3s<br/> Proactive Error Prevention"]:::success
    C --> C2["2.2 Επιβεβαίωση Προτεινόμενης Καφετέριας<br/> 5s"]
    
    %% 3. Επιλογή προϊόντων
    D --> D1["3.1 Επιλογή Κατηγορίας<br/> 10s"]
    D --> D2["3.2 Προσαρμογή Προϊόντος (Visual Builder)<br/> 20–30s"]:::warning
    D --> D3["3.3 Προσθήκη στο Καλάθι<br/> 5s"]
    
    %% 4. Επιβεβαίωση
    E --> E1["4.1 Έλεγχος Καλαθιού<br/> 10s"]
    E --> E2["4.2 Επιβεβαίωση Στάσης Παράδοσης<br/> 5s<br/> Location Check"]:::info
    
    %% 5. Πληρωμή
    F --> F1["5.1 Εισαγωγή/Επιλογή Στοιχείων Κάρτας<br/> 10s<br/> High Risk Step"]:::critical
    F --> F2["5.2 Έγκριση Συναλλαγής<br/> 5-10s<br/> Security"]
    F --> F3["5.3 Λήψη Απόδειξης<br/> 3s"]
    
    %% 6. Ειδοποίηση
    G --> G1["6.1 Εκτίμηση Παραλαβής (ETA)<br/> Auto"]
    G --> G2["6.2 Ειδοποίηση Στάσης Παράδοσης<br/> Auto<br/> Push Notification"]
    
    %% Styles
    classDef critical fill:#ffcccc,stroke:#ff0000,stroke-width:2px
    classDef warning fill:#fff3cd,stroke:#ff8800,stroke-width:2px
    classDef success fill:#d4edda,stroke:#28a745,stroke-width:2px
    classDef info fill:#cce7ff,stroke:#007bff,stroke-width:2px

