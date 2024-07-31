graph TD
    A[Client<br>Web Browser] <--> |HTTP Request/Response| B[Web Server<br>e.g., Nginx]
    B <--> |WSGI| C[Flask Framework]
    C --> D[Routing]
    C --> E[View Functions]
    C --> F[Templates]
    C --> G[Static Files]
    C <-.-> |Optional| H[Database]