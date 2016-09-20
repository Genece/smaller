### 干嘛用的？
图片压缩一直是前端的痛点，tinypng时常会变慢，智图压缩率不够高，怎么办！？怎么办？！现在smaller来了，一个命令，图片压缩本地化，统统搞定。

### 使用者是如何说的？
真的，自从使用了smaller，我可以单机压图片了，开发更高效了，简直是瞬间完成，还自动给原图备份，真是前端开发者的福音啊。

### 其他人呢？
啊，从今天开始，就用smaller了！

### 安装

可以在组里搞1台开，其他人只要使用它就行了

```
docker pull h2non/imaginary
docker run -p 9000:9000 h2non/imaginary -cors -gzip
npm i -g smaller
```

### 使用

cd到image目录

```
smaller
```

### 欢迎issues，欢迎fork
欢迎各路大神来写图片压缩算法，再把我教会，那你就是哈佛的老师了，因为会图片压缩算法就可以去哈佛了(来自百度知道--求教图片算法)

#English

###Why smaller
Smaller is a tool what make your images free up massive storage space.it's so fast and smarter.In the past time,front-end Web developer always use
Tinypny to compressed pictures,it's very slow and compression ratio is not enough.But now we developed Smaller to resolve all problems,just run commands in your
terminal,you could compress images in your local and needn't depend on network!