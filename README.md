Example of using async graphql resolvers(to get results from external API)

Pre-requisites to run this application:
1. NPM and NodeJS should be set up in your machine and you can check the versions using:
npm -v
node -v 

Steps to run this application
1. go to the root directory of the project and run : 
npm start 
2. Hit the following url to get a sandbox for testing
http://localhost:4000/
3. Run the following queries to test the queries provided in the graphql example in the sandbox workspace:

query searches {
  searches {
   term
   count
  }
}

query users {
  users {
   id
   first_name
   email
  }
}

query books {
  books {
    title
    author
  }
}



