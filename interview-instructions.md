Our goal is to build a quick API in C#

 1) Fetch the json from the URL below and convert it into objects and arrays (choose great names)
 https://run.mocky.io/v3/8cc1b858-2e3e-4249-a025-c0c52053d618

 2) Send back data with all the users only (json format). Data should have the full name of that user. NOTE: return only users with a valid numeric id

 3) Create another array that has a group based on the "numbers" property you get from the above data you just fetched. Match each user id with the number from the "numbers" multidimensional array
  
 4) Create a search feature. Have the ability to accept parameters. We should be able to retrieve the user based on id. Meaning, you do a request from the frontend to the endpoint by id, and the endpoint should return that user to be able to use it's fullname on the frontend.
 
 5) Output true/false if the sum of numbers from first diagonal is equal to the sum of numbers 
 from the second diagonal, from the multidimensional array of "numbers". (NOT THE EXAMPLE BELOW, BUT FROM THE FETCHED DATA)

 Example: [
     [ 1, 2, 3 ],
     [ 4, 5, 6 ],
     [ 7, 8, 9 ],
 ]

 Make an algorithm that iterates through the matrix and outputs 1+5+9 === 3+5+7
 You win points if you can make this through a single iteration.
