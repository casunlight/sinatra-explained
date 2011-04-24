I write this while I dig into sinatra source code myself. Please correct me if you find any mistakes or unclarity. Since Sinatra is short and concise, I hope the tutorial makes sense and it can keep pace with sinatra development with contributions from the community. The tutorial is prepared based on Sinatra 1.3.0c. 

If you want to run the tutorial, first do a bundle install, and then use command like bundle exec ruby app/tutorial_1/tutorial_1.rb
Sinatra is added as a git submodule in the sinatra folder.
As this tutorial is for sinatra, I don't include the full rack source. I only list some relevant code based on rack 1.2.2 (https://github.com/rack/rack/tree/1.2.2).
If you need I recommend to use tux to play with sinatra https://github.com/cldwalker/tux

It's assumed that you have read the sinatra README. Sinatra is well documented so that's the only thing you need for this tutorial.

Content:
________

* tutorial_1: sinatra start up(done)
* tutorial_2: extensions(work in progress)
* tutorial_3: routing(work in progress)
* tutorial_4: response
* tutorial_5: request cycle
* tutorial_6: templates