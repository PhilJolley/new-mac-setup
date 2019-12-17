<h1>New Mac Setup for Homebrew, MySQL, PHP, Valet, Composer, Laravel, and Git Config</h1>

<h2>Table of Contents:</h2>
<ol>
    <li>Install Xcode</li>
    <li>Install Homebrew</li>
    <li>Install Node</li>
    <li>Install MySql</li>
    <li>Add MySQL to the correct path</li>
    <li>Install PHP 7.x</li>
    <li>NPM Packages (Mainly for my Work)</li>
    <li>Install Composer</li>
    <li>Install Laravel</li>
    <li>Install Valet</li>
    <li>Install XDebug</li>
    <li>WordPress CLI</li>
    <li>Create SSH Keys</li>
    <li>Git Configs</li>
</ol>

<ol>
    <li>Install and then open Xcode from the App Store. Once open you can close it.</li>
    <li>Terminal Setup and CLI's
        <ul>
            <li>Install Homebrew: <code>ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"</code></li>
            <li>Install Node: <code>brew install node</code></li>
            <li>Install MySql: <code>brew install mysql@5.7</code><br><code>brew services start mysql@5.7</code><br><code>sudo mysqladmin --user=root password "root"</code></li>
            <li>Add MySQL to the correct <a href="https://stackoverflow.com/questions/26554818/using-mysql-in-the-command-line-in-osx-command-not-found/32024632">path</a>.</li>
        </ul> 
    </li>
</ol>