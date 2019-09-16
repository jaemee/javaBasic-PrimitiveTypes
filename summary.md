# Question
1. What is the knowledge point of the test? Where is the official document to the knowledge point?
2. Why the test failed at first?
3. Why you corrected the test that way?
4. Do you have further questions on this knowledge point?

## BooleanOperatorsTest

#should_perform_logical_boolean_operations
1. To learn how logical operations works in java with just looking at the condition. Document: https://www.dummies.com/programming/java/logical-operators-in-java/
2. Wrong expected result for single logical operators
3. Learned from re-reading the materials on how single logical operators ( |, &) works when it will be true/ false
4. None.


#should_do_bitwise_and_boolean_operation
1. Learning the combination of checking or using bitwise together with boolean operators. Document: https://www.vojtechruzicka.com/bit-manipulation-java-bitwise-bit-shift-operations/
2. Looking at the original codes it will fail because as per looking with the hexadecimal values it's won't return to 0, no matter what.
3. I corrected the test's expected result directly as an integer value since I can straightly get the value from the 2 hexadecimal converted to binary and using the logical operators
4. None.

#should_do_bitwise_or_boolean_operation
1. Same as above should_do_bitwise_and_boolean_operation
2. Same as above should_do_bitwise_and_boolean_operation
3. Same as above should_do_bitwise_and_boolean_operation
4. Same as above should_do_bitwise_and_boolean_operation

#should_do_bitwise_not_operation
1. To learn the NOT operation with bitwise. Document: https://www.vojtechruzicka.com/bit-manipulation-java-bitwise-bit-shift-operations/
2. Same as above should_do_bitwise_and_boolean_operation. 
3. I put the binary value to correct the test because the decimal value of my answer is too big for an int type
4. After I add my answer and run the test and succeed I got curious what the value of the actual 
really is, why too big integer so I re run the test. I found out that the value of the Actual is negative,
I was wondering why my answer with positive big value equals to negative value using binary?
I also read that with NOT operation the value will be flipped, so it will be negative, but I don't get
how I will have negative when I was doing the computation and got a positive answer instead. If there are other 
documents I can reference please share.




##CharTypeTest

#should_describe_escaped_chars
1. To learn and describe how to use escaped characters in java. Document: https://docs.oracle.com/javase/tutorial/java/data/characters.html
2. After coding, my first run failed because I'm using binary and got the wrong binary for backspace to get char
3. During coding I realize that the modification should be using the escaped string directly set to the final variable 
and not the binary value
4. None. 


##IntegerTypeTest

#should_get_range_of_primitive_int_type
1. To learn the different primitive types and to use primitive type constants. Documents: https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html
2. Not fail at first because I put changes before running test (Same as above answer, I always modify first before running tests)
3. Because as per rule apply, we need to take use of constant primitive type and Actual needs MAX/ MIN_VALUE
4. None.

#should_get_range_of_primitive_short_type
1. Same as above should_get_range_of_primitive_int_type
2. Same as above should_get_range_of_primitive_int_type
3. Same as above should_get_range_of_primitive_int_type
4. Same as above should_get_range_of_primitive_int_type

#should_get_range_of_primitive_long_type
1. Same as above should_get_range_of_primitive_int_type
2. Same as above should_get_range_of_primitive_int_type
3. Same as above should_get_range_of_primitive_int_type
4. Same as above should_get_range_of_primitive_int_type

#should_get_range_of_primitive_byte_type
1. Same as above should_get_range_of_primitive_int_type
2. Same as above should_get_range_of_primitive_int_type
3. Same as above should_get_range_of_primitive_int_type
4. Same as above should_get_range_of_primitive_int_type

#should_overflow_silently
1. To learn overflowing of int in java. Document: https://dzone.com/articles/overflow-and-underflow-data
2. No idea what will happen to an int value if it surpasses it's MAX_VALUE
3. Change the code with Integer.MIN_VALUE, since as per reading document any 32-bit java that surpasses 32 bit will get rounded, so adding 1 to Max will return the 
lowest value of Integer
4. None

 