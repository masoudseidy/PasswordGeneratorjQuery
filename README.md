# PasswordGeneratorjQuery
jQuery use To Create a Password Powerful and Easy Passage in Use

ساخت پسورد قوی با استفاده از Jquery

<hr>

<a href='http://akwade.com/generatePassword/' target='_blank' >Demo &amp; Examples </a>

<h3> How It Works </h2>

<h3> HTML </h3>
<pre class="html4strict" style="font-family:monospace;"><ol><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">  <span style="color: #009900;">&lt;<span style="color: #000000; font-weight: bold;">div</span> <span style="color: #000066;">class</span><span style="color: #66cc66;">=</span><span style="color: #ff0000;">&quot;password-gene&quot;</span>&gt;</span></div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">    <span style="color: #009900;">&lt;<span style="color: #000000; font-weight: bold;">input</span> <span style="color: #000066;">type</span><span style="color: #66cc66;">=</span><span style="color: #ff0000;">&quot;text&quot;</span>&gt;</span></div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">    <span style="color: #009900;">&lt;<span style="color: #000000; font-weight: bold;">button</span>&gt;</span> Change Password <span style="color: #009900;">&lt;<span style="color: #66cc66;">/</span><span style="color: #000000; font-weight: bold;">button</span>&gt;</span></div></li><li style="font-weight: normal; vertical-align:top;"><div style="font: normal normal 1em/1.2em monospace; margin:0; padding:0; background:none; vertical-align:top;">  <span style="color: #009900;">&lt;<span style="color: #66cc66;">/</span><span style="color: #000000; font-weight: bold;">div</span>&gt;</span></div></li></ol></pre>

<h3> Js </h3>
- <p>Required jQuery </p>
<pre>
&lt;<span class="pl-ent">script</span> <span class="pl-e">src</span>=<span class="pl-s"><span class="pl-pds">"</span>../bower_components/js/jquery.js<span class="pl-pds">"</span></span>&gt;&lt;/<span class="pl-ent">script</span>&gt;
</pre>
- <p> Required Plugin PasswordGeneratorjQuery </p>
<pre>
&lt;<span class="pl-ent">script</span> <span class="pl-e">src</span>=<span class="pl-s"><span class="pl-pds">"</span>../bower_components/js/generate-password.js<span class="pl-pds">"</span></span>&gt;&lt;/<span class="pl-ent">script</span>&gt;
</pre>
- <p> Use the plugin as follows: </p>
<pre>
  $('.password-gene').generatePassword();
</pre>

<h2> Options </h2>


<table>
  <thead>
  <tr>
  <th>Attribute</th>
  <th>Type</th>
  <th>Default</th>
  <th>Description</th>
  </tr>
  </thead>
  <tbody>
      <tr>
        <td><code>passCharachterSet</code></td>
        <td><em>String</em></td>
        <td><code>a-z,#</code></td>
        <td>attribute is used to set the character type used in the password. You can use numbers 0-9, letters a-z (and or) A-Z, and spical characters #. All of these sets can be used individually work together.</td>
      </tr>
      <tr>
        <td><code>passSize</code></td>
        <td><em>Integer</em></td>
        <td><code>15</code></td>
        <td>attribute is used to set the number of characters that is used in the field, if you need a password with 12 characters, then set this attribute to 12.</td>
      </tr>
      <tr>
        <td><code>passSeparate</code></td>
        <td><em>String</em></td>
        <td><code>,</code></td>
        <td>Mark that separates each character and another character in the property passCharachterSet </td>
      </tr>
  </tbody>
</table>

<h3>Features</h3>
<ul>
  <li> Easy To Use</li>
  <li> Directed By a Strong Password</li>
  <li> Change The Password When You Press The Button</li>
  <li> Select The Password When Clicked On Input</li>
</ul>
