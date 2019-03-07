以下のとおりに表示されるよう、Markdown記法で書いてください。

[comment]: # (This is a comment)


----

1. `トップ`のリスト項目
    - ネストしたリスト項目
      - 更にネストしたリスト項目

----

* リスト項目1

      func main() {
          fmt.Println("Hello")
      }
      
      func (c *Comment) GetComment() string {
          return "some comment"
      }

* リスト項目2

    ```go
    func main() {
        fmt.Println("Hello")
    }
      
    func (c *Comment) GetComment() (comment string) {
        comment = "some comment"
        return
    }
    ```

----

*you-should-be-gopher*

\*you-should-be-gopher\*

----

~~取り消し線（GFM記法）~~

----

GitHub  
https://github.com/

[GitHub](https://github.com/)

次は外部参照リンクを使って記述すること。

[GitHub](GitHub)

[GitHub]: https://www.github.com

----

**OKです** :+1:

----

- [x] 完了済み項目
- [ ] 未完了項目

----

> 引用  
> 引用
>> 多重引用

----

| 左揃え | 中央揃え | 右揃え |
|:---|:---:|---:|
|100 |200 |300 |
|400 |500 |600 |

----

画像にマウスカーソルを合わせて、画像のタイトルが表示されるのを確認してください。

![代替文字列](https://gophercises.com/img/gophercises_jumping.gif "タイトル")

画像のURL  
https://gophercises.com/img/gophercises_jumping.gif

<img src="https://raw.githubusercontent.com/ashleymcnamara/gophers/master/GO_LEARN.png" alt="gopher" title="タイトル" width="200" height="200">

画像のURL  
https://raw.githubusercontent.com/ashleymcnamara/gophers/master/GO_LEARN.png
