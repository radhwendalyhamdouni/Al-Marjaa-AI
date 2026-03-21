<div align="center">

# مكتبة الذكاء الاصطناعي للغة المرجع
### Al-Marjaa AI Library

[![Version](https://img.shields.io/badge/version-3.4.0-blue.svg)](https://github.com/radhwendalyhamdouni/Al-Marjaa-AI)

**المخترع والمطور: رضوان دالي حمدوني**

</div>

---

## 🎯 نظرة عامة

مكتبة الذكاء الاصطناعي للغة المرجع - تتضمن محرك Vibe Coding ومعالجة اللغة العربية NLP.

---

## 📦 التثبيت

### باستخدام Cargo

```toml
[dependencies]
almarjaa-ai = { git = "https://github.com/radhwendalyhamdouni/Al-Marjaa-AI" }
```

### مع Features

```toml
[dependencies]
almarjaa-ai = { git = "https://github.com/radhwendalyhamdouni/Al-Marjaa-AI", features = ["full"] }
```

---

## 🔧 الميزات المتاحة

| Feature | الوصف |
|---------|-------|
| `default` | لا شيء (أساسي) |
| `full` | جميع الميزات |
| `gguf` | معالجة نماذج GGUF |
| `huggingface` | تكامل Hugging Face |
| `network` | دعم الشبكة |

---

## 💡 مثال الاستخدام

```rust
use almarjaa_ai::{VibeEngine, ArabicNLP};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // محرك Vibe Coding
    let vibe = VibeEngine::new();
    
    // معالجة النص العربي
    let nlp = ArabicNLP::new();
    
    Ok(())
}
```

---

## 👨‍💻 المؤلف

**رضوان دالي حمدوني**
- البريد: almarjaa.project@hotmail.com

---

**صُنع بـ ❤️ للعالم العربي**
