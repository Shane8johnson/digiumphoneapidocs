<div class=WordSection1>

<h1>app.json File</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<p>This file describes the application and provides specific settings used by
the app engine. Every application must include an app.json file in its
directory. The app.json file is a single file written in JSON notation. You
must use double quotes to identify object keys and values in your app.json
file.</p>

<h2 id=app.jsonFile-Description>Description</h2>

<p><strong>Required:</strong>&nbsp;The app.json file must contain the following
information:</p>

<p><strong>name</strong>&nbsp;<br>
The name of the app. This is how the app engine refers to the app. name must be
64 chars or less, and the first character must be a letter or a digit. The rest
can be letters, digits, underscore, period, comma. We recommend all lowercase,
but that's not required.</p>

<p><strong>jsFiles</strong>&nbsp;<br>
The JavaScript file to load when the app starts. You may include multiple
files, they are loaded and run in left-to-right order. It is not necessary to
list language files here.</p>

<p><strong>type</strong>&nbsp;<br>
The type of app, which is always&nbsp;<strong>foreground</strong>.</p>

<p>Also, this information can be included as appropriate:</p>

<p><strong>displayName</strong>&nbsp;<br>
This is how the app name is displayed in various places (e.g., the Applications
screen). If this is not included,&nbsp;<strong>name</strong>&nbsp;is used.</p>

<p><strong>iconFile</strong><br>
Default icon file basename. The phone looks for D70.hello_world_icon.png first,
on a D70, and likewise for other models. The icon can be dynamically set by the
app instead (or in addition), but this file will be used when the app is not
running.</p>

<p><strong>hasIdle</strong><br>
Indicate&nbsp;<strong>true</strong>&nbsp;if the app supports an idle screen
display mode.&nbsp;If you don't include this, or you indicate&nbsp;<strong>false</strong>,
the app cannot use the idle screen. The digium.app.idleWindow object is created
based on this.</p>

<p><strong>hidden</strong>&nbsp;<br>
Indicate&nbsp;<strong>true</strong>&nbsp;if the app should not appear in the
Applications screen.&nbsp;If you don't include this, or you indicate&nbsp;<strong>false</strong>,
the app does appear in the Applications Screen.</p>

<h2 id=app.jsonFile-Example>Example</h2>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=fdfe7d20-a5ba-46f1-a6f1-aee425ad7c9b>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;{</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;name&quot;: &quot;helloworld&quot;,</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;jsFiles&quot;: [&quot;file1.js&quot;],</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;type&quot;: &quot;foreground&quot;,</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;displayName&quot;: &quot;Hello, world!&quot;,</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;iconFile&quot;&nbsp; : &quot;hello_world_icon.png&quot;,</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;hidden&quot; : false,</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;hasIdle&quot;: true</pre><pre>}</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Features</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<p class=MsoNormal><img width=287 height=143 id="Picture 1"
src="Digium%20One%20Page_files/image001.png"></p>

<p><a href="/wiki/spaces/Phones/pages/21070123/Sangoma+Phone+App+Engine"
data-linked-resource-id=21070123 data-linked-resource-version=3
data-linked-resource-type=page>Sangoma Phone App Engine</a></p>

<p>The Sangoma Phone API&nbsp;lets you build custom apps for your phones using
the popular programming language&nbsp;<strong>JavaScript.&nbsp;</strong>And&nbsp;the
Sangoma Phone App Engine interprets and executes this JavaScript code.</p>

<p class=MsoNormal><img border=0 width=287 height=143 id="Picture 2"
src="Digium%20One%20Page_files/image002.png"></p>

<p><a href="/wiki/spaces/Phones/pages/21364905/Control+the+Display+on+the+Phone"
data-linked-resource-id=21364905 data-linked-resource-version=4
data-linked-resource-type=page>Control the Display on the Phone</a></p>

<p>The user interface and interaction tools let you control the display on the
phone and collect data from the user with menus and forms.</p>

<p class=MsoNormal><img border=0 width=287 height=143 id="Picture 3"
src="Digium%20One%20Page_files/image003.png"></p>

<p><a href="/wiki/spaces/Phones/pages/21233883/Integrate+with+Internet+Services"
data-linked-resource-id=21233883 data-linked-resource-version=4
data-linked-resource-type=page>Integrate with Internet Services</a></p>

<p>You can build AJAX functionality into custom apps to allow your phones to
retrieve data from or submit data to the internet (just like programming for a
website).</p>

<p class=MsoNormal><img border=0 width=288 height=144 id="Picture 4"
src="Digium%20One%20Page_files/image004.png"></p>

<p><a
href="/wiki/spaces/Phones/pages/20939751/Integrate+with+Your+Business+Applications"
data-linked-resource-id=20939751 data-linked-resource-version=3
data-linked-resource-type=page>Integrate with Your Business Applications</a></p>

<p>You can build custom apps that interact with your business applications to
improve customer service and productivity.&nbsp;</p>

<h1>Phone API Reference</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h1 id=PhoneAPIReference-D-SeriesPhoneAPIReferenceGuide>D-Series Phone API
Reference Guide</h1>

<p>The D-Series Phone API is a JavaScript toolset used to build custom apps.</p>

<p>At its most basic, a custom app is a&nbsp;<strong>zip</strong>&nbsp;file
that contains an&nbsp;<strong>app.json</strong>&nbsp;file and a<strong>&nbsp;JavaScript</strong>&nbsp;file.</p>

<h2 id=PhoneAPIReference-ZipFile>Zip File</h2>

<p>An app is packaged into a zip file. The zip contains the app.json file,
JavaScript file, and additional data (icons, language files, etc.). &nbsp;</p>

<p>A Sangoma Phone uses the zip file to install the app.</p>

<h2 id=PhoneAPIReference-app.jsonFile>app.json File</h2>

<p>Each app requires a JSON file named app.json. The JSON file describes to the
Sangoma Phone App Engine what the app is and what its settings are. See the
article&nbsp;<a href="/wiki/spaces/Phones/pages/21266665/app.json+File"
data-linked-resource-id=21266665 data-linked-resource-version=2
data-linked-resource-type=page>app.json</a>&nbsp;for details.</p>

<h2 id=PhoneAPIReference-JavaScriptFile>JavaScript File</h2>

<p>The following are the principal phone API modules comprising the toolset:</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><strong>Core</strong>&nbsp;- Basic building blocks of any Sangoma
Phone app. Used for functional programming.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><strong>Classes</strong>&nbsp;- Core classes available to every
app. &nbsp;Used for functional programming.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><strong>Extended</strong>&nbsp;- Libraries to add additional
functional methods to a Sangoma Phone app.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><strong>Extended Classes</strong>&nbsp;- Additional libraries to
add more functional class constructors.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><strong>UI Core (window)</strong>&nbsp;- Automatically defined
object that enables app display for every app at runtime.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><strong>UI Classes (Widgets)</strong>&nbsp;- Basic graphical
building blocks (class constructors).</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><strong>UI Extended</strong>&nbsp;- Additional tools for building
user interaction into your app.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><strong>UI Extended Classes</strong>&nbsp;- Additional UI class
constructors for creating more than basic UI elements.</p>

<p>Links to these modules and their libraries are in the sidebar. See the&nbsp;<a
href="/wiki/spaces/Phones/pages/21037362/Getting+Started+with+the+Phone+API"
data-linked-resource-id=21037362 data-linked-resource-version=3
data-linked-resource-type=page>Getting Started</a>&nbsp;page and the other&nbsp;<a
href="/wiki/spaces/Phones/pages/21266619/Phone+API+Guides"
data-linked-resource-id=21266619 data-linked-resource-version=4
data-linked-resource-type=page>Guides</a>&nbsp;for general instructions, and
the&nbsp;<a href="/wiki/spaces/Phones/pages/21102920/Phone+API+Demos"
data-linked-resource-id=21102920 data-linked-resource-version=5
data-linked-resource-type=page>Phone API Demos</a> &nbsp;for annotated sample
programs to give you custom app examples.</p>

<div>

<div>

<p>The phone app programming model is single-threaded, event-driven. Avoid
long-running processing loops because they limit the responsiveness of apps,
and after a few seconds, they will cause your app to be killed.</p>

</div>

</div>

<h1>Phone API Reference - Classes</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<p>These core object constructors are available to all apps without requiring
any libraries.&nbsp;Objects relating to UI elements are documented in&nbsp;<a
href="https://sangomakb.atlassian.net/wiki/spaces/Phones/pages/22708398?search_id=f76e72e4-047b-40d8-8aeb-589486088f3c">UI
Classes (Widgets)</a>.</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=968
 data-layout=default data-local-id=5ee257ea-7036-4dcd-8942-5509499f9cd5>
 <colgroup><col style="width: 127.0px;"><col style="width: 841.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/19992037/Phone+API+Reference+-+Classes+-+NetRequest"
  data-linked-resource-id=19992037 data-linked-resource-version=3
  data-linked-resource-type=page>NetRequest</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Makes HTTP and similar requests from JavaScript. This object is similar to
  the standard browser XMLHttpRequest object.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/21364947/Phone+API+Reference+-+Classes+-+DOMParser"
  data-linked-resource-id=21364947 data-linked-resource-version=3
  data-linked-resource-type=page>DOMParser</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Similar to the standard&nbsp;<a
  href="https://developer.mozilla.org/en-US/docs/DOM/DOMParser">DOMParser</a>.
  Used to parse an XML string into a DOM document that can be traversed and
  manipulated in the usual ways (getElementById(), appendChild(), etc).</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/20972003/Phone+API+Reference+-+Classes+-+XMLSerializer"
  data-linked-resource-id=20972003 data-linked-resource-version=2
  data-linked-resource-type=page>XMLSerializer</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Similar to standard XMLSerializer. Used to convert a DOM document into a
  valid XML string.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Classes - DOMParser</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Classes-DOMParser-DOMParser>DOMParser</h2>

<p>Similar to the standard&nbsp;<a
href="https://developer.mozilla.org/en-US/docs/DOM/DOMParser">DOMParser</a>.
Used to parse an XML string into a DOM document that can be traversed and
manipulated in the usual ways (getElementById(), appendChild(), etc).</p>

<h3 id=PhoneAPIReference-Classes-DOMParser-ClassConstructor>Class Constructor</h3>

<h4 id=PhoneAPIReference-Classes-DOMParser-DOMParser.1><u>DOMParser</u></h4>

<p>Create a new DOMParser object.</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=a7afcf02-211a-4fd4-b9b0-7498f2eeb5a7>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var parser = new DOMParser();</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h4 id=PhoneAPIReference-Classes-DOMParser-InitializationParameters>Initialization
Parameters</h4>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=552
 data-layout=default data-local-id=92c06b9f-8b4b-42af-8b87-562ff9b64691>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Classes-DOMParser-Methods>Methods</h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=530
 data-layout=default data-local-id=ab22c4c4-8694-419c-9abf-711ff772f05d>
 <colgroup><col style="width: 163.0px;"><col style="width: 367.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/19992025/Phone+API+Reference+-+Classes+-+DOMParser+-+parseFromString"
  data-linked-resource-id=19992025 data-linked-resource-version=2
  data-linked-resource-type=page>parseFromString</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Parse a string into a standard DOM Document.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Classes - DOMParser - parseFromString</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h1 id=PhoneAPIReference-Classes-DOMParser-parseFromString-parseFromString>parseFromString</h1>

<h2 id=PhoneAPIReference-Classes-DOMParser-parseFromString-Description>Description</h2>

<p>Parse a string into a standard DOM Document.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=db8edb91-c4bf-4bc9-8261-011dfb6e2438>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var parser = new DOMParser();</pre><pre>var document = parser.parseFromString('&lt;config&gt;&lt;test attr=&quot;value&quot; /&gt;&lt;/config&gt;');</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p><strong>Parameters</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=fe1d85b8-9231-4622-a587-04abb2eafdd2>
 <colgroup><col style="width: 94.0px;"><col style="width: 105.0px;"><col style="width: 113.0px;"><col style="width: 128.0px;"><col style="width: 315.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>xml</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>String containing valid XML.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Classes - NetRequest</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Classes-NetRequest-NetRequest><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>NetRequest</span></strong></h2>

<p>Makes HTTP and similar requests from JavaScript. This object is similar to
the standard browser XMLHttpRequest object.</p>

<h2 id=PhoneAPIReference-Classes-NetRequest-ClassConstructor><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>Class
Constructor</span></strong></h2>

<p>new NetRequest()</p>

<p>Constructs a new NetRequest Object.</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=30fa599d-bb4f-4a83-aca7-9bd450062c21>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var request = new NetRequest();</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Classes-NetRequest-InitializationParameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Initialization
Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=d4656934-56c7-4252-ab45-1dcde73e1094>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Classes-NetRequest-Methods><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=987
 data-layout=default data-local-id=3c26d463-b197-433d-8cc4-9e13b01d5098>
 <colgroup><col style="width: 160.0px;"><col style="width: 827.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/19992052/Phone+API+Reference+-+Classes+-+NetRequest+-+getResponseHeader"
  data-linked-resource-id=19992052 data-linked-resource-version=2
  data-linked-resource-type=page>getResponseHeader</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns the header field value from the response of which the field name
  matches header, unless the field name is Set-Cookie or
  Set-Cookie2.&nbsp;Returns null if either the response has not yet been
  received or the header doesn't exist in the response.&nbsp;</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/21070214/Phone+API+Reference+-+Classes+-+NetRequest+-+open"
  data-linked-resource-id=21070214 data-linked-resource-version=3
  data-linked-resource-type=page>open</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Sets the request method and request URL. This method differs from the
  standard XMLHttpRequest's open() method by only accepting two parameters (all
  requests are asynchronous, and the user/password are entered in the request
  object's&nbsp;user&nbsp;and&nbsp;password&nbsp;properties.)</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/21266681/Phone+API+Reference+-+Classes+-+NetRequest+-+send"
  data-linked-resource-id=21266681 data-linked-resource-version=2
  data-linked-resource-type=page>send</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Initiates the request. The optional argument provides the request entity
  body. The argument is ignored if request method is GET or HEAD.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/21266693/Phone+API+Reference+-+Classes+-+NetRequest+-+setRequestHeader"
  data-linked-resource-id=21266693 data-linked-resource-version=2
  data-linked-resource-type=page>setRequestHeader</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Appends a header to the list of author request headers, or if header is
  already in the list of author request headers, combines its value
  with&nbsp;value.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/21070240/Phone+API+Reference+-+Classes+-+NetRequest+-+setTimeout"
  data-linked-resource-id=21070240 data-linked-resource-version=2
  data-linked-resource-type=page>setTimeout</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Sets a timeout, after which the request will be aborted with a 500
  status.&nbsp;</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Classes-NetRequest-Properties><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Properties</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=987
 data-layout=default data-local-id=290ae818-7d97-4a70-b5ca-55876e7807c0>
 <colgroup><col style="width: 188.0px;"><col style="width: 799.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>oncomplete</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called at the end of the response. This is redundant to onreadystatechange
  with readyState=4.</p>
  <p>Basic Example:</p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>request.oncomplete = function() { util.debug('request is done'); }&nbsp;</pre></div>
  </div>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>onreadystatechange</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Event handler for readyState.</p>
  <p>Basic Example:</p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>request.onreadystatechange = function () {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;util.debug(request.readyState);</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;util.debug(request.status);</pre><pre>}</pre></div>
  </div>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>password</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Password used in the request, or null if there is no password.</p>
  <p>Basic Example:</p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>request.password = 'secret';&nbsp;</pre></div>
  </div>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>readyState</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns the current state.</p>
  <p>Basic Example:</p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;var currentState = request.readyState; // returns integer such as 200</pre></div>
  </div>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>responseFile</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>If present, along with responseLoc, the response body is placed in the
  file rather than in responseText.</p>
  <p>Basic Example:</p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>request.responseFile = &quot;text.txt&quot;;&nbsp;</pre></div>
  </div>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>responseLoc</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>If present, along with responseFile, the response body is placed in the
  file rather than in responseText.</p>
  <p>Basic Example:</p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>request.responseLoc = &quot;tmp&quot;;</pre></div>
  </div>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>responseText</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns the text response entity body.</p>
  <p>Basic Example:</p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var response = request.responseText;&nbsp;</pre></div>
  </div>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>status</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns the HTTP status code; such as 200 (success), 500 (internal server
  error), 404 (file not found), etc..</p>
  <p>Basic Example:</p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var statusCode = request.status;&nbsp;</pre></div>
  </div>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>user</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns the name of the user in the request, or null if there is no
  username. Sets the user for the request.</p>
  <p>Basic Example:</p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>request.user = &quot;username&quot;; //set username for request</pre><pre>request.user; //&quot;username&quot;</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Classes - NetRequest - getResponseHeader</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2
id=PhoneAPIReference-Classes-NetRequest-getResponseHeader-getResponseHeader><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>getResponseHeader</span></strong></h2>

<h3 id=PhoneAPIReference-Classes-NetRequest-getResponseHeader-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Returns the header field value from the response of which the field name
matches header, unless the field name is Set-Cookie or
Set-Cookie2.&nbsp;Returns null if either the response has not yet been received
or the header doesn't exist in the response.&nbsp;</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=6cd29ee5-c100-4028-86eb-32a14dc3f3dd>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;var headerValue = request.getResponseHeader(header);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Classes-NetRequest-getResponseHeader-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=d070f24c-e6f8-49ca-b542-67f2a75e62a6>
 <colgroup><col style="width: 78.0px;"><col style="width: 95.0px;"><col style="width: 71.0px;"><col style="width: 110.0px;"><col style="width: 406.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>header</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Name of the header as expected from the response.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Classes - NetRequest - open</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Classes-NetRequest-open-open><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>open</span></strong></h2>

<h3 id=PhoneAPIReference-Classes-NetRequest-open-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Sets the request method and request URL. This method differs from the
standard XMLHttpRequest's open() method by only accepting two parameters (all
requests are asynchronous, and the user/password are entered in the request
object's&nbsp;<a
href="/wiki/spaces/Phones/pages/19992037/Phone+API+Reference+-+Classes+-+NetRequest"
data-linked-resource-id=19992037 data-linked-resource-version=3
data-linked-resource-type=page>user</a>&nbsp;and&nbsp;<a
href="/wiki/spaces/Phones/pages/19992037/Phone+API+Reference+-+Classes+-+NetRequest"
data-linked-resource-id=19992037 data-linked-resource-version=3
data-linked-resource-type=page>password</a>&nbsp;properties.)</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=d4a74a6e-4d37-457e-bbb1-c2d85bb69dca>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>request.open(method, url);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Classes-NetRequest-open-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=f7d60839-423c-47e5-9a63-a2a7fda2f28d>
 <colgroup><col style="width: 85.0px;"><col style="width: 86.0px;"><col style="width: 61.0px;"><col style="width: 93.0px;"><col style="width: 430.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>url</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>URL to send the request to.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>method</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>HTTP method to use; such as GET or POST.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Classes - NetRequest - send</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Classes-NetRequest-send-send><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>send</span></strong></h2>

<h3 id=PhoneAPIReference-Classes-NetRequest-send-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Initiates the request. The optional argument provides the request entity
body. The argument is ignored if request method is GET or HEAD.</p>

<p style='margin-left:22.5pt'><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=b1c69726-a81e-4d06-888a-372be0eee761>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>request.send();</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Classes-NetRequest-send-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=ad71c296-be1f-4112-a87c-31a4574a7168>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Classes - NetRequest - setRequestHeader</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Classes-NetRequest-setRequestHeader-setRequestHeader><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>setRequestHeader</span></strong></h2>

<h3 id=PhoneAPIReference-Classes-NetRequest-setRequestHeader-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Appends a header to the list of author request headers, or if header is
already in the list of author request headers, combines its value with&nbsp;<strong>value</strong>.</p>

<p style='margin-left:22.5pt'><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=7d1096a6-8154-4554-8422-02b91f36fd85>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>request.setRequestHeader(header, value);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Classes-NetRequest-setRequestHeader-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=66517688-dc2f-49ab-9a22-8e40316857d3>
 <colgroup><col style="width: 75.0px;"><col style="width: 84.0px;"><col style="width: 63.0px;"><col style="width: 85.0px;"><col style="width: 448.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>header</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Name of the header to set.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>value</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>The value to set for the header</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Classes - NetRequest - setTimeout</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Classes-NetRequest-setTimeout-setTimeout><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>setTimeout</span></strong></h2>

<h3 id=PhoneAPIReference-Classes-NetRequest-setTimeout-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Sets a timeout, after which the request will be aborted with a 500
status.&nbsp;</p>

<p style='margin-left:22.5pt'><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=3c4e00f5-4363-46dc-aa0a-0a077883035e>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>request.setTimeout(milliseconds).</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Classes-NetRequest-setTimeout-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=894
 data-layout=default data-local-id=21d2bb3b-534c-4af2-a9b6-57bf2a019557>
 <colgroup><col style="width: 127.0px;"><col style="width: 105.0px;"><col style="width: 86.0px;"><col style="width: 93.0px;"><col style="width: 483.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>milliseconds</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>integer</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Integer representing time greater than zero&nbsp;in milliseconds.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Classes - XMLSerializer</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Classes-XMLSerializer-XMLSerializer><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>XMLSerializer</span></strong></h2>

<p>Similar to standard XMLSerializer. Used to convert a DOM document into a
valid XML string.</p>

<h3 id=PhoneAPIReference-Classes-XMLSerializer-ClassConstructor><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Class Constructor</span></strong></h3>

<h4 id=PhoneAPIReference-Classes-XMLSerializer-XMLSerializer.1><u>XMLSerializer</u></h4>

<p>Creates a new XMLSerializer object</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=fb0fd175-5d62-4462-b057-652369b05af5>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var serializer = new XMLSerializer();</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h4 id=PhoneAPIReference-Classes-XMLSerializer-InitializationParameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Initialization
Parameters</span></strong></h4>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=ccaea321-73a5-482b-83c7-6c968b459093>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Classes-XMLSerializer-Methods><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=1dafd4e2-4313-45f2-9b74-cf20cf845663>
 <colgroup><col style="width: 154.0px;"><col style="width: 604.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>serializeToString</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Serialize a DOM document object to an XML string.</p>
  <p><strong>Basic Example:</strong></p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var serializer = new XMLSerializer();</pre><pre>var xml = serializer.serializeToString(document);</pre></div>
  </div>
  <h2 id=PhoneAPIReference-Classes-XMLSerializer-Parameters>Parameters</h2>
  <p>Name</p>
  <p>Required</p>
  <p>Type</p>
  <p>Default</p>
  <p>Description</p>
  <p>document</p>
  <p>Yes</p>
  <p>DOM document object.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<p>These core functions are available to all apps without requiring any
libraries. They provide functionality to interact with the application
environment, invoke phone functions, etc.</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=968
 data-layout=default data-local-id=a068ef42-ba68-4147-9e9f-da32fb241c3e>
 <colgroup><col style="width: 126.0px;"><col style="width: 842.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22020373/Phone+API+Reference+-+Core+-+require"
  data-linked-resource-id=22020373 data-linked-resource-version=2
  data-linked-resource-type=page>require</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Used to include and evaluate other scripts. Anything exported by a
  required script is then made available using&nbsp;<strong>require</strong>.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22675541/Phone+API+Reference+-+Core+-+exports"
  data-linked-resource-id=22675541 data-linked-resource-version=2
  data-linked-resource-type=page>exports</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Object used to provide functions, variables, and properties for use by
  another script. Use&nbsp;<strong>require</strong>&nbsp;in another script to
  obtain the exports in the current script.</p>
  <p>Exports will not work if you set exports = to an object (e.g.,
  {&quot;key&quot; : &quot;value&quot; }). You must set properties of the
  exports object as can be seen in the example.&nbsp;</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/20939830/Phone+API+Reference+-+Core+-+digium"
  data-linked-resource-id=20939830 data-linked-resource-version=3
  data-linked-resource-type=page>digium</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Handles application launching/hiding, system event listeners, phone
  functions, and file I/O.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22511658/Phone+API+Reference+-+Core+-+digium.app"
  data-linked-resource-id=22511658 data-linked-resource-version=3
  data-linked-resource-type=page>digium.app</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Contains methods and properties about the phone's applications.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22020316/Phone+API+Reference+-+Core+-+digium.event"
  data-linked-resource-id=22020316 data-linked-resource-version=3
  data-linked-resource-type=page>digium.event</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Used to create applications that register event listeners by calling&nbsp;<strong>digium.event.observe()</strong>&nbsp;and
  specifying one of the event names as the&nbsp;<a
  href="https://wiki-legacy.freepbx.org/display/PHON/Phone+API+Reference+-+Core+-+digium.event+-+List+of+Event+Types">eventName</a>&nbsp;parameter.&nbsp;Also
  used to trigger an event with&nbsp;<strong>digium.event.fire()</strong>&nbsp;and
  to remove callbacks for an event with&nbsp;<strong>digium.event.stopObserving()</strong>.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22315220/Phone+API+Reference+-+Core+-+digium.phone"
  data-linked-resource-id=22315220 data-linked-resource-version=3
  data-linked-resource-type=page>digium.phone</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Call handling.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.app</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.app-digium.app><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.app</span></strong></h2>

<p>Contains methods and properties about the phone's applications.</p>

<h3 id=PhoneAPIReference-Core-digium.app-Methods><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=97b4414e-c8e6-4105-9f9c-52295c3e5ee9>
 <colgroup><col style="width: 159.0px;"><col style="width: 829.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22282366/Phone+API+Reference+-+Core+-+digium.app.getIcon"
  data-linked-resource-id=22282366 data-linked-resource-version=3
  data-linked-resource-type=page>digium.app.getIcon</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns the current Image object for the specified app.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22708232/Phone+API+Reference+-+Core+-+digium.app.getInfo"
  data-linked-resource-id=22708232 data-linked-resource-version=3
  data-linked-resource-type=page>digium.app.getInfo</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns an object with information about the specified app, as defined in
  its&nbsp;<a href="/wiki/spaces/Phones/pages/21266665/app.json+File"
  data-linked-resource-id=21266665 data-linked-resource-version=2
  data-linked-resource-type=page>app.json</a>&nbsp;file.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22315188/Phone+API+Reference+-+Core+digium.app.getList"
  data-linked-resource-id=22315188 data-linked-resource-version=3
  data-linked-resource-type=page>digium.app.getList</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns an array containing the names of apps that the system knows about.
  The names are defined in&nbsp;<a
  href="/wiki/spaces/Phones/pages/21266665/app.json+File"
  data-linked-resource-id=21266665 data-linked-resource-version=2
  data-linked-resource-type=page>app.json</a>.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Core-digium.app-Properties><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Properties</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=e992ef7b-5b64-41b5-a50b-cca9688b1d80>
 <colgroup><col style="width: 245.0px;"><col style="width: 743.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.app.config.xml</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>A string containing the XML representing the app's configuration
  (appconfig) settings from the phone's master configuration xml. These are
  limited to app-specific settings distributed from the phone's configuration
  server.</p>
  <p>Basic Example<strong>:</strong></p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.app.config.xml; //returns '&lt;appconfig id=&quot;test.my_app&quot;&gt;&lt;settings /&gt;&lt;/appconfig&gt;'</pre></div>
  </div>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.app.exitAfterBackground</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>An app will start up each time it is placed in the foreground and shut
  down each time it is placed in the background. This&nbsp;Boolean property
  sets whether or not the app shuts down (exits) when it goes into the
  background.&nbsp;The&nbsp;default setting is true; i.e., the app shuts down
  when it goes into the background.&nbsp;Change the setting to false to make
  your app run persistently.&nbsp;&nbsp;</p>
  <p><strong>Basic Example:</strong></p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.app.exitAfterBackground = false; //now it won't shut down when backgrounded</pre></div>
  </div>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.app.iconFile</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Get or set the filename of the icon image used for this application. The
  icon is used in other apps such as the app manager screen and is contained in
  the app's directory.</p>
  <p><strong>Basic Example:</strong></p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>// Let's assume your app.json file inits your app with the iconFile &quot;myapp_no_msgs.png&quot;;</pre><pre>var currentIcon = digium.app.iconFile; // returns &quot;my_app_no_msgs.png&quot;;</pre><pre>&nbsp;&nbsp;</pre><pre>// Your app then may be running in the background and when it gets a message you want to&nbsp;</pre><pre>// update the iconFile to provide an indicator to the Apps screen.</pre><pre>// this could be set in some sort of call back function</pre><pre>digium.app.iconFile = &quot;my_app_msgs_waiting.png&quot;;</pre><pre>&nbsp;&nbsp;</pre><pre>// now if you go to the Apps screen (press the Apps button on the D70) you will see the icon has changed.</pre><pre>&nbsp;&nbsp;</pre><pre>currentIcon = digium.app.iconFile; // returns &quot;my_app_msgs_waiting.png&quot;;</pre></div>
  </div>
  <p>If your app is initialized for the first time, digium.app.iconFile is set
  to the iconFile from the app.json file. If setting the iconFile, the
  {MODEL}.iconFile naming convention should be used for whichever iconFile you
  are setting.&nbsp;</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.app.idleWindowShown&nbsp;</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Boolean flag reflecting whether the the app's idle screen window is
  currently displayed.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.app.inForeground&nbsp;</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Boolean value indicating whether this app is in the foreground.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a href="http://digium.app.name">digium.app.name</a>&nbsp;</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Get the name of the app as specified in the app's&nbsp;<a
  href="/wiki/spaces/Phones/pages/21266665/app.json+File"
  data-linked-resource-id=21266665 data-linked-resource-version=2
  data-linked-resource-type=page>app.json</a>&nbsp;file.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.app.getIcon</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.app.getIcon-digium.app.getIcon><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.app.getIcon</span></strong></h2>

<h3 id=PhoneAPIReference-Core-digium.app.getIcon-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Returns the current Image object for the specified app.</p>

<h3 id=PhoneAPIReference-Core-digium.app.getIcon-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=71b6caa8-3f8a-4b45-8801-7aeb2ce22edf>
 <colgroup><col style="width: 100.0px;"><col style="width: 86.0px;"><col style="width: 58.0px;"><col style="width: 77.0px;"><col style="width: 434.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>app_name</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Name of the app to act on as defined in its&nbsp;<a
  href="/wiki/spaces/Phones/pages/21266665/app.json+File"
  data-linked-resource-id=21266665 data-linked-resource-version=2
  data-linked-resource-type=page>app.json</a>&nbsp;file.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Core-digium.app.getIcon-Example>Example</h3>

<p><strong>digium.app.getIcon</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=9646ab5a-120f-4fb8-9d5b-04212a8b405d>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.app.getIcon('contacts');</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.app.getInfo</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.app.getInfo-digium.app.getInfo><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.app.getInfo</span></strong></h2>

<h3 id=PhoneAPIReference-Core-digium.app.getInfo-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Returns an object with information about the specified app, as defined in
its&nbsp;&nbsp;<a href="/wiki/spaces/Phones/pages/21266665/app.json+File"
data-linked-resource-id=21266665 data-linked-resource-version=2
data-linked-resource-type=page>app.json</a>&nbsp;&nbsp;file.</p>

<p><strong>Basic Example:</strong>&nbsp;</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=f41a636a-aa7b-4b11-b7c4-f8346ab518b0>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var appInfo = digium.app.getInfo(app_name);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Core-digium.app.getInfo-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=e6716047-ed85-49b4-b8a0-acab701d0016>
 <colgroup><col style="width: 93.0px;"><col style="width: 88.0px;"><col style="width: 58.0px;"><col style="width: 76.0px;"><col style="width: 440.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>app_name</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Name of the app to act on as defined in its&nbsp;<a
  href="/wiki/spaces/Phones/pages/21266665/app.json+File"
  data-linked-resource-id=21266665 data-linked-resource-version=2
  data-linked-resource-type=page>app.json</a>&nbsp;file.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Core-digium.app.getInfo-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>digium.app.getInfo with the return object</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=0376813f-e20f-4887-b586-4c86e24cecf2>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.app.getInfo('contacts');</pre><pre>/* returns: {&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'name' : 'contacts',&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'displayName' : 'Contacts',&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'iconFile' : 'app_contacts.png',&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'running' : true&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'hidden' : true&nbsp;</pre><pre>}&nbsp;</pre><pre>*/</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.background</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.background-digium.background>digium.background</h2>

<h3 id=PhoneAPIReference-Core-digium.background-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Puts the app in the background, returning the screen to its regular state
(e.g., idle).<br>
<strong>Basic Example:</strong>&nbsp;</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=2ca81432-efe7-4c00-869b-4061100163a4>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;digium.background();</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>When an app is put in the background, unless the&nbsp;<a
href="/wiki/spaces/Phones/pages/22511658/Phone+API+Reference+-+Core+-+digium.app"
data-linked-resource-id=22511658 data-linked-resource-version=3
data-linked-resource-type=page>digium.app.exitAfterBackground</a>&nbsp;property
is set to false, the app will shutdown.&nbsp;</p>

<h3 id=PhoneAPIReference-Core-digium.background-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=67c4dd5d-0f10-4090-8f71-b1cee3c37503>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h1 id=PhoneAPIReference-Core-digium-digium><strong><span style='font-family:
"Aptos Display",sans-serif;font-weight:normal'>digium</span></strong></h1>

<p>Handles application launching/hiding, system event listeners, phone
functions, and file I/O.</p>

<h3 id=PhoneAPIReference-Core-digium-Methods><strong><span style='font-family:
"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=987
 data-layout=default data-local-id=a46a1ad9-4ff2-4436-8a39-1d1e3ba8eeec>
 <colgroup><col style="width: 182.0px;"><col style="width: 805.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22184134/Phone+API+Reference+-+Core+-+digium.background"
  data-linked-resource-id=22184134 data-linked-resource-version=3
  data-linked-resource-type=page>digium.background</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Puts the app in the background, returning the screen to its regular state
  (e.g., idle).</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22118701/Phone+API+Reference+-+Core+-+digium.foreground"
  data-linked-resource-id=22118701 data-linked-resource-version=3
  data-linked-resource-type=page>digium.foreground</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Brings an app into the foreground. If this is called without any
  arguments, it brings the current app to the foreground.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22315169/Phone+API+Reference+-+Core+-+digium.readFile"
  data-linked-resource-id=22315169 data-linked-resource-version=2
  data-linked-resource-type=page>digium.readFile</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Reads the contents of a file as utf-8 and returns the contents as a
  string. The filename is relative to the location that is specified (this is a
  flat directory).</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22511624/Phone+API+Reference+-+Core+-+digium.resetIdleTimer"
  data-linked-resource-id=22511624 data-linked-resource-version=2
  data-linked-resource-type=page>digium.resetIdleTimer</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Resets the timeout that causes the phone to hide apps when there's no
  keyboard input for a while. This keeps the app alive and should be called
  periodicallly to prevent the app from being timed out.&nbsp;</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22216924/Phone+API+Reference+-+Core+-+digium.restart"
  data-linked-resource-id=22216924 data-linked-resource-version=2
  data-linked-resource-type=page>digium.restart</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Indicates to the app to reboot itself.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22478907/Phone+API+Reference+-+Core+-+digium.setLedState"
  data-linked-resource-id=22478907 data-linked-resource-version=2
  data-linked-resource-type=page>digium.setLedState</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>This function can be used to change the state of one of the phone's LED
  lights.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22511646/Phone+API+Reference+-+Core+-+digium.writeFile"
  data-linked-resource-id=22511646 data-linked-resource-version=2
  data-linked-resource-type=page>digium.writeFile</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Writes the string into a file. The filename is relative to the location
  that is specified (this is a flat directory).</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Core-digium-Properties><strong><span style='font-family:
"Aptos",sans-serif;font-weight:normal'>Properties</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=987
 data-layout=default data-local-id=682be841-0a2e-4c68-99dc-bd733e49922e>
 <colgroup><col style="width: 184.0px;"><col style="width: 803.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.phoneModel&nbsp;</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>This property is set to a string that represents the model of the phone
  (D40, D45, D50, D60, D62, D65, D70).</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.event</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.event-digium.event><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.event</span></strong></h2>

<p>Used to create applications that register event listeners by calling&nbsp;<strong>digium.event.observe()</strong>&nbsp;and
specifying one of the event names as the&nbsp;<a
href="/wiki/spaces/Phones/pages/22282395/Phone+API+Reference+-+Core+-+digium.event+-+List+of+Event+Types"
data-linked-resource-id=22282395 data-linked-resource-version=2
data-linked-resource-type=page>eventName</a>&nbsp;parameter.&nbsp;Also used to
trigger an event with&nbsp;<strong>digium.event.fire()</strong>&nbsp;and to
remove callbacks for an event with&nbsp;<strong>digium.event.stopObserving()</strong>.</p>

<h3 id=PhoneAPIReference-Core-digium.event-Methods><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=934
 data-layout=default data-local-id=0253e228-a805-4717-b287-2d98bcce20e2>
 <colgroup><col style="width: 224.0px;"><col style="width: 710.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22642700/Phone+API+Reference+-+Core+-+digium.event.fire"
  data-linked-resource-id=22642700 data-linked-resource-version=3
  data-linked-resource-type=page>digium.event.fire</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Fire an event of the given eventName and pass your eventData onto any
  callback that may be observing the event. Note: the list of Digium eventNames
  cannot be fired except by the system.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22740996/Phone+API+Reference+-+Core+-+digium.event.observe"
  data-linked-resource-id=22740996 data-linked-resource-version=3
  data-linked-resource-type=page>digium.event.observe</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Set a callback function to be fired when the request eventName
  fires.&nbsp;</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22675471/Phone+API+Reference+-+Core+-+digium.event.stopObserving"
  data-linked-resource-id=22675471 data-linked-resource-version=3
  data-linked-resource-type=page>digium.event.stopObserving</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Used to remove callbacks for an event. If callback is not passed in (which
  is a reference to the original observed callback), then all observed events
  are removed for the specified eventName.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.event.fire</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.event.fire-digium.event.fire><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.event.fire</span></strong></h2>

<h3 id=PhoneAPIReference-Core-digium.event.fire-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Fire an event of the given eventName and pass your eventData onto any
callback that may be observing the event. Note: the list of Digium eventNames
cannot be fired except by the system.</p>

<p><strong>Basic Example:</strong>&nbsp;</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=17a4c114-307f-4eb1-9cdf-e81e2650fa7a>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.event.fire(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Core-digium.event.fire-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=e30b73ad-411f-4c98-99ee-6ebe741e0333>
 <colgroup><col style="width: 106.0px;"><col style="width: 95.0px;"><col style="width: 85.0px;"><col style="width: 80.0px;"><col style="width: 389.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>eventName</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>String that identifies the event type. Event type can either be from
  this&nbsp;<a
  href="https://wiki.freepbx.org/wiki/display/DIGIUM/Phone+API+Reference+-+Core+-+digium.event+-+List+of+Event+Types">list</a>&nbsp;if
  you are using digium.event.observe,&nbsp;or from your own list if you're
  using digium.event.fire to fire your own event.&nbsp;</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>eventData</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>object</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Object passed to any callbacks listening for this event.&nbsp;<em>eventData</em>&nbsp;can
  contain a 'callback' property that will be executed when an event named&nbsp;<em>eventName.response</em>&nbsp;(for
  example, contacts.forwardVM.response) is sent with the same&nbsp;<em>messageId</em>.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>messageId</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>object</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Unique ID for the message. If&nbsp;<em>messageId</em>&nbsp;is not
  specified one will be generated automatically.</p>
  </td>
 </tr>
</table>

</div>

<div>

<div>

<p>A full list of system eventNames can be found <a
href="/wiki/spaces/Phones/pages/22282395/Phone+API+Reference+-+Core+-+digium.event+-+List+of+Event+Types"
data-linked-resource-id=22282395 data-linked-resource-version=2
data-linked-resource-type=page>here</a></p>

</div>

</div>

<h1>Phone API Reference - Core - digium.event.observe</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h1 id=PhoneAPIReference-Core-digium.event.observe-digium.event.observe>digium.event.observe</h1>

<h2 id=PhoneAPIReference-Core-digium.event.observe-Description>Description</h2>

<p>Set a callback function to be fired when the request eventName fires.&nbsp;</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=80e05494-90dc-4809-ae08-10d75ac84f76>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.event.observe(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h2 id=PhoneAPIReference-Core-digium.event.observe-Parameters>Parameters</h2>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=95409e25-78a4-4ba1-bc0e-81a72df693db>
 <colgroup><col style="width: 100.0px;"><col style="width: 87.0px;"><col style="width: 70.0px;"><col style="width: 74.0px;"><col style="width: 424.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>eventName</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>String that identifies the event type. Event type can either be from
  this&nbsp;<a
  href="https://wiki-legacy.freepbx.org/display/PHON/Phone+API+Reference+-+Core+-+digium.event+-+List+of+Event+Types">list</a>&nbsp;if
  you are using digium.event.observe,&nbsp;or from your own list if you're
  using digium.event.fire to fire your own event.&nbsp;</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>callback</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>object</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called when an event arrives and contains an Object with the following:</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>callHandle - the string identifying the call. This is only
  present when the notification is attached to an incoming call.</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>method - the SIP method type used to deliver the message. INFO,
  INVITE, or MESSAGE.</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>eventName - the string identifying the pushed event type</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>eventData - data associated with the message (from the
  x-event-data header or the body of an INFO or MESSAGE). If data can be parsed
  as JSON, the parsed object is used; otherwise, this field contains a string.</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>messageId - ID string for the event.</p>
  </td>
 </tr>
</table>

</div>

<div>

<div>

<p>A full list of system eventNames can be found <a
href="/wiki/spaces/Phones/pages/22282395/Phone+API+Reference+-+Core+-+digium.event+-+List+of+Event+Types"
data-linked-resource-id=22282395 data-linked-resource-version=2
data-linked-resource-type=page>here</a>.</p>

</div>

</div>

<h1>Phone API Reference - Core - digium.event.stopObserving</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2
id=PhoneAPIReference-Core-digium.event.stopObserving-digium.event.stopObserving><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.event.stopObserving</span></strong></h2>

<h3 id=PhoneAPIReference-Core-digium.event.stopObserving-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Used to remove callbacks for an event. If callback is not passed in (which
is a reference to the original observed callback), then all observed events are
removed for the specified eventName.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=7dfa60bf-2e85-474e-bfa7-3f1db3e1c54c>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;digium.event.stopObserving(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Core-digium.event.stopObserving-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=e4588201-fc28-492f-9b94-f1ac59dd2116>
 <colgroup><col style="width: 104.0px;"><col style="width: 90.0px;"><col style="width: 64.0px;"><col style="width: 90.0px;"><col style="width: 407.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>eventName</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>String that identifies the event type. Event type can either be from
  this&nbsp;<a
  href="https://wiki-legacy.freepbx.org/display/PHON/Phone+API+Reference+-+Core+-+digium.event+-+List+of+Event+Types">list</a>&nbsp;if
  you are using digium.event.observe,&nbsp;or from your own list if you're
  using digium.event.fire to fire your own event.&nbsp;</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>callback</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>object</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Callback (OPTIONAL) to remove from the event listener. If this parameter
  is undefined, all callbacks registered to&nbsp;<em>eventName</em>will be
  removed.</p>
  </td>
 </tr>
</table>

</div>

<blockquote style='margin-top:5.0pt;margin-bottom:5.0pt'>

<p>A full list of&nbsp;<a
href="/wiki/spaces/Phones/pages/22282395/Phone+API+Reference+-+Core+-+digium.event+-+List+of+Event+Types"
data-linked-resource-id=22282395 data-linked-resource-version=2
data-linked-resource-type=page>system eventNames can be found here</a>.&nbsp;</p>

</blockquote>

<h1>Phone API Reference - Core - digium.event - List of Event Types</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<p><strong>App Events</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=9c4040b9-2562-44ca-a92b-c81507b00736>
 <colgroup><col style="width: 227.0px;"><col style="width: 531.0px;"></colgroup>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.app.background</p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called when an application is about to be put in the background.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.app.exit</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called when an application is about to shut down.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.app.foreground</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called when the application is put into the foreground. The application
  name and any arguments from appconfig will be passed as arguments to the
  callback.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.app.idle_screen_hide</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called with no arguments when the app idlescreen window is hidden in the
  GUI.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.app.idle_screen_show</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called with no arguments when the app idlescreen window is displayed by
  the phone GUI.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.app.start</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called when the app first starts up.</p>
  </td>
 </tr>
</table>

</div>

<p><strong>&nbsp;Phone Events</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=60445fe6-1061-4de3-a982-68f3b530b75e>
 <colgroup><col style="width: 246.0px;"><col style="width: 512.0px;"></colgroup>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.phone.contact_presence</p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called whenever a subscribed user updates his/her presence information.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.phone.contact_update</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called when new contact information is received from the server. The app
  then rebuilds any data structures based on the result of
  digium.contacts.getList().</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.phone.icon_change</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called whenever an application changes its icon. Callback will be passed
  the name of the application in the eventData parameter.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.phone.app_install</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called when an application is installed or reinstalled. Callback will be
  passed the name of the application in the eventData parameter.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.phone.incoming_call</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called to notify of an incoming phone call. &nbsp;The eventData properties
  are the same as those given to a handler in the digium.phone api.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.phone.mwi</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called when a Message Waiting Indicator arrives. For example, a voicemail
  notification.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.phone.new_config</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called when the phone's configuration file has changed.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.phone.outgoing_call</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called to notify of an outgoing phone call. &nbsp;The eventData properties
  are the same as those given to a handler in the digium.phone api.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.phone.play_status</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called about every second while an audio file is playing, to give status.
  Also called when playback stops.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digium.phone.server_change</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Called to provide failover status for accounts.&nbsp;</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.foreground</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.foreground-digium.foreground><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.foreground</span></strong></h2>

<h3 id=PhoneAPIReference-Core-digium.foreground-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Brings an app into the foreground. If this is called without any arguments,
it brings the current app to the foreground.</p>

<p>&nbsp;<br>
<strong>Basic Example:</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=11c90faf-6b94-4559-83bd-1a4028b7021e>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><code><span style='font-size:10.0pt'>digium.foreground([app_name]);</span></code></p>
  </td>
 </tr>
</table>

</div>

<p>&nbsp;</p>

<p>Note: The app needs to be running for this to do anything.</p>

<h3 id=PhoneAPIReference-Core-digium.foreground-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=1eddbd21-83b6-45ae-8c46-38caf8132ed9>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>app_name</p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>&nbsp;</p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Name of the app to act on as defined in its&nbsp;<a
  href="/wiki/spaces/Phones/pages/21266665/app.json+File"
  data-linked-resource-id=21266665 data-linked-resource-version=2
  data-linked-resource-type=page>app.json</a>&nbsp;file.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.phone.answer</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.phone.answer-digium.phone.answer><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.phone.answer</span></strong></h2>

<h3 id=PhoneAPIReference-Core-digium.phone.answer-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Answers an incoming call.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=ec692d33-60a3-4728-800b-2541416b3101>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;digium.phone.answer(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>If a function is passed in the&nbsp;<strong>handler</strong>&nbsp;parameter,
that function is called with a&nbsp;<a
href="/wiki/spaces/Phones/pages/22675529/Phone+API+Reference+-+Core+-+digium.phone+-+Call+Status+Object"
data-linked-resource-id=22675529 data-linked-resource-version=2
data-linked-resource-type=page>call status object</a>&nbsp;to notify of state
changes to the phone call.</p>

<h3 id=PhoneAPIReference-Core-digium.phone.answer-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=970
 data-layout=default data-local-id=4ef5e446-59c4-48c5-823e-e75f50025507>
 <colgroup><col style="width: 91.0px;"><col style="width: 84.0px;"><col style="width: 76.0px;"><col style="width: 76.0px;"><col style="width: 638.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>callHandle</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Identifier of the call to act on. A call handle can be obtained by
  observing call events. Information such as this will be passed into the event
  object.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>handler</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>function</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Handler to register for the call. Executed whenever the call changes
  state.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Core-digium.phone.answer-Examples>Examples</h3>

<p><strong>digium.phone.answer with util.debug to print call state</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=3ab7cd2f-bbf0-47b5-8b2e-a5f0763af401>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.phone.answer({&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'callHandle' : callHandleVar,&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'handler' : function (obj) {&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;util.debug(obj.state);&nbsp; //prints the state of the call&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;</pre><pre>});</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.phone.dial</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.phone.dial-digium.phone.dial><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.phone.dial</span></strong></h2>

<p>&nbsp;</p>

<h3 id=PhoneAPIReference-Core-digium.phone.dial-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Initiates a call. This function returns a call handle, which is a string
identifying the call. It can be used in various other methods such as&nbsp;<a
href="/wiki/spaces/Phones/pages/22511736/Phone+API+Reference+-+Core+-+digium.phone.hangup"
data-linked-resource-id=22511736 data-linked-resource-version=3
data-linked-resource-type=page>digium.phone.hangup</a>.</p>

<p>&nbsp;<br>
<strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=f4558e7a-9a8b-4645-8185-aa2e4bf1886f>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.phone.dial(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>If a function is passed in the&nbsp;<strong>handler</strong>&nbsp;parameter,
that function is called with a&nbsp;<a
href="/wiki/spaces/Phones/pages/22675529/Phone+API+Reference+-+Core+-+digium.phone+-+Call+Status+Object"
data-linked-resource-id=22675529 data-linked-resource-version=2
data-linked-resource-type=page>call status object</a>&nbsp;to notify of state
changes to the phone call.</p>

<p>&nbsp;</p>

<h3 id=PhoneAPIReference-Core-digium.phone.dial-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=68685e18-e547-41d3-a016-27da14aa5b65>
 <colgroup><col style="width: 107.0px;"><col style="width: 89.0px;"><col style="width: 84.0px;"><col style="width: 86.0px;"><col style="width: 622.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>number</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Number to dial.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>url</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>SIP URL to call (e.g.,&nbsp;200@MY.PBX.IP). This can be used instead of a
  number. Only one of the two are required.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>headers</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>object</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Object with header values to set in the call's INVITE.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>accountSlot</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>integer</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>ID for the account.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>handler</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>function</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Handler to register for the call. Executed whenever the call changes
  state.</p>
  </td>
 </tr>
</table>

</div>

<p>&nbsp;</p>

<h3 id=PhoneAPIReference-Core-digium.phone.dial-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>digium.phone.dial with util.debug for state of the call</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=0920bc72-e66c-4c61-a711-1d00cfbd96ed>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.phone.dial({</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'number' : 100,</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'handler' : function (obj) {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;util.debug(obj.state);&nbsp; //prints the 'state' of the call</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;}</pre><pre>});</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.phone</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.phone-digium.phone><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.phone</span></strong></h2>

<p>Call handling.</p>

<h3 id=PhoneAPIReference-Core-digium.phone-Methods><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=a9cb3524-a22a-4fb9-a2a5-059b496d46a6>
 <colgroup><col style="width: 243.0px;"><col style="width: 515.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22642725/Phone+API+Reference+-+Core+-+digium.phone.answer"
  data-linked-resource-id=22642725 data-linked-resource-version=3
  data-linked-resource-type=page>digium.phone.answer</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Answers an incoming call.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22315243/Phone+API+Reference+-+Core+-+digium.phone.dial"
  data-linked-resource-id=22315243 data-linked-resource-version=3
  data-linked-resource-type=page>digium.phone.dial</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Initiates a call. This function returns a call handle, which is a string
  identifying the call. It can be used in various other methods such as
  digium.phone.hangup().</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22511736/Phone+API+Reference+-+Core+-+digium.phone.hangup"
  data-linked-resource-id=22511736 data-linked-resource-version=3
  data-linked-resource-type=page>digium.phone.hangup</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Hangs up on an ongoing call.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22446171/Phone+API+Reference+-+Core+-+digium.phone.observeCallEvents"
  data-linked-resource-id=22446171 data-linked-resource-version=3
  data-linked-resource-type=page>digium.phone.observeCallEvents</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Attaches handlers to ongoing-call status changes. Useful if you were
  unable to attach a handler when the call was created.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22315257/Phone+API+Reference+-+Core+-+digium.phone.reject"
  data-linked-resource-id=22315257 data-linked-resource-version=3
  data-linked-resource-type=page>digium.phone.reject</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Ignores (rejects) an incoming call before it is answered.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22020359/Phone+API+Reference+-+Core+-+digium.phone.sendDTMF"
  data-linked-resource-id=22020359 data-linked-resource-version=2
  data-linked-resource-type=page>digium.phone.sendDTMF</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Sends DTMF tones in an ongoing call.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22216992/Phone+API+Reference+-+Core+-+digium.phone.transfer"
  data-linked-resource-id=22216992 data-linked-resource-version=3
  data-linked-resource-type=page>digium.phone.transfer</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Transfers an active call to another extension. This is a blind transfer,
  meaning the transferor does not talk to the transferee.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.phone.hangup</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.phone.hangup-digium.phone.hangup><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.phone.hangup</span></strong></h2>

<h3 id=PhoneAPIReference-Core-digium.phone.hangup-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Hangs up on an ongoing call.</p>

<p>&nbsp;</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=86b1dff7-0b43-4cdd-95fd-e2ccd14c873a>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.phone.hangup(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>If a function is passed in the&nbsp;<strong>handler</strong>&nbsp;parameter,
that function is called with a&nbsp;<a
href="/wiki/spaces/Phones/pages/22675529/Phone+API+Reference+-+Core+-+digium.phone+-+Call+Status+Object"
data-linked-resource-id=22675529 data-linked-resource-version=2
data-linked-resource-type=page>call status object</a>&nbsp;to notify of state
changes to the phone call.</p>

<p>&nbsp;</p>

<h3 id=PhoneAPIReference-Core-digium.phone.hangup-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=efcd029d-aa51-416d-87c5-43654e585119>
 <colgroup><col style="width: 122.0px;"><col style="width: 109.0px;"><col style="width: 104.0px;"><col style="width: 105.0px;"><col style="width: 548.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>callHandle</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Identifier of the call to act on. A call handle can be obtained by
  observing call events. Information such as this will be passed into the event
  object.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>handler</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>function</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Handler to register for the call. Executed whenever the call changes
  state.</p>
  </td>
 </tr>
</table>

</div>

<p>&nbsp;</p>

<h3 id=PhoneAPIReference-Core-digium.phone.hangup-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>digium.phone.hangup with until.debug to print call state</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=d50446a9-2264-40c7-b4cc-f9973803e88b>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.phone.hangup({</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'callHandle' : callHandleVar,</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'handler' : function (obj) {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;util.debug(obj.callHandle);</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;}</pre><pre>});</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>&nbsp;</p>

<h1>Phone API Reference - Core - digium.phone.observeCallEvents</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2
id=PhoneAPIReference-Core-digium.phone.observeCallEvents-digium.phone.observeCallEvents><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.phone.observeCallEvents</span></strong></h2>

<h3 id=PhoneAPIReference-Core-digium.phone.observeCallEvents-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Attaches handlers to ongoing-call status changes. Useful if you were unable
to attach a handler when the call was created.</p>

<p>The function passed in the&nbsp;<strong>handler</strong>&nbsp;parameter is
called with a&nbsp;<a
href="/wiki/spaces/Phones/pages/22675529/Phone+API+Reference+-+Core+-+digium.phone+-+Call+Status+Object"
data-linked-resource-id=22675529 data-linked-resource-version=2
data-linked-resource-type=page>call status object</a>&nbsp;to notify of state
changes to the phone call.</p>

<h3 id=PhoneAPIReference-Core-digium.phone.observeCallEvents-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=980
 data-layout=default data-local-id=8777668f-4ffe-4ce5-b319-961090849fc5>
 <colgroup><col style="width: 91.0px;"><col style="width: 87.0px;"><col style="width: 79.0px;"><col style="width: 79.0px;"><col style="width: 644.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>handler</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>function</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Handler to register for the call. Executed whenever the call changes
  state.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>callHandle</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Identifier of the call to act on. A call handle can be obtained by
  observing call events. Information such as this will be passed into the event
  object.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Core-digium.phone.observeCallEvents-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>digium.phone.observeCallEvents with util.debug to print call state</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=76679bbf-f935-47db-a54f-92e069852244>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;digium.phone.observeCallEvents({</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'callHandle' : callHandleVar,</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'handler' : function (obj) {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;util.debug(obj.state);</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;}</pre><pre>});</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.phone.reject</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.phone.reject-digium.phone.reject><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.phone.reject</span></strong></h2>

<h3 id=PhoneAPIReference-Core-digium.phone.reject-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Ignores (rejects) an incoming call before it is answered.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=23953ac8-9422-4e95-809e-a80811aa5367>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;digium.ohone.reject(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>If a function is passed in the&nbsp;<strong>handler</strong>&nbsp;parameter,
that function is called with a&nbsp;<a
href="/wiki/spaces/Phones/pages/22675529/Phone+API+Reference+-+Core+-+digium.phone+-+Call+Status+Object"
data-linked-resource-id=22675529 data-linked-resource-version=2
data-linked-resource-type=page>call status object</a>&nbsp;to notify of state
changes to the phone call.</p>

<h3 id=PhoneAPIReference-Core-digium.phone.reject-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=3f9efc4a-24b3-46a9-96d9-4ec6c010dd37>
 <colgroup><col style="width: 90.0px;"><col style="width: 95.0px;"><col style="width: 76.0px;"><col style="width: 76.0px;"><col style="width: 648.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>callHandle</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Identifier of the call to act on. A call handle can be obtained by
  observing call events. Information such as this will be passed into the event
  object.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>handler</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>function</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Handler to register for the call. Executed whenever the call changes
  state.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.phone.sendDTMF</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.phone.sendDTMF-digium.phone.sendDTMF><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.phone.sendDTMF</span></strong></h2>

<h3 id=PhoneAPIReference-Core-digium.phone.sendDTMF-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Sends DTMF tones in an ongoing call.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=aa793980-067a-44b4-b76e-f5a7e43f9db4>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.phone.sendDTMF(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p><strong>Parameters</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=812
 data-layout=default data-local-id=58aa5fd6-9d0f-47d9-bc2e-f6c4d41cf003>
 <colgroup><col style="width: 102.0px;"><col style="width: 95.0px;"><col style="width: 78.0px;"><col style="width: 102.0px;"><col style="width: 435.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>digit</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Digit&nbsp;<strong>0-9</strong>, a letter from&nbsp;<strong>A-D</strong>,&nbsp;<strong>*</strong>,
  or&nbsp;<strong>#</strong>.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>duration</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>integer</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Length of time in milliseconds to play the tone.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Core-digium.phone.sendDTMF-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p>digium.phone.sendDTMF with a tone to play</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=d0a30bd8-b90b-443b-bcb6-e0febc657688>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.phone.sendDTMF({</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'duration' : 5000,</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'digit' : 5</pre><pre>});</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.phone.transfer</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.phone.transfer-digium.phone.transfer><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.phone.transfer</span></strong></h2>

<h3 id=PhoneAPIReference-Core-digium.phone.transfer-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Transfers an active call to another extension. This is a blind transfer,
meaning the transferor does not talk to the transferee.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=ab24448d-2f19-49e0-9cca-2c6239dbc18e>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.phone.transfer(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>If a function is passed in the&nbsp;<strong>handler</strong>&nbsp;parameter,
that function is called with a&nbsp;<a
href="/wiki/spaces/Phones/pages/22675529/Phone+API+Reference+-+Core+-+digium.phone+-+Call+Status+Object"
data-linked-resource-id=22675529 data-linked-resource-version=2
data-linked-resource-type=page>call status object</a>&nbsp;to notify of state
changes to the phone call.</p>

<h3 id=PhoneAPIReference-Core-digium.phone.transfer-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=972
 data-layout=default data-local-id=47f80d5f-19d9-47db-a76a-608c7cfe1ab5>
 <colgroup><col style="width: 121.0px;"><col style="width: 102.0px;"><col style="width: 96.0px;"><col style="width: 93.0px;"><col style="width: 560.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>callHandle</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Identifier of the call to act on. A call handle can be obtained by
  observing call events. Information such as this will be passed into the event
  object.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>number</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Number to dial.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>handler</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>function</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Handler to register for the call. Executed whenever the call changes
  state.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.phone - Call Status Object</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<p>If a handler is passed to call-related actions, that handler is called
whenever the state of the call changes.</p>

<p>The handler is called with one argument, a call status object with the
following fields:</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>state - SIP state of the call. One of<br>
&quot;CALLING&quot;, &quot;INCOMING&quot;, &quot;EARLY&quot;,
&quot;CONNECTING&quot;, &quot;CONFIRMED&quot;, &quot;DISCONNECTING&quot;,
&quot;DISCONNCTD&quot;.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>accountSlot - Identifier for the line the call is coming in on.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>callHandle - Identifier for the call. This will match the call
handle returned by&nbsp;<strong>digium.phone.dial</strong>, for example.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>remoteInfo - SIP url for the remote end of the call.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>remoteContact - SIP contact header for the remote end of the
call.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>lastStatus - Most recent SIP status code associated with the
call, or &quot;0&quot;.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>lastStatusText - Most recent text associated with status code.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>mediaStatus - Describes the current audio data flow.&nbsp;<br>
One of &quot;none&quot;, &quot;active&quot;, &quot;local_hold&quot;,
&quot;remote_hold&quot;, or &quot;error&quot;.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>headers - Object mapping SIP headers to their values.</p>

<p>However, if there's an api-level error (e.g., the callHandle is invalid, you
are trying to make a call when there's already an active call, etc.), these are
available instead:</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>state - Has the value &quot;ERROR&quot;.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>callHandle - Identifier for the call.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>errorText - Human readable error message (not for display to end
users).</p>

<h1>Phone API Reference - Core - digium.readFile</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.readFile-digium.readFile><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.readFile</span></strong></h2>

<h3 id=PhoneAPIReference-Core-digium.readFile-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Reads the contents of a file as utf-8 and returns the contents as a string.
The filename is relative to the location that is specified (this is a flat
directory).</p>

<p><strong>Basic Example:</strong>&nbsp;</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=401369b0-7c57-4067-909d-c1fd543fba75>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.readFile(location, file);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>Parameters</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=3e227c0b-e697-4998-8ee9-fb34d9083ef7>
 <colgroup><col style="width: 101.0px;"><col style="width: 84.0px;"><col style="width: 72.0px;"><col style="width: 85.0px;"><col style="width: 413.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>location</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Read-only location parameters:</p>
  <p><strong>app</strong>&nbsp;The app's own directory (so you can read files
  included in the app's zip file).<br>
  <strong>data&nbsp;</strong>The /app/data directory.</p>
  <p>Read and write location parameters:</p>
  <p><strong>nv</strong>&nbsp;Non-volatile storage.&nbsp; Data stored here
  survives firmware updates.<br>
  <strong>tmp</strong>&nbsp;Temporary storage. Data stored here is lost on
  restart.<br>
  <strong>nvshared</strong>&nbsp;Shared non-volatile storage&nbsp;that all
  custom apps can access.<br>
  <strong>tmpshared</strong>&nbsp;Shared temporary storage&nbsp;that all custom
  apps can access.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>filename</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Name of the file to act on.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Core-digium.readFile-Examples>Examples</h3>

<p><strong>Using digium.readFile / digium.writeFile to store settings.</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=be83b50b-bf32-4a05-add8-8c11cbe953b5>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>/* Here are two simple functions for working with JSON / and a JavaScript object to store some settings information. We use the readFile and writeFile method to store a string and use the native JSON JavaScript object to parse and stringify it. */</pre><pre>&nbsp;&nbsp;</pre><pre>//settings object passed in, let's assume it looks like {&quot;name&quot; : &quot;Bob&quot;, &quot;location&quot; : &quot;USA&quot;}</pre><pre>function saveSettings (settings) {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;var settingsString = JSON.stringify(settings);</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//write our settings in non-volatile storage so they are preserved.</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;digium.writeFile(&quot;nv&quot;, &quot;my_app_settings.json&quot;, settingsString);</pre><pre>}</pre><pre>&nbsp;&nbsp;</pre><pre>function readSettings () {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;var settings = {};</pre><pre>&nbsp;&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// we wrap loading this file in a try catch because we are not sure if it exists yet or not.</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// if it doesn't the app engine will throw an exception halting execution.</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// this is also why we initialize the settings object above.</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// If this errors we will return the empty object</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;try {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;var settingsString = digium.readFile(&quot;nv&quot;, &quot;my_app_settings.json&quot;);</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;settings = JSON.parse(settingsString);</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;} catch (error) {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;util.debug(&quot;my_app_settings.json file does not exist yet&quot;);</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}</pre><pre>&nbsp;&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//return our settings object</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return settings;</pre><pre>}</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.resetIdleTimer</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.resetIdleTimer-digium.resetIdleTimer><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.resetIdleTimer</span></strong></h2>

<h3 id=PhoneAPIReference-Core-digium.resetIdleTimer-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>&nbsp;</p>

<p>Resets the timeout that causes the phone to hide apps when there's no
keyboard input for a while. This keeps the app alive and should be called
periodicallly to prevent the app from being timed out.&nbsp;</p>

<p><strong>Basic Example:</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=5154f234-526d-4798-9141-a39cc327be78>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><code><span style='font-size:10.0pt'>digium.resetIdleTimer();</span></code></p>
  </td>
 </tr>
</table>

</div>

<p>&nbsp;</p>

<p>If an app is idle for 30 seconds without this function being called, the app
will go to the background and the screen will return to idle.</p>

<h3 id=PhoneAPIReference-Core-digium.resetIdleTimer-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=bd1b0271-afe7-46e6-89a6-959fd160f974>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.restart</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.restart-digium.restart><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.restart</span></strong></h2>

<h3 id=PhoneAPIReference-Core-digium.restart-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Indicates to the app to reboot itself.</p>

<p><strong>Basic Example:</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=f12b7408-7d80-48c4-bb01-ad32ccbe8e15>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><code><span style='font-size:10.0pt'>digium.restart();</span></code></p>
  </td>
 </tr>
</table>

</div>

<p>&nbsp;</p>

<p>Note: The digium.app.exit event is fired as the app is about to shutdown. If
your app is state dependent, you may need to record some information.</p>

<h3 id=PhoneAPIReference-Core-digium.restart-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=3c9d2571-c303-4244-a741-0a537c91a958>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

</div>

<p>&nbsp;</p>

<h3 id=PhoneAPIReference-Core-digium.restart-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>digium.restart example</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=ed1d5215-6d53-4bd3-b14b-f7b884b120c8>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><code><span style='font-size:10.0pt'>digium.restart();</span></code></p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.setLedState</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.setLedState-digium.setLedState><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.setLedState</span></strong></h2>

<h3 id=PhoneAPIReference-Core-digium.setLedState-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>This function can be used to change the state of one of the phone's LED
lights.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=544c580d-6391-4bdc-a932-6647f9a62288>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.setLedState(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>This function can be used to change the state of one of the phone's LED
lights.&nbsp; An app can only control LEDs when it is in the foreground; once
it goes into the background, the phone gui will return all LEDs to its default
behavior.&nbsp;When an app sets its first LED, all other LEDs will be turned
off.&nbsp; The app is then responsible for all LED settings until it is
backgrounded.&nbsp; When an app returns to the foreground, it will need to set
the LEDs to its desired state again (generally in its onforeground handler).</p>

<h3 id=PhoneAPIReference-Core-digium.setLedState-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=4c38032a-a399-4486-b4c6-8aa5f18ced72>
 <colgroup><col style="width: 101.0px;"><col style="width: 94.0px;"><col style="width: 94.0px;"><col style="width: 101.0px;"><col style="width: 595.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>name</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>The name of the LED to target. Possible values are as follows:</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>msg (Voicemail Indicator light)</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>hdst (headset), spkr (speaker), mute</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>line[n] (line number [1-6] with n being a number. E.G. line1)</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>blf[n] (blf line [1-10] with n being a number. E.G. blf1)</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>color</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Which color to activate for the LED. Possible choices are green, red and
  amber.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>state</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Which state the LED should be set as. Possible options are:</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>on</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>off</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>fast (fast blink)</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>slow (slow blink)</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - digium.writeFile</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-digium.writeFile-digium.writeFile><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.writeFile</span></strong></h2>

<p>Writes the string into a file. The filename is relative to the location that
is specified (this is a flat directory).</p>

<h3 id="PhoneAPIReference-Core-digium.writeFile-BasicExample:"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Basic Example:&nbsp;</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=7f8e6992-ea41-4cfc-abf9-4b3b55f46b8e>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.writeFile(location, filename, string);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>If the file exists, it is overwritten with the string. If the file does not
exist, it is created.</p>

<h3 id=PhoneAPIReference-Core-digium.writeFile-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=309bf371-32fe-4931-aa31-67861b60dc96>
 <colgroup><col style="width: 97.0px;"><col style="width: 90.0px;"><col style="width: 84.0px;"><col style="width: 85.0px;"><col style="width: 399.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>location</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Read-only location parameters:</p>
  <p><strong>app</strong>&nbsp;The app's own directory (so you can read files
  included in the app's zip file).<br>
  <strong>data&nbsp;</strong>The /app/data directory.</p>
  <p>Read and write location parameters:</p>
  <p><strong>nv</strong>&nbsp;Non-volatile storage.&nbsp; Data stored here
  survives firmware updates.<br>
  <strong>tmp</strong>&nbsp;Temporary storage. Data stored here is lost on
  restart.<br>
  <strong>nvshared</strong>&nbsp;Shared non-volatile storage&nbsp;that all
  custom apps can access.<br>
  <strong>tmpshared</strong>&nbsp;Shared temporary storage&nbsp;that all custom
  apps can access.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>filename</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Name of the file to act on.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>String to act on.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Core-digium.writeFile-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p>Using digium.readFile / digium.writeFile to store settings.</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=00af37d5-60be-446b-8f68-f8c1680eb10f>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>/* Here are two simple functions for working with JSON / and a JavaScript object to store some settings information. We use the readFile and writeFile method to store a string and use the native JSON JavaScript object to parse and stringify it. */</pre><pre>&nbsp;</pre><pre>&nbsp;&nbsp;</pre><pre>//settings object passed in, let's assume it looks like {&quot;name&quot; : &quot;Bob&quot;, &quot;location&quot; : &quot;USA&quot;}</pre><pre>function saveSettings (settings) {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;var settingsString = JSON.stringify(settings);</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//write our settings in non-volatile storage so they are preserved.</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;digium.writeFile(&quot;nv&quot;, &quot;my_app_settings.json&quot;, settingsString);</pre><pre>}</pre><pre>&nbsp;&nbsp;</pre><pre>function readSettings () {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;var settings = {};</pre><pre>&nbsp;&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// we wrap loading this file in a try catch because we are not sure if it exists yet or not.</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// if it doesn't the app engine will throw an exception halting execution.</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// this is also why we initialize the settings object above.</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// If this errors we will return the empty object</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;try {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;var settingsString = digium.readFile(&quot;nv&quot;, &quot;my_app_settings.json&quot;);</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;settings = JSON.parse(settingsString);</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;} catch (error) {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;util.debug(&quot;my_app_settings.json file does not exist yet&quot;);</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}</pre><pre>&nbsp;&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//return our settings object</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return settings;</pre><pre>}</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - exports</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-exports-exports><strong><span style='font-family:
"Aptos Display",sans-serif;font-weight:normal'>exports</span></strong></h2>

<p>Object used to provide functions, variables, and properties for use by
another script. Use&nbsp;<strong>require</strong>&nbsp;in another script to
obtain the exports in the current script.</p>

<p>Exports will not work if you set exports = to an object (e.g.,
{&quot;key&quot; : &quot;value&quot; }). You must set properties of the exports
object as can be seen in the example.&nbsp;</p>

<p><strong>Require Extended Library:</strong>&nbsp;</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=44bd69b1-7d1e-44a5-9de4-705649073cb1>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>exports.test = &quot;test&quot;;</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Core-exports-Examples><strong><span style='font-family:
"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<h3 id=PhoneAPIReference-Core-exports-jsexamplefilewithexports>js example file
with exports</h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=847ad4cf-eaa7-418d-b50d-0fe300bf99f1>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var example2 = {};</pre><pre>example2.init = function () {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;this.status = 'Status set by example2.init()';</pre><pre>};</pre><pre>example2.getStatus = function () {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;return this.status;</pre><pre>};</pre><pre>example2.setStatus = function (param) {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;this.status = param;</pre><pre>};</pre><pre>&nbsp;&nbsp;</pre><pre>example2.init();</pre><pre>exports.getStatus = example2.getStatus.bind(example2);</pre><pre>exports.setStatus = example2.setStatus.bind(example2);</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core - require</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Core-require-require><strong><span style='font-family:
"Aptos Display",sans-serif;font-weight:normal'>require</span></strong></h2>

<p>Used to include and evaluate other scripts. Anything exported by a required
script is then made available using&nbsp;<strong>require</strong>.</p>

<p>When&nbsp;<strong>require</strong>&nbsp;is called, the app engine first
checks for the required script in the current directory. If a script with the
specified name is not found, it will check the shared lib directory (which
contains most predefined modules such as app, util, screen, etc.).</p>

<p>The first time a script is required in an app, it is evaluated and then the
exports are returned. If that script is required somewhere else in the same
app, a reference to the object created from the first require is returned
rather than evaluating the script again.</p>

<p>The following example code includes the util javascript module, which makes
all exported util methods then available, including util.isDef,
util.forceArray, etc.</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=f2764925-711e-4566-9849-59a7e9dfbe0b>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var app = require('util');</pre><pre>&nbsp;&nbsp;</pre><pre>var foo = util.isDef(bar);&nbsp; //foo = false</pre><pre>exampleArray = util.forceArray('test');&nbsp; //exampleArray = ['test']</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>Note: Required JavaScript files are referenced by their filename without the
.js extension.</p>

<p>The same script can be required from multiple places in an application, and
the file is evaluated the first time. For example, if your app is written in
four JavaScript files, you can require a specific one of them in all of them.
This allows different parts of an application to share data and methods.</p>

<p>As an example, see the following app, which is split into three scripts:
example1.js, example2.js, and example3.js. The following is its app.json file:</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=95a9705c-3991-44d2-a285-34f5aed35b75>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>{</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;name&quot;: &quot;test&quot;,</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;jsFiles&quot;: [&quot;example1.js&quot;],</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;type&quot;: &quot;foreground&quot;,</pre><pre>}&nbsp;</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p style='margin-left:.5in;text-indent:-.25in'>1.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>When the app is started, example1.js requires both example2.js and
example3.js (and example3.js, in turn, also references example2.js).&nbsp;When
example2.js is evaluated, its init() function assigns a value to the 'status'
property of 'Status set by example2.init()'</p>

<p style='margin-left:.5in;text-indent:-.25in'>2.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>This value is saved to the variable 'foo' in example1.js</p>

<p style='margin-left:.5in;text-indent:-.25in'>3.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>example2.setStatus() is used to change the value of example2.status to
'Status reset by example1.js'</p>

<p style='margin-left:.5in;text-indent:-.25in'>4.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>When the 'bar' variable is set to the result of the example3.getStatus()
function, you can see that the 'example2' object referenced in both example1.js
and example3.js is actually the same object.</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=8702cd18-3573-4cbb-b230-335554463812>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var example2 = require('example2');</pre><pre>var example3 = require('example3');</pre><pre>&nbsp;&nbsp;</pre><pre>var foo = example2.getStatus();&nbsp; //foo = 'Status set by example2.init()'</pre><pre>example2.setStatus('Status reset by example1.js');</pre><pre>var bar = example3.getStatus();&nbsp; //bar = 'Status reset by example1.js'</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none'>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <div>
  <div><pre>var example2 = {};</pre><pre>example2.init = function () {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;this.status = 'Status set by example2.init()';</pre><pre>};</pre><pre>example2.getStatus = function () {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;return this.status;</pre><pre>};</pre><pre>example2.setStatus = function (param) {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;this.status = param;</pre><pre>};</pre><pre>&nbsp;&nbsp;</pre><pre>example2.init();</pre><pre>exports.getStatus = example2.getStatus.bind(example2);</pre><pre>exports.setStatus = example2.setStatus.bind(example2);</pre></div>
  </div>
  </td>
 </tr>
</table>

<div>

<p class=MsoNormal><span style='display:none'>&nbsp;</span></p>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=e0e9a10a-df84-4b5f-b8f6-ea8dc11081b4>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var example2 = require('example2');</pre><pre>var example3 = {};</pre><pre>&nbsp;&nbsp;</pre><pre>example3.getStatus = function () {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;return example2.getStatus();</pre><pre>};</pre><pre>exports.getStatus = example3.getStatus.bind(example3);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p><strong>Parameters</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=9116e3c9-8817-4eaa-8e9f-e1fe7755f2d6>
 <colgroup><col style="width: 151.0px;"><col style="width: 94.0px;"><col style="width: 53.0px;"><col style="width: 81.0px;"><col style="width: 376.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>JavaScript module</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>JavaScript module to include.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Core digium.app.getList</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Coredigium.app.getList-digium.app.getList><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>digium.app.getList</span></strong></h2>

<h3 id=PhoneAPIReference-Coredigium.app.getList-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Returns an array containing the names of apps that the system knows about.
The names are defined in&nbsp;<a
href="/wiki/spaces/Phones/pages/21266665/app.json+File"
data-linked-resource-id=21266665 data-linked-resource-version=2
data-linked-resource-type=page>app.json</a>.</p>

<p><strong>Basic Example:</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=1b3d02e2-4f03-45d4-87be-f4adc3007cf9>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>digium.app.getList();</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Coredigium.app.getList-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=d4da419a-6598-4f24-9e15-31dfe9948eeb>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Coredigium.app.getList-Examples>Examples</h3>

<p><strong>digium.app.getList example</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=c809edaa-dde9-4c0e-a013-80e307d00b7e>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var appList = digium.app.getList();</pre><pre>&nbsp;&nbsp;</pre><pre>// Example output</pre><pre>util.debug(JSON.stringify(appList));</pre><pre>/* outputs something that looks like the following&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;[&quot;appscreen&quot;,&quot;bootconfig&quot;,&quot;contacts&quot;,&quot;parking&quot;,&quot;phonemenu&quot;,&quot;queues&quot;,&quot;status&quot;,</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;techsupport&quot;,&quot;voicemail&quot;,&quot;myname.test_app&quot;] */</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<p>Apps can include these libraries to access additional functionality. Unlike
the core functions, they are not available to apps without first requiring a
specific library.</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=80691ae0-64a0-4241-a122-c852c4b856b2>
 <colgroup><col style="width: 138.0px;"><col style="width: 620.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22315275/Phone+API+Reference+-+Extended+-+app"
  data-linked-resource-id=22315275 data-linked-resource-version=3
  data-linked-resource-type=page>app</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Loads and saves standard settings that can be later accessed and used
  across the application by other modules, screens, etc. Note: the app should
  always have its init() method called after being included.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22020525/Phone+API+Reference+-+Extended+-+util"
  data-linked-resource-id=22020525 data-linked-resource-version=3
  data-linked-resource-type=page>util</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Contains 'helper' functions useful for development.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22315343/Phone+API+Reference+-+Extended+-+pbx"
  data-linked-resource-id=22315343 data-linked-resource-version=3
  data-linked-resource-type=page>pbx</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Object used to send API requests to the PBX.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22282495/Phone+API+Reference+-+Extended+-+localization_date"
  data-linked-resource-id=22282495 data-linked-resource-version=3
  data-linked-resource-type=page>localization_date</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Library that aids in the processing of date strings, appropriate to the
  cultural differences for the user of the app, for display purposes.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - app.checkRequired</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-app.checkRequired-app.checkRequired><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>app.checkRequired</span></strong></h2>

<h3 id=PhoneAPIReference-Extended-app.checkRequired-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Takes a parameters object and a required keys array and compares the two. If
any keys are missing from the array, then an error is logged and the error
screen is shown (<a
href="/wiki/spaces/Phones/pages/78611886/Phone+API+Reference+-Extended+-+app.showErrors"
data-linked-resource-id=78611886 data-linked-resource-version=1
data-linked-resource-type=page>app.showErrors</a>).</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=55c1276c-d9c9-4a07-9dcc-308e1d4a828f>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var app = require('app');</pre><pre>app.init();</pre><pre>app.checkRequired(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p><strong>Parameters</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=c94abd9b-26a1-402b-b775-4d8246d6d36f>
 <colgroup><col style="width: 86.0px;"><col style="width: 86.0px;"><col style="width: 66.0px;"><col style="width: 113.0px;"><col style="width: 634.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>p</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>object</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>This is an object containing key value pairs.&nbsp;</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>required</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>array</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Array of keys that are checked against the keys of the p object.</p>
  </td>
 </tr>
</table>

</div>

<p>Error screen shown after failing checkRequired<br>
The required parameter ['test'] was not a key in the 'p' object passed in.</p>

<p class=MsoNormal><img border=0 width=389 height=194 id="Picture 147551087"
src="Digium%20One%20Page_files/image005.jpg"></p>

<h1>Phone API Reference - Extended - app</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-app-app><strong><span style='font-family:
"Aptos Display",sans-serif;font-weight:normal'>app</span></strong></h2>

<p>Loads and saves standard settings that can be later accessed and used across
the application by other modules, screens, etc. Note: the app should always
have its init() method called after being included.</p>

<p><strong>Require Extended Library:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=587d8f97-f301-4e4f-9b8a-d73e6e8ad00b>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var app = require('app');</pre><pre>app.init();</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-app-Methods><strong><span style='font-family:
"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=6e2e2ae9-5e45-4fbb-87ec-ec5bb87b4ac4>
 <colgroup><col style="width: 154.0px;"><col style="width: 834.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22511757/Phone+API+Reference+-+Extended+-+app.checkRequired"
  data-linked-resource-id=22511757 data-linked-resource-version=4
  data-linked-resource-type=page>app.checkRequired</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Takes a parameters object and a required keys array and compares the two.
  If any keys are missing from the array, then an error is logged and the error
  screen is shown (<a
  href="/wiki/spaces/Phones/pages/78611886/Phone+API+Reference+-Extended+-+app.showErrors"
  data-linked-resource-id=78611886 data-linked-resource-version=1
  data-linked-resource-type=page>app.showErrors</a>).</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22446201/Phone+API+Reference+-+Extended+-+app.getAuth"
  data-linked-resource-id=22446201 data-linked-resource-version=2
  data-linked-resource-type=page>app.getAuth</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns a reference to the automatically instantiated Auth object that is
  created when app.init is called.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22446219/Phone+API+Reference+-+Extended+-+app.getConfig"
  data-linked-resource-id=22446219 data-linked-resource-version=2
  data-linked-resource-type=page>app.getConfig</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns an object that contains this app's various settings including id,
  settings, and account. These are parsed from the app's XML in the phone
  configuration's&nbsp;<strong>appconfig</strong>&nbsp;section.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22478999/Phone+API+Reference+-+Extended+-+app.init"
  data-linked-resource-id=22478999 data-linked-resource-version=2
  data-linked-resource-type=page>app.init</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Initializes the app object.&nbsp;Important: this should be done
  immediately after including the app library for consistent results.&nbsp;</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22315312/Phone+API+Reference+-+Extended+-+app.refreshConfig"
  data-linked-resource-id=22315312 data-linked-resource-version=2
  data-linked-resource-type=page>app.refreshConfig</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Reloads your appconfig and makes a new Auth object.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/78611886/Phone+API+Reference+-Extended+-+app.showErrors"
  data-linked-resource-id=78611886 data-linked-resource-version=1
  data-linked-resource-type=page>app.showErrors</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Clears the screen and shows an error popup on the entire screen. Takes an
  array of error messages so you can show multiple messages at one time.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22741070/Phone+API+Reference+-+Extended+-+app.t"
  data-linked-resource-id=22741070 data-linked-resource-version=2
  data-linked-resource-type=page>app.t</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns the translated string of the specified language key.&nbsp;</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-app-Properties><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Properties</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=c50a7e2b-954a-4202-86cf-5d2c1495e2a0>
 <colgroup><col style="width: 101.0px;"><col style="width: 657.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>app.images</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Automatically instantiated Image UI objects when app is required.&nbsp;</p>
  <p><strong>Basic Example:</strong></p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>app.images.softKeys.left; // returns left arrow Image object</pre><pre>app.images.softKeys.right; // returns left arrow Image object</pre><pre>app.images.softKeys.up; // returns left arrow Image object</pre><pre>app.images.softKeys.down; // returns left arrow Image object</pre><pre>app.images.softKeys.select; // returns the check mark image</pre><pre>app.images.softKeys.cancel; // returns left x cancel image</pre></div>
  </div>
  <p>These most likely useful for creating apps with standarized softkeys.
  See&nbsp; <a
  href="/wiki/spaces/Phones/pages/22217193/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+Widget+%28Base+Class%29+-+setSoftkeyIcon"
  data-linked-resource-id=22217193 data-linked-resource-version=1
  data-linked-resource-type=page>setSoftKeyIcon</a> &nbsp;for setting softKey
  icons on your widgets.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - app.getAuth</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-app.getAuth-app.getAuth><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>app.getAuth</span></strong></h2>

<h3 id=PhoneAPIReference-Extended-app.getAuth-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Returns a reference to the automatically instantiated Auth object that is
created when app.init is called.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=b801cbed-02be-4f1c-9652-abf61de5b991>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var authObj = app.getAuth();</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p><strong>Parameters</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=aac8123f-ec25-4666-b822-6b93c0f4753d>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - app.getConfig</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-app.getConfig-app.getConfig><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>app.getConfig</span></strong></h2>

<h3 id=PhoneAPIReference-Extended-app.getConfig-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Returns an object that contains this app's various settings including id,
settings, and account. These are parsed from the app's XML in the phone
configuration's&nbsp;<strong>appconfig</strong>&nbsp;section.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=54dedcb6-68d4-476b-aba0-357fbc69c8b1>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var configData = app.getConfig();</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-app.getConfig-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=ba85a9de-abe5-4fa5-ab9a-538c7f707136>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - app.init</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-app.init-app.init><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>app.init</span></strong></h2>

<h3 id=PhoneAPIReference-Extended-app.init-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Initializes the app object.&nbsp;Important: this should be done immediately
after including the app library for consistent results.&nbsp;</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=0cd34ef4-598f-4cd3-a868-578176617a74>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>app.init([parameters]);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-app.init-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=82bc780d-10a7-4792-87fa-5a8219ad2204>
 <colgroup><col style="width: 151.0px;"><col style="width: 86.0px;"><col style="width: 78.0px;"><col style="width: 76.0px;"><col style="width: 597.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Required</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Type</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Default</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>onError</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>function</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Overloads if your application wants to handle error specifically.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>defaultLangLocale</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>string</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Indicates the language file to use if the app does not have a language
  file for the phone's chosen language. For example, if the chosen
  language/locale is&nbsp;<strong>fr_fr</strong>, but the app does not include
  the file&nbsp;<strong>strings.fr_fr.js</strong>, then the app uses the
  default language file as indicated with this parameter. If no value has been
  defined, the phone tries to use&nbsp;<strong>en_us</strong>.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - app.refreshConfig</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-app.refreshConfig-app.refreshConfig><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>app.refreshConfig</span></strong></h2>

<h3 id=PhoneAPIReference-Extended-app.refreshConfig-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Reloads your appconfig and makes a new Auth object.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=2ca54418-9cf0-4259-b4c4-8d2c79fc8c03>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>app.refreshConfig();</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>The app library automatically calls this on itself when the event
'digium.phone.new_config' happens. This makes sure your settings and Auth
object are always up to date.</p>

<h3 id=PhoneAPIReference-Extended-app.refreshConfig-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=3beeb46d-66a3-45cc-bfb9-d0f9aaf97ee2>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - app.t</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-app.t-app.t><strong><span style='font-family:
"Aptos Display",sans-serif;font-weight:normal'>app.t</span></strong></h2>

<h3 id=PhoneAPIReference-Extended-app.t-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Returns the translated string of the specified language key.&nbsp;</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=5cebbe26-edbf-4220-b35e-f6542ad62011>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var text = app.t(key[, vars, count]);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>
