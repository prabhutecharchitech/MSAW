# API File Structure Practice with Concern Separation

#### API
- Handle request checks
- Auth checks

#### Domain
- Business Object Definitions
- Object validation
- Domain functions

#### Application
App specific orchestrations like:
- Handling Domain entities
- Data Transfer objects
- Exceptions
- Services logic that uses Infrastructure sources like Email, Background job triggers, Serverless calls

#### Infrastructure
- Database
- Authentication
- Integration

<img width="1554" height="1754" alt="image" src="https://github.com/user-attachments/assets/bc627c58-42f6-4a32-8bdf-1b28a345a8ea" />

