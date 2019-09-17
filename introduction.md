<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>introduction</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><p>First, let’s create a new project and call it <strong>SEIntro</strong>:</p>
<ol>
<li>Open <strong>Visual Studio 2019</strong></li>
<li>Select menu <strong>File &gt; New &gt; Project</strong></li>
<li>Select <strong>Installed &gt; Visual C# &gt; Space Engineers &gt; Ingame Script</strong></li>
<li>Give it name <strong>SEIntro</strong></li>
<li>Click <strong>OK</strong> and then <strong>Create New Project</strong></li>
</ol>
<p>There are two types of comments in C# – single-line and multi-line.<br>
Single-line comments are created using double slash.</p>
<pre class=" language-cs"><code class="prism  language-cs">// This is a single-line comment
</code></pre>
<p>Multi-line comments start with <strong>/**</strong> and end with <strong>**/</strong></p>
<pre class=" language-cs"><code class="prism  language-cs">/**
 * This is a multi-line comment
 **/
</code></pre>
<p>Below is the contents of the <strong>Program.cs</strong> file that you’re presented with in a new project. In this example I left comments that are generated automatically with a new project as single-line comments, and also added multi-line comments to explain some other things.</p>
<pre class=" language-cs"><code class="prism  language-cs">/*
 * R e a d m e
 * -----------
 * 
 * In this file you can include any instructions or other comments you want to have injected onto the 
 * top of your final script. You can safely delete this file if you do not want any such comments.
 */

// This file contains your actual script.
//
// You can either keep all your code here, or you can create separate
// code files to make your program easier to navigate while coding.
//
// In order to add a new utility class, right-click on your project,
// select 'New' then 'Add Item...'. Now find the 'Space Engineers'
// category under 'Visual C# Items' on the left hand side, and select
// 'Utility Class' in the main area. Name it in the box below, and
// press OK. This utility class will be merged in with your code when
// deploying your final script.
//
// You can also simply create a new utility class manually, you don't
// have to use the template if you don't want to. Just do so the first
// time to see what a utility class looks like.
//
// Go to:
// https://github.com/malware-dev/MDK-SE/wiki/Quick-Introduction-to-Space-Engineers-Ingame-Scripts
//
// to learn more about ingame scripts.

public Program()
{
    // The constructor, called only once every session and
    // always before any other method is called. Use it to
    // initialize your script.
    //
    // The constructor is optional and can be removed if not
    // needed.
    //
    // It's recommended to set Runtime.UpdateFrequency
    // here, which will allow your script to run itself without a
    // timer block.
}

public void Save()
{
    // Called when the program needs to save its state. Use
    // this method to save your state to the Storage field
    // or some other means.
    //
    // This method is optional and can be removed if not
    // needed.
}

public void Main(string argument, UpdateType updateSource)
{
    // The main entry point of the script, invoked every time
    // one of the programmable block's Run actions are invoked,
    // or the script updates itself. The updateSource argument
    // describes where the update came from. Be aware that the
    // updateSource is a  bitfield  and might contain more than
    // one update type.
    //
    // The method itself is required, but the arguments above
    // can be removed if not needed.
}
</code></pre>
</div>
</body>

</html>
