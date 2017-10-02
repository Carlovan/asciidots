[Back to docs home](../../index.md) - [Back to libs](index.md#simple-operations-on-dots)

# bool_not.dots

### Purpose
Since there is no unary operators in asciidots, this librairy operate a NOT oparation on a dots value. 

### Usage
    
     T
    L+R
     B

##### Parameters
- `L`, `R`, `T` or `B`: The dot where do do the NOT 
- `R`, `L`, `B` or `T`: The output will come strait in the same direction

##### Example

    %!bool_not.dots n

    .-#1--n--$_#-#0--n--$_#-#3--n--$_#-&

##### Output

    010

### Notes
- This is not the bitwise not
- Any other value than 0 will be changed to 0.

### Source 
The source code is availaible [here](https://github.com/ddorn/asciidots/blob/master/libs/bool_not.dots)
. If something doesn't work, do not hesitate to [open an issue](https://github.com/ddorn/asciidots/issues/new?title=Bug%20in%20bool_not%20librairy:%20).

[Back to docs home](../../index.md) - [Back to libs](index.md#simple-operations-on-dots)
