# NV-Bench Demo Page

Demo page for **NV-Bench**: Benchmarking Nonverbal Vocalization Synthesis in Expressive Text-to-Speech Models.

## Links

- **Demo**: [https://charlesnii.github.io/nvbench.github.io/](https://charlesnii.github.io/nvbench.github.io/)
- **Code**: [https://github.com/AmphionTeam/NV-Bench](https://github.com/AmphionTeam/NV-Bench)
- **Dataset**: [https://huggingface.co/datasets/CharlesNi/NV-Bench](https://huggingface.co/datasets/CharlesNi/NV-Bench)
- **NVASR Model**: [https://huggingface.co/CharlesNi/Multilingual-NVASR](https://huggingface.co/CharlesNi/Multilingual-NVASR)

## Local Preview

```bash
# Any static file server works, e.g.
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Structure

```
├── index.html          # Main page
├── style.css           # Styles
└── static/
    ├── overview.png    # Pipeline figure
    └── example*/       # Audio samples (prompt, GT, model outputs)
```
