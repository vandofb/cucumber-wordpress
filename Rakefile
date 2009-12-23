begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.version = "1.1"
    gem.name = "cucumber-wordpress"
    gem.summary = %Q{Environment setup and step definitions for testing WordPress with Cucumber}
    gem.email = "tom@thedextrousweb.com"
    gem.homepage = "http://github.com/dxw/cucumber-wordpress"
    gem.authors = ["Tom Adams"]
    gem.add_dependency "cucumber"
    gem.add_dependency "webrat"
    gem.add_dependency "mysql"
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: sudo gem install jeweler"
end
