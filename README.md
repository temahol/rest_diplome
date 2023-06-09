## Automated tests for https://globalapi.dodopizza.com/
<p align="center">
  <img src="media/dodomain.png" alt="mainLogo" width="800">
</p>
<a name="Ссылка"></a>
## Content

- <a href="#tools">Stack of technologies</a>
- <a href="#tests">List of checks</a>
- <a href="#run">Running tests from the terminal</a>
- <a href="#remote">Remote running tests</a>
- <a href="#jenkins-report">Running tests in Jenkins</a>
- <a href="#allure-report">Test results report in Allure Report</a>
- <a href="#allure-testops">Integration with Allure TestOps</a>
- <a href="#jira">Integration with Jira</a>
- <a href="#telegram">Integration with Telegram</a>


<a id="tools"></a>
## :computer: Stack of technologies

<p  align="center">

<code><img width="5%" title="IntelliJ IDEA" src="media/logo/Idea.svg"></code>
<code><img width="5%" title="Java" src="media/logo/Java.svg"></code>
<code><img width="5%" title="Junit5" src="media/logo/Junit5.svg"></code>
<code><img width="5%" title="Gradle" src="media/logo/Gradle.svg"></code>
<code><img width="5%" title="Selenide" src="media/logo/Selenide.svg"></code>
<code><img width="5%" title="GitHub" src="media/logo/GitHub.svg"></code>
<code><img width="5%" title="Jenkins" src="media/logo/Jenkins_logo.svg"></code>
<code><img width="5%" title="Allure Report" src="media/logo/Allure.svg"></code>
<code><img width="5%" title="Allure TestOps" src="media/logo/Allure_TO.svg"></code>
<code><img width="5%" title="Jira" src="media/logo/Jira.svg"></code>
<code><img width="5%" title="Telegram" src="media/logo/Telegram.svg"></code>
</p>

<a id="tests"></a>
## :bookmark_tabs: List of checks:
## E2E Tests

- [x] Check country list
- [x] Check pizzeria
- [x] Check revenue country
- [x] Ask FeedBack
- [x] Send mail for work

<a id="run"></a>
## :computer: Running tests from the terminal

```bash
gradle clean rest_diplome
```

<a id="remote"></a>
### Remote running tests

```bash
clean
rest_diplome
```

<a id="jenkins-report"></a>
## <img width="4%" title="Jenkins" src="media/logo/Jenkins_logo.svg"> Running tests in [Jenkins](https://jenkins.autotests.cloud/job/pilulka/)

After completing all the settings, you need to click on the button <code><strong>*Собрать сейчас*</strong></code> and build will be started.
When the assembly is completed, the allure report becomes available.

<p align="center">
  <img src="media/logo/allure_rest.png" alt="Jenkins" width="800">
</p>


<a id="allure-report"></a>
## <img width="4%" title="Allure Report" src="media/logo/Allure.svg"> Test results report in [Allure Report](https://jenkins.autotests.cloud/job/pilulka/30/allure/)

From <code><strong>Jenkins</strong></code> it is possible to switch to reports generated by <code><strong>Allure</strong></code>

<p align="center">
  <img src="media/logo/rest_report.png" alt="jenkins-allure" width="900">
</p>

<a id="allure-testops"></a>
## <img width="4%" title="Allure TestOPS" src="media/logo/Allure_TO.svg"> Integration with [Allure TestOps](https://allure.autotests.cloud/launch/18709)

## Test-cases

<p align="center">
  <img src="media/logo/rest_allure.png" alt="testops" width="800">
</p>

<a id="jira"></a>
## <img width="4%" title="Jira" src="media/logo/Jira.svg"> Integration with [Jira](https://jira.autotests.cloud/browse/HOMEWORK-490)

<p align="center">
  <img src="media/logo/jira_rest.png" alt="jira-project" width="800">
</p>

<a id="telegram"></a>
## <img width="4%" title="Telegram" src="media/logo/Telegram.svg"> Telegram notifications using a bot
After passing all the tests, an automatic report is sent to the <code>Telegram</code> messenger

<p align="center">
<img title="Telegram Notifications" src="media//logo/telegram_rest.png" width="500">
</p>



[Вернуться к оглавлению ⬆](#Ссылка)
