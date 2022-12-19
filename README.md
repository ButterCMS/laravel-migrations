# laravel-migrations

## Important Notice
This project was created as an example use case of ButterCMS in conjunction with a blog article, [The Ultimate Guide to Laravel Migrations](https://buttercms.com/blog/laravel-migrations-ultimate-guide/), and will not be actively maintained. 

If you’re interested in exploring the best, most up-to-date way to integrate Butter into PhP frameworks like Laravel, you can check out the following resources:

### Starter Projects

The following turn-key starters are fully integrated with dynamic sample content from your ButterCMS account, including main menu, pages, blog posts, categories, and tags, all with a beautiful, custom theme with already-implemented search functionality. All of the included sample content is automatically created in your account dashboard when you sign up for a free trial of ButterCMS.
- [Laravel Starter](https://buttercms.com/starters/laravel-starter-project/)
- [Angular Starter](https://buttercms.com/starters/angular-starter-project/)
- [React Starter](https://buttercms.com/starters/react-starter-project/)
- [Vue.js Starter](https://buttercms.com/starters/vuejs-starter-project/)
- Or see a list of all our [currently-maintained starters](https://buttercms.com/starters/). (Over a dozen and counting!)

### Other Resources
- Check out the [official ButterCMS Docs](https://buttercms.com/docs/)
- Check out the [official ButterCMS API docs](https://buttercms.com/docs/api/)

## Project Summary

Database schemas can be modified from their existing state to the desired state via migrations. This can include adding tables and columns, removing items, or altering types and constraints.

For instance, if you're working on a team project and need to modify the application requirements, you might want to consider altering the database.

Usually, an updated .sql file is shared with each team member to import into their databases. However, this approach is neither ideal nor scalable because many things could go wrong and leave the application broken. For example, a team member can forget to import the file into their database, or even import an outdated version of the .sql file.

Migrations act like version control for your database, allowing your team to share and define the schema of your application's database. Laravel migrations are essential because they help you tackle such database collaboration issues for a team. Your team members won't need to manually update their database whenever they pull your changes from source control.

In this tutorial, you will learn the importance of migrations in your Laravel application as well as the various benefits of Laravel migrations along with use cases. You will also learn various migration actions, commands, and events....[Read More](https://buttercms.com/blog/laravel-migrations-ultimate-guide/)
