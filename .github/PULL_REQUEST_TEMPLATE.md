##### Instructions

- Look for and complete the section relevant to your submission. Delete the others, including these `Instructions`.
- `{{cask_file}}` is used a placeholder to the actual cask you’re submitting/editing (if applicable).
- If there’s a checkbox you can’t complete for any reason, that’s OK. Just explain in detail why you weren’t able to do so.

### Changes to a cask
#### Editing an existing cask

- [ ] Commit message includes cask’s name (and new version, if applicable).
- [ ] `brew cask audit --download {{cask_file}}` is error-free.
- [ ] `brew cask style --fix {{cask_file}}` left no offenses.

#### Adding a new cask

- [ ] Checked there aren’t open [pull requests](https://github.com/caskroom/homebrew-fonts/pulls) for the same cask.
- [ ] Checked there aren’t closed [issues](https://github.com/caskroom/homebrew-fonts/issues) where that cask was already refused.
- [ ] When naming the cask, followed the [reference](https://github.com/caskroom/homebrew-fonts/blob/master/CONTRIBUTING.md#naming-font-casks).
- [ ] Commit message includes cask’s name.
- [ ] `brew cask audit --download {{cask_file}}` is error-free.
- [ ] `brew cask style --fix {{cask_file}}` left no offenses.
- [ ] `brew cask install {{cask_file}}` worked successfully.
- [ ] `brew cask uninstall {{cask_file}}` worked successfully.