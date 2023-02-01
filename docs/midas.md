# Midas

## Purpose

Midas is a personal finance application.

## Entities

### Movement

Represents the user's financial entries. These entries can be represented as incomes or expenses.

It contains the following information:

- movement_type_id -> Define that Movement as an income or an expense
- user_id -> The ID of the user that registered the Movement.
- description -> The description of the Movement
- amount -> The amount of the Movement
- date -> The date of the Movement

### MovementType

Represents the types of movement that the system supports (Income and Expense, for now)

It contains the following information:

- description -> The description of the MovementType

### Income

Represents the user incomes entries. This entity inherits from the Movement entity.

It contains the following information:

- movement_id -> The id of Movement entity (father in the hierarchy relation)
- income_category_id -> The id of the Category that the Income belongs

### IncomeCategory

Represents the categories that an Income can belong to. (That entity will be register by the user. Some examples of descriptions would be: Salary, Dividends, Rent, etc)

It contains the following information:

- user_id -> The ID of the user that registered the IncomeCategory
- description -> The description of the IncomeCategory

### Expense

Represents the user expenses entries. This entity inherits from the Movement entity.

It contains the following information:

movement_id -> The id of Movement entity (father in the hierarchy relation)
expense_category_id -> The id of the Category that the Expense belongs

## Entity and Relationship Diagram

<img src="https://github.com/JPAMartins/midas/raw/master/docs/midas_erd.png">
