# go-hello-world
---
>> Write in the head:
>> Because i'm just a beginner start learning go, this document may more useful for those beginner like me, it's is pleasure to get any advice if you get any wrong or have an better idea
--
1. Install the go runtime;[Download](https://golang.org/dl)
2. Set your GOROOT, GOPATH and GOBIN environment variables, for example
	+ GOROOT: $GO_INSTALL_DIR/
		+ This is the directory you installed the go runtime
	+ GOPATH: $WORKSPACES/
		+ It's get a little complex to explain it usage(English is not my mother tongue), you can image it just like a nodejs project working directory(Ofcourse a little different i thought), all the source code are lying under src directory(maybe those big project got a different structure?).still, i make a directory under the **src** for my project root.[See Detail](https://golang.org/doc/code.html#Workspaces)
	+ GOBIN: $WORKSPACE/bin
		+ Yeah, I set this environment varibale like that.As the offical document says, when you build a go program, the executable can be found in here
3. Command:**go install $GOPATH/src/${your_project}** or **cd $GOPATH/src/${your_project}** then execute **go install**
4. It should be execute very fast. when it's done, you can go to the $GOBIN find your executable, execute it
5. See the print "Hello World". haha.. wish i got noting left
