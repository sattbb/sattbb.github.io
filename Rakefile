desc "Build Jekyll site and push to master"
task :update do
  system "jekyll build"
  system "cp -r _site/* ../tmp/"
  system "git stash -u"
  system "git checkout master"
  system "rm -r ./*"
  system "mv ../tmp/* ./"
  system "git add --all"
  system "git commit -m \"updated site\""
  system "git push origin master"
end
