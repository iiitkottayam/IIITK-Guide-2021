# First Commit

You might now know that we need to upload our code in github for other people to see and use it. It's like sharing and caring the community which gives you many things. 


We made a [meme page](https://joshi008.github.io/gitify-meme/)

Now your task is to add a meme ;) 

Google search any meme or reddit search it or any thing => We want a link of image

Now follow the below steps:

1. Fork this [repository](https://github.com/joshi008/gitify-meme)
2. Clone it into PC
3. Always it is best practise to work in a development branch rather than a main branch.
4. Create a new branch 
```
git branch [branch-name]
```
5. Change branch
```
git checkout [branch-name]
```

6. Now open index.html in a text editor (Notepad, VS code anything you like)

7. There will be an option saying **Add below this line <=**, add the following code below it and replace [image-url] to your meme url. 

```
<div class="gallery-item">
    <div class="content"><img src="[image-url]"></div>
</div>
```

 8. Now that you have added this, go to you terminal or git. Then 

```
git add .
```
to add it for commiting phase.

-----------

```
git commit -m "added meme"
```
to commit changes

-----------


 9. Now you have commited changes to your side branch. Merge it to main branch by: 

```
git checkout main
```
-----------
```
git merge [branch-name]
```

----------
```
git push
```
to push the changes

 10. Now that you have merged it to main the last thing to do is to give a pull request to the fork owner. 

-----------

 11. Head over to github forked repository and create a pull request. 


------------

Worry not if you are stuck on your way it will be done by seniors as well. :)