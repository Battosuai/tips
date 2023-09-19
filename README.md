# Github Tips

### Search

**Command:** `is:issue is:open label:beginner` - will list all issue that are open and labeled `beginner`

`in:name`. Let's say I am looking for resources to learn about Data Science. In this case command would be `Data Science in:name` which will return list of repo with Data Science in the repo name.

`in:description`. Let's say I am looking for resources to learn about Data Science. In this case command would be `Data Science in:description` which will return list of repo with Data Science in the repo description.

`in:readme`. Let's say I am looking for resources to learn about Data Science. In this case command would be `Data Science in:readme` which will return list of repo with Data Science in the repo readme.

`in:topic`. Let's say I am looking for resources to learn about Data Science. In this case command would be `Data Science in:topic` which will return list of repo with Data Science in the repo topic.

### Find by Stars, Forks

Using `stars:n`. For searching repo with 1000 stars, it would be `stars:1000`

Using `forks:n`. For searching repo with less than 1000 forks, it would be `forks:<1000`

### Find by Language

Using `language:LANGUAGE`. For example if I want to find repositories written in PHP, search will be: `language:PHP`

### Find by Organization Name

`org:freecodecamp`

### Find by Date

Search using these keywords `created`,`updated`,`merged`,`closed`. Date format `YYYY-MM-DD`

Take an instance where I want to make a search of all repositories with the word freeCodeCamp that were created after 2022-10-01. Then search will be `freecodecamp created:>2022-10-01`

### Find by License

`license:LICENSE_KEYWORD`
