# RIP test.rs
## 2022-Chicken
```
fn main() { // I WAS PROMISED NO BOILERPLATE!!! WHAT DO YOU MEAN fn main() {???
    let x = "Hello";
    {
        let x = "Goodbye"; // This version of x is local to this block.
        //                  The epitome of a temporary variable.
        println!("{x} Heaven...");
    }
    println!("{} World!",x); // Prints "Hello" for x, now that we're outside that block.
}
```
"Goodbye World... Hello Heaven!"

She was a caring, *completely calm* soul, taken 2 soon.
