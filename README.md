# AI-Notebooks
Repository of notebooks for learning and experimenting with AI, Machine Learning, and Deep Learning models. Includes step-by-step tutorials and practical examples to build foundational skills in AI.

## Contributing

Thank you for considering contributing to this project! We welcome contributions of all kinds, from fixing typos to adding new features. To ensure a smooth workflow and maintainable codebase, please follow the guidelines below:

### How to Contribute

1. **Open an Issue First**  
   Before starting any work, please open an issue to discuss your proposed change. This helps avoid duplicated efforts and allows maintainers to provide feedback early. Label your issue appropriately, e.g., `bug`, `enhancement`, or `documentation`.

2. **Fork the Repository**  
   Fork this repository to your account, then clone your fork locally to start working. Always make sure your fork is up to date with the latest changes in the main repository.

3. **Create a New Branch**  
   For each contribution, create a new branch with a meaningful name. For example:
   ```bash
   git checkout -b fix-typo-in-readme
   git checkout -b feature-add-regression-model
   ```

4. **Follow Conventional Commits**  
   When writing commit messages, please follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) standard. Here are some examples:
   - `feat: add new regression model`
   - `fix: correct typo in README`
   - `docs: update contributing guidelines`

5. **Open a Pull Request (PR)**  
   Once your work is complete:
   - Push your branch to your fork.
   - Open a Pull Request (PR) to the `main` branch of this repository.
   - Include a detailed description of your changes and reference any related issues.
   - Ensure your PR title follows Conventional Commits to help reviewers understand the purpose of your change.

6. **Write Clear and Concise Code**  
   Keep your code clear, concise, and well-documented. Add comments where necessary, especially if your code includes complex logic.

7. **Testing and Review**  
   - Ensure your code passes all tests (if applicable) before submitting a PR.
   - Once submitted, a maintainer will review your PR and may request changes. Please address any requested changes promptly.
   
8. **Documentation**  
   If your contribution adds new features or changes existing functionality, please update the README or other relevant documentation.

### Additional Tips for Contributors

- **Stay Updated**  
  Regularly pull changes from the main repository into your fork to avoid conflicts.  
  ```bash
  git pull upstream main
  ```

- **Respect the Project Structure**  
  Follow the existing folder structure, naming conventions, and code styles.

## Example Commit Message

```
feat(data-processing): add data augmentation step to preprocessing pipeline

Implement data augmentation techniques to enhance the dataset diversity and improve model robustness. This step includes random rotations, horizontal flips, and normalization on image data.

- Added data augmentation to the `preprocess_images` function in `data_processing.py`
- Updated tests in `test_data_processing.py` to cover new augmentation functionality
- Improved documentation for the preprocessing pipeline

Closes #45
```

### Explanation

1. **Commit Type and Scope**
   - **`feat`**: This indicates a new feature, following Conventional Commits. Other possible types could be `fix`, `docs`, `refactor`, etc.
   - **`(data-processing)`**: This is the scope, specifying the area of the code affected. Here, it refers to the data processing part of the project.

2. **Short Description**
   - `add data augmentation step to preprocessing pipeline`: A concise summary of the change. This should be clear and to the point, ideally under 50 characters.

3. **Detailed Description**
   The next section includes a more comprehensive description of the change:
   - Explains what was added or modified (data augmentation in preprocessing).
   - Details the specific techniques implemented (random rotations, flips, normalization).
   - Mentions any files or functions that were modified (e.g., `preprocess_images`).

4. **Bullet Points for Additional Changes**
   - List relevant changes, like updates to tests, improvements to documentation, or refactoring details.
   - Use bullet points to make it easier to read and highlight important changes.

5. **Issue Reference**
   - `Closes #45`: Links this commit to an issue in the repository, which will automatically close the issue when the PR is merged.

---

This structure helps maintainers and other contributors quickly understand the purpose and context of your changes. It ensures consistency in commit history, making it easier to track project progress and debug if needed.
