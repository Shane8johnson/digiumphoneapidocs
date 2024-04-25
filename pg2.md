<h3 id=PhoneAPIReference-Extended-app.t-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=970
 data-layout=default data-local-id=db03b557-d590-43f0-a1af-37b18884f859>
 <colgroup><col style="width: 69.0px;"><col style="width: 86.0px;"><col style="width: 78.0px;"><col style="width: 79.0px;"><col style="width: 658.0px;"></colgroup>
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
  <p>key</p>
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
  <p>The language key used to fetch a string. If no string is found for the
  key, then the key is returned as the string.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>vars</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>array</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>An array of variables to use for substitution in your string. For example,
  if your string is &quot;This %s belongs to %s&quot; and you pass ['Pizza',
  'Bob'] for vars, the string returned will be &quot;This Pizza belongs to
  Bob&quot;.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>count</p>
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
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>1</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>The integer to use for pluralization. This is used if you provide
  different forms of your string based on the pluralization. For example, your
  lang key might define the following ['I have one index', 'I have many
  indices']. If you pass a value of 1 for vars then the first string will be
  returned by the translate function, if you pass a value of more than 1, then
  the second form will be returned.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-app.t-Examples>Examples</h3>

<p>Various examples of app.t</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=247b8b54-44e7-4e98-a520-be14df95983d>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>/*&nbsp;</pre><pre>&nbsp;For the purpose of this example, lets assume we have included a strings-en_us.js file in our&nbsp;</pre><pre>&nbsp;package and it looks like this.&nbsp;</pre><pre>&nbsp;This covers each combination of ways the translation library can be used.&nbsp; &nbsp;</pre><pre>&nbsp;&nbsp;</pre><pre>exports.keys = {&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;T_HELLO_WORLD&quot; : [&quot;Hello World&quot;],&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;T_MY_NAME_IS&quot; : ['My Name is %s&quot;],&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;T_DOG&quot; : [&quot;Dog&quot;, &quot;Dogs&quot;],&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;T_PERSON_PPL&quot; : [&quot;I employ %s person&quot;, &quot;I employ %s people.&quot;],&nbsp;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&quot;T_MY_ADDRESS&quot; : [&quot;My address is %s; %s, %s %s&quot;]&nbsp;</pre><pre>};&nbsp;</pre><pre>*/</pre><pre>&nbsp;&nbsp;</pre><pre>app.t(&quot;T_HELLO_WORLD&quot;);&nbsp; // returns &quot;Hello World&quot;</pre><pre>app.t(&quot;T_MY_NAME_IS&quot;, [&quot;Ryan&quot;]);&nbsp; // returns &quot;My Name is Ryan&quot;</pre><pre>app.t(&quot;T_DOG&quot;, [], 1); // returns &quot;Dog&quot;</pre><pre>app.t(&quot;T_DOG&quot;, [], 2);&nbsp; // returns &quot;Dogs&quot;</pre><pre>app.t(&quot;T_PERSON_PPL&quot;, [1], 1);&nbsp; // returns &quot;I employ 1 person.&quot;</pre><pre>app.t(&quot;T_PERSON_PPL&quot;, [3], 3);&nbsp; // returns &quot;I employ 3 people.&quot;</pre><pre>app.t(&quot;T_MY_ADDRESS&quot;. [&quot;12 Brown St.&quot;, &quot;San Diego&quot;, &quot;CA&quot;, &quot;91211&quot;]);&nbsp; // returns &quot;My address is 12 Brown St.; San Diego, CA 91211&quot;</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - app - setSoftkeyIcon</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-app-setSoftkeyIcon-setSoftkeyIcon><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>setSoftkeyIcon</span></strong></h2>

<h3 id=PhoneAPIReference-Extended-app-setSoftkeyIcon-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Sets an image object to display at the top left corner of the softkey.
Useful for indicating a hard key that calls the same handler. Suggested image
size is 5x5 pixels.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=a47213b3-cf03-43ab-ad88-6621d0a67b7b>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;exampleObj.setSoftkeyIcon(keyNum, icon);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>If you require the app library, you can use Digium's set of softkey icons.
These image objects are created when the library is required.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>app.images.softKeys.left (left arrow)</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>app.images.softKeys.right (right arrow)</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>app.images.softKeys.up (up arrow)</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>app.images.softKeys.down (down arrow)</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>app.images.softKeys.select (check mark)</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>app.images.softKeys.cancel (X)</p>

<h3 id=PhoneAPIReference-Extended-app-setSoftkeyIcon-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=68991da3-b9cd-4b67-9352-6d9d83c37707>
 <colgroup><col style="width: 80.0px;"><col style="width: 90.0px;"><col style="width: 77.0px;"><col style="width: 98.0px;"><col style="width: 410.0px;"></colgroup>
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
  <p>keyNum</p>
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
  <p>Softkeys are labeled 1-4.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>icon</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>widget</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Instance of a image widget for display.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-app-setSoftkeyIcon-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>setSoftkeyIcon to set icons for the softkeys: Digium up arrow,
Digium checkmark, custom icon</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=c46a7f3d-61ee-4558-8ab7-b4499f8553b4>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>testWidget.setSoftkeyIcon(1, app.images.softKeys.up);</pre><pre>testWidget.setSoftkeyIcon(2, app.images.softKeys.select);</pre><pre>&nbsp;&nbsp;</pre><pre>var imgWidget = new Image(&quot;app&quot;, &quot;smileyface.png&quot;, 0, 0, 5, 5);</pre><pre>testWidget.setSoftkeyIcon(3, imgWidget);</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - localization_date</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id="PhoneAPIReference-Extended-localization_date-localization_date"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>localization_date</span></strong></h2>

<p>Library that aids in the processing of date strings, appropriate to the
cultural differences for the user of the app, for display purposes.</p>

<p><strong>Require Extended Library:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=af110402-890d-4f00-922d-43e214680214>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var localization_date = require('localization_date');</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-Extended-localization_date-Methods"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=7753158e-2984-4949-8985-36e2dee0f3bc>
 <colgroup><col style="width: 188.0px;"><col style="width: 800.0px;"></colgroup>
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
  href="/wiki/spaces/Phones/pages/22217041/Phone+API+Reference+-+Extended+-+localization_date.format"
  data-linked-resource-id=22217041 data-linked-resource-version=2
  data-linked-resource-type=page>localization_date.format</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Formats an RFC822 or ISO 8601 date string and displays a localized date
  based on the phone's preferred locale.</p>
  <p>For example, take the thirtieth day in the month of April for the year
  2013. For the US locale, the phone would display 04/30/2013. If your phone's
  localization setting were set to the UK and you used this library, your
  display would read 30/04/2013.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - localization_date.format</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2
id="PhoneAPIReference-Extended-localization_date.format-localization_date.format"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>localization_date.format</span></strong></h2>

<h3 id="PhoneAPIReference-Extended-localization_date.format-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Formats an RFC822 or ISO 8601 date string and displays a localized date
based on the phone's preferred locale.</p>

<p>For example, take the thirtieth day in the month of April for the year 2013.
For the US locale, the phone would display 04/30/2013. If your phone's
localization setting were set to the UK and you used this library, your display
would read 30/04/2013.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=13a0606e-b84f-4991-b46b-235756e1b9db>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var formattedDate = localization_date.format(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>Additional display behaviors:</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>Current day, returns the&nbsp;<strong>time</strong>.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>Day previous, returns&nbsp;<strong>Yesterday</strong>.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>Within the last seven days, returns day of the week (i.e.,&nbsp;<strong>Monday</strong>).</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>More than seven days in the past returns a short or long date, in
the format associated with the phone's chosen locale.</p>

<h3 id="PhoneAPIReference-Extended-localization_date.format-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=82c25e0c-51dd-41b2-b131-ec8f3c88a4fd>
 <colgroup><col style="width: 70.0px;"><col style="width: 85.0px;"><col style="width: 62.0px;"><col style="width: 164.0px;"><col style="width: 607.0px;"></colgroup>
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
  <p>date</p>
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
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>2020-04-30 10:58:01</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>RFC822 or ISO 8601 date string</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>version</p>
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
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>short</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Format of response string. Can be&nbsp;<strong>long</strong>&nbsp;or&nbsp;<strong>short.&nbsp;</strong>Defaults
  to short. Long includes the time.</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-Extended-localization_date.format-Examples"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>date.format with different versions</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=d3bc85f7-de56-41b3-be7d-867eb1536687>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var dateString = date.format({</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'date' : '1985-08-11',</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'version' : 'short'</pre><pre>});&nbsp; // sets dateString to '8/11/85'</pre><pre>&nbsp;&nbsp;</pre><pre>dateString = date.format({</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'date' : '1985-08-11',</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'version' : 'long'</pre><pre>});&nbsp; // sets dateString to '11/8/85 0:00'</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - pbx</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-pbx-pbx><strong><span style='font-family:
"Aptos Display",sans-serif;font-weight:normal'>pbx</span></strong></h2>

<p>Object used to send API requests to the PBX.</p>

<p><strong>Require Extended Library:</strong>&nbsp;</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=6cbf369d-a17a-40d2-8fc0-515d41d4d9fb>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var pbx = require('pbx');</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-pbx-Methods>Methods</h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=a84d14a3-25f3-4c35-8f0a-4f88bffbb9b1>
 <colgroup><col style="width: 113.0px;"><col style="width: 647.0px;"></colgroup>
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
  href="/wiki/spaces/Phones/pages/22511836/Phone+API+Reference+-+Extended+-+pbx.request"
  data-linked-resource-id=22511836 data-linked-resource-version=2
  data-linked-resource-type=page>pbx.request</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Sends an API request and (optionally) handles the response. This may
  require an authenticated Auth object.</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>For information regarding the Switchvox Extend API visit&nbsp;<a
  href="http://developers.digium.com/switchvox/">http://developers.digium.com/switchvox/</a>.&nbsp;&nbsp;</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - pbx.request</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-pbx.request-pbx.request><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>pbx.request</span></strong></h2>

<h3 id=PhoneAPIReference-Extended-pbx.request-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Sends an API request and (optionally) handles the response. This may require
an authenticated Auth object.</p>

<p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span>For information regarding the Switchvox Extend API visit&nbsp;<a
href="http://developers.digium.com/switchvox/">http://developers.digium.com/switchvox/</a>.</p>

<p>&nbsp;&nbsp;<br>
<strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=33b51a1f-c4dc-4a4c-be71-a0ec827f5d82>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>pbx.request(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-pbx.request-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=380d3002-0b5b-483b-a327-c76f4cd74f01>
 <colgroup><col style="width: 102.0px;"><col style="width: 86.0px;"><col style="width: 85.0px;"><col style="width: 80.0px;"><col style="width: 637.0px;"></colgroup>
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
  <p>Name of the API method to call.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>parameters</p>
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
  <p>Javascript Object containing key value pairs of values appriopriate to the
  API method. Default is empty object.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>onSuccess</p>
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
  <p>Function to execute if request returns with a success status. This
  function will be passed a hash with the format {'result' : queryResultObject,
  'method' : 'apiMethod'}.</p>
  <p>Callback function to call when the request successfully completes. If
  nothing is passed, the default onSuccess callback writes a success message to
  the log.</p>
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
  <p>Callback function to call when there is an error making the request. If
  nothing is passed in, the default onError callback shows a screen that
  displays the error.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>loadingText</p>
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
  <p>Message to display during request execution. If none is provided, the
  loading screen will not be displayed.</p>
  <p>If you want to send the requeset to the PBX the phone is configured to as
  the extension the phone is configured as, then this parameters is not needed.
  If you want to send the request to another PBX or make it as another user,
  then you need to pass in an Auth object.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>auth</p>
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
  <p>An auth object that contains the account_id, username, password, and
  server address to authorize pbx requests.</p>
  <p>If you want to send the request to the PBX the phone is configured to as
  the extension the phone is configured as, then this parameter is not needed.
  If you want to send the request to another PBX or make it as another user,
  then you need to pass in an Auth object.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-pbx.request-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>pbx.request to print extension info associated with the account</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=6f2e0696-e17a-4a18-924a-6bc50fa8e0a1>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>pbx.request({</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'method' : ' switchvox.users.getMyInfo',</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'loadingText' : 'Getting extension info',</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'onSuccess' : function (response) {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;util.debug(response.result.extension.number);</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;}</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;});</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p><strong>pbx.request to retrieve a presence option list for specified account</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=bffdbf60-0dfd-4bdc-846b-8b59fad63e03>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;pbx.request({</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'method'&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; : 'switchvox.users.presence.options.getList',</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'parameters'&nbsp;&nbsp;&nbsp; : {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'account_id' : &quot;1235&quot;</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;},</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'loadingText'&nbsp;&nbsp; : app.t('STATUSLIST_LOADING'),</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'onSuccess'&nbsp;&nbsp;&nbsp;&nbsp; : function (p) {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;util.debug(&quot;We got status options&quot;);</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;util.debug(JSON.stringify(p.result.presence_options));</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;});</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - util.debug</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-util.debug-util.debug><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>util.debug</span></strong></h2>

<h3 id=PhoneAPIReference-Extended-util.debug-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Prints the supplied message to the standard output. &nbsp;Use the&nbsp;<a
href="/wiki/spaces/Phones/pages/20319476/Using+the+Phone%27s+App+Development+Web+Page"
data-linked-resource-id=20319476 data-linked-resource-version=3
data-linked-resource-type=page>App Development</a>&nbsp;web page for your phone
to view the output from debugging. For debugging objects, use the
JSON.stringify function.&nbsp;</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=c130c05b-51f7-4247-b954-ed2539daeec5>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var testString = &quot;Test Test&quot;;</pre><pre>util.debug(testString); // &quot;Test Test&quot;;</pre><pre>&nbsp;&nbsp;</pre><pre>var test = {};</pre><pre>util.debug(test); // &quot;[object Object]&quot;;</pre><pre>util.debug(JSON.stringify(test)); // &quot;{}&quot;</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-util.debug-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=43f8f335-37e1-452b-8768-22895b7301c6>
 <colgroup><col style="width: 79.0px;"><col style="width: 86.0px;"><col style="width: 68.0px;"><col style="width: 82.0px;"><col style="width: 440.0px;"></colgroup>
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
  <p>message</p>
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
  <p>Message to be displayed.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>indent</p>
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
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>0</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Number of tab stops to indent the message.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-util.debug-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>util.debug to print Hello World</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=91004be1-b074-4be7-b554-7e9743e5604d>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>util.debug('Hello World');</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - util.defaults</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-util.defaults-util.defaults><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>util.defaults</span></strong></h2>

<h3 id=PhoneAPIReference-Extended-util.defaults-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Merges two objects and returns the result. For each key provided, the target
object is checked for a corresponding key. If none is found, it will be created
with the provided value. Keys in target that are defined will not be
overwritten.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=dd8a6065-c51d-41e9-a262-80cba391e48f>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>util.defaults(target, object);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-util.defaults-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=49e10602-1055-4965-9831-2e729e4d238f>
 <colgroup><col style="width: 70.0px;"><col style="width: 90.0px;"><col style="width: 76.0px;"><col style="width: 76.0px;"><col style="width: 443.0px;"></colgroup>
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
  <p>target</p>
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
  <p>The target object to be filled with values.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>object</p>
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
  <p>The object containing properties to merge into target.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-util.defaults-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p>util.defaults creates an object with properties 'foo' -&gt; 'test', 'bar'
-&gt; 999</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=ad65c8fd-c6f0-45b9-93d6-c46c730515bf>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var target = {'foo' : 'test'};</pre><pre>target = util.defaults(target, {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'foo' : 'Target already contains property &quot;foo&quot;, this property will not be merged',</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'bar' : 999</pre><pre>});</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - util</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-util-util><strong><span style='font-family:
"Aptos Display",sans-serif;font-weight:normal'>util</span></strong></h2>

<p>Contains 'helper' functions useful for development.</p>

<p><strong>Require Extended Library:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=7d2ba4b8-7a0a-4dca-8ff6-27b0e8442005>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var util = require('util');</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-util-Methods><strong><span style='font-family:
"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=5ef28a53-1b31-457a-b6f1-ad1f9ff734e3>
 <colgroup><col style="width: 151.0px;"><col style="width: 837.0px;"></colgroup>
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
  href="/wiki/spaces/Phones/pages/22020544/Phone+API+Reference+-+Extended+-+util.debug"
  data-linked-resource-id=22020544 data-linked-resource-version=3
  data-linked-resource-type=page>util.debug</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Prints the supplied message to the standard output. &nbsp;Use the&nbsp;<a
  href="https://wiki-legacy.freepbx.org/display/PHON/Using+the+Phone%27s+App+Development+Web+Page">App
  Development</a>&nbsp;web page for your phone to view the output from
  debugging. For debugging objects, use the JSON.stringify function.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22741099/Phone+API+Reference+-+Extended+-+util.defaults"
  data-linked-resource-id=22741099 data-linked-resource-version=2
  data-linked-resource-type=page>util.defaults</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Merges two objects and returns the result. For each key provided, the
  target object is checked for a corresponding key. If none is found, it will
  be created with the provided value. Keys in target that are defined will not
  be overwritten.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22184285/Phone+API+Reference+-+Extended+-+util.forceArray"
  data-linked-resource-id=22184285 data-linked-resource-version=2
  data-linked-resource-type=page>util.forceArray</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns an array.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22315370/Phone+API+Reference+-+Extended+-+util.formatDuration"
  data-linked-resource-id=22315370 data-linked-resource-version=2
  data-linked-resource-type=page>util.formatDuration</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Takes a number of seconds and returns a formatted string representing that
  amount of time in hours and seconds. There are two possible formats:&nbsp;<strong>long</strong>&nbsp;and&nbsp;<strong>short</strong>.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22544558/Phone+API+Reference+-+Extended+-+util.isDef"
  data-linked-resource-id=22544558 data-linked-resource-version=2
  data-linked-resource-type=page>util.isDef</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns true if the supplied variable is defined, false if it is not
  defined (undefined).</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22675600/Phone+API+Reference+-+Extended+-+util.isUndef"
  data-linked-resource-id=22675600 data-linked-resource-version=2
  data-linked-resource-type=page>util.isUndef</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns true if the supplied variable is undefined, false if it is
  defined.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - util.forceArray</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-util.forceArray-util.forceArray><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>util.forceArray</span></strong></h2>

<h3 id=PhoneAPIReference-Extended-util.forceArray-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Returns an array.</p>

<p><strong>Basic Example:</strong>&nbsp;</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=ee489475-3806-44ea-9932-16851e345087>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var newArray = util.forceArray(value[, key]);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>If called with a single argument of an array, returns the argument forced
into an array. Otherwise, returns a new array containing argument.</p>

<p>Also can be called with an object and property name. In this case, it uses
object[propertyName] as the target.</p>

<p>If value (or value[key]) is undefined, returns an empty array.</p>

<h3 id=PhoneAPIReference-Extended-util.forceArray-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=afa90998-8899-4b91-926f-4be424932bf5>
 <colgroup><col style="width: 64.0px;"><col style="width: 86.0px;"><col style="width: 64.0px;"><col style="width: 78.0px;"><col style="width: 463.0px;"></colgroup>
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
  <p>value</p>
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
  <p>Value to be forced into an array.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>key</p>
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
  <p>If provided, value[key] is forced into an array.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-util.forceArray-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>util.forceArray returns an array</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=55bca65e-174c-42c1-b810-e9a34faa3a1e>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var param = 'foo';</pre><pre>util.forceArray(param);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p><strong>util.forceArray returns an array, takes an object as the first
parameter</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=c42af241-030b-4ea3-8c81-2349360e4f5a>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var param = {'foo' : 'bar'};</pre><pre>util.forceArray(param, 'foo');</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - util.formatDuration</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-util.formatDuration-util.formatDuration><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>util.formatDuration</span></strong></h2>

<h3 id=PhoneAPIReference-Extended-util.formatDuration-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Takes a number of seconds and returns a formatted string representing that
amount of time in hours and seconds. There are two possible formats:&nbsp;<strong>long</strong>&nbsp;and&nbsp;<strong>short</strong>.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=76597190-15f4-42b8-959c-2e8cd5a3fef4>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var timeString = util.formatDuration(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p><strong>long</strong>&nbsp;format returns a string showing hours (if greater
than 0), minutes (if seconds &gt; 60) and seconds. Time durations are shown as
strings (e.g.,&nbsp;<strong>Hour</strong>,&nbsp;<strong>Minute</strong>) and
seconds are not displayed if the number of hours &gt; 0.</p>

<p><strong>short</strong>&nbsp;format returns a string showing hours (if
greater than 0), minutes (if seconds &gt; 60) and seconds. Time durations are
shown as letters (e.g.,&nbsp;<strong>h</strong>&nbsp;for hours) and seconds are
not displayed if the number of hours &gt; 0, or if number of minutes &gt; 10.</p>

<h3 id=PhoneAPIReference-Extended-util.formatDuration-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=94a017a1-01ac-409e-87e7-b5a11e1c0680>
 <colgroup><col style="width: 77.0px;"><col style="width: 86.0px;"><col style="width: 69.0px;"><col style="width: 75.0px;"><col style="width: 448.0px;"></colgroup>
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
  <p>seconds</p>
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
  <p>Length of time to be formatted.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>format</p>
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
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>short</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Format of response string. Can be&nbsp;<strong>long</strong>&nbsp;or&nbsp;<strong>short&nbsp;</strong>(default)<strong>.</strong></p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-util.formatDuration-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>util.formatDuration in all formats</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=95218069-b57b-4c9d-83f2-1cb973e42a2c>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>// returns the string '3h, 25m'</pre><pre>var short = util.formatDuration({</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'seconds' : 12345,</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'format' : 'short'</pre><pre>});</pre><pre>&nbsp;&nbsp;</pre><pre>// returns the string '3 hours, 25 minutes'</pre><pre>var long = util.formatDuration({</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'seconds' : 12345,</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;'format' : 'long'</pre><pre>});</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - util.isDef</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-util.isDef-util.isDef><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>util.isDef</span></strong></h2>

<h3 id=PhoneAPIReference-Extended-util.isDef-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Returns true if the supplied variable is defined, false if it is not defined
(undefined).</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=9201be40-7694-4b4c-861a-b9530d887db6>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>util.isDef(var);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>Note: if the variable you are testing has not been declared in anyway, this
will throw an exception. If it has been declared but iniitalized as undefined
(e.g., not set in any way), the code will process.</p>

<h3 id=PhoneAPIReference-Extended-util.isDef-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=2f82efa7-e026-4ec9-9154-cfcec1486c7c>
 <colgroup><col style="width: 66.0px;"><col style="width: 87.0px;"><col style="width: 300.0px;"><col style="width: 151.0px;"><col style="width: 151.0px;"></colgroup>
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
  <p>var</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>variable</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Variable to be checked for definition.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-util.isDef-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p>util.isDef returns true or false</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=064ffe30-d176-4bb3-a559-da2d095592ce>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var declaredUndef;</pre><pre>var str = 'foo';</pre><pre>var obj = {'test1' : 'abc'};</pre><pre>util.isDef(str);&nbsp;&nbsp;&nbsp; // returns true</pre><pre>util.isDef(obj.test1);&nbsp; // returns true</pre><pre>util.isDef(obj.test2);&nbsp; // returns false</pre><pre>util.isDef(declaredUndef); // false</pre><pre>util.isDef(nonDeclaredVariable); // throws exception</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended - util.isUndef</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-Extended-util.isUndef-util.isUndef><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>util.isUndef</span></strong></h2>

<h3 id=PhoneAPIReference-Extended-util.isUndef-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Returns true if the supplied variable is undefined, false if it is defined.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<div><pre
data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
data-theme=Confluence>util.isUndef(var);</pre></div>

</div>

<p>Note: if the variable you are testing has not been declared in anyway, this
will throw an exception. If it has been declared but iniitalized as undefined
(e.g,. not set in any way), the code with process.</p>

<h3 id=PhoneAPIReference-Extended-util.isUndef-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=6a60bd8f-13c8-497b-bcb7-e3c93b2d5e72>
 <colgroup><col style="width: 64.0px;"><col style="width: 87.0px;"><col style="width: 73.0px;"><col style="width: 80.0px;"><col style="width: 451.0px;"></colgroup>
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
  <p>var</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>variable</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Variable to be checked for definition.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-Extended-util.isUndef-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>util.isUndef returns true or false</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=71c0913a-8866-49af-afc3-3912bef477ae>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var declaredUndef;</pre><pre>var str = 'foo';</pre><pre>var obj = {'test1' : 'abc'};</pre><pre>util.isUndef(str);&nbsp; // returns false</pre><pre>util.isUndef(obj.test1);&nbsp;&nbsp;&nbsp; // returns false</pre><pre>util.isUndef(obj.test2);&nbsp;&nbsp;&nbsp; // returns true</pre><pre>util.isUndef(declaredUndef); // true</pre><pre>util.isUndef(nonDeclaredVariable); // throws exception</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended Classes</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<p>These object constructors are made available to apps by requiring a library.
They provide specific solutions for interacting with the application
environment.</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=7123f5dc-0539-4244-9438-e66792e861d8>
 <colgroup><col style="width: 99.0px;"><col style="width: 889.0px;"></colgroup>
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
  href="/wiki/spaces/Phones/pages/22511895/Phone+API+Reference+-+Extended+Classes+-+Auth"
  data-linked-resource-id=22511895 data-linked-resource-version=3
  data-linked-resource-type=page>Auth</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Used primarily to interact with the PBX when the phone is used with a
  server running either Switchvox or the&nbsp;<a
  href="/wiki/spaces/Phones/pages/21004585" data-linked-resource-id=21004585
  data-linked-resource-version=3 data-linked-resource-type=page>Desk Phone
  Module for Asterisk (DPMA)</a>. The auth object holds the user's account id,
  extension, password, and the address of the server.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22282542/Phone+API+Reference+-+Extended+Classes+-+Language"
  data-linked-resource-id=22282542 data-linked-resource-version=3
  data-linked-resource-type=page>Language</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Localization_language library's Language constructor that creates an
  object used for translating strings. After the object is created, it checks
  the phone's lang/locale settings and attempts to load any localized string
  files available. For example, if the phone's locale is set to&nbsp;<strong>es_mx</strong>&nbsp;(Spanish/Mexico),
  the Language constructor checks the app's directory for a 'strings-es_mx.js'
  file and attempts to load language keys from this file. For more information
  about creating localized apps see&nbsp;<a
  href="/wiki/spaces/Phones/pages/20319444/Building+Localized+Apps"
  data-linked-resource-id=20319444 data-linked-resource-version=3
  data-linked-resource-type=page>Building Localized Apps</a>&nbsp;in the Guides
  section.</p>
  <p>Additionally, the phone's lang/locale settings can be overridden when
  creating the Language object by passing a langLocale string to the
  constructor.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22642782/Phone+API+Reference+-+Extended+Classes+-+Document"
  data-linked-resource-id=22642782 data-linked-resource-version=2
  data-linked-resource-type=page>Document</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Creates a new DOM Document. The document created can be manipulated with
  javascript's standard DOM methods.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended Classes - Auth</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-ExtendedClasses-Auth-Auth><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>Auth</span></strong></h2>

<p>Used primarily to interact with the PBX when the phone is used with a server
running either Switchvox or the&nbsp;<a
href="/wiki/spaces/Phones/pages/21004585" data-linked-resource-id=21004585
data-linked-resource-version=3 data-linked-resource-type=page>Desk Phone Module
for Asterisk (DPMA)</a>. The auth object holds the user's account id,
extension, password, and the address of the server.</p>

<p><strong>Require Extended Library:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=723cecdc-6764-437f-837f-74cce2bffb0a>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var Auth = require('auth').Auth; //access the Auth property which is the Auth constructor.</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-ExtendedClasses-Auth-ClassConstructor><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Class Constructor</span></strong></h3>

<h4 id="PhoneAPIReference-ExtendedClasses-Auth-newAuth()"><u>new Auth()</u></h4>

<p><strong>Create a new Auth Object.</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=ccb2ae8c-acf4-47af-88bb-49eac8589a44>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var authObj = new Auth(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h4 id=PhoneAPIReference-ExtendedClasses-Auth-InitializationParameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Initialization
Parameters</span></strong></h4>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=a786d836-420f-4aa1-968f-b30398f9f30f>
 <colgroup><col style="width: 104.0px;"><col style="width: 89.0px;"><col style="width: 81.0px;"><col style="width: 83.0px;"><col style="width: 633.0px;"></colgroup>
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
  <p>account_id</p>
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
  <p>Unique ID of the account.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>username</p>
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
  <p>Username that will be used when making requests with the auth object. For&nbsp;<a
  href="/wiki/spaces/Phones/pages/22511836/Phone+API+Reference+-+Extended+-+pbx.request"
  data-linked-resource-id=22511836 data-linked-resource-version=2
  data-linked-resource-type=page>pbx</a>&nbsp;requests, this is the account's
  extension.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>password</p>
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
  <p>Password to use with requests using the auth object. For requests made
  with the&nbsp;<a
  href="/wiki/spaces/Phones/pages/22315343/Phone+API+Reference+-+Extended+-+pbx"
  data-linked-resource-id=22315343 data-linked-resource-version=3
  data-linked-resource-type=page>pbx</a>&nbsp;library, this is the account's
  web password.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>appserver</p>
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
  <p>Address to which requests using the auth object will be directed.&nbsp;</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>lang</p>
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
  <p><a
  href="/wiki/spaces/Phones/pages/22282542/Phone+API+Reference+-+Extended+Classes+-+Language"
  data-linked-resource-id=22282542 data-linked-resource-version=3
  data-linked-resource-type=page>Language</a>&nbsp;object instance.</p>
  </td>
 </tr>
</table>

</div>

<p>The functionality of this object is included in the&nbsp; <a
href="/wiki/spaces/Phones/pages/22315275/Phone+API+Reference+-+Extended+-+app"
data-linked-resource-id=22315275 data-linked-resource-version=3
data-linked-resource-type=page>app extended library</a> . It is recommended you
use the app library if you wish to use this feature.&nbsp;</p>

<h3 id=PhoneAPIReference-ExtendedClasses-Auth-Methods><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=58e8a655-8bef-4a56-b08b-cf87eb9079a0>
 <colgroup><col style="width: 144.0px;"><col style="width: 478.0px;"><col style="width: 119.0px;"><col style="width: 247.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Name&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Parameters</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Examples</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>showLoginScreen</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Displays a login screen on which a user can enter a server, extension, and
  password.<br>
  Calls back after the user successfully logs in from the login screen. Used
  with a Switchvox configuration server environment.</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><strong>auth.showLoginScreen</strong></p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var authObj = require('auth').Auth;</pre><pre>&nbsp;&nbsp;</pre><pre>var auth = new authObj();</pre><pre>if (!auth.isLoggedIn()) {</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;return auth.showLoginScreen({</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'callback' : callbackFunction,</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;});</pre><pre>}</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended Classes - Document</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-ExtendedClasses-Document-Document><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>Document</span></strong></h2>

<p>Creates a new DOM Document. The document created can be manipulated with
javascript's standard DOM methods.</p>

<p><strong>Require Extended Library:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=82bfc4a3-270b-4321-bc40-1b12ca9eae51>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var Document = require('dom').Document;</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-ExtendedClasses-Document-ClassConstructor><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Class Constructor</span></strong></h3>

<h4 id=PhoneAPIReference-ExtendedClasses-Document-Document.1><u>Document</u></h4>

<h4 id=PhoneAPIReference-ExtendedClasses-Document-CreatesanewDocumentobject.><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Creates a new
Document object.</span></strong></h4>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=fb1f609c-b460-4024-83fe-a3eb416449e4>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var document = new Document();</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h4 id=PhoneAPIReference-ExtendedClasses-Document-InitializationParameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Initialization
Parameters</span></strong></h4>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=6d8725f0-f97f-4c53-9364-0786d5758d80>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended Classes - Language</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-ExtendedClasses-Language-Language><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>Language</span></strong></h2>

<p>Localization_language library's Language constructor that creates an object
used for translating strings. After the object is created, it checks the
phone's lang/locale settings and attempts to load any localized string files
available. For example, if the phone's locale is set to&nbsp;<strong>es_mx</strong>&nbsp;(Spanish/Mexico),
the Language constructor checks the app's directory for a 'strings-es_mx.js'
file and attempts to load language keys from this file. For more information
about creating localized apps see&nbsp;<a
href="/wiki/spaces/Phones/pages/20319444/Building+Localized+Apps"
data-linked-resource-id=20319444 data-linked-resource-version=3
data-linked-resource-type=page>Building Localized Apps</a>&nbsp;in the Guides
section.</p>

<p>Additionally, the phone's lang/locale settings can be overridden when
creating the Language object by passing a langLocale string to the constructor.</p>

<p><strong>Require Extended Library:&nbsp;</strong></p>

<div>

<div><pre
data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
data-theme=Confluence>var Language = require('localization_language').Language;&nbsp; //the Language constructor is exported in the Language property</pre></div>

</div>

<h3 id=PhoneAPIReference-ExtendedClasses-Language-ClassConstructor><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Class Constructor</span></strong></h3>

<h4 id="PhoneAPIReference-ExtendedClasses-Language-newLanguage()"><u>new
Language()</u></h4>

<h4 id=PhoneAPIReference-ExtendedClasses-Language-CreatesanewLanguageobject.><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Creates a new
Language object.</span></strong></h4>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=e3ac628c-daf7-4fa7-85aa-956a5d9adf6d>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var lang = new Language(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-ExtendedClasses-Language-InitializationParameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Initialization
Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=42150a11-ac12-49d8-813c-fce8a550182e>
 <colgroup><col style="width: 145.0px;"><col style="width: 85.0px;"><col style="width: 59.0px;"><col style="width: 74.0px;"><col style="width: 627.0px;"></colgroup>
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
  <p>langLocale</p>
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
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>en_us</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Lang/locale code to use when loading string localization files. The
  standard format for this string is [lang code]_[locale code] (e.g.,&nbsp;<strong>es_mx</strong>&nbsp;for
  Spanish/Mexico,&nbsp;<strong>en_us</strong>&nbsp;for English/US). The
  lang/locale code corresponds to the last part of a localization file's name
  (e.g., strings-en_us.js contains the translated strings for English/US).</p>
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
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>en_us</p>
  </td>
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

</div>

<p>The functionality of this object is included in the&nbsp; <a
href="/wiki/spaces/Phones/pages/22315275/Phone+API+Reference+-+Extended+-+app"
data-linked-resource-id=22315275 data-linked-resource-version=3
data-linked-resource-type=page>app extended library</a> . It is recommended you
use the app library if you wish to use this feature.&nbsp;</p>

<h3 id=PhoneAPIReference-ExtendedClasses-Language-Methods><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=eeaf92b9-568a-450f-89ec-482997371128>
 <colgroup><col style="width: 158.0px;"><col style="width: 600.0px;"></colgroup>
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
  href="/wiki/spaces/Phones/pages/22675616/Phone+API+Reference+-+Extended+Classes+-+Language+-+translate"
  data-linked-resource-id=22675616 data-linked-resource-version=2
  data-linked-resource-type=page>translate</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Look up a language key and test it against the currently specificed
  language.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - Extended Classes - Language - translate</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id=PhoneAPIReference-ExtendedClasses-Language-translate-translate><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>translate</span></strong></h2>

<h3 id=PhoneAPIReference-ExtendedClasses-Language-translate-Description><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Look up a language key and test it against the currently specificed
language.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=dbfecc95-2821-4352-af9e-84e8f9b59e02>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var string = langObj.translate(parameters);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-ExtendedClasses-Language-translate-Parameters><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=58f6eaab-52a4-4369-b9ed-29b44907bf08>
 <colgroup><col style="width: 64.0px;"><col style="width: 85.0px;"><col style="width: 71.0px;"><col style="width: 74.0px;"><col style="width: 691.0px;"></colgroup>
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
  <p>key</p>
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
  <p>Key to lookup that was exported in strings file.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>vars</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>array</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>[]</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Array of variables for substitution. For each %s found in the language
  string, these variables are substituted in order starting with index 0.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>count</p>
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
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>1</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Number of items. Intended for language keys whose value is a pluralized
  array.</p>
  </td>
 </tr>
</table>

</div>

<h3 id=PhoneAPIReference-ExtendedClasses-Language-translate-Examples><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>Language.translate for translation</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=96ee5d8c-c651-4cc2-bfb4-ba4251aef6cd>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>/* Let's assume we have two string files for our app and they look like the following. [strings-en_us.js] exports.keys = { 'T_MY_APP' : 'My App', 'T_SETTINGS' : 'Settings' 'T_HAVE_DOGS' : ['I have %s dog', 'I have %s dogs'] }; [string-es_mx.js] exports.keys = { 'T_MY_APP' : 'Mi aplicación', 'T_HAVE_DOGS' : ['Tengo un perro', ' Tengo %s perros'] }; /* instantiate Language object set to es_mx (Spanish/Mexico) with a default of en_us (English/USA). If a key is missing from es_mx, the library will try to find it in the default language's strings file. */</pre><pre>var langObj = new Language({'langLocale' : 'es_mx', 'defaultLangLocale' : 'en_us'});</pre><pre>&nbsp;&nbsp;</pre><pre>var str = langObj.translate({'key' : 'T_APP_TITLE'});&nbsp; // returns &quot;Mi aplicación&quot;</pre><pre>var str2 = langObj.translate({'key' : 'T_SETTINGS'});&nbsp; // returns &quot;Settings&quot; because the key does not exist in the es_mx file</pre><pre>var str3 = langObj.translate({'key' : 'T_HAVE_DOGS', 'count' : 4, 'vars' : ['4']}); //returns Tengo 4 perros</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets)</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<p>These object constructors are available to all apps without requiring any
libraries. They create the individual elements that can be displayed on the
screen.&nbsp;All of the UI constructors inherit from the Widget base class; it
is not possible to construct a Widget object directly.</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=7d2b5435-2107-4581-9690-1ebb6d6cc15a>
 <colgroup><col style="width: 156.0px;"><col style="width: 832.0px;"></colgroup>
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
  <p><a href="/wiki/spaces/Phones/pages/22282688"
  data-linked-resource-id=22282688 data-linked-resource-version=3
  data-linked-resource-type=page>Widget (Base Class)</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Methods and properties of the Widget object are used to control basic
  properties for any UI items. It is not possible to construct a Widget object
  directly, but all UI classes and onscreen items inherit their basic
  functionality from this Widget base class.&nbsp;</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a href="/wiki/spaces/Phones/pages/22282688"
  data-linked-resource-id=22282688 data-linked-resource-version=3
  data-linked-resource-type=page>Text</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Widget used for drawing text on the screen.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22642816/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+Group"
  data-linked-resource-id=22642816 data-linked-resource-version=3
  data-linked-resource-type=page>Group</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Widget that contains other widgets and acts as a container. For example,
  this widget is useful for showing and hiding many widgets at one time. Groups
  can have any number of widgets attached to them; e.g., Group widgets, Text
  widgets, and Input widgets.</p>
  <p>There are certain Group widgets that are automatically instantiated for an
  app and must be used for displaying anything. The&nbsp; <a
  href="/wiki/spaces/Phones/pages/22020712/Phone+API+Reference+-+UI+Core+-+window"
  data-linked-resource-id=22020712 data-linked-resource-version=3
  data-linked-resource-type=page>window</a> &nbsp;property is always accessible
  to an app and is shown when the app is foregrounded. The property&nbsp; <a
  href="/wiki/spaces/Phones/pages/22708495/Phone+API+Reference+-+UI+Core+-+digium.app.idleWindow"
  data-linked-resource-id=22708495 data-linked-resource-version=2
  data-linked-resource-type=page>digium.app.idleWindow</a> &nbsp;is
  instantiated based on the app's app.json manifest.&nbsp;</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22708459/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+Scroll"
  data-linked-resource-id=22708459 data-linked-resource-version=3
  data-linked-resource-type=page>Scroll</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Derived from a group widget. Automatically adds a scrollbar when its
  widgets overflow the box.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22282574/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+Input"
  data-linked-resource-id=22282574 data-linked-resource-version=3
  data-linked-resource-type=page>Input</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Creates a text entry widget that can be used to receive input via the
  phone's number pad. This widget manages the softkeys themselves; therefore,
  you are advised not to change them programmatically.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22446344/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+List"
  data-linked-resource-id=22446344 data-linked-resource-version=3
  data-linked-resource-type=page>List</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Scrolling table with row-wise navigation capabilities. Useful for menus,
  lists of calls, etc. The user can scroll through a list with the up and down
  direction keys after it is given focus.&nbsp;</p>
  <p>List text is black on white background, and the selected/highlighted item
  is inverted. The width of the selected item highlight is that of the List
  Object itself and not of the summation of column widths.</p>
  <p>When referring to columns and rows, indexes always begin at 0.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22020587/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+Image"
  data-linked-resource-id=22020587 data-linked-resource-version=3
  data-linked-resource-type=page>Image</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Widget that displays an image file on the screen using a location and
  filename.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Group</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<p>Widget that contains other widgets and acts as a container. For example,
this widget is useful for showing and hiding many widgets at one time. Groups
can have any number of widgets attached to them; e.g., Group widgets, Text
widgets, and Input widgets.</p>

<p>There are certain Group widgets that are automatically instantiated for an
app and must be used for displaying anything. The&nbsp;&nbsp;<a
href="/wiki/spaces/Phones/pages/22020712/Phone+API+Reference+-+UI+Core+-+window"
data-linked-resource-id=22020712 data-linked-resource-version=3
data-linked-resource-type=page>window</a>&nbsp;&nbsp;property is always
accessible to an app and is shown when the app is foregrounded. The
property&nbsp;&nbsp;<a
href="/wiki/spaces/Phones/pages/22708495/Phone+API+Reference+-+UI+Core+-+digium.app.idleWindow"
data-linked-resource-id=22708495 data-linked-resource-version=2
data-linked-resource-type=page>digium.app.idleWindow</a>&nbsp;&nbsp;is
instantiated based on the app's app.json manifest.&nbsp;</p>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Group-ClassConstructor"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>Class
Constructor</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Group-newGroup()"><strong><u><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>new Group()</span></u></strong></h3>

<p>Constructs a new Group Object. A Group acts as a container for other
widgets.</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=d4625248-1521-49d6-9905-411095874e99>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var groupObj = new Group(x, y, width, height);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Group-InitializationParameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Initialization
Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=256dd3d3-701c-4e58-b7b5-587d602297bd>
 <colgroup><col style="width: 70.0px;"><col style="width: 84.0px;"><col style="width: 70.0px;"><col style="width: 84.0px;"><col style="width: 447.0px;"></colgroup>
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
  <p>x</p>
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
  <p>x coordinate value for top left corner.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>y</p>
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
  <p>y coordinate value for top left corner.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>width</p>
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
  <p>Width in pixels.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>height</p>
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
  <p>Height in pixels.</p>
  </td>
 </tr>
</table>

</div>

<p>This Class inherits methods and properties from the Widget Base Class.
See&nbsp; <a href="/wiki/spaces/Phones/pages/22282688"
data-linked-resource-id=22282688 data-linked-resource-version=3
data-linked-resource-type=page>Widget Base Class</a> &nbsp;for more information
about setting your Object's x, y, w, and h properties or adding children to it.</p>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Group-Methods"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=094959be-08c1-45ef-adb5-2a88a90e8ce6>
 <colgroup><col style="width: 119.0px;"><col style="width: 639.0px;"></colgroup>
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
  href="https://sangomakb.atlassian.net/wiki/spaces/Phones/pages/22118839/Phone+API+Reference+-+UI+Classes+(Widgets)+-+Group+-+add?search_id=f76e72e4-047b-40d8-8aeb-589486088f3c">add</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Adds one or more widgets to the group.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="https://sangomakb.atlassian.net/wiki/spaces/Phones/pages/22282558/Phone+API+Reference+-+UI+Classes+(Widgets)+-+Group+-+clear?search_id=f76e72e4-047b-40d8-8aeb-589486088f3c">clear</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Removes all child elements from the group or removes all content from the
  list.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="https://sangomakb.atlassian.net/wiki/spaces/Phones/pages/22511934/Phone+API+Reference+-+UI+Classes+(Widgets)+-+Group+-+remove?search_id=f76e72e4-047b-40d8-8aeb-589486088f3c">remove</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Removes one or more widgets from a group.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Group - add</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Group-add-add"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>add</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Group-add-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Adds one or more widgets to the group.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=df359b89-33dc-4538-9529-4e8c72822b90>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;exampleObj.add(widget[, widget...]);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Group-add-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=4772d918-bf87-4315-bbc1-8810a9536581>
 <colgroup><col style="width: 70.0px;"><col style="width: 87.0px;"><col style="width: 79.0px;"><col style="width: 143.0px;"><col style="width: 376.0px;"></colgroup>
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
  <p>widget</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>widget</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Widget to act on.</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Group-add-Examples"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>Using the 'add' method with a variety of widgets</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=86ef287e-0f70-4c6c-9cb2-a7f9b64f6cac>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>// add a group to the window.</pre><pre>var group = new Group(0, 0, window.w, window.h);</pre><pre>window.add(group);</pre><pre>&nbsp;&nbsp;</pre><pre>//add a title to the group</pre><pre>group.add(new Text(0, 0, winow.w, Text.LINE_HEIGHT));</pre><pre>//add a scroll to the group slightly smaller due to the text @ top and offset the same.</pre><pre>var scroll = new Scroll(0, Text.LINE_HEIGHT, window.w, (window.h - Text.LINE_HEIGHT));</pre><pre>group.add(list);</pre><pre>&nbsp;&nbsp;</pre><pre>//add a set of images to the list.</pre><pre>var img1 = new Image(&quot;tmp&quot;, &quot;test1.png&quot;, 30, 30, 50, 10);</pre><pre>var img2 = new Image(&quot;tmp&quot;, &quot;test2.png&quot;, 30, 45, 50, 10)</pre><pre>var img3 = new Image(&quot;tmp&quot;, &quot;test3.png&quot;, 30, 60, 50, 10)</pre><pre>scroll.add(img1, img2, img3); //support for adding multiple is the same with group and window.</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Group - clear</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Group-clear-clear"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>clear</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Group-clear-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Removes all child elements from the group or removes all content from the
list.</p>

<h4 id="PhoneAPIReference-UIClasses(Widgets)-Group-clear-BasicExample:"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Basic Example:</span></strong></h4>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=baead687-6583-4639-8d4a-72be62de7da7>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;exampleObj.clear();</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Group-clear-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=194b0b3f-cc59-4766-b0dd-004acda1b87b>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Group - remove</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Group-remove-remove"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>remove</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Group-remove-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Removes one or more widgets from a group.</p>

<p><strong>Basic Example: &nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=70e7ebe1-7cfd-4211-8eb5-e9a2e4221f55>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;exampleObj.remove(widget[, widget...]);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Group-remove-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=950489b8-782a-497a-9ccf-70903356a19b>
 <colgroup><col style="width: 79.0px;"><col style="width: 89.0px;"><col style="width: 70.0px;"><col style="width: 122.0px;"><col style="width: 395.0px;"></colgroup>
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
  <p>widget</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>widget</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Widget to act on.</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Group-remove-Examples"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>Remove widgets from a variety of objects.</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=ce314a28-2e45-4a16-888e-c42232ff5e0c>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>window.remove(alertWidget);</pre><pre>group.remove(titleWidget);</pre><pre>scroll.remove(imgWidget1, imgWidget2);</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Image</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<p>Widget that displays an image file on the screen using a location and
filename.</p>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Image-ClassConstructor"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>Class
Constructor</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Image-newImage()"><strong><u><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>new Image()</span></u></strong></h3>

<p>For images stored in the app's directory, location should be set to app, and
filename should be set to the name of the image file.Construct a new Image
Object.</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=0654161b-4033-4176-b8d2-7a393013c993>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;var imgObj = new Image(&quot;location&quot;, &quot;filename&quot;, x, y, w, h);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Image-InitializationParameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Initialization
Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=661d2c04-0a0d-4932-a0ac-0275d7a560d8>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

</div>

<p>This Class inherits methods and properties from the Widget Base Class.
See&nbsp; <a
href="https://wiki-legacy.freepbx.org/pages/viewpage.action?pageId=220893400">Widget
Base Class</a> &nbsp;for more information about setting your Object's x, y, w,
and h properties or adding children to it.</p>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Image-Methods"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=bd2277c5-180f-4be0-a098-3a1e5db0dabb>
 <colgroup><col style="width: 71.0px;"><col style="width: 917.0px;"></colgroup>
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
  href="/wiki/spaces/Phones/pages/22741176/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+Image+-+reload"
  data-linked-resource-id=22741176 data-linked-resource-version=2
  data-linked-resource-type=page>reload</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Reloads the image from disk. This is needed to clear the UI drawing cache.
  Should only be used if a new image is written over an existing one of the
  same name that has been used in the current run of the app.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22118859/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+Image+-+resize"
  data-linked-resource-id=22118859 data-linked-resource-version=2
  data-linked-resource-type=page>resize</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Changes the size of the image. If either width or height is set to 0, the
  image will be scaled to the other width/height, maintaining the aspect ratio.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Image - reload</h1>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Image-reload-reload"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>reload</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Image-reload-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Reloads the image from disk. This is needed to clear the UI drawing cache.
Should only be used if a new image is written over an existing one of the same
name that has been used in the current run of the app.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=ce621996-7207-4dac-878d-38fdac9bd983>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;imageObj.reload();</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Image-reload-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=d3178a01-67a9-41c7-80f0-48ef91836090>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Image - resize</h1>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Image-resize-resize"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>resize</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Image-resize-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Changes the size of the image. If either width or height is set to 0, the
image will be scaled to the other width/height, maintaining the aspect ratio.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=54b997ea-9e37-4b65-96b9-df170badb4fd>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>imageObj.resize(width, height);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Image-resize-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=25adcb7d-2833-44d6-b715-81e898771806>
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
  <p>height</p>
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
  <p>Height in pixels.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>width</p>
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
  <p>Width in pixels.</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Image-resize-Examples"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>resize an image widget to width of 20 pixels and preserve the
previous aspect ratio</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=535a8c65-7a21-4d08-9de2-1a2549fea8e4>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var testImage = new Image(0, 0, 40, 100);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; // image at 0,0 width=40 height = 100</pre><pre>testImage.resize(20, 0);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; // image at 0,0 width=20 height = 50</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Input</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<p>Creates a text entry widget that can be used to receive input via the
phone's number pad. This widget manages the softkeys themselves; therefore, you
are advised not to change them programmatically.</p>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Input-ClassConstructor"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>Class
Constructor</span></strong></h2>

<h4 id="PhoneAPIReference-UIClasses(Widgets)-Input-newInput()"><u>new Input()</u></h4>

<p>Constructs a new text Input Object.</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=7199b3fc-7a32-4da0-8a40-f2719925715b>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var inputObj = new Input(x, y, widght, height);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Input-InitializationParameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Initialization
Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=30e7f89c-40f4-412e-bbae-3a1f450da58a>
 <colgroup><col style="width: 80.0px;"><col style="width: 89.0px;"><col style="width: 99.0px;"><col style="width: 90.0px;"><col style="width: 397.0px;"></colgroup>
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
  <p>x</p>
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
  <p>x coordinate value for top left corner.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>height</p>
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
  <p>Height in pixels.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>y</p>
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
  <p>y coordinate value for top left corner.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>width</p>
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
  <p>Width in pixels.</p>
  </td>
 </tr>
</table>

</div>

<p>This Class inherits methods and properties from the Widget Base Class.
See&nbsp; <a href="/wiki/spaces/Phones/pages/22282688"
data-linked-resource-id=22282688 data-linked-resource-version=3
data-linked-resource-type=page>Widget Base Class</a> &nbsp;for more information
about setting your Object's x, y, w, and h properties or adding children to it.</p>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Input-Methods"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=902
 data-layout=default data-local-id=9cea2baa-a754-46d8-b1e5-bfa2d8110411>
 <colgroup><col style="width: 125.0px;"><col style="width: 777.0px;"></colgroup>
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
  href="/wiki/spaces/Phones/pages/22446321/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+Input+-+cycleModes"
  data-linked-resource-id=22446321 data-linked-resource-version=2
  data-linked-resource-type=page>cycleModes</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Sets up a softkey that cycles through a set of modes. Can be any of
  &quot;normal&quot;, &quot;email&quot;, &quot;ip&quot;, or
  &quot;numeric&quot;.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22741190/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+Input+-+replace"
  data-linked-resource-id=22741190 data-linked-resource-version=2
  data-linked-resource-type=page>replace</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Replaces a range of text from the input widget with another string.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22708429/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+Input+-+toString"
  data-linked-resource-id=22708429 data-linked-resource-version=2
  data-linked-resource-type=page>toString</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns the value of the input (same as the value property).</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Input-Properties"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Properties</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=54c75660-dd5b-4bd6-ac9a-827f3f92841e>
 <colgroup><col style="width: 95.0px;"><col style="width: 893.0px;"></colgroup>
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
  <p>textColor</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Color of the text. Can be <strong>white</strong> or <strong>black</strong>
  for D40, D50, and D70, or any of the colors specified in the Base Class color
  properties for the D6X models.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>firstUpper</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>&nbsp;If set to true, user input for this Input widget will begin cycling
  with capitalized letters rather than lowercase for the first character.</p>
  <p><strong>Basic Example:</strong></p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>textObj.firstUpper = true;&nbsp;</pre></div>
  </div>
  <p>An example use case for this would be input for names or other proper
  nouns.&nbsp;</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>mode&nbsp;</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Controls the characters inserted when number keys are pressed on the
  keypad. Can be&nbsp;<strong>normal</strong>,&nbsp;<strong>email</strong>,&nbsp;<strong>ip</strong>,&nbsp;<strong>numeric</strong>.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>onchange&nbsp;</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Function to be called whenever the contents changes.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>position</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Get or set current position of the cursor.</p>
  <p><strong>Basic Example:</strong></p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var cursorAt = inputObj.position;</pre><pre>inputObj.position = 0; //back to the beginning.&nbsp;</pre></div>
  </div>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>value</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Get the current value or set the value of the Input.</p>
  <p><strong>Basic Example:</strong></p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var currentValue = inputObj.value;</pre><pre>inputObj.value = &quot;&quot;; //set the value to a blank string</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Input - cycleModes</h1>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Input-cycleModes-cycleModes"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>cycleModes</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Input-cycleModes-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Sets up a softkey that cycles through a set of modes. Can be any of
&quot;normal&quot;, &quot;email&quot;, &quot;ip&quot;, or &quot;numeric&quot;.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<div><pre
data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
data-theme=Confluence>textObj.cycleModes(modesArray);</pre></div>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Input-cycleModes-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=832
 data-layout=default data-local-id=3b16e664-6a92-437c-a2ff-58a6c40a2cbc>
 <colgroup><col style="width: 79.0px;"><col style="width: 100.0px;"><col style="width: 66.0px;"><col style="width: 83.0px;"><col style="width: 504.0px;"></colgroup>
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
  <p>modes</p>
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
  <p>Array of modes. Can be any of &quot;normal&quot;, &quot;email&quot;,
  &quot;ip&quot;, or &quot;numeric&quot;.</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Input-cycleModes-Examples"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>cycleModes for a softkey that cycles numeric and normal</strong></p>

<div>

<div><pre
data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
data-theme=Confluence>theInput.cycleModes(['numeric', 'normal']);</pre></div>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Input - replace</h1>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Input-replace-replace"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>replace</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Input-replace-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Replaces a range of text from the input widget with another string.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<div><pre
data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
data-theme=Confluence>&nbsp;textObj.replace(begin, end, replacement);</pre></div>

</div>

<p>Note, this will focus the cursor at the end of the replacement.</p>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Input-replace-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=a1afd186-5229-4dc6-a1a5-6e0685663c4c>
 <colgroup><col style="width: 105.0px;"><col style="width: 89.0px;"><col style="width: 74.0px;"><col style="width: 90.0px;"><col style="width: 397.0px;"></colgroup>
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
  <p>begin</p>
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
  <p>Index to begin replacing.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>end</p>
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
  <p>Index to end replacing.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>replacement</p>
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
  <p>The string to use as the replacement.</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Input-replace-Examples"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>replace bar with foo</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=f058ddcf-4c39-4899-8db2-9cb4b20228e2>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var input = new Input(0, 0, 100, Text.LINE_HEIGHT);</pre><pre>input.value = 'FooBar';</pre><pre>input.replace(3, 5, 'Foo')</pre><pre>return input.toString();&nbsp; //returns 'FooFoo'</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Input - toString</h1>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Input-toString-toString"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>toString</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Input-toString-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Returns the value of the input (same as the value property).</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=8677f801-ff81-4ffa-9342-3d7424490e12>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>textInput.toString(); //get the value of the Input</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Input-toString-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=844
 data-layout=default data-local-id=661537f7-668f-4dde-8909-2afa90d6d2c4>
 <colgroup><col style="width: 84.0px;"><col style="width: 103.0px;"><col style="width: 69.0px;"><col style="width: 80.0px;"><col style="width: 508.0px;"></colgroup>
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
  <p>modes</p>
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
  <p>Array of modes. Can be any of &quot;normal&quot;, &quot;email&quot;,
  &quot;ip&quot;, or &quot;numeric&quot;.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - List</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<p>Scrolling table with row-wise navigation capabilities. Useful for menus,
lists of calls, etc. The user can scroll through a list with the up and down
direction keys after it is given focus.&nbsp;</p>

<p>List text is black on white background, and the selected/highlighted item is
inverted. The width of the selected item highlight is that of the List Object
itself and not of the summation of column widths.</p>

<p>When referring to columns and rows, indexes always begin at 0.</p>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-ClassConstructor"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Class Constructor</span></strong></h3>

<h4 id="PhoneAPIReference-UIClasses(Widgets)-List-newList()"><strong><u><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>new List()</span></u></strong></h4>

<p>Constructs a new List Object.</p>

<div>

<div><pre
data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
data-theme=Confluence>var listObj = new List(x, y, width, height);</pre></div>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-InitializationParameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Initialization
Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=857b7b2c-a68e-4ac3-bf8b-2807119aafbe>
 <colgroup><col style="width: 65.0px;"><col style="width: 87.0px;"><col style="width: 85.0px;"><col style="width: 79.0px;"><col style="width: 439.0px;"></colgroup>
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
  <p>x</p>
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
  <p>x coordinate value for top left corner.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>y</p>
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
  <p>y coordinate value for top left corner.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>width</p>
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
  <p>Width in pixels.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>height</p>
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
  <p>Height in pixels.</p>
  </td>
 </tr>
</table>

</div>

<p>This Class inherits methods and properties from the Widget Base Class.
See&nbsp; <a
href="https://wiki-legacy.freepbx.org/pages/viewpage.action?pageId=220893400">Widget
Base Class</a> &nbsp;for more information about setting your Object's x, y, w,
and h properties or adding children to it.</p>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-Methods"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=9ae1525d-88c0-474a-8629-91ceb8f7e5f2>
 <colgroup><col style="width: 145.0px;"><col style="width: 843.0px;"></colgroup>
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
  href="/wiki/spaces/Phones/pages/22184346/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+List+-+clear"
  data-linked-resource-id=22184346 data-linked-resource-version=1
  data-linked-resource-type=page>clear</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Removes all child elements from the group or removes all content from the
  list.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22511971/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+List+-+get"
  data-linked-resource-id=22511971 data-linked-resource-version=1
  data-linked-resource-type=page>get</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Retrieves contents of a specific cell in the list.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22741231/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+List+-+select"
  data-linked-resource-id=22741231 data-linked-resource-version=1
  data-linked-resource-type=page>select</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Selects the specified row.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22544633/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+List+-+set"
  data-linked-resource-id=22544633 data-linked-resource-version=1
  data-linked-resource-type=page>set</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Sets the contents of the given cell in the List.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22446381/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+List+-+setColumnWidths"
  data-linked-resource-id=22446381 data-linked-resource-version=1
  data-linked-resource-type=page>setColumnWidths</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Sets the widths of each column in pixels. If the last value is set to 0,
  it will use all remaining space to fill the list's width.</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-Properties"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Properties</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=abf0b0c3-b4d7-4fbb-b866-20c1fecd6095>
 <colgroup><col style="width: 91.0px;"><col style="width: 897.0px;"></colgroup>
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
  href="/wiki/spaces/Phones/pages/22511952/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+List+-+cellFunc"
  data-linked-resource-id=22511952 data-linked-resource-version=1
  data-linked-resource-type=page>cellFunc</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Function that takes row and column numbers as parameters and returns the
  text for a cell. When this property is set, the function is immediately
  executed.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>cols&nbsp;</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Number of columns. Columns are numbered from 0, starting on the left.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22642865/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+List+-+onchange"
  data-linked-resource-id=22642865 data-linked-resource-version=1
  data-linked-resource-type=page>onchange</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Callback function called when the selection changes.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>rowHeight&nbsp;</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Number of pixels high each row should be. Defaults to Text.LINE_HEIGHT in
  D40, D50, and D70, but defaults to Text.ROW_HEIGHT for D6X models.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>rows&nbsp;</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Number of rows the list contains. Rows are numbered from 0, starting at
  the top of the list.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22020620/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+List+-+selected"
  data-linked-resource-id=22020620 data-linked-resource-version=1
  data-linked-resource-type=page>selected</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns the currently selected row number or set the row you wish to be
  selected.</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - List - cellFunc</h1>

<h1
id="PhoneAPIReference-UIClasses(Widgets)-List-cellFunc-PhoneAPIReference-UIClasses(Widgets)-List-cellFunc">Phone
API Reference - UI Classes (Widgets) - List - cellFunc</h1>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-List-cellFunc-cellFunc"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>cellFunc</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-cellFunc-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Function that takes row and column numbers as parameters and returns the
text for a cell. When this property is set, the function is immediately
executed.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-layout=default
 data-local-id=b0b5da8c-3319-46dc-9743-054e1a2003f9>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>list.cellFunc = function(r, c) {return &quot;&quot;; }&nbsp;</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>Use the cellFunc property for functions that take a row and column as
parameters and return the string or image to be displayed at that position.
This is more efficient because the list doesn't need to build a large data
structure. The cellfunc will be called only for items that are on the screen.</p>

<p>The cellFunc option is recommended for large lists.</p>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-cellFunc-Examples"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>List.cellFunc to create a list of employee data</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-layout=default
 data-local-id=b28296a5-46ae-4e12-9fb7-19f56952ff6f>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>//clear the window and add a header</pre><pre>window.clear();</pre><pre>window.add(new Text(0, 0, 100, 100, &quot;Employees&quot;));</pre><pre>&nbsp;&nbsp;</pre><pre>//add the list object</pre><pre>var list = new List(0, 20, window.w, window.h-20);</pre><pre>window.add(list);</pre><pre>&nbsp;&nbsp;</pre><pre>//column widths will be 70, 70, and rest of the visible object</pre><pre>list.setColumnWidths(70, 70, 0); //last column will take the up as much space as possible</pre><pre>&nbsp;&nbsp;</pre><pre>/* This data structure was created to take advantage of the cellFunc function and make filling out our List very easy. Rows will go in order, and are the index of the 'content' array. Each item in the content array is then an array. Each node of the inner array is a set of values which will correspond to the columns. This combination will be used to fill out all of our cells. */</pre><pre>var content = [</pre><pre>&nbsp;&nbsp;&nbsp;['--Emp.--', '--ID--', '--Country--'],</pre><pre>&nbsp;&nbsp;&nbsp;['Tom', '1231451', 'USA'],</pre><pre>&nbsp;&nbsp;&nbsp;['Ralph', '7567567', 'China'],</pre><pre>&nbsp;&nbsp;&nbsp;['Sam', '890294', 'Canada'],</pre><pre>];</pre><pre>&nbsp;&nbsp;</pre><pre>//set cols and rows (rows equal to length of array</pre><pre>list.rows = content.length;</pre><pre>list.cols = 3;</pre><pre>&nbsp;&nbsp;</pre><pre>// run over the cellFunc function accessing our content array each row and column at a time.</pre><pre>list.cellFunc = function (r, c) { return content[r][c]; };</pre><pre>&nbsp;&nbsp;</pre><pre>//focus and select the first item in the list (not the header)</pre><pre>list.takeFocus();</pre><pre>list.select(1);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p><strong>List.cellFunc</strong>&nbsp;<strong>to create a multiplication table</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-layout=default
 data-local-id=46fcc0f6-b8e5-43d3-9aaa-11264ecde76e>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;//Create and add our List object</pre><pre>var listObj = new List(0, 20, window.w, (window.h - 20));</pre><pre>window.add(listObj);</pre><pre>&nbsp;&nbsp;</pre><pre>// we will use this variable in a couple places. It represents how large our grid will be.</pre><pre>var num = 10;</pre><pre>&nbsp;&nbsp;</pre><pre>//programmatically create a widths array which will be passed to setColumnWidths();</pre><pre>var widths = [];</pre><pre>while (widths.length &lt; num) {</pre><pre>&nbsp;&nbsp;&nbsp;//all the columns are even and will fill the whole screen</pre><pre>&nbsp;&nbsp;&nbsp;widths.push(window.w/num);</pre><pre>}</pre><pre>&nbsp;&nbsp;</pre><pre>//set rows and columns</pre><pre>listObj.rows = num;</pre><pre>listObj.columns = num;</pre><pre>&nbsp;&nbsp;</pre><pre>//setColumnWidths takes a variable amount of arguments, that is why apply is used here.</pre><pre>listObj.setColumnWidths.apply(listObj, widths);</pre><pre>&nbsp;&nbsp;</pre><pre>//set the cellFunc to return the row multiplied by the column (e.g. row 3, column 4 = 12)</pre><pre>listObj.cellFunc = function(r, c) { return r*c; };</pre><pre>&nbsp;&nbsp;</pre><pre>//focus on the list so we can scroll</pre><pre>listObj.takeFocus();</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - List - clear</h1>

<h1
id="PhoneAPIReference-UIClasses(Widgets)-List-clear-PhoneAPIReference-UIClasses(Widgets)-List-clear">Phone
API Reference - UI Classes (Widgets) - List - clear</h1>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-List-clear-clear"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>clear</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-clear-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Removes all child elements from the group or removes all content from the
list.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-layout=default
 data-local-id=5b4254c0-7610-4e6c-8972-4e8c3c6de488>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>exampleObj.clear();</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-clear-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-layout=default
 data-local-id=b190812b-bce9-4d9d-9317-add8d1a51844>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - List - get</h1>

<h1
id="PhoneAPIReference-UIClasses(Widgets)-List-get-PhoneAPIReference-UIClasses(Widgets)-List-get">Phone
API Reference - UI Classes (Widgets) - List - get</h1>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-List-get-get"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>get</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-get-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Retrieves contents of a specific cell in the list.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-layout=default
 data-local-id=9b26d3e0-2761-4100-b5cf-e8c466ee1dae>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var value = listObj.get(row, column);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>rows and columns begin at 0,0.</p>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-get-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-layout=default
 data-local-id=f355f32e-40b3-49ee-8ab7-0fc135ece6be>
 <colgroup><col style="width: 71.0px;"><col style="width: 86.0px;"><col style="width: 71.0px;"><col style="width: 83.0px;"><col style="width: 444.0px;"></colgroup>
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
  <p>row</p>
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
  <p>Row number of the cell.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>column</p>
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
  <p>Column number of the cell.</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-get-Examples"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p>get the contents of row 1 column 1</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-layout=default
 data-local-id=1ef14104-47b9-4570-9d70-702dac6c14fb>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>list.get(1, 1);</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - List - onchange</h1>

<h1
id="PhoneAPIReference-UIClasses(Widgets)-List-onchange-PhoneAPIReference-UIClasses(Widgets)-List-onchange">Phone
API Reference - UI Classes (Widgets) - List - onchange</h1>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-List-onchange-onchange"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>onchange</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-onchange-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Callback function called when the selection changes.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<div><pre
data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
data-theme=Confluence>exampleObj.onchange = function() { util.debug('selection change'); }</pre></div>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - List - select</h1>

<h1
id="PhoneAPIReference-UIClasses(Widgets)-List-select-PhoneAPIReference-UIClasses(Widgets)-List-select">Phone
API Reference - UI Classes (Widgets) - List - select</h1>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-List-select-select"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>select</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-select-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Selects the specified row.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<div><pre
data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
data-theme=Confluence>listObj.select(row);</pre></div>

</div>

<p>the first row is row zero.</p>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-select-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-layout=default
 data-local-id=2c57a63b-550c-4168-99b6-acef6ce6afd0>
 <colgroup><col style="width: 75.0px;"><col style="width: 96.0px;"><col style="width: 93.0px;"><col style="width: 99.0px;"><col style="width: 392.0px;"></colgroup>
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
  <p>row</p>
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
  <p>Row number of the cell.</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-select-Examples"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>select row 14 of a list widget</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-layout=default
 data-local-id=5fc4da86-aa1c-492c-a4c3-857a3851753a>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var list = new List(50, 50, 200, 200);</pre><pre>list.setProp('rows', 30)</pre><pre>&nbsp;&nbsp;&nbsp;&nbsp;.setProp('cellFunc', function () { return 'This is a row!'; });</pre><pre>list.select(14);</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - List - selected</h1>

<h1
id="PhoneAPIReference-UIClasses(Widgets)-List-selected-PhoneAPIReference-UIClasses(Widgets)-List-selected">Phone
API Reference - UI Classes (Widgets) - List - selected</h1>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-List-selected-selected"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>selected</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-selected-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Returns the currently selected row number or set the row you wish to be
selected.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<div><pre
data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
data-theme=Confluence>listObj.select(2);</pre><pre>listObj.selected; //returns 2</pre></div>

</div>

<p>Note: setting the selected property is the same as using the List.select()
method.</p>

<h1>Phone API Reference - UI Classes (Widgets) - List - set</h1>

<h1
id="PhoneAPIReference-UIClasses(Widgets)-List-set-PhoneAPIReference-UIClasses(Widgets)-List-set">Phone
API Reference - UI Classes (Widgets) - List - set</h1>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-List-set-set"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>set</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-set-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Sets the contents of the given cell in the List.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-layout=default
 data-local-id=b129133b-3819-4e4c-976c-79ddaf578644>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;listObj.set(row, column, content);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-set-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=880
 data-layout=default data-local-id=626c1a43-7a05-440e-a9a8-e6d0fa277256>
 <colgroup><col style="width: 113.0px;"><col style="width: 115.0px;"><col style="width: 118.0px;"><col style="width: 101.0px;"><col style="width: 433.0px;"></colgroup>
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
  <p>row</p>
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
  <p>Row number of the cell.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>column</p>
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
  <p>Column number of the cell.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>content</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>No</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>varied</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>The contents of the cell. Can be a string, or a widget.</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-set-Examples"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>set the contents of a list widget</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-layout=default
 data-local-id=61b54e81-afe6-4131-82b7-95cdb260aae1>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var list = new List(50, 50, 200, 200);</pre><pre>list.set(0, 0, 'Foo');</pre><pre>list.set(0, 1, 'Bar');</pre><pre>list.set(1, 0, 'Bar');</pre><pre>list.set(1, 1, 'Foo');&nbsp;</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - List - setColumnWidths</h1>

<h1
id="PhoneAPIReference-UIClasses(Widgets)-List-setColumnWidths-PhoneAPIReference-UIClasses(Widgets)-List-setColumnWidths">Phone
API Reference - UI Classes (Widgets) - List - setColumnWidths</h1>

<h2
id="PhoneAPIReference-UIClasses(Widgets)-List-setColumnWidths-setColumnWidths"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>setColumnWidths</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-setColumnWidths-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Sets the widths of each column in pixels. If the last value is set to 0, it
will use all remaining space to fill the list's width.&nbsp;<strong>&nbsp;</strong></p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-layout=default
 data-local-id=c92f3b4d-1cf1-42fb-8136-04b00b541f52>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>listObj.setColumnWidths(width[, width...]);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>A List object will not be visible until you perform this method and set the
column widths. If not set, column widths default to zero.</p>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-setColumnWidths-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-layout=default
 data-local-id=ff599639-dd6f-4dcc-8729-d10e8dfbb53c>
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
  <p>width</p>
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
  <p>Width in pixels.</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-List-setColumnWidths-Examples"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>setColumnWidth with different column widths, and the last column
fits in the remaining space</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-layout=default
 data-local-id=140656c9-e36f-4665-a24e-e5b5f521632b>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>list.setColumnWidths(35, 100, 0);</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Scroll</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<p>Derived from a group widget. Automatically adds a scrollbar when its widgets
overflow the box.</p>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-ClassConstructor"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>Class
Constructor</span></strong></h2>

<h4 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-newScroll()"><strong><u><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>new Scroll()</span></u></strong></h4>

<p>Construct a new Scroll object.</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=68e3ef6e-39fe-45ca-ab10-effa7892a47d>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var scrollObj = new Scroll(x, y, width, height);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-InitializationParameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Initialization
Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=85e60edf-43b3-434e-9ed8-4c733eb5d048>
 <colgroup><col style="width: 76.0px;"><col style="width: 92.0px;"><col style="width: 77.0px;"><col style="width: 92.0px;"><col style="width: 418.0px;"></colgroup>
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
  <p>y</p>
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
  <p>y coordinate value for top left corner.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>x</p>
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
  <p>x coordinate value for top left corner.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>width</p>
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
  <p>Width in pixels.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>height</p>
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
  <p>Height in pixels.</p>
  </td>
 </tr>
</table>

</div>

<p>This Class inherits methods and properties from the Widget Base Class.
See&nbsp; <a href="/wiki/spaces/Phones/pages/22282688"
data-linked-resource-id=22282688 data-linked-resource-version=3
data-linked-resource-type=page>Widget Base Class</a> &nbsp;for more information
about setting your Object's x, y, w, and h properties or adding children to it.</p>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-Methods"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=ba4b03af-2e33-43b8-ac0f-984e170f94ce>
 <colgroup><col style="width: 130.0px;"><col style="width: 628.0px;"></colgroup>
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
  href="/wiki/spaces/Phones/pages/22675688/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+Scroll+-+add"
  data-linked-resource-id=22675688 data-linked-resource-version=2
  data-linked-resource-type=page>add</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Adds one or more widgets to the group.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22184392/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+Scroll+-+clear"
  data-linked-resource-id=22184392 data-linked-resource-version=2
  data-linked-resource-type=page>clear</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Removes all child elements from the group or removes all content from the
  list.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22544650/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+Scroll+-+remove"
  data-linked-resource-id=22544650 data-linked-resource-version=2
  data-linked-resource-type=page>remove</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Removes one or more widgets from a group.</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-Properties"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Properties</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=80e47382-3c6b-46a0-acae-71e85cbc9aa0>
 <colgroup><col style="width: 84.0px;"><col style="width: 674.0px;"></colgroup>
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
  <p>yPosition</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Returns the current yPosition of the Scroll object. Note: this is not
  relative to the placement of the Scroll on the screen in anyway. Also can be
  used to set the y value of the scroll bar, causing it to scroll.</p>
  <p><strong>Basic Example:</strong></p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>//scroll down the Scroll Widget by 3 a factor of 3 LINE_HEIGHTS.</pre><pre>scrollObj.yPosition =(scrollObj.yPosition + (Text.LINE_HEIGHT * 3));</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Scroll - add</h1>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-add-add"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>add</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-add-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Adds one or more widgets to the group.</p>

<p><strong>Basic Example:&nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=4cbecd41-25c6-48b7-8849-1f03e20e5bea>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;exampleObj.add(widget[, widget...]);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-add-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=e4fa095f-b40c-423c-8db3-7545a81c3321>
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
  <p>widget</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>widget</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Widget to act on.</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-add-Examples"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>Using the 'add' method with a variety of widgets</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=95573dc2-8401-4bdf-9eca-246a6056e867>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>// add a group to the window.</pre><pre>var group = new Group(0, 0, window.w, window.h);</pre><pre>window.add(group);</pre><pre>&nbsp;&nbsp;</pre><pre>//add a title to the group</pre><pre>group.add(new Text(0, 0, winow.w, Text.LINE_HEIGHT));</pre><pre>//add a scroll to the group slightly smaller due to the text @ top and offset the same.</pre><pre>var scroll = new Scroll(0, Text.LINE_HEIGHT, window.w, (window.h - Text.LINE_HEIGHT));</pre><pre>group.add(list);</pre><pre>&nbsp;&nbsp;</pre><pre>//add a set of images to the list.</pre><pre>var img1 = new Image(&quot;tmp&quot;, &quot;test1.png&quot;, 30, 30, 50, 10);</pre><pre>var img2 = new Image(&quot;tmp&quot;, &quot;test2.png&quot;, 30, 45, 50, 10)</pre><pre>var img3 = new Image(&quot;tmp&quot;, &quot;test3.png&quot;, 30, 60, 50, 10)</pre><pre>scroll.add(img1, img2, img3); //support for adding multiple is the same with group and window.</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Scroll - clear</h1>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-clear-clear"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>clear</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-clear-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Removes all child elements from the group or removes all content from the
list.</p>

<p><strong>Basic Example:</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=eb1d4023-9300-49ee-88fc-ab49fa171a42>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>exampleObj.clear();</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-clear-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=75a69068-9c09-458e-b85d-479bb00b8e3f>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>None</p>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Scroll - remove</h1>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-remove-remove"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>remove</span></strong></h2>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-remove-Description"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Description</span></strong></h3>

<p>Removes one or more widgets from a group.</p>

<p><strong>Basic Example: &nbsp;</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=9fd5c34f-bab2-492c-8c9d-f0bdedbc3c18>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>exampleObj.remove(widget[, widget...]);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-remove-Parameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=63a7445b-cee1-4a72-ae94-53476e4b94a7>
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
  <p>widget</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Yes</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>widget</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'></td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Widget to act on.</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Scroll-remove-Examples"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Examples</span></strong></h3>

<p><strong>Remove widgets from a variety of objects.</strong></p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=380c1cfd-8b8a-4702-b8bf-b6d6ae07899f>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>window.remove(alertWidget);</pre><pre>group.remove(titleWidget);</pre><pre>scroll.remove(imgWidget1, imgWidget2);</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>

<h1>Phone API Reference - UI Classes (Widgets) - Text</h1>

<div>

<div>

<p>Desk Phone API features described in this section are deprecated and
supported only on the following models: D40, d45, d50, d60, d62, d65, d70</p>

</div>

</div>

<p>Widget used for drawing text on the screen.</p>

<h2 id="PhoneAPIReference-UIClasses(Widgets)-Text-ClassConstructor"><strong><span
style='font-family:"Aptos Display",sans-serif;font-weight:normal'>Class
Constructor</span></strong></h2>

<h4 id="PhoneAPIReference-UIClasses(Widgets)-Text-newText()"><strong><u><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>new Text()</span></u></strong></h4>

<p>Creates a new Text Object.</p>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=aaa66a98-11df-49fc-9548-bbb9d866c4dc>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'
  data-highlight-colour=initial>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>&nbsp;var textObj = new Text(x, y, width, height[, label]); //new Text Widget</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Text-InitializationParameters"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Initialization
Parameters</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=fa7d7215-a2c6-42f0-9e7e-4cde9efa55a3>
 <colgroup><col style="width: 69.0px;"><col style="width: 89.0px;"><col style="width: 73.0px;"><col style="width: 75.0px;"><col style="width: 449.0px;"></colgroup>
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
  <p>x</p>
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
  <p>x coordinate value for top left corner.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>y</p>
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
  <p>y coordinate value for top left corner.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>width</p>
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
  <p>Width in pixels.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>height</p>
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
  <p>Height in pixels.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>label</p>
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
  <p>Text to display</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Text-ClassConstants"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Class Constants</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=e62f2876-58d4-481b-8e92-d8342a3d6b2d>
 <colgroup><col style="width: 218.0px;"><col style="width: 770.0px;"></colgroup>
 <tr>
  <td style='border:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Title&nbsp;</strong></p>
  </td>
  <td style='border:solid windowtext 1.0pt;border-left:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p align=center style='text-align:center'><strong>Description&nbsp;</strong></p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Text.LINE_HEIGHT</p>
  <p><strong>D6X Only</strong></p>
  <p>Text.LINE_HEIGHT_2</p>
  <p>Text.ROW_HEIGHT</p>
  <p>Text.TITLE_HEIGHT</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Recommended number of pixels to use for the height of a line of text.
  &nbsp;You can put another line at y+Text.LINE_HEIGHT, and it will render
  correctly. This property is dependent on the model of phone the app is
  running on. For the D6X models three more height definitions are specified.
  They are Text.LINE_HEIGHT_2, Text.ROW_HEIGHT, and Text.TITLE_HEIGHT.</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>LINE_HEIGHT = 15 for D40/D50 (~6 lines per screen minus title
  and soft keys, also height of titles)</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>LINE_HEIGHT = 17 for D70 (~7 lines per screen minus title and
  soft keys, also height of titles)</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>LINE_HEIGHT = 25 for D6X (~8 lines per screen, minus title and
  soft keys)</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>LINE_HEIGHT_2 = 28 (~7 lines per screen, minus title and soft
  keys)</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>ROW_HEIGHT = 32 (~6 lines per screen, minus title and soft
  keys, used by most D6X screens, leaves good spacing, and room for border
  lines)</p>
  <p style='margin-left:.5in;text-indent:-.25in'><span style='font-size:10.0pt;
  font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span></span>TITLE_HEIGHT = 40 (title bar heights of all D6X screens)</p>
  <p><strong>Basic Example:</strong></p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>var h = Text.LINE_HEIGHT; //retrieve our models line height for use below</pre><pre>new Text(0,0, 100, h);</pre></div>
  </div>
  </td>
 </tr>
</table>

</div>

<p>This Class inherits methods and properties from the Widget Base Class.
See&nbsp; <a href="/wiki/spaces/Phones/pages/22282688"
data-linked-resource-id=22282688 data-linked-resource-version=3
data-linked-resource-type=page>Widget Base Class</a> &nbsp;for more information
about setting your Object's x, y, w, and h properties or adding children to it.</p>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Text-Methods"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Methods</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=760
 data-layout=default data-local-id=7aa7bd8a-ea29-4720-8a48-5097e9ccdde4>
 <colgroup><col style="width: 74.0px;"><col style="width: 684.0px;"></colgroup>
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
  href="/wiki/spaces/Phones/pages/22315616/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+Text+-+align"
  data-linked-resource-id=22315616 data-linked-resource-version=2
  data-linked-resource-type=page>align</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Controls the placement of the text display.</p>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p><a
  href="/wiki/spaces/Phones/pages/22642936/Phone+API+Reference+-+UI+Classes+%28Widgets%29+-+Text+-+fitLabel"
  data-linked-resource-id=22642936 data-linked-resource-version=2
  data-linked-resource-type=page>fitLabel</a></p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Resizes the box around the widget to fit it to the contents. A padding
  argument is optional, to add additional pixels on each side of the text.</p>
  </td>
 </tr>
</table>

</div>

<h3 id="PhoneAPIReference-UIClasses(Widgets)-Text-Properties"><strong><span
style='font-family:"Aptos",sans-serif;font-weight:normal'>Properties</span></strong></h3>

<div>

<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none' data-table-width=988
 data-layout=default data-local-id=ecdc309c-60cf-4f4d-b23e-1b318ca66f45>
 <colgroup><col style="width: 125.0px;"><col style="width: 863.0px;"></colgroup>
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
  <p>label</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>The string to display. Change the string of a Text object without having
  to re instantiate one.</p>
  <p><strong>Basic Example:</strong></p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>textObj.label = &quot;New Value for Display&quot;;&nbsp;</pre></div>
  </div>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>labelColor</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>Color of the text. Can be&nbsp;<strong>white</strong>&nbsp;or&nbsp;<strong>black
  </strong>for D40, D50, and D70, or any of the colors specified in the Base
  Class color properties for the D6X models.</p>
  <p><strong>Basic Example:</strong></p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>textObj.labelColor = &quot;white&quot;;&nbsp;</pre></div>
  </div>
  </td>
 </tr>
 <tr style='page-break-inside:avoid'>
  <td style='border:solid windowtext 1.0pt;border-top:none;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>labelSize</p>
  </td>
  <td style='border-top:none;border-left:none;border-bottom:solid windowtext 1.0pt;
  border-right:solid windowtext 1.0pt;padding:3.75pt 3.75pt 3.75pt 3.75pt'>
  <p>The font size of the label. The default value differs based on phone
  model, so it is best to make changes relative to the current size instead of
  specifying a specific size. For example, if you have some bit of text you
  want a bit larger in your app then create a Text object and multiple it's
  current label size by 1.2.</p>
  <p><strong>Basic Example:</strong></p>
  <div>
  <div><pre
  data-syntaxhighlighter-params="brush: java; gutter: false; theme: Confluence"
  data-theme=Confluence>textObj.labelSize = parseInt((textObj.labelSize * 1.2), 10); &nbsp;</pre></div>
  </div>
  </td>
 </tr>
</table>

<p class=MsoNormal>&nbsp;</p>

</div>
