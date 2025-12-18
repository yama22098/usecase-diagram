mermaid
sequenceDiagram
    participant Client
    participant Server
    participant Database

    Client->>Server: データ要求
    Server->>Database: データ問い合わせ
    Database-->>Server: 結果返却
    Server-->>Client: データ返却