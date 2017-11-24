#find and grep, this will also print the matched content of file
find . -type f -exec grep "react" -R {} \; -and -print

#only find in file package.json
find . -type f -name package.json -exec grep "react" -R {} \; -and -print
