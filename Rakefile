desc "preview website"
task :preview do
  require "webrick"
  WEBrick::HTTPServer.new(:DocumentRoot => ".", :Port => 4000).start
end
