# Midas

## Purpose

Midas is a personal finance application.

## Entities

### Movement

Represents the user's financial entries. These entries can be represented as incomes or expenses.

It contains the following information:

- movement_type_id -> Define that Movement as an income or an expense
- description -> The description of the Movement
- amount -> The amount of the Movement
- date -> The date of the Movement

### MovementType

Represent the types of movement that the system supports (income and expense, for now)

It contains the following information:

- description -> The description of the MovementType

## Entity and Relationship Diagram

<img src="https://github.com/JPAMartins/midas/raw/master/docs/midas_erd.png">
