Try running with:

$ mocha

Output is:

> Should not see this
> 
> Array
>    #indexOf()
>      √ should return -1 when the value is not present
>
>  SomethingElse
>    √ should do something else

Now try with

$ mocha -g Array

**Output is same**