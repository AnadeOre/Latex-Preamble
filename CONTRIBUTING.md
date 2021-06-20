# Contributing

Contributions are always welcome! Here is some documentation to show you how to do it!

### Workflow

#### Step 1: Find an issue

Step 1 is to find an issue that you can do. check the [issues](https://github.com/Uklizdev/Latex-Preamble/issues) page or just raise your own with a new idea.

#### Step 2: Create a fork

All work should be done on a fork. Make sure to [keep your fork up to date](https://dev.to/giannellitech/keeping-your-fork-up-to-date-klh).

#### Step 3: Making changes

##### Clone repository

```bash
git clone https://github.com/YOUR-USERNAME/Latex-Preamble
```

##### Testing preambles

Create a new file for testing. Let's call it `testing.tex`. This file should be in the same folder as the `Preambles.tex` cloned file

##### Create a new branch

```bash
git branch newcontribution
git checkout newcontribution
```

##### Making changes

In `testing.tex` add the preamble by writing 

```tex
\input{preamble.tex}
```
Add commands to `Preamble.tex` and test them in `texting.tex`.


### Step 4: Make sure to write good documentation

Make sure you explain your changes very well, information such as linking the issue (#issueNumber) and screenshots is highly appreciated.

### Step 5: Pull Request

Open a pull request into the Latex Preamble "Contributions" branch with only the `Preamble.tex` file. Someone will review your project as soon as possible.


### Problems?

If you experience a bug or issues you could not fix, do not hesitate to open a new [GitHub issue](https://github.com/Uklizdev/Latex-Preamble/issues).
