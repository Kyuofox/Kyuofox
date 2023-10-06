```rust
use std::collections::HashMap;

static ABOUT: [&str; 1] = [
    "Studied at Guangzhou Institute of Technology and an Android Enthusiast.",
];

static DOING: [&str; 2] = [
    "Learning Kotlin/Rust/C/Go.",
    "In GZIST.",
];

static DEVICE: [&str; 3] = [
    "Xiaomi 8",
    "Redmi K30 Pro / POCO F2 Pro",
    "Redmi Note 12 Turbo / POCO F5",
];

fn contact() -> HashMap<&'static str, &'static str> {
    let mut contact = HashMap::new();
    contact.insert("Email", "kyuofox@gmail.com");
    contact.insert("Telegram", "https://t.me/Kyuofox");
    contact
}

static PGP_KEY: &str = "9F99 998E 2BB1 51FD 6738 8973 9865 B9A0 9D89 A6FC";
```
