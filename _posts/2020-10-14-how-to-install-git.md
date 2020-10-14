---
title: "How to Install Git"
---

Git is a wonderful version control tool, that many people don't make use of.

If you are wondering how to install Git on your machine, keep reading on.

<br>

# Windows

You can download the setup <a href="https://git-scm.com/download/win">here</a>, the setup is pretty much straight forward. The default settings are fine. After you are done, you can type `git --version` in a console to check if it installed properly.

<br>

# macOS

macOS ships with a built in version of Git, but if you'd like to update it, there are a few methods.

If you have Xcode installed, you most likely have Git already.

<br>

## Git for Mac Installer

By far the easiest way to install Git.

<ol>
 	<li>Download and install the setup from <a href="https://sourceforge.net/projects/git-osx-installer/files/">here</a>.</li>
 	<li>Make sure Git installed correctly:
<code>git --version</code></li>
 	<li>Configure Git:
<code>git config --global user.name "Your Name"</code>
<code>git config --global user.email "your@email.address"</code></li>
</ol>

<br>

## Homebrew

If you have Homebrew installed, you can use this method.

1. Install Git:

    ```
    brew install git
    ```

2. Make sure Git installed correctly:

    ```
    git --version
    ```

3. Configure Git:

    ```
    git config --global user.name "Your Name"
    git config --global user.email "your@email.address"
    ```

<br>

## MacPorts

If you have MacPorts installed, you can use this method.

1. Update MacPorts:

    ```
    sudo port selfupdate
    ```

2. Search for latest Git ports and variants:

    ```
    port search git
    port variants git
    ```

3. Install Git: (make sure everything here is in one command!)

    ```
    sudo port install git +bash_completion+credential_osxkeychain+doc
    ```

4. Make sure Git installed correctly:

    ```
    git --version
    ```

5. Configure Git:

    ```
    git config --global user.name "Your Name"
    git config --global user.email "your@email.address"
    ```

<br>

# Linux

## Debian (apt)

1. In a terminal, type:

    ```
    sudo apt update
    sudo apt install git
    ```

2. Make sure Git installed correctly:

    ```
    git --version
    ```

3. Configure Git:

    ```
    git config --global user.name "Your Name"
    git config --global user.email "your@email.address"
    ```

<br>

## Fedora (dnf/yum)

1. In a terminal, type:

    ```
    sudo dnf install git
    ```

    or

    ```
    sudo yum install git
    ```

2. Make sure Git installed correctly:

    ```
    git --version
    ```

3. Configure Git:

    ```
    git config --global user.name "Your Name"
    git config --global user.email "your@email.address"
    ```
