Dowonload and instal these software/tools to run this project :
- CMDer
- Atom text editor
- Ruby 
- Chrome

URL refs:
- https://atom.io/
- https://github.com/cmderdev/cmder/releases/download/v1.3.2/cmder.zip
- https://dl.bintray.com/oneclick/rubyinstaller/rubyinstaller-2.3.3-x64.exe
- https://dl.bintray.com/oneclick/rubyinstaller/DevKit-mingw64-64-4.7.2-20130224-1432-sfx.exe

After instal all tools/software, open CMDer and install gems :
$> gem install bundler
$> gem install selenium-webdriver
$> gem install cucumber
$> gem install rspec

Then download chromedriver, extract and put on Ruby directory > bin  because we using chrome,then set the path :
System Properties > Advance System Settings > Environment variables > System Variables > Path > (input chrome driver address)

Then make your project directory for example :D/automation, open CMder and go to those directory and type command "cucumber --init"

Open Atom editor and open automation folder then create steps.rb at step_definiton folder and maake feature file at features folder.

See my example search.feature and steps.rb

Write cucumber at CMDer an now your automation will running.
