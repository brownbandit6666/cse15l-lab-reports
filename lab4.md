# **Lab Report 4 - Vim (Week 7)**
  * ![Image](Step_4.JPG)
    * **Key Path:** `ssh cs15lfa23qa@ieng6.ucsd.edu`,  `<enter>`
    * This remotely logged me into the UCSD ieng6-202.ucsd.edu.
  * ![Image](Step_5.JPG)
    * **Key Path:** `git clone git@github.com:brownbandit6666/lab7.git`,   `<enter>`
    * This clones the git repository `lab7` to my working environment.
  * ![Image](Step_6.JPG)
    * **Key Path:** `bash test.sh`,   `<enter>`
    * This runs the JUNIT tests.
  * ![Image](Step_7.JPG)
    * **Key Path:** `vim ListExamples.java`, `<down>` x44,   `<right>` x12,   `x`,    `i`,   `2`,   `<esc>`,   `:wq`
    * I first open the .java file in Vim in order to edit its contents. I then proceed down 44 lines and over 12 columns. I delete the 1 out of `index1` using `x`, enter insert mode using `i`, and type 2 to make it `index2`. I exit insert mode using `<esc>` and save/quit using `:wq`.
  * ![Image](Step_8.JPG)
    * **Key Path:** `bash test.sh`,   `<enter>`
    * This runs the JUNIT tests.
  * ![Image](Step_9.JPG)
    * **Key Path:** `git status`, `git add .`, `git commit -m "GreatJob"`, `git push`, `git status`
    * Finally, `git status` gives me the general diagnostics on what has been saved etcetera. Following, `git add .` adds the changes, `git commit -m "GreatJob"` commits the changes with the message *GreatJob*, `git push` finally pushes them. Ultimately I use `git status` to make sure my commands accomplished what I wanted them to.
