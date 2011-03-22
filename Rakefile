task :default => :deploy
 
desc 'Deploy'
task :deploy do
  sh 'rsync -rtzh --progress --delete _site/ blue:/home/kale/public_html/hackernewsletter.com/public/'
end
