# PAction
Semi-visual scripting system in unity.
____________
A semi-visual scripting system to execute commands in sequence and flow control using functions, conditional statements, loops, etc.

### Why should you use PAction?

When you want to implement simple mechanics without coding, for part of casual games, hyper casual or even part of larger projects!
No coding! Do it fast and clean!

## Requirements
* Unity 2019.4.7 or later versions.
* [NaughtyAttributes](https://github.com/dbrizov/NaughtyAttributes)
* [PashmakCore](https://github.com/mohammadroohian/PashmakCore)
* TextMesh Pro 2.0.1
* Post Processing 2.3.0


## Installation
* First install `TextMesh Pro` and `Post Processing` packages in Unity through Package Manager.`MenuItem - Window - Package Manager`
* Add `TextMesh Pro` sample scenes.

### Perform one of the following methods:
#### zip file (The simple way)
1. Download a `source code` zip from [releases](https://github.com/mohammadroohian/PAction/releases).
2. Extract it.
3. Copy the items in the `Assets` folder into the `Assets` folder of your project. (Click replace files if necessary)

#### unitypackage file
1. Install [NaughtyAttributes](https://github.com/dbrizov/NaughtyAttributes#installation).
2. Install [PashmakCore](https://github.com/mohammadroohian/PashmakCore#installation).
3. Download `.unitypackage` file from [releases](https://github.com/mohammadroohian/PAction/releases).
4. Import it into your project.

## Overview
To learn more about how these components work, check out the sample scenes.
The following are a number of practical cases.

### ExecuteNode
![image](https://user-images.githubusercontent.com/80090999/113096767-120bf080-920b-11eb-96f1-5f8be17b7e0d.png)

The ExecuteNode component is used to execute a normal command.

![ExecuteNode](https://user-images.githubusercontent.com/80090999/113096744-07515b80-920b-11eb-911d-2d3979427580.gif)

### CallFunctionNode

![image](https://user-images.githubusercontent.com/80090999/113096962-68792f00-920b-11eb-93a7-752c094fafea.png)

The CallFunctionNode component is used to call a function from within another function.

![CallFunctionNode](https://user-images.githubusercontent.com/80090999/113097260-d45b9780-920b-11eb-90d7-4fb54cafaf16.gif)

### ExitFunctionNode

![image](https://user-images.githubusercontent.com/80090999/113097340-f7864700-920b-11eb-9096-3bddeb3b3ed2.png)

The ExitFunctionNode component is used to exit the current running function.

![ExitFunctionNode](https://user-images.githubusercontent.com/80090999/113097485-34ead480-920c-11eb-93cc-b15bce2b8458.gif)

### LoopNode

![image](https://user-images.githubusercontent.com/80090999/113097575-606dbf00-920c-11eb-8497-106a4112d175.png)

The LoopNode component is used to place a number of commands inside a loop and repeat them.
The loop can be infinite as well.

![LoopNode](https://user-images.githubusercontent.com/80090999/113097763-bcd0de80-920c-11eb-8643-61516a010811.gif)

### BreakNode

![image](https://user-images.githubusercontent.com/80090999/113097832-df62f780-920c-11eb-95cd-5515e591934b.png)

The BreakNode component is used to exit the current loop.
In nested loops, the innermost loop will break.

![BreakNode](https://user-images.githubusercontent.com/80090999/113097970-10dbc300-920d-11eb-9812-9c5d74f35589.gif)

### WaitForButtonNode

![image](https://user-images.githubusercontent.com/80090999/113098172-64e6a780-920d-11eb-9527-04a64d9151e4.png)

The WaitForButtonNode component is used to delay the execution of commands until a specific button is tapped.

![WaitForButtonNode](https://user-images.githubusercontent.com/80090999/113098132-526c6e00-920d-11eb-8b14-725ff88cf5cb.gif)

### WaitForKeyNode

![image](https://user-images.githubusercontent.com/80090999/113098274-85aefd00-920d-11eb-8b0a-0d3d17a6bdf5.png)

The WaitForKeyNode component is used to delay the execution of commands until a specific key is pressed.

![WaitForKeyNode](https://user-images.githubusercontent.com/80090999/113098473-bee76d00-920d-11eb-92bf-f406f37d1ed5.gif)

### WaitForSecondsNode

![image](https://user-images.githubusercontent.com/80090999/113098562-dfafc280-920d-11eb-8c49-47fb38aa15e3.png)

The WaitForSecondsNode component is used to delay the execution of the command.

![WaitForSecondsNode](https://user-images.githubusercontent.com/80090999/113098735-1dace680-920e-11eb-80a1-de814092580a.gif)

### WaitForCallbackNode

![image](https://user-images.githubusercontent.com/80090999/113098869-4c2ac180-920e-11eb-83ac-778451276012.png)

The WaitForCallbackNode component is used to delay the execution of commands until the callback is called.

![WaitForCallbackNode](https://user-images.githubusercontent.com/80090999/113099225-dffc8d80-920e-11eb-9da6-cbc4608bbfb4.gif)
