# WordScramble
This is a simple app that shows a random word in the header
and asks the users to enter a possible permutation of the word.
Points are rewarded for each unique word. Points are calculated
by adding all the letters from each unique word formed.

# Code structure
- All properties are initialized using @State 
- View body has a navitation view with a list
- List has multiple sections for all the rows in the view
- Multiple backend process are applied to the list using various modifiers
- The code has seven methods.
- The main addNewWord method checks to see if input word is valid
- Lastly ContentView_Preview renders the page
