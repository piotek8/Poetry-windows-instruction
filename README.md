# Poetry - How to install on windows?

## 1. First, you need to enable PowerShell as an administrator and enter the command:


```
(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | py -
```
![powershell-command](https://github.com/piotek8/Langchain_Ask_App_update/assets/82182989/02ebf31b-dbed-424e-8798-acf07c299fb0)
## (I have it installed, so it shows me that the latest version (1.6.1) is already installed).

## 2.Open "edit system environment variables ( edytuj zmienne srodowiskowe systemu )"
  - then click it :  "Environment variable ( Zmienne srodowiskowe... )" 
  - press 'Path' in user variables ( zmienne użytkownika ) ->  add the path to your poetry ( will be similar to mine: C:\Users\Gaming\AppData\Roaming\Python\Scripts)
  - do the same for system variables: press 'Path' in system variables ( zmienne systemowe ) -> add the path to your poetry ( will be similar to mine: C:\Users\Gaming\AppData\Roaming\Python\Scripts)

![image](https://github.com/piotek8/Langchain_Ask_App_update/assets/82182989/2699d092-4a45-42c6-8500-3584ec532cbc)

## Here are examples:
![variables](https://github.com/piotek8/Langchain_Ask_App_update/assets/82182989/92fa4442-3c4a-46a9-a42f-5e16343df284)

## This is the path to the poetry.exe file
![poetry](https://github.com/piotek8/Poetry-windows-instruction/assets/82182989/ce5556dd-125b-4f33-92ef-2b7370069156)

## 3. Check if poetry works using the command (you should have information like here:)
![poetry version](https://github.com/piotek8/Poetry-windows-instruction/assets/82182989/4d0c16a2-e4a7-431a-8de5-ad58a27109b9)

Reset pycharm, terminals or computer if not working yet.



## 4. Open pycharm and you can add it to your project ( by clicking in the lower right corner - here you will see an arrow )
![poetry-pycharm](https://github.com/piotek8/Poetry-windows-instruction/assets/82182989/439440f5-c52d-4f84-81b8-944a69b7823b)


