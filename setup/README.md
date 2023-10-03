# Intro to Javascript Arrays Lab - Setup

![Hero image](../assets/tktkhero-main-subhead.png)
tktk Hunter - we need to replace this stock hero image with one that includes "Intro to JavaScript Arrays Lab - Setup"
## Setup 

Open your Terminal application and navigate to your **`~/code/ga/labs`** directory:

```bash
cd ~/code/ga/labs
```

Make a new directory called **`js-arrays-lab`**, then enter this directory:

```bash
mkdir js-arrays-lab
cd js-arrays-lab
```

Then, create an **`script.js`** and an **`index.html`** file. These files will hold your work for this lab:

```bash
touch script.js index.html
```

With the files created, open the contents of the directory in VS Code:

```bash
code .
```

Open the **`index.html`** file and add HTML boilerplate. Then make use of the **`script.js`** file by adding this line inside the `<head>` tag:

```html
<script defer src="./script.js"></script>
```

With this setup complete, we'll have two methods at our disposal for executing the code we write in **`script.js`**:

- Open the **`index.html`** file in your browser and access the console output in your browser's dev tools.
- Use `node` to execute the **`script.js`** file directly by using this command in your terminal:

```bash
node script.js
```

While either method is acceptable, you should use the same method as your instructor for simplicity.
