# codenameJDAL_FrontEnd
Client Web Frontend for the project

# Requirements 1.0
1. UI Page
    1. View service providers
    2. Search Service Providers
    3. Display reviews for service providers
    4. Create New Accounts (for users)
    5. Allow users to write reviews.
    6.Allow each user to submit one star rating per service provider.
2. Admin Page
    1. Add new service provider
    2. Remove service provider.
    3. View all users.
    4. Search users.
    5. Search Service provider listings.
    6. Remove/Block User accounts(via email).
## DATABASE TABLES
### SERVICE_PROVIDERS
ID | Provider_Name | Description | Contact | Service_category | Region_Location | Service_Price | Member_Price
---|---------------|-------------|---------|------------------|-----------------|---------------|-------------

### USERS
ID | F_NAME | L_NAME | EMAIL | 
---|----------|--------|-------|

### REVIEWS
ID | USERS_ID | PROVIDER_ID | COMMENT | STARS
---|----------|-------------|---------|------
