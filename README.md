tx3TagCloud
===========

very simple tag cloud jQuery Plugin. [Live Demo](http://tuxes3.github.io/tx3TagCloud/).

# Usage

```html
	<ul id="tagcloud">
      <li data-weight="50"><a href="#">HTML5</a></li>
      <li data-weight="24"><a href="#">Sharepoint</a></li>
      <li data-weight="28"><a href="#">Silverlight</a></li>
      <li data-weight="32"><a href="#">CSS3</a></li>
      <li data-weight="38"><a href="#">ASP.NET</a></li>
      <li data-weight="60"><a href="#">.NET</a></li>
      <li data-weight="38"><a href="#">C#</a></li>
      <li data-weight="27"><a href="#">VB.NET</a></li>
      <li data-weight="47"><a href="#">MySql</a></li>
      <li data-weight="30"><a href="#">SQL 2008</a> </li>
      <li data-weight="37"><a href="#">html</a></li>
      <li data-weight="60"><a href="#">jQuery</a></li>
      <li data-weight="40"><a href="#">WCF</a></li>
      <li data-weight="38"><a href="#">C#</a></li>
      <li data-weight="47"><a href="#">VB.NET</a></li>
      <li data-weight="20"><a href="#">Visual Studio 2008</a></li>
      <li data-weight="21"><a href="#">SharePoint Designer 2010</a></li>
      <li data-weight="27"><a href="#">Visual Studio 2010</a></li>
      <li data-weight="47"><a href="#">Oracle 9i</a></li>
	</ul>
```
```javascript
	// default multiplier is "1"
	$(document).ready(function(){
		$("#tagcloud").tx3TagCloud({
			multiplier: 5
		});
	});
```

# Result
![tx3 cloud tag result](https://cloud.githubusercontent.com/assets/5341293/2799865/2916b19a-cc68-11e3-8123-b128541c88e5.PNG)
