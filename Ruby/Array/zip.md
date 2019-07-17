zipメソッドは、配列の要素を引数の配列other_arrayの要素と組み合わせ、配列の配列を作成して返します。
transposeメソッドで[array, other_array, ...].transposeとしたときと同じく、行と列を入れ替えます。
ただし、transposeメソッドと違って足りない要素はnilで埋められ、余分な要素は捨てられます。

```ruby.rb
arr1 = [1, 2, 3]
arr2 = [4, 5]
arr3 = [6, 7, 8, 9]
p arr1.zip(arr2, arr3)
```
```bash
[[1, 4, 6], [2, 5, 7], [3, nil, 8]]
```

## 参照
https://ref.xaio.jp/ruby/classes/array/zip
