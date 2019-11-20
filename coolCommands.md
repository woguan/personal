Kill all xcode proccess:

ps -fea | grep -i xcode | grep -v grep | tr -s " " ":" | cut -d ":" -f3 | awk '{ print "kill -9", $0 }' | bash



Find all files of a specific extension:

 find . -type f -name "*.plist"



Remove cache:

rm -rf ~/Library/Caches/Cocoapods /tmp/Cocoapods



Show last commit:

git log -n 1



Show a specific commit info:

git show {commit hash}



modify last commit:

git commit --ament



Read gitsubmodule... then get the file name:

grep "path =" .gitmodules | cut -d "=" -f2 | cut -d " " -f2



Entitlement:

https://developer.apple.com/library/archive/technotes/tn2318/_index.html#//apple_ref/doc/uid/DTS40013777-CH1-TNTAG68
