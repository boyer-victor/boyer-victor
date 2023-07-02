# Grüezi!
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)
```
struct Engineer {
    name: String,
    role: String,
    education: String,
    spoken_languages: Vec<String>,
    coding_languages: Vec<String>,
    interests: Vec<String>,
}

impl Engineer {
    fn new(name: String, role: String,education:String, spoken_languages: Vec<String>, coding_languages: Vec<String>, interests: Vec<String>) -> Engineer {
        Engineer {
            name,
            role,
            education,
            spoken_languages,
            coding_languages,
            interests,
        }
    }

    fn print_info(&self) {
        println!("Name: {}", self.name);
        println!("Role: {}", self.role);
        println!("Education: {}", self.education);
        println!("I can speak: {:?}", self.spoken_languages);
        println!("I have experience coding with: {:?}", self.coding_languages);
        println!("My interests are: {:?}", self.interests);
    }
}

fn main() {
    let engineer = Engineer::new(
        String::from("Victor Boyer"),
        String::from("Software Engineer"),
        String::from("B.S. in Mathematics, B.S. in Quantitative Finance, M.S. in Applied Mathematics"),
        vec![String::from("English"), String::from("German")],
        vec![String::from("Cryptology"), String::from("Parallel systems"), String::from("GPU Acceleration/CUDA"), String::from("High Performance Computing")],
    );

    engineer.print_info();
}
```
## 🔧 Technologies & Tools

![](https://img.shields.io/badge/OS-Linux-informational?style=flat&logo=linux&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Editor-VS_Code-informational?style=flat&logo=visual-studio-code&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-Rust-informational?style=flat&logo=rust&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-Golang-informational?style=flat&logo=go&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-Julia-informational?style=flat&logo=julia&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Shell-Bash-informational?style=flat&logo=gnu-bash&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Database-MySQL-informational?style=flat&logo=mysql&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Database-MongoDB-informational?style=flat&logo=mongodb&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-Docker-informational?style=flat&logo=docker&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-Terraform-informational?style=flat&logo=terraform&logoColor=white&color=6aa6f8)


