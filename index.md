# Part1 : Bug

### Success Example:

@Test

public void testRight(){  

    int [] input = {};
    
    assertArrayEquals(new int[]{}, ArrayExamples.reversed(input));  
  }

### Failure Example:

@Test

public void testReverseInPlace(){

    int[] input1 = {1,2,3,4};
    int[] test = {4,3,2,1};
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(test,input1);
    
  }

### Output Example:
