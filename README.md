### Well Hello There 👋

I'm the h4ck3r@parrot aka the <b><a href="https://parrothacker1.github.io">parrothacker1</a></b>
<br>
<font height='1vh'>😈</font>
<br>
<div align="center">
<img height="auto" width="200vw" src="profile.jpg"></div>

```
src/skill.rs
```
```rust
use serde_json::json;

pub fn skills() {
    let out=json!({
"skills":["Bash","Rust",
          "Java","HTML","CSS",
          "Javascript","MongoDB",
          "MySQL","PostgresSQL",
          "Python"]
});   
    println!("{:?}",out["skills"]);
}
```
```
src/main.rs
```
```rust
#[path="./skill.rs"] mod skill;
fn main() {
      skill::skills();
}
```

Well Contact Me @
* <a href="http://t.me/parrothacker1">Telegram</a>
* <a href="https://www.instagram.com/parrothacker1">Instagram</a>
