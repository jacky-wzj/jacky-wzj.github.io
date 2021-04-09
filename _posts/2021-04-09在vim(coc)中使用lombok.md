---
tilte : 在vim（coc）中使用lombok
layout: post
---
<style>
table, td, th {
  border: 1px solid black;
}

table {
  width: 100%;
  border-collapse: collapse;
}
</style>

lombok是在编译时生成代码注入程序，coc是基于language server protocol的开发平台。
coc-java通过java.jdt.ls 实现java的lsp , 那么为了支持lombok只需在编译前将lombok.jar追加到依赖包。
方法一：`-javaagent:/path/lombok.jar`
方法二: `-Xbootclasspath/a:/path/lombok.jar`

