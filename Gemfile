source "https://rubygems.org"

gem "zapr", github: 'matteverson/zapr'

# Install vendored projects gems
Dir.glob(File.join(File.dirname(__FILE__), 'vendor', '**', "Gemfile")) do |gemfile|
  eval(IO.read(gemfile), binding)
end
