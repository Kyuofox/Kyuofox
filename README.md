use std::collections::HashMap;

struct RustExample {
    about: Vec<&'static str>,

    doing: Vec<&'static str>,

    device: Vec<&'static str>,

    contact: HashMap<&'static str, &'static str>,
}

impl RustExample {
    fn new() -> RustExample {
        let about = vec!["Just a High School Grad and an Android Enthusiast"];

        let doing = vec![
            "Learning Kotlin/Rust",
            "Stay at home in a daze",
        ];

        let device = vec![
            "Xiaomi 8",
            "Redmi K30 Pro / POCO F2 Pro",
        ];

        let mut contact = HashMap::new();
        contact.insert("Email", "kyuofox@gmail.com");
        contact.insert("Telegram", "https://t.me/Kyuofox");

        RustExample {
            about,
            doing,
            device,
            contact,
        }
    }
}
