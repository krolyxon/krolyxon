```rust
fn main() {
    #[derive(Debug)]
    struct Krolyxon {
        whoami: String,
        languages: String,
        fav_lang: String,
        website: String,
    }

    let me = Krolyxon {
        whoami: String::from("I am Krolyxon, a computer science student who loves free and open-source software."),
        languages: String::from("C, Rust, Bash"),
        fav_lang: String::from("Rust 🦀 ❤️"),
        website: String::from("https://krolyxon.tildevarsh.in"),
    };
    
    println!("{:?}", me);
}
```
