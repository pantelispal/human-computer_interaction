flowchart TD
    A["Goal: Παραγγελία από Καφετέρια<br/>⏱️ Target: 3–5 mins<br/>📊 Success Rate: 92%"] 
        --> B["1. Σύνδεση σε Καφετέρια<br/>⏱️ 30–45s<br/>❌ Error Rate: 8%"]
    A --> C["2. Επιλογή Προϊόντων<br/>⏱️ 1–2 mins<br/>⚠️ Decision Complexity"]
    A --> D["3. Επιβεβαίωση Παραγγελίας<br/>⏱️ 20–30s<br/>🔄 Review Step"]
    A --> E["4. Πληρωμή με Κάρτα<br/>⏱️ 20s<br/>⚠️ Critical Path"]
    A --> F["5. Ειδοποίηση Παράδοσης<br/>⏱️ Auto<br/>😊 Satisfaction Point"]

    %% 1. Σύνδεση
    B --> B1["1.1 Επιλογή Καφετέριας<br/>⏱️ 10s<br/>🎯 95% Success"]
    B --> B2["1.2 Έλεγχος Διαθεσιμότητας<br/>⏱️ 5s<br/>ℹ️ Feedback"]
    B --> B3["1.3 Σύνδεση Λογαριασμού (προαιρετικό)<br/>⏱️ 15–20s<br/>❓ Confusion Point"]

    %% 2. Επιλογή προϊόντων
    C --> C1["2.1 Επιλογή Κατηγορίας (Καφές/Ροφήματα/Σνακ)<br/>⏱️ 10–15s<br/>🔍 Browsing"]
    C --> C2["2.2 Προσαρμογή Προϊόντος (ζάχαρη, γάλα, μέγεθος)<br/>⏱️ 20–30s<br/>🎛️ Customization"]
    C --> C3["2.3 Προσθήκη στο Καλάθι<br/>⏱️ 5s<br/>🛒 Confirmation Sound"]

    %% 3. Επιβεβαίωση
    D --> D1["3.1 Έλεγχος Περιεχομένων Καλαθιού<br/>⏱️ 10–15s<br/>🔍 Verification"]
    D --> D2["3.2 Επιλογή Στάσης Παράδοσης<br/>⏱️ 5–10s<br/>📍 Location Select"]
    D --> D3["3.3 Επιβεβαίωση Τελικού Ποσού<br/>⏱️ 5s<br/>💶 Cost Check"]

    %% 4. Πληρωμή
    E --> E1["4.1 Εισαγωγή Στοιχείων Κάρτας<br/>⏱️ 10s<br/>🔥 High Risk Step"]
    E --> E2["4.2 Έγκριση Συναλλαγής (3D Secure)<br/>⏱️ 10–15s<br/>🔐 Security"]
    E --> E3["4.3 Λήψη Απόδειξης<br/>⏱️ 3s<br/>📄 Auto-save"]

    %% 5. Ειδοποίηση
    F --> F1["5.1 Εκτίμηση Παραλαβής<br/>⏱️ Auto<br/>🕒 ETA"]
    F --> F2["5.2 Ειδοποίηση Στάσης Παράδοσης<br/>⏱️ Auto<br/>🔔 Push Notification"]
    F --> F3["5.3 Ειδοποίηση Ολοκλήρωσης<br/>⏱️ Auto<br/>🙂 Success"]

    %% Styles
    classDef critical fill:#ffcccc,stroke:#ff0000,stroke-width:2px
    classDef warning fill:#fff3cd,stroke:#ff8800,stroke-width:2px
    classDef success fill:#d4edda,stroke:#28a745,stroke-width:2px
    classDef info fill:#cce7ff,stroke:#007bff,stroke-width:2px
    
    class E,E1 critical
    class B3,C2 warning
    class B1,F3 success
    class C1,D2 info
