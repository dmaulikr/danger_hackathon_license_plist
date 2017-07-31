# Warn when there is a big PR
warn("Big PR") if git.lines_of_code > 500

podfile_updated = !git.modified_files.grep(/Podfile/).empty?

if podfile_updated
  message("Podfile did update")
end

