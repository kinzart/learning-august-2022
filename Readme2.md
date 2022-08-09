# Class 2



## How to fix dependency releases so you never have problems:

#### 1- create a file: ".npmrc".

#### 2- into the ".npmrc" put the code:
´´´
save-exact=true
´´´

#### 3- Now go to package.json and remove the circumflex accent that appears before the version:

before:
´´´
"@testing-library/jest-dom": "^5.16.5",
´´´
after remove:
 ´´´  
   "@testing-library/jest-dom": "5.16.5",
 ´´´  
