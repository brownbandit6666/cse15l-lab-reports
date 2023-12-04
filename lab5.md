# **Lab Report 5 - Putting it All Together (Week 9)**
  1. "Hey TA, I ran into a problem when running my `ListExamples.java` file using my `test.sh` bash script. It seems like I had some sort of out of bounds error some type of bug that increments the type of length incorrectly. I currently do not have an IDE handy to make the changes, so all I'm working with is my terminal remotely connecting to my PC at home. Any ideas about how to fix this error using nothing but the terminal?" -*Michael*
    ![Image](Symptom1.JPG)
  2. "Hey Michael, try looking back at your notes about what techniques we can use to edit files wihtin the terminal. One possibility is using Vim, for starters. As for your reported symptom, I think you've got a good idea about a possible bug so try and fix it using Vim. Also make sure to take note of the comparison inducing failure." -*TA*
  3. "Thank you for the assistance! I used Vim to view and ultimately edit my code straight from the terminal. My bug was rooted in the incrementation, it seemed to be incrementing by 2 rather than 1. Moreover thank you for making me aware about the comparison issue, it seemed I was comparing the wrong `index` values in the last `while` loop." -*Michael*
     # **Bug:**
     ![Image](Bug.JPG)
     # **Bug Fix:**
     ![Image](BugFix.JPG)
     # **Passed JUNIT Tests:**
     ![Image](PassedTests.JPG)
# **Step 4**
* The file & directory structure needed was a `tesh.sh` file with the `set -e` notation and JUNIT commands in order to successfully run JUNIT Tests. `ListExamples.java` and `ListExamplesTests.java` files are necessary for the bug which is found in `ListExamples.java` and being able to run the tests found in `ListExamplesTests.java`. All files aforementioned can be found under a singular directory.
* The contents of each file before fixing the bug is as follows:
  ![Image](Bug.JPG)
  ![Image](ContentsbeforeFix.JPG)
