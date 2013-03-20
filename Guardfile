# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard 'livereload' do
  watch(%r{^stylesheets/.+\.css$})
  watch(%r{^.+\.html$})
end

guard 'compass', :configuration_file => 'config.rb' do
  watch(%r{^sass/.+\.s[c|a]ss})
end

guard 'coffeescript', :input => 'coffeescripts', :output => 'javascripts'
