# Understanding Asynchronous Code, and API's
01. What is the difference between `asynchronous` code and `synchronous` code?

  > | when code runs synchronously, it reads line after line top to bottom whereas async code allows for wait, pause, hold, await response |

02. What is an event listener?

  > | an event listener (AppState.on(event, do thing)) waits for an event to happen or a line of code to change before performing a function or method |

03. What does *REST* stand for, and in simple terms what does it mean??

  > | REST stands for REpresational State Transfer
  
  you want your web pages to demonstrate that you're taking the user to the next area/page based on what they are interested in (represented by click usually) and what they want to do with that (get, post, push, delete)
   |

04. What is a callback / higher order function?

  > | a callback function is a function that is passed into another function as an argument which is then invoked inside the outer function |

05. What is a `promise`? How do you capture an error from a `promise`?

  > | promises create functions to pause the standard sychronous running of code. a promise is a class that can be accepted or rejected via resolve and reject.
  
  you can capture an error w/ the try-catch method|

06. Name three processes used to make requests over `HTTP`?

  > | Establishing a connection, requesting data, receiving data|


07. What does the `API` acronym stand for?

  > | Application Project Interface |

08. What must you do in order to `await` a promise inside of a function?

  > | must be asynchronous in order to 'await' before proceeding|

09. What is the purpose of encapsulation in programming?

  > | encapsulation allows for hidden or background processes to run and operate without the user seeing it  |


10. What is `HTTP` response code for a successful request?

  > | 200 ok |

11. What is a 400 error?

  > | Bad Request
  will not process the request due to something that is perceived to be a client error (for example, malformed request syntax, invalid request message framing, or deceptive request routing).
   |
