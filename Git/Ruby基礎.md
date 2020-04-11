# while文
while &nbsp;繰り返し続ける条件 &nbsp;do\
  &emsp;繰り返したい処理\
end

```Ruby
i = 10
while i <= 10 
  puts i
  i = i + 1
end
```

# timesメソッド
繰り返す回数.times &nbsp;do\
  &emsp;繰り返したい回数\
end

繰り返しの回数が決まっている時は、「timesメソッド」を使うとシンプルにできる！\
「do」は省略できない。

「All work and no play makes Jack a dull boy.」と100行表示する
```Ruby
100.times do
putst "All work and no play makes Jack a dull boy."
```
