require "rake/packagetask"

Rake::PackageTask.new('theme', :version => :noversion) do |t|
  t.need_tar_gz = true
  t.package_files.include("src/**/*")
  t.package_dir = "package"
end
