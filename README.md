```rust
use std::collections::HashMap;

static ABOUT: [&str; 1] = [
    "Just a High School Grad and an Android Enthusiast.",
];

static DOING: [&str; 2] = [
    "Learning Kotlin/Rust.",
    "Stay at home in a daze.",
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
```
