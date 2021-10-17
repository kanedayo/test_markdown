# Mardownの文法
- 段落/改行/見出し
- 強調/斜体
- コード
- リスト
- リンク
- 引用

# 段落/改行/見出し
## H2 
### H3 
行末に半角スペースを2個置くと改行される。
行末に半角スペースを2個置くと  
改行される。

# 強調/斜体
 **強調**
*斜体*
 `<p>段落</p>`

# コード
    //半角スペース4個を行頭に挿入
    int main(void){
        return 0;
    }

```c
//半角スペースなし
int main(void){
    return 0;
}
```

# リスト
- リスト
- リスト
- リスト
    - 半角スペース4個を行頭に挿入
    - 半角スペース4個を行頭に挿入

# リンク
[Google](https://www.google.co.jp/)  
![価格.com](https://img1.kakaku.k-img.com/images/logo.png)  
脚注[^1]を記載することもできる
GitHubMarkdown[^2]

[^1]:https://google.com
[^2]:https://help.github.com/articles/markgown-basics/

# 引用
> 引用文
