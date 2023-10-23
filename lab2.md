# **Lab Report 2 - Servers and SSH Keys (Week 3)**
* **Part 1**
  * ![Image](StringServer_1.JPG)
  * ![Image](1_output.JPG)
  * ![Image](2_outputJPG.JPG)
  * For both screenshots the `handleRequest` method is being run each time.
  * The relevant arguments are the url path, the query, and the text following the queries equal signs. The relevant fields starts with the arraylist
    assigned to `str` which appends each element as its added, `nums` which increments as each element is added, and the resulting `output` String that
    it was returned upon completion.
  * The arraylist `str`, the int `nums`, and String `output` all change. Each one changes after every input, incrementing singularly everytime. This goes
    for the strings added and the `nums` value.
* **Part 2**
  * ![Image](ls_image.JPG)
  * Working Directory: `/home` & `/home/lecture1`
  * When working with the `ls` command each usage outputed a list format of all immediate contents of the
    working directory. In the last instance of using `ls` with a file, since there are no consecutive routes
    or content it outputed the file itself.
* **Part 3**
  * Something that I enjoyed truly learning through experience with this lab was the relationship between my raw code, manually compiling it and
    testing it on my locally hosted server. Primarily it felt like my programming was actually being used for something that produced a real result
    whereas in previous CS classes we test through JUNIT or unit tests. I enjoyed learning the nuances of setting up my own server to test my code.
