# Find GitHub Email

[![Tests](https://github.com/jemmaissroff/find_github_email/workflows/Main/badge.svg)](https://github.com/jemmaissroff/find_github_email/actions?query=workflow%3AMain)
[![security](https://hakiri.io/github/jemmaissroff/find_github_email/main.svg)](https://hakiri.io/github/jemmaissroff/find_github_email/main)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Gem Version](https://img.shields.io/gem/v/find_github_email.svg)](https://rubygems.org/gems/find_github_email)
[![Gem Downloads](https://img.shields.io/gem/dt/find_github_email.svg)](https://rubygems.org/gems/find_github_email)

### ☀️ **The warmest start to a cold email** ❄️

Find GitHub Email allows you to find any GitHub user's email addresses based on their commit history and GitHub profile.

Check out [this post](https://jemma.dev/blog/find-github-email) for a little more background on the gem.

## ⏬ Installation

    $ gem install find_github_email
    

Find Github Email uses [GitHub's API](https://developer.github.com/v4/). In order to use Find GitHub Email, you need a GitHub API token 🔑. Fortunately, these are very easy to obtain: 

1. 👩‍💻 Visit https://github.com/settings/tokens/new
2. ✍️ Label the token whatever you would like 
3. ✔️ Select the `read:user` box within the `user` section
4. 🟩 Click the green `Generate Token` button
5. 📝 Copy your token

Once you have your API token, in a console run

    $ find_github_email -g <GITHUB_API_TOKEN>
    
You will only need to run this command once 🎉. It will store your API token at `~/.find_github_email_access_token`, and the gem will always look for it at that location.

## 📬 Usage

 After you've followed the installation instructions, you can run:

    $ find_github_email <USERNAME>
    
For example:

    $ find_github_email torvalds
	torvalds@linux-foundation.org


## 👩‍💻 Contributing

[Bug reports](https://github.com/jemmaissroff/find_github_email/issues) and
[pull requests](https://github.com/jemmaissroff/find_github_email/pulls) are welcome on GitHub at
https://github.com/jemmaissroff/find_github_email. This project is intended to be a safe,
welcoming space for collaboration, and contributors are expected to adhere to
the [code of conduct](https://github.com/jemmaissroff/find_github_email/blob/main/CODE_OF_CONDUCT.md).

## 📃 License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

##  ♥️ Code of Conduct

Everyone interacting in Find GitHub Email's codebase is expected to follow the
[code of conduct](https://github.com/jemmaissroff/find_github_email/blob/main/CODE_OF_CONDUCT.md).
