# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > | the four pillars of OOP are
  Abstraction - hiding away the details of something inside a prototype or function
  breaking up larger functions into smaller functions and calling them
  Encapsulation - each object should control it's own state, own this.state example
  can be achieved by separating longer lines of code into smaller functions/modules
  Inheritance - how objects receive characteristics from classes unless negated/overwritten
  Polymorphism - the ability for objects to take on multiple different appearances (view)
    |

02. How does `export` differ from `export default`?
  
  > | an export is a specific definition that cannot change using "business logic" whereas export default is modifiable |

03. What is Encapsulation?
  
  > | Encapsulation is the process of building data and methods that are only accessible when you want them to be, containing data, methods and code so that the user may not have access to them on specific pages or at all |

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > | a proxy can be used to 'trap' data and make set and get more difficult to overwrite, basically kind of like a proxy for your code |

05. What the difference between a `class` and an instance of a `class`?
  
  > | class sets values for an object, whereas an instance of a class is 'drilling down' and assigning/specifying the values for a particular object of the class |

06. What is a computed Property?
  
  > | computed properties don't hold value directly and only re-run when one of their dependencies change |

07. What is the purpose of the `MVC` pattern?
  
  > | the MVC pattern keeps data and code away from users on specified pages, the model creates a rough outline for objects, the view is controlled through the router and the controller is the limit for what the user can do |

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > | user interface |

09. What is the job of the `Service` in `MVC`?
  
  > | the service interacts wit the model from various data sources, updates values in appstate, and performs assigned logic and manipulations  |

10. What is the job of the `Model` in `MVC`?
  
  > | the model holds all data-related information like a blueprint
   an object will retrieve the information from the database, manipulate or update their record in the database, or use it to render data.
   |
