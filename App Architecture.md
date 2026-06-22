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
