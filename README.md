# Hello, I'm Michael Lund! (hackoverride) 👋

## 🌐 Connect with Me

- **Website:** [michaelwalund.com](https://www.michaelwalund.com)
- **SaaS Activity Hub:** [Klikkit](https://www.klikkit.no)
- **LinkedIn:** [Michael Lund](https://www.linkedin.com/in/michael-lund-67350b95/)

```rust
struct Skills {
    frontend: Vec<&'static str>,
    backend: Vec<&'static str>,
    databases: Vec<&'static str>,
    apis: Vec<&'static str>,
}

impl Skills {
    fn new() -> Self {
        Skills {
            frontend: vec!["JavaScript", "React", "TypeScript"],
            backend: vec![".NET (C#)", "Java", "Go", "Kotlin", "JavaScript", "Rust"],
            databases: vec!["MongoDB", "SQL"],
            apis: vec!["REST", "WebSockets", "Payment Webhooks (Nets, Vipps, Stripe)"],
        }
    }

    fn display(&self) {
        println!("Frontend: {:?}", self.frontend);
        println!("Backend: {:?}", self.backend);
        println!("Databases: {:?}", self.databases);
        println!("APIs: {:?}", self.apis);
    }
}

fn main() {
    let my_skills = Skills::new();
    my_skills.display();
}
```


