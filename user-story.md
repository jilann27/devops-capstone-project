## User Story

**As a** User,
**I want** to be able to create, read, update, and delete accounts,
**So that** I can manage customer account information effectively.

### Acceptance Criteria

1. Given a valid account payload, When I send a POST request to /accounts, Then a new account is created and returned with status 201.
2. Given existing accounts, When I send a GET request to /accounts, Then all accounts are returned with status 200.
3. Given an existing account ID, When I send a GET request to /accounts/{id}, Then that account is returned with status 200.
4. Given an existing account ID, When I send a PUT request to /accounts/{id}, Then the account is updated and returned with status 200.
5. Given an existing account ID, When I send a DELETE request to /accounts/{id}, Then the account is deleted with status 204.

### Definition of Done

- [ ] All acceptance criteria are met
- [ ] Code has been reviewed
- [ ] Tests have been written and pass
- [ ] Documentation has been updated
