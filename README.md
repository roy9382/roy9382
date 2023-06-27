const booksData = [
  {
    id: 1,
    title: "Book 1",
    author: "Author 1"
  },
  {
    id: 2,
    title: "Book 2",
    author: "Author 2"
  },
  // Add more books as needed
];

export default booksData;
import React from "react";
import booksData from "./booksData";
function BookList() {
  return (
    <div>
      {/* Display the list of books here */}
    </div>
  );
}

export default BookList;
function BookList() {
  return (
    <div>
      {booksData.map(book => (
        <div key={book.id}>
          <h3>{book.title}</h3>
          <p>{book.author}</p>
        </div>
      ))}
    </div>
  );
}
import BookList from "./BookList";
function App() {
  return (
    <div className="App">
      <h1>Book List</h1>
      <BookList />
    </div>
  );
}
- 👋 Hi, I’m @roy9382
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
roy9382/roy9382 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
