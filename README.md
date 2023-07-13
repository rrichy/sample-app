### Add `sail` alias
`echo "alias sail='[ -f sail ] && sh sail || sh vendor/bin/sail'" >> ~/.bashrc`

### To run the laravel project
Run `sail up`, this will generate the docker containers.
App will run on default http://localhost

### To remove containers
Run `sail down`





### Helpful vscode extensions
- PHP Intelephense
- Laravel goto view
- Laravel Extra Intellisense
- Laravel Snipepts