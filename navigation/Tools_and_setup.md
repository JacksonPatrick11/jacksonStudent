---
layout: page
title: Tools and setup
description: Tools & Setup
hide: true
---

<h2>Step-by-Step Guide for MacOS Terminal Setup</h2>

<p>1. Install Homebrew:</p>
<pre><code>/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"</code></pre>

<p>2. Verify Homebrew Installation:</p>
<pre><code>brew --version</code></pre>

<p>3. Create a project directory and clone the repository:</p>
<pre><code>
cd ~
mkdir nighthawk
cd nighthawk
git clone https://github.com/nighthawkcoders/portfolio_2025.git
</code></pre>

<p>4. Run the script to install all necessary tools:</p>
<pre><code>
cd nighthawk/portfolio_2025/scripts
./activate_macos.sh
</code></pre>

<p>5. If using Apple Silicon M series, create symbolic links for Python and Pip:</p>
<pre><code>
sudo ln -sF /opt/homebrew/bin/python3.12 /usr/local/bin/python
sudo ln -sF /opt/homebrew/bin/pip3.12 /usr/local/bin/pip
</code></pre>

<p>6. For Apple Intel series, create symbolic links for Python and Pip:</p>
<pre><code>
sudo ln -sF /usr/local/bin/python3.12 /usr/local/bin/python
sudo ln -sF /usr/local/bin/pip3.12 /usr/local/bin/pip
</code></pre>

<p>7. Check that versions are correct (Ruby, Python, Jupyter):</p>
<pre><code>
ruby -v
bundle -v
python --version
jupyter --version
</code></pre>

<p>8. Set up your GitHub credentials:</p>
<pre><code>
git config --global user.email "youremail@gmail.com"
git config --global user.name "yourGHID"
</code></pre>

<p>9. Start the project:</p>
<pre><code>
cd ~/nighthawk/student_2025
scripts/venv.sh
source venv/bin/activate
pip install -r requirements.txt
bundle install
code .
</code></pre>

<p>10. Run the local server:</p>
<pre><code>make</code></pre>

<p>11. To stop the server:</p>
<pre><code>make stop</code></pre>

<p>12. To clean the build files:</p>
<pre><code>make clean</code></pre>

<p>13. To convert Jupyter Notebook files:</p>
<pre><code>make convert</code></pre>


[Back to home](../index.md)