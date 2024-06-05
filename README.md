# WDXcodeCodeSnippet
ios代码片段，可用于多台设备的xcode同步代码片段

#### 首次同步
`git clone git@github.com:15837003633/WDXcodeCodeSnippet.git`

`cd WDXcodeCodeSnippet`
#### 把xcode的/Users/mac/Library/Developer/Xcode/UserData/CodeSnippets 软链接到 WDXcodeCodeSnippet/CodeSnippets
`./setup_snippets.sh`

#### 日常更新场景
第一步：A电脑的Snippet有变化时，push到github

`git push origin main`

第二步：B电脑pull一下就ok了

`git pull origin main`
