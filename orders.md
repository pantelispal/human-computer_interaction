flowchart TD

    A["Goal: Order from Café<br/>Target: 3–5 mins<br/>Success Rate: 92%"]

    A --> B["1. Connect to Café<br/>~40s<br/>Error Rate: 8%"]
    A --> C["2. Select Products<br/>~1–2 mins<br/>Decision Load"]
    A --> D["3. Confirm Order<br/>~30s<br/>Review Step"]
    A --> E["4. Payment<br/>~20s<br/>Critical Path"]
    A --> F["5. Delivery Notification<br/>Auto<br/>Success Point"]

    %% 1. Connect
    B --> B1["1.1 Choose Café<br/>10s<br/>Success: 95%"]
    B --> B2["1.2 Check Availability<br/>5s<br/>Feedback"]
    B --> B3["1.3 Login (Optional)<br/>20s<br/>Confusion Point"]

    %% 2. Products
    C --> C1["2.1 Select Category<br/>15s"]
    C --> C2["2.2 Customize Drink<br/>30s"]
    C --> C3["2.3 Add to Cart<br/>5s"]

    %% 3. Confirm
    D --> D1["3.1 Review Cart<br/>15s"]
    D --> D2["3.2 Choose Delivery Stop<br/>10s"]
    D --> D3["3.3 Confirm Price<br/>5s"]

    %% 4. Payment
    E --> E1["4.1 Enter Card Details<br/>10s"]
    E --> E2["4.2 Approve Transaction<br/>15s"]
    E --> E3["4.3 Receive Receipt<br/>3s"]

    %% 5. Delivery
    F --> F1["5.1 Estimated Delivery Time<br/>Auto"]
    F --> F2["5.2 Stop Notification<br/>Auto"]

    %% STYLING (same classes as template)
    classDef critical fill:#ffcccc,stroke:#ff0000,stroke-width:2px
    classDef warning fill:#fff3cd,stroke:#ff8800,stroke-width:2px
    classDef success fill:#d4edda,stroke:#28a745,stroke-width:2px
    classDef info fill:#cce7ff,stroke:#007bff,stroke-width:2px

    class E,E1 critical
    class B3,C2 warning
    class B1,F2 success
    class C1,D2 info
