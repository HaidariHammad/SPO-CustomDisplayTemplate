# SPO-CustomDisplayTemplate
Return link to View/Edit properties of an Item in the hover panel. 

Create custom display template 
Follow below step to create custom word document hover panel with View and Edit Properties button
1.	Make sure publishing future activated on your site/web
 ![Screen Shot 2019-07-15 at 3 41 16 PM](https://user-images.githubusercontent.com/27656163/61243961-1c284b80-a717-11e9-886c-4a5623702dc9.png)
 
2.	Go to your search display template in your site
a.	{Site Url}/_catalogs/masterpage/Display Templates/Search
b.	Click on file upload from ribbon button to upload display template. Please don’t rename any file
 
 ![Screen Shot 2019-07-15 at 3 41 23 PM](https://user-images.githubusercontent.com/27656163/61243959-1c284b80-a717-11e9-957e-72ea81b9050c.png)
 
c.	Upload both file one by one
i.	Item_word_custom.html
ii.	Item_Word_HoverPanel_custom.html
d.	Publish both files. If js file crated with same name, then it’s publish successfully.
 ![Picture1](https://user-images.githubusercontent.com/27656163/61243986-3530fc80-a717-11e9-9131-0ed1344d39a9.png)

3.	Configure search result webpart on site
a.	Add search result web part on your page. If already added, then skip this step
b.	Edit web part
![Screen Shot 2019-07-15 at 3 45 05 PM](https://user-images.githubusercontent.com/27656163/61244193-a2dd2880-a717-11e9-86c5-ebf0fe634aa9.png)
 
c.	Configure your search web part query as per your requirement
d.	Expand Display Template option and Check radio button “Use a single template to display item”
 ![Screen Shot 2019-07-15 at 3 45 10 PM](https://user-images.githubusercontent.com/27656163/61244192-a2449200-a717-11e9-9889-b4a298a0a5b2.png)

e.	Select display item template with name “Custom Word Item Display Templates”
 ![Screen Shot 2019-07-15 at 3 45 16 PM](https://user-images.githubusercontent.com/27656163/61244191-a2449200-a717-11e9-84e5-fa806e48e201.png)

f.	Apply changes and Save
4.	After configuration when we hover on search result item the hover panel will look like as shown below
 
![Screen Shot 2019-07-15 at 3 48 22 PM](https://user-images.githubusercontent.com/27656163/61244390-1d0dad00-a718-11e9-902a-9edd6e9003c9.png)

