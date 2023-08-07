# Read about: ^ - caret and ~ - tilda

```
https://www.geeksforgeeks.org/difference-between-tilde-and-caret-in-package-json

```

# Why should I not modify `package-lock.json`?

### The `package-lock. json` file was introduced in npm version 5 to solve this problem. It is a generated file and is not designed to be manually edited. Its purpose is to track the entire tree of dependencies (including dependencies of dependencies) and the exact version of each dependency.

### so the problem we all face is it is working on my local but not working on production generally due to version difference only. due to if we put package-lock.json inside the .gitignore file.

### package-lock.version locks the dependencies version.
