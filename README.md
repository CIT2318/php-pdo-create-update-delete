# Create, Update and Delete

The assignment focussed on reading data from a database table. You also need to be able to insert, update and delete data in a database using PHP. This practical is based on simple examples where the databse database consists of a single table - https://github.com/CIT2318/php-pdo-databases-lec-examples.

1. Choose a database table to work with. This could be from the *films* example we used previously or it could be one of your assignment database tables.

2. Create
  - Make a new HTML page, name it *create.php*. Inside this page create an HTML form where the user can enter data for a new row in your database table. See: https://github.com/CIT2318/php-pdo-databases-lec-examples/blob/master/create.php for a simple example.
    * Your table may have a foreign key column, to start with simply allow the user to enter an id number into a textbox for the FK value.
  - Next create a page called *save.php*. This page should take the data from the form and insert it into a database table/ Have a look at https://github.com/CIT2318/php-pdo-databases-lec-examples/blob/master/save.php for an example of using PHP to insert a row into a database table.

3. Delete
  - Make a new PHP page, name it *delete-list.php*. *delete-list.php* should list all the items from your chosen database table with a checkbox next to each item. See https://github.com/CIT2318/php-pdo-databases-lec-examples/blob/master/delete-list.php for an example.
  - Make a new page, name it *delete.php*. *delete.php* should delete the selected items from *delete-list.php*. See https://github.com/CIT2318/php-pdo-databases-lec-examples/blob/master/delete.php for an example.
  - **Important! You will only be able to delete items that aren't referenced as a foreign key in a different table. You should be able to delete the new items you have created as part of this practical work.**

4. Update
  - Make a new PHP page, name it *edit-list.php*. *edit-list.php* should list all the items from your chosen database table with a radio next to each item. See https://github.com/CIT2318/php-pdo-databases-lec-examples/blob/master/edit-list.php for an example.
  - Next make a PHP page called *edit.php*. This page should populate a HTML form with data based on the item the user selected on *edit-list.php*. The user will be able to edit the details in this form and submit the changes. See https://github.com/CIT2318/php-pdo-databases-lec-examples/blob/master/edit.php for an example.
  -  Finally, create a page called *update.php*.*update.php* will take the data submitted from *edit.php* and update a row in the database. See https://github.com/CIT2318/php-pdo-databases-lec-examples/blob/master/update.php for an example.

## There's more
The obvious weakness of the above is we haven't really considered related data e.g. when we insert a new film
