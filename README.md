/*What are your favorite books? You can make a database table to store them in! In this first step, create a table to store your list of books. It should have columns for id, name, and rating. Now, add three of your favorite books into the table.*/

/**Favorite Books:
I will make you rich
flyy girl
the source
**/

CREATE TABLE books (id INTEGER PRIMARY KEY, name TEXT, rating INTEGER);

INSERT INTO books VALUES (1, "I Will Make You Rich", 5);
INSERT INTO books VALUES (2, "Flyy Girl", 3);
INSERT INTO books VALUES (3, "The Source", 5);
SELECT * FROM books;
*/
