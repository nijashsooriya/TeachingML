# TeachingML

Machine learning taught from the ground up: the math, the intuition, and the code that ties them together.

This repo has the notebooks and code behind my teaching videos. Each topic is built from first principles. Instead of calling a library and moving on, we derive what's happening, implement it ourselves, and then check it against the real thing.

## 📺 Watch along

I make short and long-form videos walking through this material:

- **YouTube:** [@extrakneejosh](https://www.youtube.com/@extrakneejosh)
- **Instagram:** [@extra_kneejosh](https://www.instagram.com/extra_kneejosh)
- **TikTok:** [@kneej0shgoestoschool](https://www.tiktok.com/@kneej0shgoestoschool)

If a video left you with questions, the code here is the place to dig in.

## 📚 Topics

| Topic | What you'll learn | Where |
|---|---|---|
| **Linear Regression** | Least squares from scratch, the geometry of the solution, gradient descent vs. the closed form | `LinearRegressionTeaching.ipynb` |
| **Random Forests on EMNIST** | Decision trees, bagging, and ensembles applied to handwritten character recognition | `RF_EMNIST/` |

### 🔜 Coming soon

- **Neural Networks in C / CUDA:** a multilayer perceptron with no frameworks, from backpropagation by hand to running on the GPU

## 🚀 Getting started

```bash
git clone git@github.com:nijashsooriya/TeachingML.git
cd TeachingML
pip install numpy matplotlib scikit-learn jupyter
jupyter notebook
```

> The EMNIST dataset isn't stored in this repo. Download it separately before running the `RF_EMNIST` notebooks.

## 🧭 Philosophy

- **Math first, then code.** Every algorithm comes with its derivation.
- **Build it, then compare it.** Write it from scratch, then check it against the library version.
- **Intuition over memorization.** If you can't explain why it works, you don't really know it yet.

## 🤝 Feedback

Found a bug, have a question, or want a topic covered? Open an issue or reach out on any of the channels above.

---

Made by **Nijash Sooriyakumaran** (Nj)
