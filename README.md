# Poetry - How to install on windows?

## 1. First, you need to enable PowerShell as an administrator and enter the command:
(I have it installed, so it shows me that the latest version (1.6.1) is already installed).
```
(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | py -
```


![powershell-command](https://github.com/piotek8/Langchain_Ask_App_update/assets/82182989/02ebf31b-dbed-424e-8798-acf07c299fb0)


2.Open "edit system environment variables ( edytuj zmienne srodowiskowe systemu )", next press "Environment variable ( Zmienne srodowiskowe... )"
3.Add into "system variables ( zmienne systemowe ) " and "user variables ( zmienne uzytkownika )"
4.Enter:
"C:\Users\Gaming\AppData\Roaming\Python\Scripts"
into Path in both ( step3 ) and move under the python path. I have like this:
C:\Users\Gaming\AppData\Local\Programs\Python\Python311

C:\Users\Gaming\AppData\Local\Programs\Python\Python311\Scripts

C:\Users\Gaming\AppData\Roaming\Python\Scripts

5. Reset pycharm, terminals or computer if not wroking yet.
6. Add new interpreter ( in the bottom right corner into pycharm )-> Add local interpreter -> Poetry environment -> OK
Poetry executable:
C:\Users\Gaming\AppData\Roaming\Python\Scripts\poetry.exe

If doesn't work - delete poetry ( po prostu wyjeb wszystkie pliki z poetry ) and try again
