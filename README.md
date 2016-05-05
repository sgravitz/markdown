Welcome to StackEdit!
===============================


### Using inline Javascript
```javascript
$(function(){
  $('div').html('I am a div.');
});
```

### Tables
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

### Using inline List
This is an example of combining inline with a list
> **Note:**
> - StackEdit is accessible offline after the application has been loaded for the first time.
> - Your local documents are not shared between different browsers or computers.
> - Clearing your browser's data may **delete all your local documents!** Make sure your documents are synchronized with **Google Drive** or **Dropbox** (check out the [<i class="icon-refresh"></i> Synchronization](#synchronization) section).

### Link Examples
- [GitHub](http://github.com)
- http://github.com - automatic!
- Online Markdown Editors
  - [jbt.github.io/markdown-editor](https://jbt.github.io/markdown-editor/)
  - [stackedit.io](https://stackedit.io/editor)
  - [dillinger.io](http://dillinger.io/)


### Inline Example
As Kanye West said:
> We're living the future so 
> the present is our past.

### Italics/Bold
- *This text will be italic* 
- _This will also be italic_
- **This text will be bold**
- __This will also be bold__
- _You **can** combine them_


### Go in Action
- Chapter 1 - Introducing Go
  - Go is designed for distributed teams coordinating via Git/GitHub, etc.
  - Go tools simplify using and publishing packages.
  - Objective --> solving modern programming challenges
    - few language keywords
    - robust standard library
    - fast compilation
      - simplified dependency resolution
    - Cross-platform Windows/Mac/Linux
  - built-in concurrency
    - goroutines, like threads, but less memory and less code.
      - executed against a set of pre-configured logical processors - each LP is bound to a single thread.
    - channels - send typed messages between goroutines
  - simple and effective hierarchy-free type system
    - embedded types/composition to reuse functionality
  - Unique interface system
    - express behavior of a type
    - typically aligned with single actions
  - garbage collection

### Introducing Go
- Chapter 1 - Getting Started
  - GOPATH
  - Hello World app - does not need GOPATH
  - Comments: either // or /* followed by */
  - goDoc command - good resource
- Chapter 2 - Types
  - Numbers
    - Integers
      - uint8,uint16,uint32,uint64 , int8,int16,int32,int64
      - byte=uint8
      - rune=int32
      - machine dependent: uint, int, uintptr
      - in general, use 'int'
    - Floating Point
      - float32 and float64
      - NaN=not a number and positive and negative infinity
      - Complex numbers: complex64 and complex128
  - Strings
    - made up of individual bytes with a definite length
    - use len(stringValue) to get length
    - access by index is zero-based
    - Use + for concatenation
    - double quotes - single line and can use escape characters (\n \t)
    - back ticks ` - can span multiple lines
    - [n] to get byte value, string() to get char --> "Hello"[1] = 101 = 'e'
  - Booleans
    - represented as: true/false
    - && - and
    - || - or
    - ! - not

