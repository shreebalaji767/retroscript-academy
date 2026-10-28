# RetroScript Academy

A free, retro-inspired teaching website for scripting languages, from absolute beginner to advanced. It teaches real concepts with worked examples, practice tasks, and instructions for running code in the correct environment.

## What is included

- Step-by-step lessons for DOS-style command-line use, Windows Batch, JavaScript, Microsoft JScript, VBScript, PowerShell, Bash, Python, PHP, and a scripting-language atlas
- Explanations of variables, types, paths, quoting, conditions, loops, functions, arrays, objects, pipelines, redirection, exit codes, asynchronous code, file handling, error handling, and safe automation
- Worked code examples plus exercises that ask learners to predict output and verify results
- A browser JavaScript workshop that executes real JavaScript in a sandboxed browser engine
- Real-environment practice instructions for Windows Command Prompt, PowerShell, Bash/Linux, Node.js, and language runtimes
- Searchable course directory, lesson navigation, quick reference, quiz, responsive retro styling, and locally saved course progress

## No simulations of operating systems

The DOS simulator has been removed. The practice section now gives commands for a real Windows Command Prompt, PowerShell, and Bash environment. These are modern environments; modern Windows Command Prompt is not identical to original MS-DOS.

The website can execute JavaScript in the browser. Other languages require their own compatible runtime and must be run on a computer or environment where that runtime is installed. The website does not pretend to execute those languages on GitHub Pages.

## Run real practice

### Windows Command Prompt / Batch
1. Press **Win + R**, enter `cmd`, and press Enter.
2. Work inside a folder you created for practice.
3. Try `cd`, `dir`, `mkdir Practice`, `cd Practice`, `echo Hello>hello.txt`, and `type hello.txt`.
4. Save Batch examples as `.bat` files using a plain-text editor, then run them from the practice folder.

### PowerShell
Open PowerShell or Windows Terminal and try read-only commands such as `Get-Location`, `Get-ChildItem`, and `Get-Help Get-ChildItem`. Understand a command before using it to modify system state.

### Bash / Linux
Use a Linux/macOS terminal or a Linux environment such as WSL on Windows. Start with `pwd`, `printf '%s\\n' 'Hello'`, `mkdir -p practice`, and `cat` to inspect a file you created.

### JavaScript
Use the browser workshop for immediate execution. For scripts outside a browser, install Node.js from [nodejs.org](https://nodejs.org/), save a script as `lesson.js`, and run `node lesson.js`.

### Python and PHP
Install the relevant runtime from its official source: [Python](https://www.python.org/) or [PHP](https://www.php.net/). Save source files with the appropriate extension and run them in a terminal or a suitable local development environment.

### JScript and VBScript
These are legacy Windows Script Host technologies. Their availability and compatibility depend on the Windows version and configuration; VBScript is deprecated in modern Windows. Study them for historical and maintenance knowledge, and use a controlled environment that you own.

## Publish with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select the GitHub Actions workflow if the workflow is available, or choose **Deploy from a branch** and select **main** and **/(root)**.
3. Wait for the Pages workflow to complete successfully, then open the URL shown in repository Pages settings.

The site is plain HTML, CSS, and JavaScript. No build step, server, database, paid API, or paid AI service is required.

## Safety and limitations

- GitHub Pages serves static files. It does not run DOS, Batch, PowerShell, Bash, JScript, VBScript, Python, or PHP on its server.
- The browser JavaScript workshop is sandboxed and has no network access, but browser sandboxing is not a substitute for reviewing code.
- Practise in a dedicated folder and use harmless sample files. Do not run unknown scripts or copy commands that delete files, change system settings, access credentials, or require administrator privileges without understanding them.
- Legacy runtimes and command syntax differ by operating system and version. Check the documentation for the environment you are actually using.

## Local development

Open `index.html` in a modern browser or serve the repository using any static local web server. No dependencies are required.

## License

Add a license file if you intend to grant others explicit reuse rights.
