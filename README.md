Download Link: https://assignmentchef.com/product/solved-cs174a-assignment-1
<br>
<h3><a id="user-content-step-1--begin-with-these-steps-to-repository-setup" class="anchor" href="https://github.com/Luke-ZL/CS174A/tree/master/project1/a1-Luke-ZL#step-1--begin-with-these-steps-to-repository-setup" aria-hidden="true"></a>Step 1: Begin with these steps to repository setup:</h3>

<ol>

 <li>By now you have followed the link to create your assignment repository at <a href="https://classroom.github.com/classrooms/55804222-intro-graphics-master-f19-classroom-1">https://classroom.github.com/classrooms/55804222-intro-graphics-master-f19-classroom-1</a>. Please use this link once as it will create an repository we will not check for submissions if you use it multiple times. The repository name should lool like <strong>a1-githubusername</strong>. Any others will get removed.</li>

 <li>As part of this process you will also receive an invite from GitHub to join the class organization which is where all of your class assignments and term project will live.

  <ul>

   <li>You should also be sure to setup your local git environment and ssh keys to work with GitHub.</li>

  </ul></li>

 <li>Once your repository is created you will have a copy of the assignment template in your github repository. Now you can clone the repository onto your local computer using the following command. Be sure do execute this command from the directory you wish to locate your work.</li>

</ol>

<ol start="4">

 <li>You can now follow the remaining steps of the assignment.</li>

</ol>

<h3><a id="user-content-step-2--now-follow-these-steps-to-run-and-modify-your-project" class="anchor" href="https://github.com/Luke-ZL/CS174A/tree/master/project1/a1-Luke-ZL#step-2--now-follow-these-steps-to-run-and-modify-your-project" aria-hidden="true"></a>Step 2: Now follow these steps to run and modify your project:</h3>

<ol>

 <li>Go to your folder. The easiest way is to right click the popup that downloaded it, then choose “Show in Folder”.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-01.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="icons" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-01.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-01.png?w=980&amp;ssl=1" alt="icons" data-recalc-dims="1">

    </noscript></a></li>

 <li>You should see the file index.html in your folder. You can already try clicking that open to see the code run on your machine… mostly. This is a start; you’ll see an animation. But this isn’t good enough. Your animation is still unable to load local files (texture images, sounds, models) out of your own file-system, due to its safety protections against your web browser.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-02.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="triangle" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-02.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" alt="triangle" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-02.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

     <noscript>

      <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-02.png?w=980&amp;ssl=1" alt="triangle" data-recalc-dims="1">

     </noscript>

    </noscript></a></li>

 <li>Run a fake server. which lacks those security protections. Do this by opening the file we gave you called “host” – “host.bat” if you’re Windows, “host.command” if your Mac. On Windows you can just double click the file open.

  <ul>

   <li><strong>On Mac, you might get a security warning instead if you double-click.</strong> Instead, right click the files, then choose Open, or you can go into System Preferences/Security &amp; Prinvacy/General and click ‘Open Anyway’. You may possibly need to check the file permissions and set them to 744.</li>

  </ul><a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-03.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="dialog" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-03.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-03.png?w=980&amp;ssl=1" alt="dialog" data-recalc-dims="1">

    </noscript></a></li>

 <li>Look in the resulting console window. If you can’t find a message starting with “Serving HTTP on …”, your operating system might not have come with Python; go download and install that first — use Google for help on that, then try our files again.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-04.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="http server" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-04.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-04.png?w=980&amp;ssl=1" alt="http server" data-recalc-dims="1">

    </noscript></a></li>

 <li>Now you’re hosting. Keep that window open.</li>

 <li>Open a new window of Google Chrome. Download it first if needed.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-05.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="url bar" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-05.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-05.png?w=980&amp;ssl=1" alt="url bar" data-recalc-dims="1">

    </noscript></a></li>

 <li>Navigate Chrome to the url <a href="http://localhost:8000/" rel="nofollow">http://localhost:8000/</a> That assumes that step 5’s message said port 8000 – otherwise change the number in the URL to match.</li>

 <li>Observe that your project shows up at this new URL. That’s where you’ll access it from now on.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-02.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="triangle" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-02.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" alt="triangle" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-02.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

     <noscript>

      <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-02.png?w=980&amp;ssl=1" alt="triangle" data-recalc-dims="1">

     </noscript>

    </noscript></a></li>

</ol>

Unfortunately, web developers in practice have to do that fake server thing pretty often to be able to work on their files locally. <strong>Keep the .bat or .command program open while you work.</strong>

<h3><a id="user-content-step-3--continue-the-next-steps-to-begin-viewing-the-code" class="anchor" href="https://github.com/Luke-ZL/CS174A/tree/master/project1/a1-Luke-ZL#step-3--continue-the-next-steps-to-begin-viewing-the-code" aria-hidden="true"></a>Step 3: Continue the next steps to begin viewing the code.</h3>

<ol>

 <li>Although any text editor will work on our files, for this class you’ll need to use the editor inside of Chrome, because of its debugging tools.</li>

 <li>Resume with the open Chrome window from the previous step 8.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-06.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="triangle code" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-06.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-06.png?w=980&amp;ssl=1" alt="triangle code" data-recalc-dims="1">

    </noscript></a></li>

 <li>Press F12 (Windows) or Cmd+Option+i (Mac) to open the Chrome developer tools panel (DevTools).</li>

 <li>You want DevTools to be able to take up the whole screen. Undock it from your web page window. Do this by clicking the ellipsis at the upper right corner, and selecting the first choice under “Dock Side”.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-07.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="triangle code 2" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-07.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-07.png?w=980&amp;ssl=1" alt="triangle code 2" data-recalc-dims="1">

    </noscript></a></li>

 <li>Maximize both your web page window and DevTools windows. Use the keyboard shortcut Alt+tab (Windows) or three finger swipe (Mac) to switch between them quickly.</li>

 <li>Click the “Sources” tab of the DevTools panel, towards the top of the screen.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-08.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="menu bar" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-08.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-08.png?w=980&amp;ssl=1" alt="menu bar" data-recalc-dims="1">

    </noscript></a></li>

 <li>Without leaving the “Sources” outer tab, look at the navigator panel on the left. This might be collapsed in the upper corner. Regardless open the “Page” inner tab underneath it.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-09.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="navigator" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-09.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-09.png?w=980&amp;ssl=1" alt="navigator" data-recalc-dims="1">

    </noscript></a></li>

 <li>You should see all the files you downloaded from GitHub here. Click them open to make sure you can see the code. Now you can read it all here.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-10.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="url bar" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-10.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-10.png?w=980&amp;ssl=1" alt="url bar" data-recalc-dims="1">

    </noscript></a></li>

 <li>Press F1 to open settings, and choose “Default indentation: 2 spaces”. Close settings.

  <ul>

   <li>This is just so you won’t be prevented from matching our formatting.</li>

  </ul></li>

</ol>

These steps, and the following ones, may seem like a lot of work but they are part of becoming a real web developer with a good workflow, as opposed to someone who just knows the language. The biggest key of all to becoming a good developer is actually going be mastering the <strong>debugger</strong> feature, but first for this assignment let’s just take it slow and set up our editor.

<h3><a id="user-content-step-4--continue-the-next-steps-to-begin-modifying" class="anchor" href="https://github.com/Luke-ZL/CS174A/tree/master/project1/a1-Luke-ZL#step-4--continue-the-next-steps-to-begin-modifying" aria-hidden="true"></a>Step 4: Continue the next steps to begin modifying:</h3>

<ol>

 <li>Change from the “Page” inner tab to the “Filesystem” inner tab, which might be collapsed behind the arrow. This one should be empty.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-11.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="filesystem" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-11.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-11.png?w=980&amp;ssl=1" alt="filesystem" data-recalc-dims="1">

    </noscript></a></li>

 <li>Drag and drop your local file folder from your computer’s folder navigator straight into the middle of the DevTools window. If you can’t figure out how to drag between maximized windows (you can), just use the manual “add folder to workspace” button and choose your folder. Either way this will complete the mapping between your real local files and the fake ones over the network.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-12.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="copy" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-12.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-12.png?w=980&amp;ssl=1" alt="copy" data-recalc-dims="1">

    </noscript></a>

  <ul>

   <li>It’s going to ask you for permission to modify your local files. Hit yes.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-13.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="allow" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-13.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

      <noscript>

       <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-13.png?w=980&amp;ssl=1" alt="allow" data-recalc-dims="1">

      </noscript></a></li>

   <li>If this doesn’t happen as described, try to find help on setting your local folder as a workspace.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-14.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="url bar" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-14.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

      <noscript>

       <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-14.png?w=980&amp;ssl=1" alt="url bar" data-recalc-dims="1">

      </noscript></a></li>

  </ul></li>

 <li>Observe the little green dots next to each file in the “Filesystem” subtab. These green dots verify that your Chrome has matched your fake server to your local files.</li>

 <li>Sometimes a green dot is missing — especially on index.html. That is dangerous; the file is not mapped right and any changes you make to it will be lost. When green dots are missing, hit ctrl+F5 (Windows) or cmd+F5 (Mac) to do a hard refresh. This re-loads them from your local files and re-maps them again.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-15.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="reload" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-15.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-15.png?w=980&amp;ssl=1" alt="reload" data-recalc-dims="1">

    </noscript></a></li>

</ol>

Be aware that for as long as you have DevTools open, back at browser window you have unlocked some new ways to refresh: Right-click the refresh button to see them.

<ol start="5">

 <li>If the green dots still don’t show up, delete what’s in the workspace area and try again until they appear.</li>

 <li>Now you can edit the files directly inside Chrome, in the DevTools “Sources” tab.

  <ul>

   <li>As long as you make changes under “Sources” and not “Elements”, your changes will now persist in your own local files even after page refreshes.</li>

   <li>You should avoid ever accidentally typing in the “Elements” tab. That’s only for temporary HTML stuff your code generates.</li>

  </ul></li>

</ol>

Editing directly in Chrome like this is the workflow we will use. One reason is that your code immediately changes its behavior as you type. Even when it’s in the middle of running, or as soon as you un-pause it in the debugger. Elements will move around on the page immediately when you make changes. This allows you to you dynamically test new code without re-starting your whole animation and losing your place — without having to wait for your timed scenes to progress to that point again — or without having to enter the right inputs again.

<h3><a id="user-content-step-5--continue-the-next-steps-to-begin-using-chrome-as-a-code-editor" class="anchor" href="https://github.com/Luke-ZL/CS174A/tree/master/project1/a1-Luke-ZL#step-5--continue-the-next-steps-to-begin-using-chrome-as-a-code-editor" aria-hidden="true"></a>Step 5: Continue the next steps to begin using Chrome as a code editor:</h3>

<ol>

 <li>If you’ve never learned your way around an IDE for editing code, now is the time to. Chrome’s code editor is kind of in-between in terms of quality: Better than Windows Notepad or TextEdit, but not quite as good as Notepad++ or Microsoft VSCode. In order for it to be better than crudely opening your code in notepad, you need to know what basic features to expect from a text editor. Let’s learn them.</li>

 <li>Find and try each of the following code editing commands once. They’re found in that DevTools Sources tab.

  <ul>

   <li>Block indent / unindent (Tab and Shift+Tab)</li>

   <li>Block comment / uncomment (Ctrl+/ or Cmd+/) ** For both of the above bullet points, try it on multiple highlighted lines at once.</li>

   <li>Zoom in/out while reading ** Hold down Ctrl (Windows) or Cmd (Mac) and then press plus, minus, or zero to adjust. ** Use this fit a comfortable amount of code on-screen for you to read at once.</li>

   <li>find (Ctrl+f or Cmd+f)</li>

   <li>find-and-replace<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-16.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="find and replace" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-16.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

      <noscript>

       <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-16.png?w=980&amp;ssl=1" alt="find and replace" data-recalc-dims="1">

      </noscript></a>** For both of the above bullet points, note that you don’t have to find specific or exact strings; Chrome supports matching <strong>regular expressions</strong>, for finding all text of a more general pattern. That’s the .* button.</li>

  </ul></li>

</ol>

<h4><a id="user-content-step-6--continue-the-next-steps-to-complete-homework-0" class="anchor" href="https://github.com/Luke-ZL/CS174A/tree/master/project1/a1-Luke-ZL#step-6--continue-the-next-steps-to-complete-homework-0" aria-hidden="true"></a>Step 6: Continue the next steps to complete homework 0:</h4>

<ol>

 <li>With our animation running in Chrome, with DevTools still open to the Sources tab. Open the file “dependencies.js”. This is under the “Filesystem” tab of the navigator panel, which might be collapsed in the upper corner.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-17.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="code" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-17.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-17.png?w=980&amp;ssl=1" alt="code" data-recalc-dims="1">

    </noscript></a></li>

 <li>If there’s no green dot next to “dependencies.js”, fix it as described above.</li>

 <li>The code is divided up into two JavaScript classes. The one at the bottom of the file makes the triangle. Let’s edit it.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-18.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="code" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-18.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-18.png?w=980&amp;ssl=1" alt="code" data-recalc-dims="1">

    </noscript></a></li>

 <li>On line 39, add the following three items to the JavaScript array, which is all the text enclosed by square brackets [ ]. Add a comma to separate from previous items in the array.

  <ul>

   <li>Vec.of(0,1,0), Vec.of(1,0,0), Vec.of(1,1,0)</li>

  </ul></li>

 <li>On line 40, add the following three items to the JavaScript array:

  <ul>

   <li>Color.of(0,0,1,1), Color.of(0,1,0,1), Color.of(1,1,0,1)</li>

  </ul></li>

 <li>Save the file, and reload the page (using Ctrl+Shift+r for Windows, Cmd+Shift+r for Mac). Switch back to look at your web page window. The triangle should be a square now, because you just attached a second triangle to it. If so, your edit worked and your file is saved. If not, check for green dots and fix it as per above.<a href="https://i0.wp.com/github.com/Luke-ZL/CS174A/blob/master/project1/a1-Luke-ZL/docs/image-19.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" alt="square" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-19.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="https://i0.wp.com/github.com/Luke-ZL/CS174A/raw/master/project1/a1-Luke-ZL/docs/image-19.png?w=980&amp;ssl=1" alt="square" data-recalc-dims="1">

    </noscript></a></li>

 <li>If you typed the wrong thing, you could get console errors, a blank web page, or missing triangles. Later on we’ll show you how to use the debugger and the console together to approach errors in a smart way. For now, just type it right.</li>

 <li>Your files should be ready to turn in now, including your trivial change.</li>

</ol>

<h4><a id="user-content-step-7--continue-the-next-steps-to-turn-in-homework-0-on-github" class="anchor" href="https://github.com/Luke-ZL/CS174A/tree/master/project1/a1-Luke-ZL#step-7--continue-the-next-steps-to-turn-in-homework-0-on-github" aria-hidden="true"></a>Step 7: Continue the next steps to turn in homework 0 on GitHub:</h4>

<ol>

 <li>Once you are finished working it is time to ‘commit’ your work to your remote respository on GitHub. You will want to do this periodically while you are working to make a backup of your work and to make your final submission. We will keep the process very simple by simply ‘committing’ the master branch of your local repository into the remote repository on GitHub.</li>

 <li>The first step is to add any new files into the respository so they can be tracked.</li>

</ol>

<ol start="3">

 <li>Then we commit any new and or changed files to the repository. The text after the -m is for you to describe what is included in this commit to the respository.</li>

</ol>

<ol start="4">

 <li>Finally, we need to push these changes up to our remote repository on GitHub. This is a very important step! Without it you are not copying your work back to GitHub and we will not be able to see it if you forget.</li>

</ol>

<ol start="5">

 <li>You can repeat these commands as often as you feel the need as your work on your assignment. However, again, you must always make a final push to GitHub when you are finished in order to submit your work. We will make a copy of all assignments at the assignment deadline. That implies two things. First, make your final push to GitHub ahead of time and second, any pushes you make after the deadline will not be seen by us.</li>

</ol>

5/5 - (1 vote)

<pre>$ git clone <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="16717f6256717f627e63743875797b">[email protected]</a>:intro-graphics-master-F19/a1-githubusername.git</pre>

<pre>$ git add <span class="pl-k">*</span></pre>

<pre>$ git commit -m <span class="pl-s"><span class="pl-pds">"</span>Description of what I did<span class="pl-pds">"</span></span></pre>