## GOG's git server addon

---


#### Very Important. There is No WaRRanty
#### It's my first project on ```go``` and can contain errors.

---

<br/>

It's contains a custom ```Webhooks``` addon.

<br/>
<br/>

### Patch & Build

1. doWnload ```gogs```
<pre>
    git clone --branch=v0.13.0 https://github.com/gogs/gogs.git
</pre>

1. dOwnload & cOpy ```gogs-git.patch```
<pre>
    git apply --ignore-whitespace {PATH_TO}/gogs-git.patch
</pre>

2. bUild ```gogs```
* PS: I'm not familiar with ```go``` language, so is better to look at the instruction on ```gogs``` homepage. 

<pre>
    go get
    go build
</pre>

<br/>


<img src="img/img_cmds_01.png" width="320">

---

### HOWTO:

Choose custom hook

<img src="img/img_05.png" width="320">

To time it's working with POST, GET, PATCH, DELETE, PUT http-methods.

<img src="img/img_01.png" width="320">

With RAW json-requests you can trigger systems like Jenkins, TeamCity and so on...

<img src="img/img_02.png" width="320">

The respOnse that you can see in the next image is just made by a python script that i have wrote for tests.

<img src="img/img_03.png" width="320">

And there is a simple output in python script. 

<img src="img/img_04.png" width="320">

