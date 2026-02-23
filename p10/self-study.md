# Meeting 10: Self-Study Materials
## Databases & Data Management

---

## Overview

This self-study package supports your learning from Meeting 10. Complete these activities before the next class to reinforce vocabulary, grammar, and skills.

| Component | Estimated Time | Priority |
|-----------|----------------|----------|
| A. Vocabulary Self-Study | 25-30 minutes | Required |
| B. Grammar Self-Study | 30-40 minutes | Required |
| C. Extension Reading | 20-25 minutes | Recommended |
| D. Extension Listening | 25-30 minutes | Optional |
| E. Writing Task | 60-75 minutes | Required (Homework) |

---

## A. VOCABULARY SELF-STUDY

### A1. Flashcard List (Quizlet-Ready Format)

Copy and paste this list into Quizlet or your preferred flashcard app.

```
Term | Definition | Example Sentence
-----|------------|------------------
Database | Organized collection of structured data stored electronically | We store all customer information in a centralized database.
Table | Structure that organizes data in rows and columns (also called relation) | The products table contains information about all items we sell.
Record | Single entry in a database table (also called row or tuple) | Each customer record includes name, email, and phone number.
Field | Individual data element in a table (also called column or attribute) | The "email" field stores customer email addresses.
Primary Key | Unique identifier for each record in a table | We use customer ID as the primary key in the customers table.
Foreign Key | Field that references the primary key in another table | The order table uses customer ID as a foreign key.
Index | Database structure that improves speed of data retrieval | Creating an index on product ID makes searches much faster.
Schema | Blueprint or logical structure of a database | The database schema shows all tables and their relationships.
SQL | Structured Query Language - language for managing databases | We use SQL to query data from multiple tables.
Query | Request for data from a database | This query retrieves all orders from last month.
SELECT | SQL command to retrieve data from tables | Use SELECT to get specific columns from a table.
INSERT | SQL command to add new records to a table | INSERT new customer information into the database.
UPDATE | SQL command to modify existing records | UPDATE the stock quantity when products are sold.
DELETE | SQL command to remove records from a table | DELETE outdated records from the archive table.
JOIN | SQL operation to combine data from multiple tables | Use JOIN to connect customers with their orders.
Backup | Copy of data for recovery purposes | We run automated backups every night at midnight.
Restore | Recover data from a backup | We had to restore the database from yesterday's backup.
Migration | Process of moving data to a new system | The cloud migration will take three weeks to complete.
Replication | Duplicating data across multiple servers | Database replication ensures data availability.
Transaction | Unit of database operation that must complete entirely | Each purchase is processed as a single transaction.
Normalization | Organizing data to reduce redundancy | Database normalization improves data integrity.
Redundancy | Unnecessary repetition of data | Normalization helps eliminate data redundancy.
DBA | Database Administrator - professional who manages databases | The DBA optimizes query performance regularly.
store IN | Save data within a database or location | Store all sensitive data IN encrypted format.
connect TO | Establish link with a server or system | The application connects TO the database server.
```

### A2. Vocabulary Practice Exercises

**Exercise 1: Complete the Sentences**

Choose the correct word from the box to complete each sentence.

```
[ schema | backup | query | foreign key | index | normalize | restore | replication ]
```

1. We created an _____________ on the email field to speed up customer searches.
2. The database _____________ shows how all tables are connected to each other.
3. If the server crashes, we can _____________ the data from last night's backup.
4. Database _____________ ensures that our data is available even if one server fails.
5. Each order table record contains a _____________ that links to the customer table.
6. We should _____________ the database to eliminate duplicate customer information.
7. Run this SQL _____________ to find all products with low stock levels.
8. Always create a _____________ before making major changes to the database.

**Exercise 2: Match SQL Commands to Their Functions**

| SQL Command | Function |
|-------------|----------|
| 1. SELECT | a. Remove records from a table |
| 2. INSERT | b. Modify existing data |
| 3. UPDATE | c. Add new records |
| 4. DELETE | d. Combine data from multiple tables |
| 5. JOIN | e. Retrieve data from tables |

**Exercise 3: Preposition Collocations**

Complete each sentence with the correct preposition.

1. We store customer data _______ a secure database.
2. The system connects _______ the server using SSL encryption.
3. Query the product information _______ the inventory table.
4. Insert new records _______ the orders table.
5. Back up all files _______ the cloud automatically.
6. The results are sorted _______ alphabetical order.
7. Database maintenance runs _______ midnight every day.
8. Filter the data _______ customer location.
9. All passwords are saved _______ encrypted format.
10. Retrieve archived records _______ the backup server.

---

## B. GRAMMAR SELF-STUDY

### B1. Grammar Summary: Reported Speech & Prepositions

#### What is Reported Speech?

Reported speech (also called indirect speech) is used to tell someone what another person said, without using their exact words.

**Direct Speech:** "The database is running smoothly."
**Reported Speech:** The DBA said (that) the database was running smoothly.

#### Key Changes in Reported Speech

**1. Tense Backshifting**

| Direct Speech | Reported Speech |
|---------------|-----------------|
| Present Simple (is/are) | Past Simple (was/were) |
| Present Continuous (is/are...ing) | Past Continuous (was/were...ing) |
| Present Perfect (has/have) | Past Perfect (had) |
| Past Simple (did) | Past Perfect (had done) |
| Will | Would |
| Can | Could |
| May | Might |
| Must | Had to |

**IT Examples:**
- Direct: "We **need** more storage."
  - Reported: They said they **needed** more storage.
- Direct: "The backup **is running**."
  - Reported: He mentioned the backup **was running**.
- Direct: "I **will** migrate the data."
  - Reported: She said she **would** migrate the data.

**2. Pronouns Change**

- I → he/she
- We → they
- You → I/we (depending on context)
- My → his/her
- Our → their

**3. Time/Place Words Change**

| Direct Speech | Reported Speech |
|---------------|-----------------|
| today | that day |
| tomorrow | the next day / the following day |
| yesterday | the day before / the previous day |
| this week/month | that week/month |
| next week | the following week |
| last week | the previous week |
| here | there |
| this | that |

**4. Reporting Verbs**

Common reporting verbs in database/IT contexts:
- **said/told**: "The client said that..." / "They told me that..."
- **explained**: "The DBA explained that normalization reduces redundancy."
- **mentioned**: "They mentioned that the migration would take hours."
- **reported**: "She reported that the backup had failed."
- **asked**: "The client asked whether we could optimize the query."
- **wanted to know**: "They wanted to know if the data was secure."
- **recommended/advised**: "The consultant recommended using indexes."
- **warned**: "He warned us not to modify the production database."

**Important:**
- Use "said that" OR "told (someone) that"
- ✓ She said that... / She told me that...
- ✗ She told that... / She said me that...

#### Reported Questions

**Yes/No Questions:** Use if/whether
- Direct: "Can you optimize the query?"
- Reported: She asked **if/whether** I could optimize the query.

**Wh- Questions:** Keep the question word, change to statement order
- Direct: "Where is the data stored?"
- Reported: They asked where the data **was stored**. (NOT: where was the data stored)

---

#### Prepositions in Database Contexts

| Preposition | Usage | Example |
|-------------|-------|---------|
| **IN** | Inside a database, system, format | Store data IN a database |
| **ON** | On a server, device, field | Save files ON the server |
| **AT** | At a specific location/time | Data stored AT this location |
| **TO** | Direction/connection | Connect TO the database |
| **FROM** | Source of data | Query FROM the table |
| **INTO** | Movement into something | Insert records INTO the table |

**ALWAYS use these prepositions:**
- ✓ Store data **IN** a database
- ✓ Connect **TO** a server
- ✓ Query **FROM** a table
- ✓ Insert records **INTO** the database
- ✓ Back up **TO** the cloud
- ✓ Based **ON** criteria
- ✓ Filter **BY** category
- ✓ Sort **IN** order (ascending/descending)
- ✓ Run backups **AT** midnight
- ✓ Save **ON** the server
- ✓ Retrieve **FROM** the backup

**NEVER use:**
- ✗ Store data ON database
- ✗ Connect WITH database
- ✗ Insert TO table
- ✗ Back up ON cloud

---

### B2. Grammar Reference

📖 **Murphy's English Grammar in Use (2019 Edition)**

| Topic | Units | Key Points |
|-------|-------|------------|
| Reported Speech (statements) | Unit 47 | Tense changes, that-clauses |
| Reported Questions | Unit 48 | if/whether, question word order |
| Prepositions of Time | Units 129-130 | at, in, on for time |
| Prepositions of Place | Units 131-132 | at, in, on for place |
| Other Prepositions | Units 133-136 | by, with, about, etc. |

**Recommended Study Order:**
1. Read Unit 47 (Reported Speech — statements)
2. Complete exercises 47.1 - 47.4
3. Read Unit 48 (Reported Questions)
4. Complete exercises 48.1 - 48.3
5. Review Units 129-136 (Prepositions)
6. Complete selected exercises focusing on technical contexts

---

### B3. Additional Grammar Practice

**Exercise 1: Transform to Reported Speech**

Change these direct statements to reported speech.

1. "The database is running slowly." (The DBA said...)
   → _________________________________________________________________

2. "We will migrate all data next month." (They told us...)
   → _________________________________________________________________

3. "I can optimize this query." (She mentioned...)
   → _________________________________________________________________

4. "The backup has completed successfully." (He reported...)
   → _________________________________________________________________

5. "We are implementing new security measures." (The team explained...)
   → _________________________________________________________________

**Exercise 2: Reported Questions**

Transform these questions to reported speech.

1. "Where is the data stored?" (The client asked...)
   → _________________________________________________________________

2. "Can you restore the database?" (He wanted to know...)
   → _________________________________________________________________

3. "How many records are in the table?" (She asked...)
   → _________________________________________________________________

4. "Will the migration finish by Friday?" (They asked...)
   → _________________________________________________________________

5. "What backup schedule do you recommend?" (The manager asked...)
   → _________________________________________________________________

**Exercise 3: Prepositions Practice**

Complete with the correct preposition.

1. All customer data is stored _______ the main database.
2. We connect _______ the server using a secure VPN.
3. Query the order information _______ this table.
4. Insert the new products _______ the inventory database.
5. Backups run automatically _______ 2:00 AM every morning.
6. We back up all critical files _______ the cloud daily.
7. The query filters results _______ product category.
8. This report is based _______ last quarter's sales data.
9. Sort the records _______ descending order by date.
10. We can retrieve historical data _______ the archive server.

---

## C. EXTENSION READING

### Recommended Articles

**Article 1: "Introduction to Relational Databases"**
- Source: Oracle Learning Library
- URL: https://www.oracle.com/database/what-is-a-relational-database/
- Time: 10 minutes
- Focus: Understanding table relationships and SQL basics

**Article 2: "Database Normalization Explained"**
- Source: Microsoft SQL Server Documentation
- URL: https://docs.microsoft.com/en-us/sql/relational-databases/
- Time: 12 minutes
- Focus: Why and how to organize data efficiently

**Article 3: "Best Practices for Database Backup Strategies"**
- Source: PostgreSQL Documentation
- URL: https://www.postgresql.org/docs/current/backup.html
- Time: 8 minutes
- Focus: Different backup methods and recovery procedures

### Reading Comprehension Questions

After reading the articles, answer these questions:

1. What is the main advantage of using a relational database over spreadsheets?
2. Explain the concept of a foreign key in your own words.
3. According to the articles, why is regular database backup important?
4. What is the difference between full backup and incremental backup?
5. How does normalization help improve database performance?

---

## D. EXTENSION LISTENING

### Recommended Videos/Podcasts

**Video 1: "SQL Tutorial for Beginners"**
- Platform: YouTube (Programming with Mosh)
- Search: "SQL Tutorial for Beginners Mosh"
- Duration: 20-30 minutes
- Focus: Basic SQL commands (SELECT, INSERT, UPDATE, DELETE)

**Video 2: "Database Design Fundamentals"**
- Platform: YouTube (freeCodeCamp)
- Search: "Database Design freeCodeCamp"
- Duration: 25 minutes
- Focus: Entity-relationship diagrams and schema design

**Video 3: "Data Engineering Podcast"**
- Platform: Spotify / Apple Podcasts
- Search: Data Engineering Podcast — any recent episode about databases
- Duration: 30-45 minutes
- Focus: Real-world database management

### Listening Log Template

Complete this log for each video you watch:

```
Video Title: _________________________________________________
Duration: ______________ Date Watched: _____________

Key Vocabulary I Heard:
1. _______________________ 2. _______________________
3. _______________________ 4. _______________________

Main Points:
1. _________________________________________________________
2. _________________________________________________________
3. _________________________________________________________

Grammar Structures I Noticed:
• Reported Speech example: ____________________________________
• Preposition collocation example: _____________________________

Questions I Have:
_____________________________________________________________
```

---

## E. WRITING TASK (Homework)

### Assignment: Database Schema Documentation

**Sub-CPMK:** LO10.1 (Reported Speech), LO10.2 (Prepositions)

#### Task Description

Write documentation for a student information system database (250-300 words). Imagine you are a database administrator documenting a database design for a university.

#### Requirements Checklist

Your documentation MUST include:

| Requirement | Check |
|-------------|-------|
| Database purpose and context | ☐ |
| At least 3 main tables described (students, courses, enrollments, etc.) | ☐ |
| Description of what data is stored IN each table | ☐ |
| How tables connect TO each other (foreign keys) | ☐ |
| At least 3 reported speech sentences referencing stakeholder requirements | ☐ |
| At least 5 correct preposition collocations in database contexts | ☐ |
| Technical details (data types, indexes, backup strategy) | ☐ |
| Minimum 8 database vocabulary terms | ☐ |
| 250-300 words | ☐ |

#### Documentation Structure Guide

**Section 1: Introduction (1 paragraph)**
- Database purpose
- What stakeholders said they needed (use reported speech)

**Section 2: Database Schema (2-3 paragraphs)**
- Main tables and their fields
- Where data is stored (prepositions)
- How tables connect (foreign keys)

**Section 3: Technical Details (1 paragraph)**
- Data types, indexes, or constraints
- Backup and recovery strategy

#### Model Answer

> The student information system database was designed based on requirements from the university registrar. The registrar explained that they needed a centralized system to manage student records, course enrollment, and academic performance. They mentioned that the current spreadsheet system was causing data integrity issues.
>
> The database consists of three main tables: Students, Courses, and Enrollments. The Students table stores all student information in the database, including student ID, name, email, and major. Each record is identified by a unique student ID as the primary key. The Courses table contains course details such as course code, title, credits, and instructor. The Enrollments table connects students to their courses using foreign keys that reference both the Students and Courses tables.
>
> An index was created on the email field to speed up searches. All data is backed up to the cloud server at midnight every day. The DBA told us that backups must run automatically to prevent data loss.

*Word count: ~160 words*

**Note:** The model answer is shorter than required. Your documentation should be 250-300 words with more details.

---

### Assessment Rubric

Your writing will be assessed using this rubric:

| Criterion | Excellent (5) | Good (4) | Fair (3) | Needs Work (2) | Poor (1) |
|-----------|---------------|----------|----------|----------------|----------|
| **Technical Content** (LO10.1) | Clear description of tables, relationships, and purpose | Most elements with good detail | Basic description, some gaps | Several elements missing | Many elements missing |
| **Reported Speech** (LO10.1) | 4+ correct uses with proper tense backshifting | 3 correct uses | 2 uses with minor errors | 1-2 uses with errors | No correct examples |
| **Prepositions** (LO10.2) | 6+ correct database preposition collocations | 5 correct collocations | 3-4 collocations with minor errors | 2-3 collocations with errors | No correct collocations |
| **Database Vocabulary** (LO10.1) | 10+ terms used correctly | 8-9 terms used correctly | 6-7 terms used correctly | 4-5 terms used | 0-3 terms used |
| **Organization** | Clear structure, logical flow, professional tone | Good structure, mostly logical | Some structure, occasionally unclear | Poor structure | No clear structure |

**Total: _____ / 25 points**

#### Submission Details

| Item | Details |
|------|---------|
| **Due Date** | Next class meeting |
| **Format** | Printed (preferred) or digital submission |
| **File Name** | `[YourName]_Meeting10_DatabaseDocumentation.docx` |
| **Font** | Times New Roman or Arial, 12pt |
| **Spacing** | Double-spaced |

---

## Self-Study Completion Checklist

Before the next class, confirm you have completed:

| Task | Completed |
|------|-----------|
| Created vocabulary flashcards (25 terms) | ☐ |
| Completed vocabulary exercises A2 | ☐ |
| Read grammar summary B1 | ☐ |
| Completed grammar exercises B3 | ☐ |
| Reviewed Murphy's Units 47-48 (Reported Speech) | ☐ |
| Reviewed Murphy's Units 129-136 (Prepositions) | ☐ |
| Read at least 1 extension article | ☐ |
| Watched at least 1 extension video (optional) | ☐ |
| Completed writing task (database documentation) | ☐ |

---

## Answer Key for Self-Study Exercises

### Vocabulary Exercise 1
1. index
2. schema
3. restore
4. replication
5. foreign key
6. normalize
7. query
8. backup

### Vocabulary Exercise 2
1-e, 2-c, 3-b, 4-a, 5-d

### Vocabulary Exercise 3
1. in
2. to
3. from
4. into
5. to
6. in
7. at
8. by
9. in
10. from

### Grammar Exercise 1 (Reported Speech)
1. The DBA said (that) the database was running slowly.
2. They told us (that) they would migrate all data the following month.
3. She mentioned (that) she could optimize that query.
4. He reported (that) the backup had completed successfully.
5. The team explained (that) they were implementing new security measures.

### Grammar Exercise 2 (Reported Questions)
1. The client asked where the data was stored.
2. He wanted to know if/whether I could restore the database.
3. She asked how many records were in the table.
4. They asked if/whether the migration would finish by Friday.
5. The manager asked what backup schedule I recommended.

### Grammar Exercise 3 (Prepositions)
1. in
2. to
3. from
4. into
5. at
6. to
7. by
8. on
9. in
10. from

---

*End of Self-Study Materials*
