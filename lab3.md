# **Lab Report 3 - Bugs and Commands (Week 5)**
* **Part 1**
  * `@Test 
	public void testReverseInPlace2() {
    int[] input1 = {1,2,3,4};
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{4,3,2,1}, input1);
	}`
  * `@Test 
	public void testReverseInPlace3() {
    int[] input1 = {1};
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{1}, input1);
	}`

  * ![Image](part2_2.JPG)
  * ![Image](part2_1.JPG)
    
  * **Before:**
  * `static void reverseInPlace(int[] arr) {
    for(int i = 0; i < arr.length; i += 1) {
      arr[i] = arr[arr.length - i - 1];
    }
  }`
  * **After:**
  * `static void reverseInPlace(int[] arr) {
    for(int i = 0; i < arr.length / 2; i += 1) {
      int temp  = arr[i];
      arr[i] = arr[arr.length - i - 1];
      arr[arr.length - i - 1] = temp;
    }
  }`
* **Part 2**
  * ![Image](part2_2.JPG)
  * ![Image](part2_1.JPG)
* **Part 3**
  * Something that I enjoyed truly learning through experience with this lab was the relationship between my raw code, manually compiling it and
    testing it on my locally hosted server. Primarily it felt like my programming was actually being used for something that produced a real result
    whereas in previous CS classes we test through JUNIT or unit tests. I enjoyed learning the nuances of setting up my own server to test my code.
