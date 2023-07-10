```rust
fn main() {
    #[derive(Debug)]
    struct Me {
        name: String,
        languages: String,
        fav_lang: String,
        website: String,
    }

    let me = Me {
        name: String::from("Krolyxon"),
        languages: String::from("C, Rust, Bash"),
        fav_lang: String::from("Rust 🦀 ❤️"),
        website: String::from("https://krolyxon.tildevarsh.in"),
    };
    
    println!("{:#?}", me);
}
```
