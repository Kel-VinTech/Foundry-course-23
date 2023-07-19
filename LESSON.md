we use "forge init" to start a new foundry project.

note: use "-v to -vvvvv to check an exact error"

we have different type of testing
1. unit - test any part of our code
2. integration - test how code works with other part of our code
3. forked - test our code on a simulated environment
4. staging - test our code in real environment that is not prod

-- Mock contract
it is like a fake contract

Note: use "--mt" when you want to run test on a single function


-- 3 methods for working with a test
- Act
- Arrange
- Assert

-- cheaper withdrawal

use "forge snapshot" to check the gas fee for a function
Note: one way we can actually reduce gas fee is by storage


--storage
we can use "forge inspect" to check our storage
we can also use "cast storage"

Note: 
- immutable variables are not saved in storage and hey have the (i_)
- storage variable have the (s_)


--MakeFiles

it allows us to create shortcuts for commands that we are going to commonly use