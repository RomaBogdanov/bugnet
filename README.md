## BugNET
[![Build status](https://ci.appveyor.com/api/projects/status/ror9c96krbd7knld?svg=true)](https://ci.appveyor.com/project/dubeaud/bugnet)

BugNET is a free, open source issue tracking and project issue management solution for the ASP.NET platform.

### More Information & Support

To report issues use the github issue tracker.

* Code Metrics - https://www.openhub.net/p/bugnet

### Getting started

**Getting started with Git and GitHub**

 * [Setting up Git for Windows and connecting to GitHub](http://help.github.com/win-set-up-git/)
 * [Forking a GitHub repository](http://help.github.com/fork-a-repo/)
 * [The simple guide to GIT](http://rogerdudler.github.com/git-guide/)

### Инсталяция приложения
* Для начала создаём БД(если она не создана). Для этого:
* Находим проект BugNET.Database, нажимаем на нём ПКМ и выбираем "Опубликовать".
* Далее по советам мастера: выбираем сервер, желательно создать скрипт и его уже запустить.
* Вносим изменения в строку подключения к БД:
приложение: BugNET_WAP, файл: Web.config
* Пример:
```
  <connectionStrings>
    <clear />
    <!--<add name="BugNET" connectionString="Data Source=(localdb)\ProjectsV12;Initial Catalog=BugNET;Integrated Security=SSPI;" providerName="System.Data.SqlClient" />-->
    <add name="BugNET" connectionString="Data Source=WIN-N96M7792NND;Initial Catalog=BugNET;Integrated Security=SSPI;" providerName="System.Data.SqlClient" />
  </connectionStrings>
```

### License

Source code is licensed under [MS-PL](http://opensource.org/licenses/MS-PL)
