# overview

html content for the overview is pulled directly from the **overview** post.
- https://forum.metastock.com/posts/t155735-overview

sessions
- https://forum.metastock.com/topics/756-sessions

each session is a post in the **sessions** folder.

post titles need to be formated exactly this way:

> SESSION TITLE - PRESENTER NAME - TIME

for example:

> Q&A Session - Jeff Gibby - 5:00 PM EST

the post contents needs to have this format (click Source in post editor for html):

```html
<div rel="presenter-200px.jpg">

    <p>Bla bla bla... any forum-safe html can go here.</p>

</div>
```


----


***ON THE WEBSITE***, alias.xml is involved.    Here is last year's HongKong2019 entry:
```xml
<promo whc="hongkong2019" alias="dyn-summit" expires="2/27/2019" due="2/27/2019" title="Hong Kong Seminar"
				banner="hongkong2019.jpg" banner-width="1100" banner-height="473" forum="755" overview="155735" sessions="756" >
	<venue>
		<h2>The Excelsior - Hong Kong</h2>
		<p>281 GLOUCESTER ROAD, CAUSEWAY BAY<br/>3rd Floor<br/>Tel:852 2894 8888</p>
		<p>One of the most famous hotels in Hong Kong, The Excelsior enjoys a fantastic location in Causeway Bay. Combining high style with elegant harbour living, our stylish décor, excellent facilities and fantastic service create a first-class experience.</p>
		<a href="https://www.mandarinoriental.com/hong-kong/the-excelsior/luxury-hotel" rel="nofollow" title="Follow link">Find out more</a>
		<h3>You could easily spend days in Causeway Bay</h3>
		<p>One of the busiest neighborhoods on Hong Kong Island. Jam-packed with restaurants and shops, but also featuring Hong Kong’s main library, as well as the Island’s largest public park, there truly is something for everyone. Such as:</p>
		<ul><li>Food Street</li><li>Shopping</li><li>Victoria Park</li><li>Tin Hau Temple</li><li>Ride the Ding Ding</li></ul>
	</venue>
	<venue2>
		<amp-img width="600" height="600" layout="responsive" src="//metastock.com/images/i/excelsior-hongkong.jpg"></amp-img>
	</venue2>
</promo>
```
