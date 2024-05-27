| BE Services       | Requests                                   | Responses              |
|-------------------|--------------------------------------------|------------------------|
| AuthService       |  /auth/login, /auth/logout, /auth/register, /auth/validate-token, /auth/token-renewal      | User                   |
| ProductInfo       | /product, /products/{prodCategory}, /products/{productId},/products/{storeId}                  | Product                |
| StoreLocator      | /stores/{storeId}, /stores                 | Store                  |
| FeedbackManager   | /feedback/{productId}                      | Feedback               |
| AccountService    | /preferences, /account-details          | Product, User          |
| QRCodeScanner     | /scan                                    | Product                |
| NewsService       | /news/newsID, /news                        | News, NewsList         |
| StatsAnalyzer     | /statistics                                | Statistics             |