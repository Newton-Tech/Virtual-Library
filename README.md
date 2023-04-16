# Virtual-Library

This code is a simple book library app that allows users to add, edit, and delete books from a collection. The app displays a grid of book cards, each containing information such as title, author, pages, and read status. The app tracks the number of books that are completed, in progress, and on the user's list, and updates the stats accordingly.

The app creates a Book class with properties for each book, such as title, author, pages, and read. The read property indicates the number of pages that the user has read so far. The Book constructor function sets the status, statistic, and progressWidth properties based on the value of read.

The app uses several event listeners to trigger functions. For example, when the user clicks the "Add new book" button, the openForm function is called to display a form where the user can enter book details. When the user submits the form, the addBook function is called to create a new Book object and add it to the myLibrary array.

The app also includes an edit form that allows the user to update a book's details or delete it from the collection. When the user clicks the "Edit" button on a book card, the editFormFunction function is called to display the edit form and fill it with the book's current details. The user can then edit the details and submit the form to update the book's information. The user can also delete the book by clicking the "Delete" button.



