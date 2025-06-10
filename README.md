<div align="left" style="position: relative;">
<h1>AI_FACE_GENERATION-GAN</h1>
<p align="left">
	<img src="https://img.shields.io/github/last-commit/MarcGeorgeML/AI_face_generation-GAN?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/MarcGeorgeML/AI_face_generation-GAN?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/MarcGeorgeML/AI_face_generation-GAN?style=default&color=0080ff" alt="repo-language-count">
</p>
<p align="left"><!-- default option, no dependency badges. -->
</p>
<p align="left">
	<!-- default option, no dependency badges. -->
</p>
</div>
<br clear="right">

##  Table of Contents

- [ Overview](#-overview)
- [ Features](#-features)
- [ Project Structure](#-project-structure)
  - [ Project Index](#-project-index)
- [ Getting Started](#-getting-started)
  - [ Prerequisites](#-prerequisites)
  - [ Installation](#-installation)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ Acknowledgments](#-acknowledgments)

---

##  Overview

This project implements a Deep Convolutional Generative Adversarial Network (DCGAN) using PyTorch to generate realistic human face images. The model is trained on the CelebA dataset and follows the official DCGAN architecture outlined in the [PyTorch documentation](https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html).


---

##  Features

<p>❯ 

- Implements a standard DCGAN from scratch in PyTorch
- Trained on the [CelebA dataset](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) 
- Generates synthetic 64×64 face images
- Includes training, visualization, and model checkpointing</p>

---

##  Project Structure

```sh
└── AI_face_generation-GAN/
    └── GAN.ipynb
```


###  Project Index
<details open>
	<summary><b><code>AI_FACE_GENERATION-GAN/</code></b></summary>
	<details> <!-- __root__ Submodule -->
		<summary><b>__root__</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/MarcGeorgeML/AI_face_generation-GAN/blob/master/GAN.ipynb'>GAN.ipynb</a></b></td>
				<td><code>❯ Code to train generator and discriminator</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
</details>

---
##  Getting Started

###  Prerequisites

Before getting started with AI_face_generation-GAN, ensure your runtime environment meets the following requirements:

- **Programming Language:** JupyterNotebook


###  Installation

Install AI_face_generation-GAN using one of the following methods:

**Build from source:**

1. Clone the AI_face_generation-GAN repository:
```sh
❯ git clone https://github.com/MarcGeorgeML/AI_face_generation-GAN
```

2. Navigate to the project directory:
```sh
❯ cd AI_face_generation-GAN
```

3. Install the project dependencies:

echo 'pip install -r requirements.txt'



---

##  Contributing

- **💬 [Join the Discussions](https://github.com/MarcGeorgeML/AI_face_generation-GAN/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/MarcGeorgeML/AI_face_generation-GAN/issues)**: Submit bugs found or log feature requests for the `AI_face_generation-GAN` project.
- **💡 [Submit Pull Requests](https://github.com/MarcGeorgeML/AI_face_generation-GAN/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/MarcGeorgeML/AI_face_generation-GAN
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/MarcGeorgeML/AI_face_generation-GAN/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=MarcGeorgeML/AI_face_generation-GAN">
   </a>
</p>
</details>

---


##  Acknowledgments

- Dataset link: [CelebA dataset](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) 
- Documentation: [DCGAN documentation](https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html).

---
