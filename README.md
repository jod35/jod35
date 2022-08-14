# About Me
```
fn main() {
    let name = String::from("Jonathan");
    let jona = Animal { name, age: 23 };

    jona.print_name();
    jona.print_age();
    jona.print_bio();
}

struct Animal {
    name: String,
    age: i8,
}

impl Animal {
    fn print_name(&self) {
        println!("My name is {}", self.name);
    }

    fn print_age(&self) {
        println!("My age is {}", self.age);
    }

    fn print_bio(&self) {
        println!("I am a software engineer who learns and teaches others what I learn.");
    }
}

```

