modx-rss-feed
=============

Create a RSS Feed of your MODX Resources

---

###Create Page Template

Use the **rss_Template.xml** file in this repo. Nothing special to setup. 

---

###Create Chunk Template

Use the **rss_Chunk.html** file in this repo. Nothing special to setup. 

---

###Create your RSS Feed Resource

 - Title example "News Feed"
 - Alias example "news"
 - Set Template
 - Settings -> "Content Type" == RSS
 - Settings -> Set Publish Date
 - Not Rich Text, Not Searchable, Not Cacheable, Not Container

**Content:**

```
[[getResources? &parents=`XXX` &tpl=``]]
```

---

###Test your Feed:

http://feedvalidator.org/
