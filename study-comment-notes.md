# Study Questions and Answers

## Python Programming Questions

### analyze.py Questions:

**Q: What does @router.post() do?**
A: @router.post() is a FastAPI decorator that defines an HTTP POST endpoint.

**Q: What does "/analyze" do?**
A: "/analyze" is the URL path where an endpoint can be accessed.

**Q: What is async?**
A: async makes a function an asynchronous function - it can pause and resume, allowing the server to handle other requests while waiting for operations (like AI processing) to complete.

**Q: What's an HTTPException?**
A: FastAPI's way of returning HTTP error responses with status codes and messages.

**Q: What is FastAPI?**
A: A modern, high-performance Python web framework for building APIs.

**Q: What is PDFService?**
A: PDFService is a custom class that handles PDF operations like extracting text from pages.

**Q: What does request do? (request.page_range_end)**
A: The input parameter object that contains the user's data including page range information.

**Q: I don't understand the line above this comment (Line was: cache_key = f"analysis:{hash(extracted_text)}:{upload_info['grade_level']}")**
A: Creates a unique cache key by combining "analysis:" with a hash of the text and grade level. Used to store/retrieve analysis results to avoid reprocessing the same text.

**Q: What does await do?**
A: await pauses execution until the AI analysis completes.

**Q: What is ai_service?**
A: ai_service is likely the Z.AI GLM-4.6 integration service.

**Q: What does commit() do?**
A: Saves all pending changes to the database permanently.

**Q: What is enumerate()?**
A: enumerate() provides both index (i) and value when looping through items.

**Q: What is finally() used for?**
A: finally always executes code regardless of whether an exception occurred - used for cleanup like closing database connections.

### test.py Questions:

**Q: What does SessionLocal do?**
A: Creates a new database session from your SQLAlchemy configuration.

**Q: What does yield do?**
A: Returns control while maintaining the database connection, allowing the endpoint to use it, then returns for cleanup.

**Q: What does .query() do?**
A: Creates a database query.

**Q: What does .all() do?**
A: Executes and returns all matching records.

**Q: What does raise do?**
A: Throws/creates an exception to stop execution with an error message.

**Q: What does .sample() do?**
A: Randomly selects specified number of items from a list.

**Q: What does utcnow do?**
A: Gets current UTC timestamp for database records.

**Q: What does .dict() do?**
A: Converts Pydantic model to Python dictionary.

**Q: What does {str(e)} do?**
A: str(e) converts exception to string for error message display.

**Q: What do these three strings do? (""")**
A: Triple quotes (""") create a docstring - documentation for what the function does.

**Q: What does .filter() do?**
A: .filter() adds WHERE conditions to database queries.

**Q: What does set do?**
A: Creates unordered collection with unique items.

**Q: What does .intersection() do?**
A: Returns common elements between sets.

### words.py Questions:

**Q: What does .where do?**
A: .where() adds SQL WHERE conditions to filter query results.

**Q: What does .word do?**
A: Accesses the word field.

**Q: What does .ilike() do?**
A: Performs case-insensitive SQL LIKE pattern matching.

**Q: What does f"%{search}%" do?**
A: Creates SQL pattern that matches text containing the search term anywhere.

**Q: What does .definition do?**
A: Accesses the definition field of the meaning record.

**Q: What does .execute do?**
A: Runs the SQL query.

**Q: What does .fetchall() do?**
A: Returns all matching results.

**Q: What does .join() do?**
A: Combines tables.

**Q: What does .isoformat() do?**
A: Converts datetime to ISO 8601 string format (standardized date/time format).

**Q: What does .scalars() do?**
A: Returns single column results.

**Q: What does .all() do?**
A: Gets all matching records.

### upload.py Questions:

*Questions section incomplete - needs to be filled in.*