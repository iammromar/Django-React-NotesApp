### Cloning the repository

--> Clone the repository using the command below :
```bash
git clone https://github.com/divanov11/Django-React-NotesApp.git

```

--> Move into the directory where we have the project files : 
```bash
cd Django-React-NotesApp

```

```bash
4. How to compare with null and undefined?

    -- In JavaScript, I can use the strict equality operator (===) to compare a value to null or undefined.

    For example:

    let x = null;
    
    if (x === null) {
          console.log("x is null");
        } else {
              console.log("x is not null");
            }


       
    This will log "x is null" to the console, because x is strictly equal to null.

    Similarly, I can use the strict inequality operator (!==) to check if a value is not null or undefined:

    let y = undefined;
    
    if (y !== null && y !== undefined) {
          console.log("y is not null or undefined");
        } else {
              console.log("y is null or undefined");
            }


    This will log "y is null or undefined" to the console, because y is strictly equal to undefined.

    I can also use the typeof operator to check if a value is null or undefined.


    let z = null;
    
    if (typeof z === "undefined") {
          console.log("z is undefined");
        } else if (z === null) {
              console.log("z is null");
            } else {
                  console.log("z is neither null nor undefined");
                }

    
    This will log "z is null" to the console, because z is strictly equal to null.

    null represents a lack of value, while undefined represents a value that has not been assigned.
```




--> Create a virtual environment :
```bash
# If you are on Windows
virtualenv env
# If you are on Linux or Mac
python -m venv env
```

--> Activate the virtual environment :
```bash
# If you are on Windows
.\env\Scripts\activate
# If you are on Linux or Mac
source env/bin/activate
```

#

### Running the App

--> To run the Notes App, we use :
```bash
python manage.py runserver
```

> ⚠ Then, the development server will be started at http://127.0.0.1:8000/

