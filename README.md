# Hands on assignments for NodeJS

A small set of hands-on assignments on NodeJS for interview candidates.
# Instructions:

    All the solutions should be stored in a public git repository. It can be github, gitlab or anything else but clone-able publicly. Send us only the repository path.
    There is a README.md or README.txt in the repository. This can contain your notes to the evaluator, how to run if its not default etc.
    Each solution is placed in a git branch with prefix sol_N, so that git checkout sol_2 will take us to the solution for question number 2.
    Commit everything to the respository e.g. archives (zips, tars), binaries etc.
    Extra files can be placed in separate folders and documented in README.
    If it was impossible to finish, its okay to have it incomplete, just update the README in that case. 
    During evaluation, points are given also to approach if the solution is not complete.

# Mandatory questions
1. Create an express app to serve a html file "app.html" that displays "hello cloudronics!"
2. modify app.html to show a login form with username and password, and a button "test authentication"
3. create an express route to authenticate username and passowrd. use sqlite for databases (use JWT for authentication)
4. hide login form and show logout button on login success
5. create a route that can be accessed only by an autheticated user. Access the route on clicking "test authentication". Alert success, if the user is logged in.
6. logout and click "test authentication" to show "failure"

# optional questions:
7. dockerize the whole app
8. create an image upload functionality to store the uploaded image in /tmp => image size should be square, so you may need to implement cropping
