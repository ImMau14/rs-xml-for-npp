# Rust Autocompletion File for Notepad++

This repository holds an **XML file** to add basic **Rust language syntax autocompletion** functionality to the **Notepad++** text editor.

While it may not include the entire standard library (yet!), it's a very useful tool to increase speed and accuracy when programming in Rust with this editor. Feel free to post an *issue* or a *Pull Request* if you want to add more words and improve the file!

***

## How to Install

1.  **Download the XML file** (`rust.xml`) from this repository.
2.  **Copy and paste** the downloaded file into the autocompletion directory of your Notepad++ installation, which is usually:
    ```
    C:\Program Files\Notepad++\autoCompletion
    ```
    *(Be sure to replace `C:\Program Files\Notepad++` with your actual Notepad++ installation path).*
3.  **Restart Notepad++** so it can recognize the new autocompletion file.
4.  Start coding in Rust!

***

## Content of the Autocompletion File (`rust.xml`)

The XML file provides autocompletion suggestions for fundamental elements of the Rust language, categorized as follows:

### **Keywords**
Includes all Rust reserved keywords, such as `fn`, `let`, `mut`, `if`, `else`, `loop`, `match`, `struct`, `enum`, `trait`, `impl`, `use`, `mod`, `pub`, `async`, `await`, and others.

### **Essential Macros**
Support for common macros, including:
* **Printing and Formatting:** `println!`, `print!`, `eprintln!`, `format!`.
* **Control Flow and Debugging:** `panic!`, `assert!`, `dbg!`, `unreachable!`.
* **Collections and Utilities:** `vec!`, `cfg!`, `include_str!`.

### **Core Types and Structures**
Definitions for important standard library types, such as:
* **Error/Optional Handling:** `Option`, `Result`, `Some`, `None`, `Ok`, `Err`.
* **Main Collections:** `Vec`, `String`, `HashMap`, `HashSet`, `BTreeMap`.
* **Smart Pointers and Concurrency:** `Box`, `Rc`, `Arc`, `Mutex`, `RwLock`.
* **Primitive Types:** `i32`, `u64`, `bool`, `char`, `str`, etc.

### **Common Methods**
Many of the most frequently used methods in Rust programming are included, with descriptions of their main function and return value (`retVal`):
* **Collections:** `push`, `pop`, `insert`, `remove`, `len`, `is_empty`, `new`, `with_capacity`.
* **Strings:** `push_str`, `as_str`, `to_lowercase`, `split`, `trim`.
* **Iterators:** `next`, `collect`, `map`, `filter`, `fold`, `enumerate`, `zip`, `find`, `sum`.
* **Option/Result Handling:** `unwrap`, `expect`, `map`, `and_then`, `is_some`, `is_ok`.
* **IO, Network, and Time:** `open`, `read_to_string`, `write_all`, `connect`, `now`, `elapsed`.

***

## Important Notice

**This repository is not an official Notepad++ repository**. For now, it was created and is maintained by me (ImMau14) to offer a simple autocompletion solution for **Rust** in **Notepad++**. It is not associated with or endorsed by the developers of Notepad++ or Rust.