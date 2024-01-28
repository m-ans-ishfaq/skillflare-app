# Skillflare - Freelancing Management System
Built in C++ as semester project for Programming Fundamentals Course
![skillflaret2](https://github.com/m-ans-ishfaq/skillflare-app/assets/150812466/c2fb4f99-5976-4afd-9e5e-c62f082ffdd9)
Demo Video: [LinkedIn Post](https://www.linkedin.com/posts/muhammad-anas-650070281_excited-to-share-my-project-skillflare-activity-7149394197840670720-IVkJ?utm_source=share&utm_medium=member_desktop)
## About
SkillFlare is a command-line interface (CLI) based freelancing platform designed to provide a seamless and efficient experience for both freelancers and businesses. This documentation serves as a comprehensive guide to help users navigate and maximize their experience on the SkillFlare platform. Whether you're looking to create a freelancer profile, post a job, browse available gigs, or manage your projects, this documentation covers it all. It provides step-by-step instructions, tips, and best practices to ensure that you can harness the full potential of SkillFlare for all your freelancing needs.
## Special Features
- Cursor Navigation
- Responsive on different screen sizes horizontally and vertically
- Dropdowns/Options menu for selection
- Password typed appears hidden by '*' astericks
- While fetching data, each tuple is validated on a deeper level
- App can't be crashed, even on Alt+F4 or Ctrl+C
- If you close app using close icon, changes wouldn't be lost
- Graphs for analytics: Frequency distribution bar (horizontal) graph, and Scatter Plot Graph
- Colorful tables for different 2D structures
## Users & Functionalities
| User Type     | Required Function to be Performed          | Result of Action Performed                                                                                                              |
|---------------|-------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| Administrator | View All Users                            | A Tabular Form of Users showing their Serial, ID, Account Type, Full Name, User Name, Account Balance, Age, Gender, Email Address, and Password.      |
|               | View All Gigs                             | A Tabular Form of Gigs showing their Serial, ID, Seller ID, Category, Subcategory, Title, Price, and Duration.                                     |
|               | View All Bank Accounts                     | A Tabular Form of Bank Accounts showing their Bank ID, Seller ID, Name, Account Number, and Branch Code.                                          |
|               | View All Credit/Debit Cards                | A Tabular Form of Cards showing their Card ID, Buyer ID, Balance, Type, Name, Number, Exp. Month, Exp. Year, and CVC.                               |
|               | View All Orders                            | A Tabular Form of Orders showing their Order ID, Gig ID, Buyer ID, Status, Task, Submission, Rating, and Review.                                  |
|               | View All Queries                           | A Tabular Form of Queries showing their Query ID, Buyer ID, Seller ID, Question, and Answer.                                                  |
|               | View Profit                                | Shows Total Profit of Administrator/Owner in $ Dollars.                                                                                 |
|               | View Users Gender Statistics               | Shows a frequency distribution horizontal bar graph representing gender statistics.                                                     |
|               | View Users Age Statistics                  | Shows a scatter plot graph representing age statistics of users.                                                                        |
|               | View Gigs Category Statistics              | Shows a frequency distribution horizontal bar graph representing gigs category statistics.                                                |
|               | View Gigs Price Statistics                 | Shows a scatter plot graph representing price statistics of gigs.                                                                       |
|               | View Orders Status Statistics              | Shows a frequency distribution horizontal bar graph representing all orders status statistics.                                           |
| Seller        | Manage Account Settings                   | User can change full name, username, age, gender, email, and password.                                                                   |
|               | View Earnings                             | Shows Total Earnings from Freelancing of Seller in $ Dollars.                                                                           |
|               | Manage Gigs                               | Seller can view all of its own gigs, create and delete them.                                                                             |
|               | Manage Orders                              | Seller can track orders, send submission, or cancel an order.                                                                            |
|               | Manage Earnings                            | Seller can link or unlink a bank account, view all banks, and transfer profit to a particular bank account.                                |
|               | Manage Queries                             | Seller can track queries asked by buyers, and reply to them.                                                                             |
| Buyer         | Manage Account Balance                    | Manage Credit Card details like Credit Card Number, CVC, Expiration Date and Year and deposits the amount to buyer account’s balance.           |
|               | Browse Through Sellers                    | Shows all Gigs in Tabular Form with selected Category.                                                                                  |
|               | Browse Through Gigs                       | Shows all Gigs in Tabular Form with selected Subcategory.                                                                               |
|               | Manage Orders                              | Shows all Gigs in Tabular Form that match with search query.                                                                            |
|               | Manage Queries                             | Takes Gig ID and shows its detail as well as seller’s details.                                                                          |
|               | Manage Account Settings                    | Takes link of order task documentation and adds order to the Database.                                                                 |
## 2D Data Structures
#### Users
| 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
|-|-|-|-|-|-|-|-|-|
| Id | Account Type | Username | Full Name | Gender | Age | Email | Password | Balance |

#### Cards
| 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
|-|-|-|-|-|-|-|-|-|
| Id | Buyer Id | Type | Number | Expiration Month | Expiration Year | CVC | Name | Balance |

#### Bank Accounts
| 0 | 1 | 2 | 3 | 4 |
|-|-|-|-|-|
| Id | Seller Id | Name | Account Number | Branch Code |

#### Gigs
| 0 | 1 | 2 | 3 | 4 | 5 | 6 |
|-|-|-|-|-|-|-|
| Id | Seller ID | Category | Subcategory | Title | Price | Duration |

#### Orders
| 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|-|-|-|-|-|-|-|-|
| Id | Gig Id | Buyer Id | Status | Task | Submission | Rating | Review |

#### Queries
| 0 | 1 | 2 | 3 | 4 |
|-|-|-|-|-|
| Id | Buyer Id | Seller Id | Question | Answer |

## App Flowchart
#### Authentication System
![image](https://github.com/m-ans-ishfaq/skillflare-app/assets/150812466/66751637-4ee4-437a-a3cf-031b367893d0)
#### Buyer & Seller Interactions
![image](https://github.com/m-ans-ishfaq/skillflare-app/assets/150812466/daf32e91-520c-47c6-a2a9-70bb268fa063)
#### For Admin
![image](https://github.com/m-ans-ishfaq/skillflare-app/assets/150812466/0c1c5ba8-5519-4877-801f-7cf210f80556)

Thanks for Reading ❤️

