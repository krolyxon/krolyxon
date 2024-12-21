```rust
#[derive(Debug)]
struct Me {
    name: &'static str,
    operating_system: &'static str,
    languages: &'static [&'static str],
    technologies: &'static [&'static str],
    website: &'static str,
    working_on: &'static str,
}

fn main() {
    let me = Me {
        name: "Krolyxon",
        operating_system: "Arch Linux",
        languages: &["C", "Rust", "Javascript", "Java", "Bash"],
        technologies: &["ReactJS", "NodeJS", "TailwindCSS"],
        website: "https://krolyxon.github.io",
        working_on: "A really goodlooking website",
    };

    println!("{:#?}", me);
}
```


<!-- <div> -->
<!--     <img src="https://github-readme-stats.vercel.app/api?username=krolyxon&show_icons=true&hide_border=true&bg_color=181825&text_color=cdd6f4&icon_color=f5c2e7&hide_title=true&include_all_commits=true&count_private=true&ring_color=f5c2e7&border_radius=8" style="margin-bottom: 20px;" /> -->
<!-- </div> -->
