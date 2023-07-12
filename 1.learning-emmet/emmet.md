# Emmet shortcuts



### 1. auto complete html tags
> type p / div / button and hit enter


### 2. add class

>.group
```
 <div class="group"></div>
```

> div.purple
```
  <div class="purple"></div>
```

> type a.button-link
```
  <a href="" class="button-link"></a>
```

### 3. add id
> type div#header-center
```
  <div class="purple"></div>
```


### 4. combination of class and id
> type div.class-1.class-2#nav-bar
```
  <div class="class-1 class-2" id="nav-bar"></div>
```


### 5. button and type
> button[type=button]
```
  <button type="button"></button>
```


### 6. Nested elements and css
> div.purple>h1.header
```
  <div class="purple">
    <h1 class="header"></h1>
  </div>
```

> div#profile-avatars>ol>li*3
```
  <div id="profile-avatars">
    <ol>
      <li></li>
      <li></li>
      <li></li>
    </ol>
  </div>
```

> div#profile-avatars>ol>li*3{lorem}
```
  <div id="profile-avatars">
    <ol>
      <li>lorem</li>
      <li>lorem</li>
      <li>lorem</li>
    </ol>
  </div>
```

### 7. List items
> li*2{student $ is absent}
```
  <li>student 1 is absent</li>
  <li>student 2 is absent</li>
```

> ol>li*3.class-$-avatar
```
  <ol>
    <li class="class-1-avatar"></li>
    <li class="class-2-avatar"></li>
    <li class="class-3-avatar"></li>
  </ol>
```


> div.professional-footballers>ul>li*3{player $}
```
  <div class="professional-footballers">
    <ul>
      <li>player 1</li>
      <li>player 2</li>
      <li>player 3</li>
    </ul>
  </div>
```

### 8. Multi-Nested elements
> div.banner>h1+div.title+div#subtitle>p
```
  <div class="banner">
    <h1></h1>
    <div class="title"></div>
    <div id="subtitle">
      <p></p>
    </div>
  </div>
```


### 9. Forms
> .group>input:b
```
  <div class="group"><input type="button" value=""></div>
```


>.form-submit>input:text
```
  <div class="form-submit"><input type="text" name="" id=""></div>
```


>.test>label+input:text
```
  <div class="test"><label for=""></label><input type="text" name="" id=""></div>
```

### 10. List with 2 nested elements
> .ul>li*3>img+a+p
```
    <ul>
      <li>
        <img src="" alt=""><a href=""></a>
        <p></p>
      </li>
      <li>
        <img src="" alt=""><a href=""></a>
        <p></p>
      </li>
      <li>
        <img src="" alt=""><a href=""></a>
        <p></p>
      </li>
    </ul>
```
