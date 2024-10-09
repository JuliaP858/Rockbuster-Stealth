# Rockbuster Stealth LLC - Database Schema

## Objective

The goal of this project is to design and implement a database schema for Rockbuster Stealth LLC, a movie rental company, to support business intelligence (BI) operations. The schema enables the analysis of customer rental behavior, film performance, payment transactions, and store operations, helping Rockbuster make data-driven decisions to improve business performance and customer satisfaction.

## Introduction

This repository contains the database schema for Rockbuster Stealth LLC, a movie rental company. The schema outlines the structure of the database, including the relationships between the various tables, as well as detailed descriptions of the fact and dimension tables.

## Entity-Relationship Diagram (ERD)

The ERD diagram visually represents the relationships between the tables in the Rockbuster database. It shows how different entities such as Customers, Films, Rentals, and Payments interact with one another.

## Fact Tables

## Rental
Tracks rental transactions, including when a rental occurred and its return date.

## Payment
Contains information about payments made, including payment amount and related rental transactions.

# Dimension Tables

## Customer
Stores customer details, including contact information and active status.

## Film
Provides details about films such as title, description, release year, and rental rate.

## Inventory
Keeps track of inventory items, linking films to stores.

## Actor
Information about actors, including first and last names.

## Address
Stores addresses, including postal codes and phone numbers, linked to customers and staff.

## Staff
Holds information about staff members, including access credentials and store assignment.

## Store
Contains information about each store location, including the store manager and address.

## City
Information about cities and their relationship to countries.

## Country
Stores country names.

## Language
Contains the list of languages associated with films.

## Category
Details the categories for film classification.

## Film Actor
Links actors to films.

## Film Category
Links films to their respective categories.

## Usage
This schema is used to support business intelligence (BI) activities for Rockbuster Stealth LLC, helping the company analyze rentals, payments, customer activity, and other business metrics.

## Tools
SQL Postgrade
Tableau 
