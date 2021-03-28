# notes on programming

## git Commit message guideline

Would be something like that.
`<type>(<scope>): <subject>`

### type
* build: Build related changes (eg: npm related/ adding external dependencies)
* chore: A code change that external user won't see (eg: change to .gitignore file or .prettierrc file)
* feat: A new feature
* fix: A bug fix
* docs: Documentation related changes
* refactor: A code that neither fix bug nor adds a feature. (eg: You can use this when there is semantic changes like renaming a variable/ function name)
* perf: A code that improves performance
* style: A code that is related to styling
* test: Adding new test or making changes to existing test

### subject
* use imperative, present tense (eg: use "add" instead of "added" or "adds")
* don't use dot(.) at end
* don't capitalize first letter

### emoji
* 🛠 build
* 👀 chore
* 📦 feat
* 🐛 fix
* 📝 docs
* 🗜️ refactor
* 🚀 perf
* 🎨 style
* 🧪 test

### example
🛠 build(app gradle): add new itextpdf library

