# Learning Notes

A running set of personal notes on machine learning fundamentals, built while working through video courses and my own handwritten derivations. Published as a static site via GitHub Pages.

🔗 **Live site:** https://yourusername.github.io/

## What's here

| Post | Topic |
|---|---|
| [`posts/neural-networks.html`](posts/neural-networks.html) | Neurons, weights, bias, forward propagation, the cost function, gradient descent, and a full worked derivation of backpropagation (one neuron per layer, generalized to many). |
| [`posts/cnn.html`](posts/cnn.html) | Convolutional Neural Networks — coming soon. |

## Structure

```
.
├── index.html              # homepage, lists all posts
└── posts/
    ├── neural-networks.html
    └── cnn.html
```

## Adding a new post

1. Drop the new post's HTML file into `posts/`.
2. Add a new `<li class="post">` card to `index.html` linking to it.
3. Commit and push — GitHub Pages rebuilds automatically within a minute.

## Notes

These are self-contained HTML files (math rendered via MathJax, diagrams as inline SVG) — no build step required. Sources for each post are credited at the bottom of the post itself.