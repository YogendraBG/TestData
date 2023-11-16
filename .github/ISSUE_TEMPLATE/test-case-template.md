---
name: Test Case Template
about: Create a Test Case
title: "[TC]"
labels: TestCase
assignees: ''

---

Objective: {what's the purpose of the test}

# Environment
- [ ] Desktop 
- [ ] Service 


# Pre-conditions/Test Data

1. {environment setup}
2. {any tests that need to be run first}

# Steps

Feature: Account Holder withdraws cash
 
Scenario: Account has sufficient funds
    Given The account balance is $100
      And the card is valid
      And the machine contains enough money
     When the Account Holder requests $20
     
- [ ] Then the ATM should dispense $20
- [ ]       And the account balance should be $80
- [ ]       And the card should be returned






# Notes

* {any notes}
