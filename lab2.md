# **Lab Report 2 - Servers and SSH Keys (Week 3)**
* **Part 1**
  * ![Image](cd_image.JPG)
  * Working Directory: `/home` & `/home/lecture1`
  * With no argument I saw since being at the `/home` directory, it did nothing.
    If I had started at any other directory when strictly typing `cd`, it would've returned
    me back to the root directory. Otherwise when providing the `lecture1` parameter it changed directory
    and lastly when I tried changing to a non-directory pathway, it outputed an error. 
* **Part 2**
  * ![Image](ls_image.JPG)
  * Working Directory: `/home` & `/home/lecture1`
  * When working with the `ls` command each usage outputed a list format of all immediate contents of the
    working directory. In the last instance of using `ls` with a file, since there are no consecutive routes
    or content it outputed the file itself.
* **Part 3**
  * ![Image](cat_image.JPG)
  * Working Directory: `/home`
  * Primarily, the first instance of use with `cat` we can see it cause an input loop. Since I used it
    at the root directory with no argument it waits for an input to be typed and then returns it back to the user,
    until you exit ("^C"). Otherwise it views the directory or file provided as an argument, hence why the `lecture1/Hello.java`
    argument prints the contents of the Java file.
