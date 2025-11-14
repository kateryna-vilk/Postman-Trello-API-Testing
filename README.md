# Trello API Testing Portfolio Project (Postman)

This is a complete API test automation project for the Trello API, built using Postman. The project demonstrates a full CRUD workflow (Create, Read, Update, Delete) for core Trello features.

## Project Features 
**Full CRUD Lifecycle:** Tests cover the creation, reading, updating, and deletion of Boards, Lists, and Cards.  **Dynamic Data:** Uses **Pre-request Scripts** (JavaScript) to generate unique data (like board names) for each run, ensuring tests are repeatable.  **Environments:** Utilizes Postman Environments to manage variables like base_url, key, and token securely and efficiently.  **Test Suite:** Includes a suite of **60 automated tests** (assertions) that validate response codes, body content, and data integrity.

## How to Use 
1. Download both the **Collection** file and the **Environment** file from this repository.
2. Open Postman and import both files (Import button).
3. In the Trello APIs Environment, update the following variables with your credentials and the correct URL:

key: YOUR_KEY_HERE

token: YOUR_TOKEN_HERE

base_url: https://api.trello.com 

4. Run the entire collection to see all 60 tests pass!

## Project Previews

### 1. Test Run Results (60/60 Passed) 
<img width="1377" height="880" alt="image" src="https://github.com/user-attachments/assets/45fafd76-4a81-4c3c-9d63-f2f9f46057cb" />


### 2. Example: Pre-request Script & Variables 
<img width="1442" height="957" alt="image" src="https://github.com/user-attachments/assets/c2c3b677-70fc-40f6-a2bc-09cbd16c74cb" />


### 3. Full Collection Structure (CRUD) 
<img width="376" height="664" alt="image" src="https://github.com/user-attachments/assets/36860e41-17e2-41bd-94b1-4983dff5b00c" />
