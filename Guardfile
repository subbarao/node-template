guard 'shell' do
  watch(%r{^(test/.*_test\.coffee)$})   { |m| system("make test") }
  watch(%r{^lib/(.+)([^/]+)\.coffee$})  { |m| system("make test") }
end
