SYMLINKS = %w(
  zsh/zshrc
  tmux/tmux.conf
).freeze

task :symlink do
  puts SYMLINKS.inspect

  Dir["./**/*"].each do |file|
    puts File.expand_path(file)
  end
end

task :default => [:symlink]