# A sample Guardfile
# More info at https://github.com/guard/guard#readme



# Add files and commands to this file, like the example:
#   watch(%r{file/path}) { `command(s)` }
#

ignore_paths '.git'

guard 'shell' do
  watch(/(.*)/) {|m| `git add -u;git add -A;git commit -m "auto upload";git push;git gc` } 
end
