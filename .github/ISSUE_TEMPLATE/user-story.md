---
name: User story
about: This template is for creating user stories
title: ''
labels: ''
assignees: ''

---

**As a** [role]  
 **I need** [function]  
 **So that** [benefit]  
   
 ### Details and Assumptions
 * [document what you know]
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given [some context]
 When [certain action is taken]
 Then [the outcome of action is observed]

Scenario: Update an existing product
Given a product exists in the catalog
When I update the product information
Then the product details are updated

Scenario: Update a non-existing product
Given the product does not exist
When I try to update the product
Then an error message is returned```
