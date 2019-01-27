<h1>0x03. Git</h1>
<p>At the end of this project, you are expected to be able to explain to anyone, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>What is source code management</li>
<li>What is Git</li>
<li>How to create a repository</li>
<li>How to commit</li>
<li>How to push code</li>
<li>How to create a branch</li>
<li>How to pull updates</li>
<li>How to merge branches</li>
<li>How to work as collaborators on a project</li>
<li>What is GitHub?</li>
<li>What is the difference between Git and GitHub</li>
<li>How to write helpful commit messages</li>
<li>Which files should and which files should not appear in your repo</li>
</ul>
<h2>Tasks</h2>
  <h3>
    0. Create and setup your Git and Github account
  </h3>
  <p>Git is installed on your iMac provided by Holberton, but if you&rsquo;re using another computer, you might have to install it yourself.</p>
<ul>
<li>As a Holberton School student, you are eligible to get a GitHub student developer pack, with some nice goodies. Get you pack here: https://education.github.com/pack</li>
<li>Configure the basics you need on your local account that will be part of your commits: your name, your email. Tips</li>
</ul>
<p>In Github.com:</p>
<ul>
<li>Create your first repository (please use the graphical interface)
<ul>
<li>name: <code>my_first_repository</code></li>
<li>description: <code>I&#39;m now a Holberton Student, it&#39;s my first repository as a full-stack engineer</code></li>
<li>public</li>
<li>no Readme, .gitignore or license</li>
</ul></li>
</ul>
<p>In your computer, open a terminal to:</p>
<ul>
<li>navigate to your home/login directory. Tips</li>
<li>create a directory <code>my_first_repository</code>. Tips</li>
<li>navigate to this new directory. Tips</li>
<li>initialize git and add the remote origin</li>
<li>create a file <code>README.md</code> with Emacs (or other command line editors) and write a small Markdown text to present this project. <strong>This file is mandatory in all Holberton School projects</strong></li>
<li>add this new file to git, commit the change with this message &ldquo;My first commit&rdquo; and push to the remote server / origin (you will probably need to set your login/password to push to the remote server)</li>
</ul>
<p>Good job! </p>
<p>You did your <strong>push</strong> in your <strong>first repository</strong> of your <strong>first task</strong> of your <strong>first Holberton School project</strong>.</p>
        <p>File: <code>README.md</code></p>
  <h3>
    1. Coding fury road
  </h3>
  <p>For the moment we have an empty project, only the description with the <code>README.md</code>, it&rsquo;s time to code!</p>
<ul>
<li>create these directories at the root of your project: <code>bash</code>, <code>c</code>, <code>js</code> </li>
<li>create empty files:
<ul>
<li><code>c/c_is_fun.c</code></li>
<li><code>js/main.js</code></li>
<li><code>js/index.js</code></li>
</ul></li>
<li>create a file <code>bash/holberton</code> with these two lines inside: <code>#!/bin/bash</code> and <code>echo &quot;Holberton&quot;</code></li>
<li>create a file <code>bash/school</code> with these two lines inside: <code>#!/bin/bash</code> and <code>echo &quot;School&quot;</code> </li>
<li>add all these new files to git</li>
<li>commit your changes (message: &ldquo;Starting to code today, so cool&rdquo;) and push to the remote server</li>
</ul>
        <p>File: <code>bash/holberton, bash/school, c/c_is_fun.c, js/main.js, js/index.js</code></p>
  <h3>
    2. Collaboration is the base of a company
  </h3>
  <p>A branch is like a copy of your project. It&rsquo;s used mainly for:</p>
<ul>
<li>to not breaking your repository</li>
<li>to add a feature in development</li>
<li>collaboration on the same project with someone else</li>
<li>to not upset your co-worker</li>
</ul>
<p>The goal of a branch is to isolate your work with the main code of your project or with coworker&rsquo;s work.</p>
<p>For your first project, you will create a branch <code>update_script</code> and in this branch you will:</p>
<ul>
<li>create an empty file <code>bash/98</code></li>
<li>update <code>bash/holberton</code> by replacing <code>echo &quot;Holberton&quot;</code> by <code>echo &quot;Holberton School&quot;</code></li>
<li>update <code>bash/school</code> by replacing <code>echo &quot;School&quot;</code> by <code>echo &quot;The school is open!&quot;</code></li>
<li>add and commit these changes (message: &ldquo;My personal work&rdquo;)</li>
<li>push this new branch. Tips</li>
</ul>
<p>Perfect! you did an amazing update in your project and it&rsquo;s isolated correctly from the <strong>master</strong> branch. </p>
<p>Ho wait, your manager needs a quick fix in your project and it should be deployed now:</p>
<ul>
<li>change branch to <code>master</code></li>
<li>update the file <code>bash/holberton</code> by replacing <code>echo &quot;Holberton&quot;</code> by <code>echo &quot;Holberton School is so cool!&quot;</code></li>
<li>delete the directory <code>js</code></li>
<li>commit your changes (message: &ldquo;Hot fix&rdquo;) and push to the origin</li>
</ul>
<p>Ouf, hot fix is done!</p>
        <p>File: <code>bash/holberton, bash/school, bash/98</code></p>
  <h3>
    3. Collaboration: be up to date
  </h3>
  <p>Of course, you can also work on the same branch as your co-workers and it&rsquo;s better for you to be up to date with their changes.</p>
<p>For this task, <strong>and only for this task</strong>, please update your file <code>README.md</code> in the master branch from Github.com. It&rsquo;s the <strong>only time</strong> you are allowed to update and commit from Github interface.</p>
<p>When it&rsquo;s done, in your terminal:</p>
<ul>
<li>get locally all changes of the master branch (your <code>README.md</code> file will be updated)</li>
<li>write in a file <code>up_to_date</code> (at the root of your repository) the git command line used</li>
<li>add this new file <code>up_to_date</code>, commit (message: &ldquo;How to be up to date in git&rdquo;) and push to the origin</li>
</ul>
        <p>File: <code>README.md, up_to_date</code></p>
  <h3>
    4. HAAA what did you do???
  </h3>
  <p>Collaboration is cool, but not really when you update the same file at the same time&hellip;</p>
<p>To illustrate that, please merge the branch <code>update_script</code> to <code>master</code>: &ldquo;Cool, all my changes will be now part of the main branch, ready to be deployed!&rdquo;</p>
<p><strong>HHHHHHHAAAAAAAA</strong></p>
<p>As you can see, you have conflicts between you two branches on the same file.</p>
<p>Your goal now is to resolve conflicts by using the version of the branch <code>update_script</code>, and push the result to the origin.</p>
<p>At the end, you will have all your work from the branch <code>update_script</code> (new file and update of 2 files) + all last <code>master</code> commits (new files, delete folder etc&hellip;) except for conflicts.</p>
  <h3>
    5. Never push too much
  </h3>
  <p>Create a <code>.gitignore</code> file and define a rule to never push <code>~</code> files (generated by Emacs). Tips</p>
        <p>File: <code>.gitignore</code></p>
