## Git Branching & Merging

1.  Goto directory e:\my-repos or c:\my-repos

2.  Create a new empty repository.

    ```cmd
    $ git init website1
    $ cd website1
    ```

3.  Open VS Code inside your repository.

    ```cmd
    $ code . 
    ```

4.  Created a new HTML file `index.html`

    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <meta charset='utf-8'>
        <meta http-equiv='X-UA-Compatible' content='IE=edge'>
        <title>Home Page</title>
    </head>
    <body>
        <h1>Hello World!</h1>
        <p>The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. </p>
    </body>
    </html>
    ```

5.  Save the changes made inside the file and use `git add` and `git commit`

    ```cmd
    $ git add index.html
    $ git commit -m "first"
    ```

6.  Create a new branch from MASTER (current)

    ```cmd
    $ git checkout -b css
    ```

7.  Switch back to VSCode and make following changes to index.html 

    Goto Line #7, use ENTER to force new line and copy following code

    ```html
    <style>
        h1 {
            padding: 4px;
            margin: 0px;
            padding-left: 12px;
            background-color: burlywood;
        }
        p{
            padding: 5px;
            margin-left: 4px;
            border-left: 2px solid black;
            border-right: 4px double black;
        }
    </style>
    ```

8.  Save, Add & Commit file changes

    ```cmd
    $ git add .
    $ git commit -m "style"
    ```

9.  Switch back to `master` branch and again EDIT the `index.html` file with following additional contents at line#12 :

    ```html
    <h2>Solar System</h2>
    <p>The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. </p>
    <ul>
        <li>
            <h4>Earth</h4>
            <p>The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. </p>
        </li>
        <li>
            <h4>Mars</h4>
            <p>The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. </p>
        </li>
        <li>
            <h4>Venus</h4>
            <p>The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. </p>
        </li>
    </ul>
    ```

10. Save, Add & Commit

    ```cmd
    $ git add .
    $ git commit -m "solar"
    ```

11. Try Switch from `master` to `css` and `css` to `master`

12. Switch to `master` branch and MERGE `css` branch

    ```cmd
    $ git checkout master
    $ git merge css -m "Merged branches"
    ```

13. What to Expect? 

    Now, `master` branch has changes from `css` branch as well !
