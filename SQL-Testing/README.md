# SQL & Database Testing

This section demonstrates my approach to validating backend data using MySQL and SQL queries.

## 🗄️ Database Testing Areas

* Backend data validation
* Data accuracy verification
* Data consistency checks
* Data integrity validation
* Relationship validation
* CRUD operation validation
* Verification of data after application actions
* Validation of records created or updated through APIs

## 🧪 Sample SQL Queries

### 1. Retrieve all records

```sql
SELECT * FROM patients;
```

### 2. Retrieve a specific patient

```sql
SELECT *
FROM patients
WHERE patient_id = 101;
```

### 3. Find records based on status

```sql
SELECT *
FROM sessions
WHERE status = 'Scheduled';
```

### 4. Sort records

```sql
SELECT *
FROM patients
ORDER BY created_at DESC;
```

### 5. Count records

```sql
SELECT COUNT(*) AS total_patients
FROM patients;
```

### 6. Filter records using multiple conditions

```sql
SELECT *
FROM sessions
WHERE status = 'Scheduled'
AND session_date >= '2026-01-01';
```

### 7. Join related tables

```sql
SELECT p.patient_id, p.name, s.session_date, s.status
FROM patients p
JOIN sessions s
ON p.patient_id = s.patient_id;
```

## 🔍 Database Validation Example

**Scenario:** Verify that a newly created session is correctly stored in the database.

**Steps:**

1. Create a new session through the application.
2. Note the session details.
3. Execute an SQL query to retrieve the corresponding record.
4. Compare the application data with the database record.
5. Verify that related patient/provider information is correctly mapped.
6. Confirm that the record is stored with the correct status and values.

**Expected Result:**
The database should contain accurate and consistent data matching the information submitted through the application.

## 📋 QA Approach

**Perform Application Action → Identify Expected Database Change → Execute SQL Query → Compare Data → Validate Relationships → Verify Data Integrity**
