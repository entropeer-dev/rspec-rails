class Rails < Thor
  desc "checkout VERSION", "checks it out"
  def checkout(version)
    puts "***** checking out rails at #{version} ..."
    Dir.chdir("vendor/rails") do
      `git checkout #{version}`
    end
  end

  desc "fetch", "update vendor/rails"
  def fetch
    Dir.chdir("vendor/rails") do
      `git fetch`
    end
  end
end