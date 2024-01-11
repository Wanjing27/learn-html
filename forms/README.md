## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
      The _action_ attribute directs the code to send the submitted form data to the specified URL. In the form.html example, it sends the inputs to http://localhost:3000/login using the GET method.

2. What is the purpose of the _method_ attribute in the _form_ tag?
      The _method_ attribute defines how the data is sent to the server. For instance, "Get" appends the form data to the URL as pairs of names and values, while "Post" transmits the form data using an HTTP POST transaction.

3. What is the purpose of the _name_ attribute in the _input_ tag?
      The _name_ attribute serves to reference the input element in JavaScript and assigns a name to the input element.

4. What is the purpose of the _type_ attrbute in the _input_ tag?
      The purpose of the _type_ attribute is to specify the display format of the input. In form.html, when a user enters a password, the assigned type as 'password' ensures that it is displayed as dots instead of revealing the actual input.

5. What is the purpose of the _label_ tag?
      The purpose of the _label_ tag is to assist users in defining elements on the web page.

6. What is the purpose of the _required_ attribute?
      The purpose of the required attribute is to inform both the user and the program that these elements denote a mandatory input field that must be completed before proceeding with form submission.
      
