

<img align="left" src="https://github.com/leungwensen/svg-icon/blob/master/dist/svg/logos/react.svg" height="50" alt="react icon"/>
<h2>Portfolio Template</h2>

<pre>
⭐ Easy to adapt and deploy portfolio project covering most important 
sections(about, exp, skills, projects), inspired with solutions found 
at GitHub. Check live preview(link below).
</pre>

<strong>:crown: advantages</strong>

<br/>

<h3>:eye_speech_bubble: Live demo</h3>

<h3>:books: Getting started</h3>

1. Clone or fork project.
2. Install required dependencies with `npm install`.
3. Remove `homepage` entirely from `package.json` or set it to single dot. 
4. `npm start` project and customize it.
5. Deploy on github-pages using `npm run deploy` command.

<pre>
⚠️ Note that:
- if you want to have portfolio on different repository than `{username}.github.io`, 
set `homepage` in `package.json` to `https://{username}.github.io/{repository-name}/` 
before deploying portfolio.
- if you want to run it locally with <strong>npm run start</strong>, make sure that you have edited 
homepage property or json data won't load.
</pre>

<h3>:star: Inspirations</h3>
<h3>:memo: Changelog</h3>
<details>
<summary>[ 05.03.2022, contributor: <a href="https://github.com/mangelarilla">@mangelarilla</a> ]</summary>
<pre>
- update DevIcon stylesheet to latest one
</pre>
</details>
<details>
<summary>[ 03.10.2021, contributor: <a href="https://github.com/shahednasser">@shahednasser</a> ]</summary>
<pre>
- updated sass dependency.
</pre>
</details>
<details>
<summary>[ 26.05.2021, contributor: <a href="https://github.com/DavidMatalik">@DavidMatalik</a> ]</summary>
<pre>
- removed nonexisting logos references: logo192 and logo512.  
</pre>
</details>
<details>
<summary>[ 17.01.2021, contributor: <a href="https://github.com/igorperic17">@igorperic17</a> ]</summary>
<pre>
- wrapped the Typical component into a fixed height div due to the bad transitions for a brief moment between two titles when the string is empty (the content bellow jumps up-down very quickly).
- removed the title from the page document.title due to the increased title length.
</pre>
</details>
<details>

<pre>
- updated readme section
- fixed problem of json files not being read
</pre>
</details>
<details>
<summary>[ 29/30.11.2020, contributor: <a href="https://github.com/trolit">@trolit</a> ]</summary>
<pre>
- changed resume files names to more "universal"
- moved languages names to global variables
- moved section names to json files
- added target="_blank" for footer links
- added startDate property for projects
- excluded common json data to portfolio_shared_data file
- added header section height calculation based on formula: window.innerHeight - 140
- small changes to vertical timeline item (color/font-size)
- project link in modal is not shown if empty
- changed slider preloader bar color
- wrapped each skill into tile
- footer fullname is fetched from json now
- added mising "px" for avatar in About.js component
- updated json files content
- page title is fetched from json data
- added GitHub reference corner "label"
- edited page meta
- added margin, padding 0 for html tag
- excluded light theme ref from theme-dark file
- slightly changed Header.js section look
- made some changes to App.js to apply global variables/shared json etc.
- centered fullname/pos/theme toggler in Header section
</pre>
</details>

<h3>:gear: Contribution</h3>

If you have any suggestions on what to improve in <em>react-frontend-dev-portfolio</em> and would like to share them, feel free to leave an issue or fork project to implement your own ideas :slightly_smiling_face:

<h3>:camera: Credits(images)</h3>




