# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > | "var" "let" and "const"|

02. What is the definition of a function?

    > | Functions are blocks of code that wait to be called until invoked |

03. What are the `SOLID` principles?

    > |  SOLID is an acronym 
S represents the Single Responsibility principle which describes cohesion and the functional readiness of elements within a module
O represents the Open Closed principle which describes that software entities should be open for extension yet closed for modification, meaning that it is able to extend what the module does, but not result in changes to the source code.
L represents the Liskov Substitution principle says that we should create software from interchangeable parts that must adhere to a contract that allows for substitution use
I represents the Interface Segregation principle advises software designers to avoid depending on things they don't use
D represents the Dependency Inversion principle states that the most flexible systems are where code dependencies refer only to abstractions and not completions |

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    | function removePineapple(){
        for(i=0; i<fruit.length; i++)
        delete arr[2],
    } 
    removePineapple()
    |

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > | 
    function addFriendToYou(){
        let youFriends = you.friends[]
        youFriends.push(them.name)
    }
    function addFriendToThem(){
        let themFriends = them.friends[]
        themfriends.push(you.name)
    }
    addFriendToThem()
    addFriendToYou()
     
     
     also via splice method 
     
     function addFriendToThem(){
        you.friends += ['them']
        them.friends += ['you']
     }|

06. Give an example of a JavaScript `Conditional`:

    > | function checkout(rewardsTier) {
  return rewardsTier ? '(price x .95)' : '(price)';
} |

07. What is the main difference between `parameters` and `arguments`?

    > | parameters are the outline/ conditions that, if met, allow the argument to follow, or said another way, which "settings" need to be met, whereas arguments are what happens within the function itself. 
    
    said more simply, IF parameters are met, THEN arguments will follow |

08. Instead of writing everything to the console, what is a better way to debug your code?

    > |  there are debugging extensions that are downloadable, but assuming that is not allowed, coding small is a good practice that may prevent this, but also you could try to comment out sections that you suspect may be the issue and use process of elimination. additionally you could use print statements or "try-catch blocks" such as 
    
    try {possibleErrorCode()
    } catch (error) {
        print(error)
    } |

09. What is the difference between a `primitive` value and a `reference` value?

    > | when primitives are passed, they only move their value to a new separate source, whereas when reference types are passed, they share the same source |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > |  function seekRange() {
    let newArray = [];
    for (i= -100; count <= 100; i++) {
        newArray.push(Math.floor(Math.random() )); 
    }
    return newArray;
} |
