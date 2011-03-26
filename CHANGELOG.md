
== Fri Mar 25 23:58:48 CET 2011

Lauranovara namespace (Lauranovara::Application) was erroneously leaved here, during the porting to Rails3. It seems correct to me step back to the original name space Grokphoto::Application

=== Here are the file changed:

lsoave@ubuntu:~/rails/github/grokphoto$ find . -exec grep Lauranovara {} \; -print | grep ^./
./app/views/layouts/application.html.erb
./config.ru
./Rakefile
./config/environments/test.rb
./config/environments/production.rb
./config/environments/development.rb
./config/routes.rb
./config/environment.rb
./config/initializers/session_store.rb
./config/initializers/secret_token.rb
./config/application.rb
lsoave@ubuntu:~/rails/github/grokphoto$

