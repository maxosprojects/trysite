<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>introduction</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><hr>
<p>layout: post</p>
<p>title: “Welcome to Jekyll!”</p>
<p>date: 2019-09-16 20:45:02 -0700</p>
<p>categories: jekyll update</p>
<hr>
<p>You’ll find this post in your <code>_posts</code> directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run <code>jekyll serve</code>, which launches a web server and auto-regenerates your site when a file is updated.</p>
<p>Jekyll requires blog post files to be named according to the following format:</p>
<p><code>YEAR-MONTH-DAY-title.MARKUP</code></p>
<p>Where <code>YEAR</code> is a four-digit number, <code>MONTH</code> and <code>DAY</code> are both two-digit numbers, and <code>MARKUP</code> is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.</p>
<p>Jekyll also offers powerful support for code snippets:</p>
<p>{% highlight ruby %}</p>
<p>def print_hi(name)</p>
<p>puts “Hi, #{name}”</p>
<p>end</p>
<p>print_hi(‘Tom’)</p>
<p>#=&gt; prints ‘Hi, Tom’ to STDOUT.</p>
<p>{% endhighlight %}</p>
<p>Check out the <a href="https://jekyllrb.com/docs/home">Jekyll docs</a> for more info on how to get the most out of Jekyll. File all bugs/feature requests at <a href="https://github.com/jekyll/jekyll">Jekyll’s GitHub repo</a>. If you have questions, you can ask them on <a href="https://talk.jekyllrb.com/">Jekyll Talk</a>.</p>
<pre class=" language-csharp"><code class="prism  language-csharp">
<span class="token comment">/*

* R e a d m e

* -----------

*

* In this file you can include any instructions or other comments you want to have injected onto the

* top of your final script. You can safely delete this file if you do not want any such comments.

*/</span>

  

<span class="token comment">// This file contains your actual script.</span>

<span class="token comment">//</span>

<span class="token comment">// You can either keep all your code here, or you can create separate</span>

<span class="token comment">// code files to make your program easier to navigate while coding.</span>

<span class="token comment">//</span>

<span class="token comment">// In order to add a new utility class, right-click on your project,</span>

<span class="token comment">// select 'New' then 'Add Item...'. Now find the 'Space Engineers'</span>

<span class="token comment">// category under 'Visual C# Items' on the left hand side, and select</span>

<span class="token comment">// 'Utility Class' in the main area. Name it in the box below, and</span>

<span class="token comment">// press OK. This utility class will be merged in with your code when</span>

<span class="token comment">// deploying your final script.</span>

<span class="token comment">//</span>

<span class="token comment">// You can also simply create a new utility class manually, you don't</span>

<span class="token comment">// have to use the template if you don't want to. Just do so the first</span>

<span class="token comment">// time to see what a utility class looks like.</span>

<span class="token comment">//</span>

<span class="token comment">// Go to:</span>

<span class="token comment">// https://github.com/malware-dev/MDK-SE/wiki/Quick-Introduction-to-Space-Engineers-Ingame-Scripts</span>

<span class="token comment">//</span>

<span class="token comment">// to learn more about ingame scripts.</span>

  

<span class="token keyword">public</span>  <span class="token function">Program</span><span class="token punctuation">(</span><span class="token punctuation">)</span>

<span class="token punctuation">{</span>

<span class="token comment">// The constructor, called only once every session and</span>

<span class="token comment">// always before any other method is called. Use it to</span>

<span class="token comment">// initialize your script.</span>

<span class="token comment">//</span>

<span class="token comment">// The constructor is optional and can be removed if not</span>

<span class="token comment">// needed.</span>

<span class="token comment">//</span>

<span class="token comment">// It's recommended to set Runtime.UpdateFrequency</span>

<span class="token comment">// here, which will allow your script to run itself without a</span>

<span class="token comment">// timer block.</span>

<span class="token punctuation">}</span>

  

<span class="token keyword">public</span>  <span class="token keyword">void</span>  <span class="token function">Save</span><span class="token punctuation">(</span><span class="token punctuation">)</span>

<span class="token punctuation">{</span>

<span class="token comment">// Called when the program needs to save its state. Use</span>

<span class="token comment">// this method to save your state to the Storage field</span>

<span class="token comment">// or some other means.</span>

<span class="token comment">//</span>

<span class="token comment">// This method is optional and can be removed if not</span>

<span class="token comment">// needed.</span>

<span class="token punctuation">}</span>

  

<span class="token keyword">public</span>  <span class="token keyword">void</span>  <span class="token function">Main</span><span class="token punctuation">(</span><span class="token keyword">string</span>  argument<span class="token punctuation">,</span> UpdateType  updateSource<span class="token punctuation">)</span>

<span class="token punctuation">{</span>

<span class="token comment">// The main entry point of the script, invoked every time</span>

<span class="token comment">// one of the programmable block's Run actions are invoked,</span>

<span class="token comment">// or the script updates itself. The updateSource argument</span>

<span class="token comment">// describes where the update came from. Be aware that the</span>

<span class="token comment">// updateSource is a bitfield and might contain more than</span>

<span class="token comment">// one update type.</span>

<span class="token comment">//</span>

<span class="token comment">// The method itself is required, but the arguments above</span>

<span class="token comment">// can be removed if not needed.</span>

<span class="token punctuation">}</span>

</code></pre>
</div>
</body>

</html>
