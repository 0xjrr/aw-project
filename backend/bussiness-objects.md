| BE Services      | Requests                                              | Responses             |
|-----------------|------------------------------------------------------------------|-----------------------------------|
| AuthService     | LoginRequest, RegisterRequest.              | User  |
| ProductInfo     | /product , /product/PRODID.                  | Product |
| StoreLocator     | /stores/{storeId} , /store   | Store.  |
| FeedbackManager | /feedback/{productId} | Feedback   |
| AccountService | /preferences/productId , /account | Product, User       |
| QRCodeScanner   | QRcode       | Product|
| NewsService   | /news/newsID , /news.     |News, NewsList|
| StatsAnalyzer     | /statistics.       | Statistics       |
