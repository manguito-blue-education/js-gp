# js-gp

This is a tool to create and push git commits with some checks beforehand

- Runs TS compiler to check if you have all your types correctly 
- Runs stylelint to check if your styles are correct 
- Runs eslint to check that you don't left unwanted console.logs
- Runs test files for the changed files if they exist 

If all checks pass then it adds, commmits and push your changes 


