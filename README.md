# Grid_Color
Explain what is execution context in detail with diagram

First Javascript engine scan the script file, it makes an enviroment called Excution context. That handle the entire and transformation and excution the code. There are two type of excution context in the enginer 1. Global  2.function.



![image](https://github.com/rajchatterz/Grid_Color/assets/45287321/e0869043-1c18-4b59-a50d-f6420a809909)

During the execution of the javascript code , multiple execution context might be created. Each time function envoked multiple execution can be created, formning a stack called call stack.

General when javascript code run in the browser it will create two column named MEMORY(Variable enviroment) and CODE(Thread of component).
After scanning the code javascript excution tend to store the variable in the memory section with give the default value undefined. Then when it start executing it will assign value to the respective variable. Lets say if there is any other function then it will create a another execution context that will have the same operation like variable enviroment and thread of component. after executing that second excution context , it will come to the first one. Then after assigning the value to respective variable then it will end.

![image](https://github.com/rajchatterz/Grid_Color/assets/45287321/51d51505-e776-4394-a0ca-73888afa0282)
