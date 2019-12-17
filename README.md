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
    <li>Install Valet and Park Valet</li>
    <li>Install XDebug</li>
    <li>WordPress CLI</li>
    <li>Create SSH Keys</li>
    <li>Git Configs</li>
</ol>
<hr>
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
    <li>Install PHP 7.x
        <ul>
            <li><code>brew install php</code></li>
        </ul>
    </li>
    <li>NPM Packages (Optional)
        <ul>
            <li><code>npm install -g webpack @vue/cli yarn</code></li>
            <li>Issues with global <a href="https://medium.com/@jagatjyoti.1si13cs040/npm-g-install-npm-package-not-working-as-desired-why-why-why-19795abf0b59">install</a>.</li>
        </ul>
    </li>
    <li>Install Composer
        <ul>
            <li><code>brew install composer</code></li>
        </ul>
    </li>
    <li>Install Laravel
        <ul>
            <li><code>composer global require laravel/installer</code></li>
        </ul>
    </li>
    <li>Install Valet and Park
        <ul>
            <li><code>composer global require laravel/valet</code></li>
            <li><strong>YOU NEED TO PARK YOUR VALET</strong><code>valet park (in the directory you keep your Sites)</code></li>
        </ul>
    </li>
    <li>Install WP CLI
        <ul>
            <li><code>curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar</code></li>
            <li><code>chmod +x wp-cli.phar</code></li>
            <li><code>sudo mv wp-cli.phar /usr/local/bin/wp</code></li>
        </ul>
    </li>
    <li>Create SSH Keys
        <ul>
            <li><a href="https://www.siteground.com/kb/how_to_generate_an_ssh_key_pair_in_mac_os/">How to generate an SSH key on Mac</a></li>
            <li>Add public key to Github</li>
        </ul>
    </li>
    <li>Git Configs
        <ul>
            <li><code>git config --global user.name "YOUR_USERNAME"</code></li>
            <li><code>git config --global user.email "your@email.com"</code></li>
            <li><code>git config --global push.default simple</code></li>
        </ul>
    </li>
</ol>